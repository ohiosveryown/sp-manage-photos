<!-- layout -->
<template>
  <div class="albums-photos">

    <section class="albums">
      <!-- header -->
      <header class="albums-header mb-1">
        <h3 class="title f-lg f-bold">Albums</h3>
        <!-- actions -->
        <div class="mb-4 actions">
          <div class="pointer sorting">
            <h5 class="mr-0 f-sm f-semi op-5 uc">sort:</h5>
            <h5 class="f-sm f-semi uc">custom</h5>
            <svg style="transform: translateY(-2px);" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
              <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
            </svg>
          </div>
          <div class="pointer tools">
            <h5 class="mr-0 f-sm f-semi uc">album tools</h5>
            <svg style="transform: translateY(-2px);" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
              <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
            </svg>
          </div>
        </div>
      </header>

      <!-- album -->
      <figure class="active">
        <img src="../assets/img/album-cover-01@2x.jpg" alt="album cover image">
        <div class="img__block">
          <h6 class="mb-0 f-xs f-semi uc">2.5k photos</h6>
          <h4 class="mb-0 f-md f-bold">All Photos</h4>

          <!-- meta -->
          <div class="img__meta">
            <div class="img__icons">
              <svg class="mr-1" width="10" height="12" viewBox="0 0 10 12">
                <path fill="#353543" d="M2,5 L2,3 C2,1.34314575 3.34314575,0 5,0 C6.65685425,0 8,1.34314575 8,3 L8,5 L9,5 C9.55228475,5 10,5.44771525 10,6 L10,11 C10,11.5522847 9.55228475,12 9,12 L1,12 C0.44771525,12 6.76353751e-17,11.5522847 0,11 L0,6 C-6.76353751e-17,5.44771525 0.44771525,5 1,5 L1,5 L2,5 Z M3,5 L7,5 L7,3 C7,1.8954305 6.1045695,1 5,1 C3.8954305,1 3,1.8954305 3,3 L3,5 Z"/>
              </svg>
              <svg style="transform: translateY(1.5px);" width="13" height="13" viewBox="0 0 13 13">
                <g fill="#353543">
                  <path d="M10.8373571 3.23384286L9.82428571 4.98791429C10.0443571 5.4587 10.1762143 5.97962857 10.1762143 6.53398571 10.1762143 8.45148571 8.70257143 10.0077714 6.82871429 10.1767714L6.29571429 11.1007C6.36442857 11.1025571 6.43035714 11.1099857 6.5 11.1099857 10.2142857 11.1099857 13 8.35305714 13 6.46712857 13 5.47634286 12.1772857 4.19862857 10.8373571 3.23384286M7.37137143 4.86190714C7.11137143 4.72076429 6.81701429 4.63626429 6.50037143 4.63626429 5.47337143 4.63626429 4.64137143 5.46826429 4.64137143 6.49433571 4.64137143 7.16012143 4.99701429 7.73490714 5.52444286 8.06083571L4.60422857 9.65519286C3.54194286 9.01355 2.82415714 7.86583571 2.82415714 6.53333571 2.82415714 4.50347857 4.46958571 2.85805 6.50037143 2.85805 7.14108571 2.85805 7.73444286 3.03633571 8.25722857 3.32790714L7.37137143 4.86190714zM10.6789429.0621214286C10.4560857-.0660214286 10.1728714.0101214286 10.0447286.23205L8.8933 2.22662143C8.15972857 1.97497857 7.35465714 1.82455 6.50037143 1.82455 2.78608571 1.82455.000371428571 4.63812143.000371428571 6.46740714.000371428571 7.89926429 1.61887143 9.81862143 4.02108571 10.66455L3.08044286 12.2951214C2.95137143 12.51705 3.02751429 12.8002643 3.25037143 12.9293357 3.4723 13.0574786 3.75644286 12.9813357 3.88458571 12.7594071L10.8488714.696335714C10.9770143.474407143 10.9008714.190264286 10.6789429.0621214286L10.6789429.0621214286z"/>
                </g>
              </svg>
            </div>

            <div class="album-actions">
              <h5 class="pointer mr-0 f-xs f-semi uc">actions</h5>
              <svg style="margin-top: -2px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
              </svg>
            </div>
          </div>

        </div>
      </figure>

      <!-- album -->
      <figure>
        <img src="../assets/img/album-cover-02@2x.jpg" alt="album cover image">
        <div class="img__block">
          <h6 class="mb-0 f-xs f-semi uc">1260 photos</h6>
          <h4 class="mb-0 f-md f-bold">Ceremony</h4>

          <!-- meta -->
          <div class="img__meta">
            <div class="img__icons">
              <svg class="mr-1" width="10" height="12" viewBox="0 0 10 12">
                <path fill="#353543" d="M2,5 L2,3 C2,1.34314575 3.34314575,0 5,0 C6.65685425,0 8,1.34314575 8,3 L8,5 L9,5 C9.55228475,5 10,5.44771525 10,6 L10,11 C10,11.5522847 9.55228475,12 9,12 L1,12 C0.44771525,12 6.76353751e-17,11.5522847 0,11 L0,6 C-6.76353751e-17,5.44771525 0.44771525,5 1,5 L1,5 L2,5 Z M3,5 L7,5 L7,3 C7,1.8954305 6.1045695,1 5,1 C3.8954305,1 3,1.8954305 3,3 L3,5 Z"/>
              </svg>
              <svg style="opacity: 0; transform: translateY(1.5px);" width="13" height="13" viewBox="0 0 13 13">
                <g fill="#353543">
                  <path d="M10.8373571 3.23384286L9.82428571 4.98791429C10.0443571 5.4587 10.1762143 5.97962857 10.1762143 6.53398571 10.1762143 8.45148571 8.70257143 10.0077714 6.82871429 10.1767714L6.29571429 11.1007C6.36442857 11.1025571 6.43035714 11.1099857 6.5 11.1099857 10.2142857 11.1099857 13 8.35305714 13 6.46712857 13 5.47634286 12.1772857 4.19862857 10.8373571 3.23384286M7.37137143 4.86190714C7.11137143 4.72076429 6.81701429 4.63626429 6.50037143 4.63626429 5.47337143 4.63626429 4.64137143 5.46826429 4.64137143 6.49433571 4.64137143 7.16012143 4.99701429 7.73490714 5.52444286 8.06083571L4.60422857 9.65519286C3.54194286 9.01355 2.82415714 7.86583571 2.82415714 6.53333571 2.82415714 4.50347857 4.46958571 2.85805 6.50037143 2.85805 7.14108571 2.85805 7.73444286 3.03633571 8.25722857 3.32790714L7.37137143 4.86190714zM10.6789429.0621214286C10.4560857-.0660214286 10.1728714.0101214286 10.0447286.23205L8.8933 2.22662143C8.15972857 1.97497857 7.35465714 1.82455 6.50037143 1.82455 2.78608571 1.82455.000371428571 4.63812143.000371428571 6.46740714.000371428571 7.89926429 1.61887143 9.81862143 4.02108571 10.66455L3.08044286 12.2951214C2.95137143 12.51705 3.02751429 12.8002643 3.25037143 12.9293357 3.4723 13.0574786 3.75644286 12.9813357 3.88458571 12.7594071L10.8488714.696335714C10.9770143.474407143 10.9008714.190264286 10.6789429.0621214286L10.6789429.0621214286z"/>
                </g>
              </svg>
            </div>

            <div class="album-actions">
              <h5 class="pointer mr-0 f-xs f-semi uc">actions</h5>
              <svg style="margin-top: -2px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
              </svg>
            </div>
          </div>

        </div>
      </figure>

      <!-- album -->
      <figure>
        <img src="../assets/img/album-cover-03@2x.jpg" alt="album cover image">
        <div class="img__block">
          <h6 class="mb-0 f-xs f-semi uc">1240 photos</h6>
          <h4 class="mb-0 f-md f-bold">Reception</h4>

          <!-- meta -->
          <div class="img__meta">
            <div class="op-0 img__icons">
              <svg class="mr-1" width="10" height="12" viewBox="0 0 10 12">
                <path fill="#353543" d="M2,5 L2,3 C2,1.34314575 3.34314575,0 5,0 C6.65685425,0 8,1.34314575 8,3 L8,5 L9,5 C9.55228475,5 10,5.44771525 10,6 L10,11 C10,11.5522847 9.55228475,12 9,12 L1,12 C0.44771525,12 6.76353751e-17,11.5522847 0,11 L0,6 C-6.76353751e-17,5.44771525 0.44771525,5 1,5 L1,5 L2,5 Z M3,5 L7,5 L7,3 C7,1.8954305 6.1045695,1 5,1 C3.8954305,1 3,1.8954305 3,3 L3,5 Z"/>
              </svg>
              <svg style="transform: translateY(1.5px);" width="13" height="13" viewBox="0 0 13 13">
                <g fill="#353543">
                  <path d="M10.8373571 3.23384286L9.82428571 4.98791429C10.0443571 5.4587 10.1762143 5.97962857 10.1762143 6.53398571 10.1762143 8.45148571 8.70257143 10.0077714 6.82871429 10.1767714L6.29571429 11.1007C6.36442857 11.1025571 6.43035714 11.1099857 6.5 11.1099857 10.2142857 11.1099857 13 8.35305714 13 6.46712857 13 5.47634286 12.1772857 4.19862857 10.8373571 3.23384286M7.37137143 4.86190714C7.11137143 4.72076429 6.81701429 4.63626429 6.50037143 4.63626429 5.47337143 4.63626429 4.64137143 5.46826429 4.64137143 6.49433571 4.64137143 7.16012143 4.99701429 7.73490714 5.52444286 8.06083571L4.60422857 9.65519286C3.54194286 9.01355 2.82415714 7.86583571 2.82415714 6.53333571 2.82415714 4.50347857 4.46958571 2.85805 6.50037143 2.85805 7.14108571 2.85805 7.73444286 3.03633571 8.25722857 3.32790714L7.37137143 4.86190714zM10.6789429.0621214286C10.4560857-.0660214286 10.1728714.0101214286 10.0447286.23205L8.8933 2.22662143C8.15972857 1.97497857 7.35465714 1.82455 6.50037143 1.82455 2.78608571 1.82455.000371428571 4.63812143.000371428571 6.46740714.000371428571 7.89926429 1.61887143 9.81862143 4.02108571 10.66455L3.08044286 12.2951214C2.95137143 12.51705 3.02751429 12.8002643 3.25037143 12.9293357 3.4723 13.0574786 3.75644286 12.9813357 3.88458571 12.7594071L10.8488714.696335714C10.9770143.474407143 10.9008714.190264286 10.6789429.0621214286L10.6789429.0621214286z"/>
                </g>
              </svg>
            </div>

            <div class="album-actions">
              <h5 class="pointer mr-0 f-xs f-semi uc">actions</h5>
              <svg style="margin-top: -2px;" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
                <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
              </svg>
            </div>
          </div>

        </div>
      </figure>

    </section>

    <section class="photos">
      <!-- header -->
      <header class="albums-header mb-1">
        <h3 class="title f-lg f-bold">Photos</h3>
        <!-- actions -->
        <div class="mb-4 actions">
          <div class="pointer sorting">
            <h5 class="mr-0 f-sm f-semi op-5 uc">sort:</h5>
            <h5 class="f-sm f-semi uc">timestamp</h5>
            <svg style="transform: translateY(-2px);" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
              <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
            </svg>
          </div>
          <div class="pointer tools">
            <h5 class="mr-3 f-sm f-semi uc">add photos</h5>
            <h5 class="mr-3 f-sm f-semi uc">edit watermark</h5>
            <h5 class="mr-0 f-sm f-semi uc">photo tools</h5>
            <svg style="transform: translateY(-2px);" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
              <path fill="#353543" fill-rule="evenodd" d="M6.70710678,6.70710678 C6.88807119,6.52614237 7,6.27614237 7,6 L7,1 C7,0.44771525 6.55228475,-1.01453063e-16 6,0 C5.44771525,1.01453063e-16 5,0.44771525 5,1 L5,1 L5,5 L1,5 C0.44771525,5 -6.40303515e-18,5.44771525 6.123234e-17,6 L6.123234e-17,6 L6.123234e-17,6 C1.28867715e-16,6.55228475 0.44771525,7 1,7 L1,7 L6,7 C6.27614237,7 6.52614237,6.88807119 6.70710678,6.70710678 Z" transform="rotate(45 2.768 10.096)"/>
            </svg>
          </div>
        </div>
      </header>

      <div class="photo-wrapper">
        <div class="img-wrapper">
          <img src="../assets/img/01@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/02@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/03@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/04@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/05@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/06@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/07@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/08@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/09@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/10@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/11@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/12@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/13@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/14@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/15@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/16@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <!-- -->
        <div class="img-wrapper">
          <img src="../assets/img/01@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/02@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/03@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/04@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/05@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/06@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/07@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/08@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/09@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/10@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/11@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/12@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/13@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/14@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/15@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
        <div class="img-wrapper">
          <img src="../assets/img/16@2x.jpg" alt="">
          <span class="mt-1 op-6 f-sm">Zach_Cathy_Wedding_geodun-683.JPG</span>
        </div>
      </div>

    </section>

  </div>
