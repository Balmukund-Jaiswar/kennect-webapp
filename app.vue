<template>
<div class="m-0 p-0 h-screen flex flex-col">
  <header class="lg:h-[12vh] lg:px-24 h-12 bg-white sticky top-0 flex justify-between items-center  bg-[#fff] grow-0">
    <div class="left-2 top-2 h-24 ml-2 w-24 lg:w-36 lg:h-36">
      <img src="./assets/mobile-pics/Artboard 1full logo.png" alt="avatar" class="h-full w-full mt-1">
    </div>
    <div class="hidden lg:flex text-[#004749] justify-between gap-x-10 mt-3 items-center">
      <p>Solution</p>
      <p>Industries</p>
      <p>Resources</p>
      <p>Company</p>
      <p>Pricing</p>
      <div class="flex gap-x-6">
        <button type="button" class="bg-[#ff4261] text-[#fff] rounded-full text-sm font-medium py-1 px-4">
          BOOK A MEETING
        </button>
        <button class="border-solid border-2 px-2 py-0.5 rounded-full">
          Login
        </button>
      </div>
    </div>
    <div class="menuhide icon nav-icon-5"
      :class="{open:isMenuOpen}"
      @click="isMenuOpen=!isMenuOpen"
    >
      <span></span>
      <span></span>
      <span></span>
    </div>
  </header>
  <div class="lg:flex lg:gap-x-10 lg:bg-[#047d80] lg:h-[88vh] lg:justify-center">
    <div class="bg-[#047d80] pt-8 pb-6 text-[#fff] lg:pl-20 lg:pt-16 lg:min-w-[650px] lg:max-w-[650px] lg:shrink-0 lg:grow">
      <h2 class="text-center lg:text-left text-xl font-bold px-5 lg:px-0 lg:text-4xl">
        Run your <span class="text-[#05dee3]">sales compensation</span> programs in <img src="./assets/mobile-pics/cruise mode! mobile.png" alt="crrtyu" class="lg:h-[27px] lg:w-auto h-[17.5px] w-32 inline mb-1">
      </h2>
      <p class="text-[9.5px] text-center lg:text-left px-3 mt-3 mb-4 lg:pl-0 lg:pr-24 lg:text-xl lg:mt-10">
        Build, run and automate your incentive compensation plans to create transparency and achieve operationl efficiency.
      </p>
      <button type="button" class="hidden lg:block bg-[#ff4261] rounded-full py-2 px-3 shadow-gray my-8">
        Let's KENNECT
      </button>
      <div class="hidden lg:h-32 lg:grow-0 lg:flex lg:flex-col" >
        <div class="grow flex flex-col">
          <h1 class="text-[#fff] text-base font-bold">
            Trusted By
          </h1>
        </div>
        <div class="slider grow-0">
          <div class="slide-track">
            <div class="slide">
              <img src="./assets/desktop-pic/Lupin white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/Swigg white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/boehringer-ingelheim-international white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/Astrazeneca white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/Incyte white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/Lonza white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/Zydus white.png" class="h-[40px] w-auto" alt="" />
            </div>
            <div class="slide">
              <img src="./assets/desktop-pic/sanofi white.png" class="h-[35px] w-auto" alt="" />
            </div>
          </div>
        </div>
      </div>
    <!-- desktop carousel below -->
      <div class="flex flex-col items-center lg:hidden">
        <form class="rounded-full bg-[#fff] p-0.5 flex items-center">
          <input class="focus:outline-none text-gray text-[11px] placeholder:text-slate-600 ml-2" placeholder="Enter your Work Email" type="email" pattern="[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{1,63}$" required>
            <button class="bg-[#ff4261] rounded-full text-[11px] px-2 py-1.5" type="button">BOOK A DEMO</button>
        </form>
        <p class="text-[5px] mt-1.5">
          By Submitting this form, you are agreeging to Kennect's <span class="underline">Privacy Policy</span> and <span class="underline">Terms of Service.</span>
        </p>
      </div>
      <div class="flex justify-center gap-x-6 ml-2 pt-6 pb-5 px-8 lg:hidden">
          <img src="./assets/mobile-pics/G2 monile rating.png" alt="avatar" class="h-auto max-w-[120px] min-w-[80px]">
          <img src="./assets/mobile-pics/Gartner mobile rating.png" alt="avatar" class="h-auto max-w-[156px] min-w-[104px]">
      </div>
      <div class="flex justify-center gap-x-6 mr-4 px-14 lg:hidden">
          <img src="./assets/mobile-pics/Copy of SalesCompensation_HighPerformer_HighPerformer copy.png" alt="avatar" class="h-auto max-w-[120px] min-w-[80px]">
          <img src="./assets/mobile-pics/Copy of SalesCompensation_EasiestToDoBusinessWith_Enterprise_EaseOfDoingBusinessWith copy.png" alt="avatar" class="h-auto max-w-[120px] min-w-[80px]">
      </div>
    </div>
    <div class="hidden lg:flex lg:shrink lg:pt-10 lg:justify-center lg:items-end">
      <div class="lg:relative lg:flex lg:justify-center lg:items-center lg:mr-20 w-[62%]">
        <img src="./assets/desktop-pic/heroImage.png" alt="avatar" class="w-auto flex-initial">
        <img src="./assets/desktop-pic/G2 rating home page.png" alt="avatar" class="h-auto w-[35%] absolute top-[20%] left-[-10%]">
        <img src="./assets/desktop-pic/easyBusiness.png" alt="avatar" class="h-auto w-[30%] absolute top-[-15%] left-[10%]">
        <img src="./assets/desktop-pic/Gartner rating home page.png" alt="avatar" class="h-auto w-[50%] absolute top-[-10%] left-[65%]">
        <img src="./assets/desktop-pic/highPerformer.png" alt="avatar" class="h-auto w-[30%] absolute top-[10%] right-[-18%]">
      </div>
    </div>
    <div class="h-32 grow-0 flex flex-col lg:hidden" >
      <div class="grow flex flex-col items-center justify-center">
        <h1 class="text-[#004749] text-base font-bold text-center">
          Trusted By
        </h1>
        <span class="w-[18px] bg-[#ff4261] h-[2px] rounded-2xl"> 
        </span>
      </div>
      <div class="slider grow-0">
        <div class="slide-track">
          <div class="slide">
            <img src="./assets/mobile-pics/2070612.png" class="h-[50px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/62722382edf1cc560f13cfad_Swiggy-Logo-2-300x120.png" class="h-[50px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/Ajanta.png" class="h-[50px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/astrazeneca-logo.png" class="h-[60px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/Incyte_logo.svg.png" class="h-[50px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/logo indoco.png" class="h-[40px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/logo sanofi.png" class="h-[35px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/Looza.png" class="h-[50px] w-auto" alt="" />
          </div>
          <div class="slide">
            <img src="./assets/mobile-pics/Zydus logo.png" class="h-[50px] w-auto" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default{
  data(){
    return{
      isMenuOpen:false
    }
  }
}
</script>

