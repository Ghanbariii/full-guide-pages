<!-- Please remove this file from your project -->
<template>
  <nav class="nav  flex flex-wrap items-center md:justify-start justify-between px-4 md:px-24">
    <div class="flex flex-no-shrink items-center mr-6 py-5 text-grey-darkest">
      <svg width="40" height="40" viewBox="0 0 58 58" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M51.875 12.125C46.625 5.375 38.375 0.5 29 0.5C13.25 0.5 0.5 13.25 0.5 29V53C0.5 55.625 2.375 57.5 5 57.5H29C38.375 57.5 46.625 53 51.875 45.875C53.75 43.625 54.875 41 56 38C56.75 35 57.5 32 57.5 29C57.5 22.625 55.25 17 51.875 12.125Z"
          fill="url(#paint0_linear_509_1221)" />
        <path
          d="M46.625 29C46.625 34.625 44 39.5 39.875 42.875C38.75 44 36.875 44 35.75 42.875C34.25 41.375 33.875 39.125 35.75 37.625C38.375 35.75 39.875 32.375 39.875 29C39.875 25.625 38.375 22.25 35.75 20.375C33.875 18.875 34.25 16.625 35.75 15.125C36.875 14 38.75 14 39.875 15.125C44 18.5 46.625 23.375 46.625 29Z"
          fill="#5EFFB1" />
        <path
          d="M33.5 45.5C32 44 30.875 42.125 30.875 40.25C30.875 39.5 30.875 38.75 31.25 38C30.5 38.375 29.75 38.375 28.625 38.375C23.375 38.375 19.25 34.25 19.25 29C19.25 23.75 23.75 20 29 20C29.75 20 30.5 20 31.625 20.375C31.25 19.625 30.875 18.5 30.875 17.75C30.875 15.875 31.625 13.625 33.5 12.5C34.625 12.125 35.375 11.375 36.5 11.375C34.25 10.25 31.625 9.875 29 9.875C18.5 9.875 9.875 18.5 9.875 29C9.875 39.5 18.5 48.125 29 48.125C31.625 48.125 34.25 47.75 36.5 46.625C35.375 46.625 34.625 46.25 33.5 45.5Z"
          fill="#F8FAFB" />
        <defs>
          <linearGradient id="paint0_linear_509_1221" x1="7.46225" y1="54.7449" x2="47.4496" y2="6.9335"
            gradientUnits="userSpaceOnUse">
            <stop offset="6.92613e-08" stop-color="#13B38B" />
            <stop offset="1" stop-color="#16CEA0" />
          </linearGradient>
        </defs>
      </svg>
    </div>

    <input class="menu-btn hidden" type="checkbox" id="menu-btn">
    <label class="menu-icon block cursor-pointer md:hidden px-2 py-4 relative select-none" for="menu-btn">
      <span class="navicon flex items-center relative"></span>
    </label>
    <ul class="menu border-b md:border-none flex justify-evenly list-reset m-0 w-full md:w-auto font-regular text-lg navbar__right animate__animated animate__slideInRight">
      <li class="border-t md:border-none hover-underline-animation">
        <a href="#page1"
          class="block md:inline-block px-4 py-3 no-underline target" id='target1'>پنل های کاروان 
          </a>
      </li>
      <li class="border-t md:border-none hover-underline-animation">
        <a href="/"
          class="block md:inline-block px-4 py-3 no-underline "> امکانات
          </a>
      </li>
      <li class="border-t md:border-none hover-underline-animation">
        <a href="/"
          class="block md:inline-block px-4 py-3 no-underline ">راهنمای کاروان 
          </a>
      </li>
      <li class="border-t md:border-none hover-underline-animation">
        <a href="/"
          class="block md:inline-block px-4 py-3 no-underline ">  تماس با ما 
          </a>
      </li>
    </ul>
    <ul class="menu border-b md:border-none flex list-reset m-0 w-full md:w-auto mr-auto text-lg customize-color animate__animated animate__slideInRight animate__animated">
      <li class="border-t md:border-non">
        <a href="/"
          class="block md:inline-block px-4 py-3 no-underline font-regular">سفارشات
          روز</a>
      </li>
      <div class="md:flex items-center hidden ml-5">
        <img src="../assets/img/first page/png/button-link-icon.png" alt="Button">
      </div>

      <li class="border-t md:border-none">
        <a href="/about/"
          class="block md:inline-block px-4 py-3 no-underline font-regular">ورود به حساب
          کاربری</a>
      </li>
      <div class="md:flex items-center hidden">
        <img src="../assets/img/first page/png/button-account-icon.png" alt="Button">
      </div>
    </ul>
  </nav>
