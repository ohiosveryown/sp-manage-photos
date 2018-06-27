<!-- layout -->
<template>
  <section class="galleries">

    <!-- header -->
    <header class="mb-1">
      <h3 class="f-lg f-bold">Galleries</h3>
      <svg class="pointer" width="28" height="28" viewBox="0 0 18 28">
        <defs>
          <path id="a" d="M13.0814755,18.5814755 L13.0814755,18.5814755 L13.0814755,18.5814755 C13.6337602,18.5814755 14.0814755,19.0291907 14.0814755,19.5814755 L14.0814755,24.5814755 L14.0814755,24.5814755 C14.0814755,25.1337602 13.6337602,25.5814755 13.0814755,25.5814755 L13.0814755,25.5814755 L13.0814755,25.5814755 C12.5291907,25.5814755 12.0814755,25.1337602 12.0814755,24.5814755 L12.0814755,19.5814755 L12.0814755,19.5814755 C12.0814755,19.0291907 12.5291907,18.5814755 13.0814755,18.5814755 Z M13.0814755,18.5814755 C16.395184,18.5814755 19.0814755,15.895184 19.0814755,12.5814755 C19.0814755,9.26776695 16.395184,6.58147545 13.0814755,6.58147545 C9.76776695,6.58147545 7.08147545,9.26776695 7.08147545,12.5814755 C7.08147545,15.895184 9.76776695,18.5814755 13.0814755,18.5814755 Z M13.0814755,20.5814755 C8.66319745,20.5814755 5.08147545,16.9997535 5.08147545,12.5814755 C5.08147545,8.16319745 8.66319745,4.58147545 13.0814755,4.58147545 C17.4997535,4.58147545 21.0814755,8.16319745 21.0814755,12.5814755 C21.0814755,16.9997535 17.4997535,20.5814755 13.0814755,20.5814755 Z"/>
        </defs>
          <use fill="#353543" fill-rule="nonzero" transform="rotate(45 13.081 15.081)" xlink:href="#a"/>
        </g>
      </svg>
    </header>

    <!-- actions -->
    <div class="mb-4 actions">
      <div class="pointer sorting">
        <h5 class="mr-1 f-sm f-semi op-5 uc">view:</h5>
        <h5 class="f-sm f-semi uc">all</h5>
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
          <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
        </svg>
      </div>
      <div class="pointer tools">
        <h5 class="mr-0 f-sm f-semi uc">gallery tools</h5>
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
          <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
        </svg>
      </div>
    </div>

    <!-- gallery -->
    <div class="mb-4 gallery gallery__one">
      <div class="active"></div>
      <h2 class="gallery-title__one pointer mb-1 f-md f-bold">A Typical Wedding</h2>
        <div class="gallery-info">
          <img class="gallery-cover" src="../assets/img/gallery-cover-01@2x.jpg" alt="gallery cover image">
            <div class="gallery-meta">
              <h5 class="stats mb-0 f-xs f-medium uc">3 albums – 2.5k photos</h5>
              <h4 class="contact f-sm f-medium op-6">Lianne La Havas</h4>
            </div>
            <div class="actions">
              <h5 class="actions__trigger pointer mr-0 f-xs f-semi uc">actions</h5>
              <svg class="chevron" style="margin-top: -2px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
              </svg>
              <!-- actions open -->
              <div class="actions__open">
                <ul class="pointer f-sm f-semi">
                  <li>View Gallery Visitors</li>
                  <li>Preview Gallery</li>
                  <li>Share Gallery</li>
                  <li>Settings</li>
                  <li>Archive</li>
                  <li>Delete Gallery</li>
                </ul>
              </div>
            </div>
        </div>
    </div>

    <!-- gallery -->
    <div class="mb-4 gallery gallery__two">
      <h2 class="gallery-title__two pointer mb-1 f-md f-bold">ShootProof Culture Photos</h2>
        <div class="gallery-info">
          <img class="gallery-cover" src="../assets/img/gallery-cover-02@2x.jpg" alt="gallery cover image">
            <div class="gallery-meta">
              <h5 class="stats mb-0 f-xs f-medium uc">0 albums – 324 photos</h5>
              <h4 class="contact f-sm f-medium op-6">Jennifer Rice</h4>
            </div>
            <div class="actions">
              <h5 class="pointer mr-0 f-xs f-semi uc">actions</h5>
              <svg style="margin-top: -2px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
              </svg>
            </div>
        </div>
    </div>

    <!-- gallery -->
    <div class="mb-4 gallery gallery__three">
      <h2 class="gallery-title__three pointer mb-1 f-md f-bold">A Lovely Bunch of Coconuts</h2>
        <div class="gallery-info">
          <img class="gallery-cover" src="../assets/img/gallery-cover-03@2x.jpg" alt="gallery cover image">
            <div class="gallery-meta">
              <h5 class="stats mb-0 f-xs f-medium uc">5 albums – 808k photos</h5>
              <h4 class="contact f-sm f-medium op-6">No Linked Contact</h4>
            </div>
            <div class="actions">
              <h5 class="pointer mr-0 f-xs f-semi uc">actions</h5>
              <svg style="margin-top: -2px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
              </svg>
            </div>
        </div>
    </div>

    <!-- plan details -->
    <div class="plan-details">
      <div class="mb-1 plan-details__meta uc">
        <h6 class="f-xs f-demi op-5">using 3.6k of 8k photos</h6>
        <h6 class="f-xs f-medium pointer">upgrade plan</h6>
      </div>
      <div class="plan-details__bar">
        <div class="plan-details__bar__usage"></div>
        <div class="plan-details__bar-bg"></div>
      </div>
    </div>

  </section>