<style>
.nav-icon-5{
  width: 25px;
  height: 21px;
  margin: 8px 15px;
  position: relative;
  cursor: pointer;
  display: inline-block;
}
.nav-icon-5 span{
  background-color:#c1b6b6;
  position: absolute;
  border-radius: 2px;
  transition: .3s cubic-bezier(.8, .5, .2, 1.4);
  width:100%;
  height: 3px;
  transition-duration: 200ms
}
.nav-icon-5 span:nth-child(1){
  top:0px;
  left: 0px;
}
.nav-icon-5 span:nth-child(2){
  top:9px;
  left: 0px;
  opacity:1;
}
.nav-icon-5 span:nth-child(3){
  bottom:0px;
  left: 0px;
}

.nav-icon-5.open span:nth-child(1){
  transform: rotate(45deg);
  top: 7px;
}
.nav-icon-5.open span:nth-child(2){
  opacity:0;
}
.nav-icon-5.open span:nth-child(3){
  transform: rotate(-45deg);
  top: 7px;
}

.slider {
	background: white; 
	height: 80px;
  padding-top: 15px;
  padding-bottom: 15px;
	margin: auto;
	overflow: hidden;
	position: relative;
	width: 100%;
}

@media screen and (min-width: 1024px) {
  .slider {
    background: none;
  }
  .slider::before,
  .slider::after {
    background: none !important;
  }
  .menuhide{
    display: none !important;
  }
}

.slider::before,
.slider::after {
	background: linear-gradient(to right, rgba(255, 255, 255, 1) 0%, rgba(255, 255, 255, 0) 100%);
	content: "";
	height: 80px;
	position: absolute;
	width: 80px;
	z-index: 2;
}

.slider::after {
	right: 0;
	top: 0;
	transform: rotateZ(180deg);
}

.slider::before {
	left: 0;
	top: 0;
}

.slide-track {
	animation: scroll 20s linear infinite;
	display: flex;
	width: calc(150px * 8);
}

.slide {
	height: 50px;
	width: 160px;
  display: flex;
  justify-content: center;
}

@keyframes scroll {
	0% { transform: translateX(0); }
	100% { transform: translateX(calc(-160px * 7)); }
}

</style>