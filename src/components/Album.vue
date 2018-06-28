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
            <h5 class="mr-0 f-sm f-semi op-5 uc">sort by:</h5>
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
            <h5 class="mr-0 f-sm f-semi op-5 uc">sort by:</h5>
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

      <p class="debug">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Leo urna molestie at elementum. Ipsum dolor sit amet consectetur adipiscing elit. At in tellus integer feugiat. Cras pulvinar mattis nunc sed. Vitae auctor eu augue ut lectus. Facilisi cras fermentum odio eu feugiat pretium. Turpis massa sed elementum tempus egestas sed. In aliquam sem fringilla ut. Nec feugiat in fermentum posuere urna. Risus sed vulputate odio ut enim blandit volutpat maecenas. Tortor id aliquet lectus proin nibh nisl condimentum. Tristique senectus et netus et. Accumsan lacus vel facilisis volutpat est. Orci dapibus ultrices in iaculis nunc sed augue lacus. Vulputate dignissim suspendisse in est ante in nibh mauris cursus. Consectetur adipiscing elit duis tristique sollicitudin nibh sit amet. Tincidunt vitae semper quis lectus nulla at volutpat diam ut. Ullamcorper dignissim cras tincidunt lobortis feugiat vivamus. Cursus risus at ultrices mi tempus.

        Parturient montes nascetur ridiculus mus mauris vitae ultricies leo integer. Quam quisque id diam vel quam elementum. Scelerisque viverra mauris in aliquam sem fringilla ut morbi tincidunt. Velit scelerisque in dictum non. Lorem ipsum dolor sit amet. Tortor posuere ac ut consequat semper viverra. Enim sit amet venenatis urna. Purus non enim praesent elementum facilisis. Gravida arcu ac tortor dignissim. Eu nisl nunc mi ipsum faucibus vitae aliquet nec ullamcorper. Vehicula ipsum a arcu cursus vitae congue. Risus commodo viverra maecenas accumsan lacus vel facilisis. Sed risus ultricies tristique nulla aliquet enim. Tincidunt id aliquet risus feugiat in.

        Arcu cursus vitae congue mauris rhoncus. Interdum posuere lorem ipsum dolor sit amet consectetur adipiscing elit. Lorem ipsum dolor sit amet consectetur adipiscing elit. Arcu odio ut sem nulla. Sed odio morbi quis commodo odio. Senectus et netus et malesuada fames ac turpis. Senectus et netus et malesuada fames. Suspendisse ultrices gravida dictum fusce ut placerat orci nulla pellentesque. Venenatis cras sed felis eget velit aliquet sagittis. Eget mauris pharetra et ultrices neque ornare aenean. Diam maecenas ultricies mi eget mauris. Egestas sed tempus urna et pharetra pharetra massa massa ultricies. Porttitor eget dolor morbi non arcu risus quis varius quam. Erat nam at lectus urna duis. Nibh tellus molestie nunc non. Mi ipsum faucibus vitae aliquet nec ullamcorper sit. Tincidunt id aliquet risus feugiat in ante metus. Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum posuere. Id velit ut tortor pretium viverra suspendisse potenti nullam ac.

        At tempor commodo ullamcorper a lacus vestibulum sed arcu non. Leo vel orci porta non pulvinar neque laoreet. Sagittis id consectetur purus ut faucibus pulvinar elementum integer. Tempor orci eu lobortis elementum nibh tellus. Mollis nunc sed id semper risus in hendrerit gravida. Vitae tempus quam pellentesque nec nam aliquam. Suspendisse potenti nullam ac tortor vitae purus faucibus ornare. Faucibus et molestie ac feugiat. Vestibulum rhoncus est pellentesque elit. Arcu dictum varius duis at. Convallis convallis tellus id interdum velit laoreet id donec. Pharetra diam sit amet nisl suscipit adipiscing bibendum est. Integer malesuada nunc vel risus commodo viverra maecenas. Fusce id velit ut tortor pretium viverra suspendisse. Blandit aliquam etiam erat velit. Maecenas sed enim ut sem viverra aliquet eget sit amet.

        Sollicitudin aliquam ultrices sagittis orci. Tellus mauris a diam maecenas sed enim. Eget nunc scelerisque viverra mauris in aliquam sem. Id velit ut tortor pretium viverra suspendisse potenti nullam. Non nisi est sit amet. Donec ultrices tincidunt arcu non. Lectus proin nibh nisl condimentum id venenatis a. Nisi quis eleifend quam adipiscing vitae proin. Felis imperdiet proin fermentum leo vel orci. Auctor neque vitae tempus quam pellentesque nec nam. Sit amet commodo nulla facilisi nullam vehicula. Quam quisque id diam vel quam elementum pulvinar etiam. Vulputate dignissim suspendisse in est ante in. Quis vel eros donec ac odio. Amet porttitor eget dolor morbi non arcu. Malesuada pellentesque elit eget gravida. Vel facilisis volutpat est velit. Maecenas accumsan lacus vel facilisis. Penatibus et magnis dis parturient.
      </p>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Leo urna molestie at elementum. Ipsum dolor sit amet consectetur adipiscing elit. At in tellus integer feugiat. Cras pulvinar mattis nunc sed. Vitae auctor eu augue ut lectus. Facilisi cras fermentum odio eu feugiat pretium. Turpis massa sed elementum tempus egestas sed. In aliquam sem fringilla ut. Nec feugiat in fermentum posuere urna. Risus sed vulputate odio ut enim blandit volutpat maecenas. Tortor id aliquet lectus proin nibh nisl condimentum. Tristique senectus et netus et. Accumsan lacus vel facilisis volutpat est. Orci dapibus ultrices in iaculis nunc sed augue lacus. Vulputate dignissim suspendisse in est ante in nibh mauris cursus. Consectetur adipiscing elit duis tristique sollicitudin nibh sit amet. Tincidunt vitae semper quis lectus nulla at volutpat diam ut. Ullamcorper dignissim cras tincidunt lobortis feugiat vivamus. Cursus risus at ultrices mi tempus.

        Parturient montes nascetur ridiculus mus mauris vitae ultricies leo integer. Quam quisque id diam vel quam elementum. Scelerisque viverra mauris in aliquam sem fringilla ut morbi tincidunt. Velit scelerisque in dictum non. Lorem ipsum dolor sit amet. Tortor posuere ac ut consequat semper viverra. Enim sit amet venenatis urna. Purus non enim praesent elementum facilisis. Gravida arcu ac tortor dignissim. Eu nisl nunc mi ipsum faucibus vitae aliquet nec ullamcorper. Vehicula ipsum a arcu cursus vitae congue. Risus commodo viverra maecenas accumsan lacus vel facilisis. Sed risus ultricies tristique nulla aliquet enim. Tincidunt id aliquet risus feugiat in.

        Arcu cursus vitae congue mauris rhoncus. Interdum posuere lorem ipsum dolor sit amet consectetur adipiscing elit. Lorem ipsum dolor sit amet consectetur adipiscing elit. Arcu odio ut sem nulla. Sed odio morbi quis commodo odio. Senectus et netus et malesuada fames ac turpis. Senectus et netus et malesuada fames. Suspendisse ultrices gravida dictum fusce ut placerat orci nulla pellentesque. Venenatis cras sed felis eget velit aliquet sagittis. Eget mauris pharetra et ultrices neque ornare aenean. Diam maecenas ultricies mi eget mauris. Egestas sed tempus urna et pharetra pharetra massa massa ultricies. Porttitor eget dolor morbi non arcu risus quis varius quam. Erat nam at lectus urna duis. Nibh tellus molestie nunc non. Mi ipsum faucibus vitae aliquet nec ullamcorper sit. Tincidunt id aliquet risus feugiat in ante metus. Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum posuere. Id velit ut tortor pretium viverra suspendisse potenti nullam ac.

        At tempor commodo ullamcorper a lacus vestibulum sed arcu non. Leo vel orci porta non pulvinar neque laoreet. Sagittis id consectetur purus ut faucibus pulvinar elementum integer. Tempor orci eu lobortis elementum nibh tellus. Mollis nunc sed id semper risus in hendrerit gravida. Vitae tempus quam pellentesque nec nam aliquam. Suspendisse potenti nullam ac tortor vitae purus faucibus ornare. Faucibus et molestie ac feugiat. Vestibulum rhoncus est pellentesque elit. Arcu dictum varius duis at. Convallis convallis tellus id interdum velit laoreet id donec. Pharetra diam sit amet nisl suscipit adipiscing bibendum est. Integer malesuada nunc vel risus commodo viverra maecenas. Fusce id velit ut tortor pretium viverra suspendisse. Blandit aliquam etiam erat velit. Maecenas sed enim ut sem viverra aliquet eget sit amet.

        Sollicitudin aliquam ultrices sagittis orci. Tellus mauris a diam maecenas sed enim. Eget nunc scelerisque viverra mauris in aliquam sem. Id velit ut tortor pretium viverra suspendisse potenti nullam. Non nisi est sit amet. Donec ultrices tincidunt arcu non. Lectus proin nibh nisl condimentum id venenatis a. Nisi quis eleifend quam adipiscing vitae proin. Felis imperdiet proin fermentum leo vel orci. Auctor neque vitae tempus quam pellentesque nec nam. Sit amet commodo nulla facilisi nullam vehicula. Quam quisque id diam vel quam elementum pulvinar etiam. Vulputate dignissim suspendisse in est ante in. Quis vel eros donec ac odio. Amet porttitor eget dolor morbi non arcu. Malesuada pellentesque elit eget gravida. Vel facilisis volutpat est velit. Maecenas accumsan lacus vel facilisis. Penatibus et magnis dis parturient.
      </p>
    </section>

  </div>
</template>


<!-- style -->
<style scoped lang="scss">
  @import '../assets/style/mq';
  @import '../assets/style/type';

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
      max-width: 300px; width: 33%; height: 100vh;
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