</template>


<style>
@media (max-width: 769px) {
  ul li{
    font-size: 10px;
  }
}
@media (max-width: 1107px) {
  ul li{
    font-size: 13px;
  }
  nav{
    padding:0 9px !important;
  }
}
body {
  direction: rtl;
}
.active:active {
    color: #24A973;
}

.focus:focus {
    color: #24A973;
}

:target {
    color: #24A973;
}
.hover-underline-animation{
  position: relative;
  text-decoration: none;
  color: #26292B;
}
.hover-underline-animation::after {
  content: '';
  position: absolute;
  width: 60%;
  height: 3px;
  bottom: 0;
  left: 0;
  background-color: #54DBA4;
  transform-origin: bottom right;
  transition: transform 0.25s ease-out;
}
.hover-underline-animation::after{
  transform: scaleX(0);
}
.hover-underline-animation:hover::after {
  transform: scaleX(1);
}
.hover-underline-animation:hover::after {

  transform-origin: bottom left;
}
.navbar__right a:hover {
 color: #54DBA4;
 padding-bottom: 0.75rem;
 padding-top: 0.75rem;
 padding-right: 1rem; /* 16px */

}
/*Transition*/
* {
 transition-timing-function: ease-in-out;
 -ms-transition-timing-function: ease-in-out;
 -moz-transition-timing-function: ease-in-out;
 -webkit-transition-timing-function: ease-in-out;
 -o-transition-timing-function: ease-in-out;
 transition-duration: 0.1s;
 -ms-transition-duration: 0.1s;
 -moz-transition-duration: 0.1s;
 -webkit-transition-duration: 0.1s;
 -o-transition-duration: 0.1s;
}

.customize-color a:hover{
  border: 2px solid #24A973;
  border-radius:10px;
}

* {
 transition-timing-function: ease-in-out;
 -ms-transition-timing-function: ease-in-out;
 -moz-transition-timing-function: ease-in-out;
 -webkit-transition-timing-function: ease-in-out;
 -o-transition-timing-function: ease-in-out;
 transition-duration: 0.1s;
 -ms-transition-duration: 0.1s;
 -moz-transition-duration: 0.1s;
 -webkit-transition-duration: 0.1s;
 -o-transition-duration: 0.1s;
}

@media (max-width: 767px) {
  .navicon {
    width: 1.125em;
    height: .125em;
  }

  .navicon::before,
  .navicon::after {
    display: block;
    position: absolute;
    width: 100%;
    height: 100%;
    transition: all .2s ease-out;
    content: '';
    background: #3D4852;
  }

  .navicon::before {
    top: 5px;
  }

  .navicon::after {
    top: -5px;
  }

  .menu-btn:not(:checked)~.menu {
    display: none;
  }

  .menu-btn:checked~.menu {
    display: block;
  }

  .menu-btn:checked~.menu-icon .navicon {
    background: transparent;
  }

  .menu-btn:checked~.menu-icon .navicon::before {
    transform: rotate(-45deg);
  }

  .menu-btn:checked~.menu-icon .navicon::after {
    transform: rotate(45deg);
  }

  .menu-btn:checked~.menu-icon .navicon::before,
  .menu-btn:checked~.menu-icon .navicon::after {
    top: 0;
  }
}

.customize-color{
  color: #24A973;
}
</style>

<script>
export default {
  name: 'NuxtTutorial'
}

const toggle = () => {
  const nav = document.getElementById("topnav");
  nav.className === "topnav" ? nav.className += " responsive" : nav.className = "topnav";
};
</script>