</template>


<!-- style -->
<style scoped lang="scss">
  @import '../assets/style/mq';
  @import '../assets/style/type';

  section {
    background: #f8f9f9;
    @include breakpoint(mdl) {
      padding: 76px 24px 0 24px;
      max-width: 424px; width: 25vw; height: 100vh;
    }
  }

  header {
    display: flex;
    justify-content: flex-end;

    h3 { margin-right: auto; }
    svg { margin-top: 2px; opacity: .5; }
  }

  .gallery-info, .actions, .sorting, .tools {
    display: flex;
    justify-content: flex-end;
  }

  .sorting, .stats { margin-right: auto; }

  .gallery > h2 { transition: var(--ease); }
  .gallery-title-active, .gallery > h2:hover { color: var(--primary); }


  .gallery-cover {
    border-radius: 4px;
    width: 40px; height: 40px;
  }

  .gallery-meta {
    margin-right: auto;
    margin-left: 8px;
    align-self: center;
  }

  .actions {
    position: relative;
    margin-top: 4.4px;
  }

  .actions__open {
    display: flex;
    flex-direction: column;
    position: absolute;
    top: 24px; right: -10px;
    padding: 4px 16px;
    width: 180px;
    background: #fff;
    border: 1px solid rgba(53,53,67,0.10);
    box-shadow: 0 8px 16px 0 rgba(151,153,157,.2);
    border-radius: 2px;
    transform: translateY(-10px);
    opacity: 0;
    transition: transform 400ms ease, opacity 200ms ease;

    ul, li { display: flex; flex-direction: column; }
    li { transition: var(--ease); margin: 9px 0; }
    li:hover { transform: translateX(6px); }
    li:last-of-type { padding-top: 10px; color: var(--danger); }
    li:last-of-type:before {
      content: '';
      position: absolute;
      right: 0;
      width: 94%; height: 1px;
      background: rgba(0,0,0,.15);
      transform: translateY(-14px);
    }
  }

  .actions__open-active {
    opacity: 1;
    transform: translateY(0);
    z-index: var(--z4);
  }

  .chevron { transition: var(--ease); }
  .chevron__active { transform: scale(1,-1); }

  .active {
    position: absolute;
    left: 0;
    width: 5px; height: 88px;
    background: var(--primary);
    transform: translateY(0);
    transition: all 600ms cubic-bezier(0.770, 0, 0.175, 1);
  }

  .active__two { transform: translateY(96px); }
  .active__three { transform: translateY(196px); }

  .plan-details {
    position: absolute;
    bottom: 32px;
    max-width: calc(424px - 56px);
    width: calc(25vw - 56px);
  }

  .plan-details__meta {
    display: flex;
    justify-content: flex-end;
    h6:nth-of-type(1) { margin-right: auto; }
    h6:nth-of-type(2) { color: var(--primary); text-decoration: underline; }
  }

  .plan-details__bar { position: relative; }

  .plan-details__bar__usage {
    position: absolute;
    width: 45%; height: 8px;
    border-radius: 10px;
    background: var(--primary);
    z-index: var(--z2);
  }

  .plan-details__bar-bg {
    position: absolute;
    width: 100%; height: 8px;
    border-radius: 10px;
    background: var(--cloud);
    box-shadow: 0 6px 16px 0 #ccc;
    z-index: var(--z1);
  }

</style>


<!-- logic -->
<script>
  export default {
    name: 'Galleries' ,

    mounted() {
      const gallery__one = document.querySelector('.gallery__one')
      const gallery__two = document.querySelector('.gallery__two')
      const gallery__three = document.querySelector('.gallery__three')
      const active = document.querySelector('.active')

      const actions__trigger = document.querySelector('.actions__trigger')
      const chevron = document.querySelector('.chevron')

      actions__trigger.addEventListener('click', () => {
        document.querySelector('.actions__open').classList.toggle('actions__open-active')
        chevron.classList.toggle('chevron__active')
      })

      const gallery__title__one = document.querySelector('.gallery-title__one')
      const gallery__title__two = document.querySelector('.gallery-title__two')
      const gallery__title__three = document.querySelector('.gallery-title__three')

      gallery__title__one.classList.add('gallery-title-active')

      gallery__one.addEventListener('click', () => {
        active.classList.remove('active__two', 'active__three')
        gallery__title__one.classList.add('gallery-title-active')
        gallery__title__two.classList.remove('gallery-title-active')
        gallery__title__three.classList.remove('gallery-title-active')
      })

      gallery__two.addEventListener('click', () => {
        active.classList.add('active__two')
        active.classList.remove('active__three')
        gallery__title__one.classList.remove('gallery-title-active')
        gallery__title__two.classList.add('gallery-title-active')
        gallery__title__three.classList.remove('gallery-title-active')
      })

      gallery__three.addEventListener('click', () => {
        active.classList.add('active__three')
        gallery__title__one.classList.remove('gallery-title-active')
        gallery__title__two.classList.remove('gallery-title-active')
        gallery__title__three.classList.add('gallery-title-active')
      })
    }
  }
</script>