</template>


<!-- style -->
<style scoped lang="scss">
  @import '../assets/style/mq';
  @import '../assets/style/type';

  .photo-wrapper {
    display: flex;
    flex-wrap: wrap;
  }

  .img-wrapper {
    display: flex;
    flex-direction: column;
    max-width: 25%;
    margin-bottom: 28px;

    img { cursor: pointer; width: 84%; border-radius: 4px; transition: transform 500ms ease, box-shadow 200ms ease; }
    img:hover { transform: translateY(-8px); box-shadow: 0px 32px 56px -38px rgba(0,0,0,.2); }
  }

  .albums-photos {
    display: flex;
    width: 80%;
  }

  .photos {
    // border: 1px solid green;
    padding: 75px 24px 0;
    width: 72%; height: 100vh;
    overflow-y: scroll;
  }

  .albums {
    @include breakpoint(mdl) {
      padding: 75px 16px 0 16px;
      max-width: 280px; width: 33%; height: 100vh;
      overflow-y: scroll;
    }
  }

  .albums-header {
    display: flex;
    justify-content: flex-end;

    position: sticky;
    top: 0;
    z-index: var(--z3);

    h3 { margin-right: auto; }
    svg { margin-top: 2px; opacity: .5; }
  }

  .albums-header::after {
    content: '';
    position: absolute;
    top: -20px;
    width: 150%; height: 100%;
    background: var(--cloud);
    transform: translateX(-50px);
    z-index: var(--z0);
  }

 .albums-header, .album-actions, .sorting, .tools, .album-meta {
    display: flex;
    justify-content: flex-end;
  }

  .title { margin-bottom: 9px; }

  .actions { display: flex; }
  .albums-header { flex-direction: column; }
  .sorting, .stats { margin-right: auto; }

  figure {
    border-radius: 9px;
    box-shadow: 0px 32px 56px -38px rgba(0,0,0,.4);
    margin-bottom: 40px;
  }

  figure:last-of-type {
    margin-bottom: 180px;
  }

  .active { border: 4px solid var(--primary); }

  img {
    position: relative;
    border-radius: 6px 6px 0 0;
    z-index: var(--z2);
  }

  .img__block {
    position: relative;
    padding: 8px 16px 6px 16px;
    width: 100%;
    border-radius: 0 0 6px 6px ;
    background: var(--cloud);
    z-index: var(--z1);
  }

  .img__meta { margin-top: -12px; padding-bottom: 4px; }
  .img__icons { transform: translateY(15px); }

</style>


<!-- logic -->
<script>
  export default {
    name: 'album' ,

    mounted() {

    }
  }
</script>
