<template>
   <div class="mt-20 grid grid-cols-12">
   <div class="col-span-2"/>
   <div class="col-span-8">
   <div class="text-5xl font-bold">About Me</div>
   <div class="mt-2">
      <span class="text-3xl select-none">Hi, I'm Carlos, and I create open-source apps out of Austin, Texas. <br/><br/>Connect with me!</span>
      <div class="mt-4 mb-3">
        <a href="https://www.github.com/ccrama" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="mr-2 p-3 shadow-lg bg-black font-bold text-xl text-white rounded-full"><i class="fab fa-github"/>  GitHub</a>
        <a href="https://www.linkedin.com/in/carlos-crane/" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="mr-2 p-3 shadow-lg bg-black font-bold text-xl text-white rounded-full"><i class="fab fa-linkedin"/>  LinkedIn</a>
        <a href="mailto:carloscrane3@gmail.com" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="mr-2 p-3 shadow-lg bg-black font-bold text-xl text-white rounded-full"><i class="fas fa-envelope"></i>  Email</a>
        <a href="https://www.reddit.com/u/ccrama" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="mr-2 p-3 shadow-lg bg-black font-bold text-xl text-white rounded-full"><i class="fab fa-reddit"/>  Reddit</a>
      </div>
   </div>
   <div style="
        background: #111827;
        margin-left: -100%;
        margin-right: -100%;
        padding-left: 100%;
        padding-right: 100%;
        padding-top: 40px;
        padding-bottom: 40px;
        box-shadow: inset 0 0 15px 5px #0000009e;
    " class="grid sm:grid-cols-1 md:grid-cols-1 lg:grid-cols-2 gap-5 mt-20">
      <div class="sm:col-span-1 md:col-span-1 lg:col-span-2 text-5xl text-white font-bold">Apps</div>
      <div class="text-white col-span-1 p-5 border bordered-1 border-blue-500 shadow-xl bg-gradient-to-r from-blue-500 to-purple-400 rounded-3xl">
         <div class="flex">
            <div class="mr-3">
               <img class="rounded-full" style="width: 5rem;height: 5rem;object-fit: cover;max-width: 10000px;" src="../assets/slide_ios.png"/>
            </div>
            <div>
               <span class="select-none font-bold text-2xl">Slide iOS</span>
               <br/>
               <div class="select-none text-xl mb-3">
                  The best way to Reddit on iOS: open source, ad free, privacy focused.
               </div>
            </div>
         </div>
         <div class="mt-5">
            <a href="https://apps.apple.com/us/app/slide-for-reddit/id1260626828" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="p-2 shadow-sm bg-blue-400 font-bold mr-2 text-sm text-white rounded-full"><i class="fab fa-apple"/>  App Store</a>
            <a href="https://github.com/ccrama/Slide-iOS" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="p-2 shadow-sm bg-white font-bold text-sm text-black rounded-full"><i class="fab fa-github"/>  GitHub</a>
         </div>
      </div>
      <div class="text-white col-span-1 p-5 border bordered-1 border-yellow-500 shadow-xl bg-gradient-to-r from-yellow-500 to-red-400 rounded-3xl">
         <div class="flex">
            <div class="mr-3">
               <img class="rounded-full" style="width: 5rem;height: 5rem;object-fit: cover; max-width: 10000px;" src="../assets/slide_ios_rounded.png"/>
            </div>
            <div>
               <span class="font-bold text-2xl select-none">Slide for Reddit</span>
               <br/>
               <div class="text-xl mb-3 select-none">
                  A beautiful, open source Reddit client for Android<br/><br/>
               </div>
            </div>
            </div>
            <div class="mt-5">
              <a href="https://play.google.com/store/apps/details?id=me.ccrama.redditslide" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="p-2 shadow-sm bg-yellow-600 font-bold mr-2 text-sm text-white rounded-full"><i class="fab fa-google-play"/>  Play Store</a>
              <a href="https://f-droid.org/app/me.ccrama.redditslide" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="p-2 shadow-sm bg-yellow-600 font-bold mr-2 text-sm text-white rounded-full"><i class="fab fa-android"></i>  F-Droid</a>
              <a href="https://github.com/ccrama/Slide" style="float: left; margin-top: 0.5rem; margin-bottom: 1.5rem;" class="p-2 shadow-sm bg-white font-bold text-sm text-black rounded-full"><i class="fab fa-github"/>  GitHub</a>
            </div>
            </div>
            <div class="relative select-none text-white overflow-hidden col-span-1 p-5 border bordered-1 border-gray-700 shadow-xl bg-gradient-to-r from-gray-800 to-gray-900 rounded-3xl">
                   <span class="text-white text-3xl font-mono font-bold uppercase absolute" style="text-align: center;top: 50%;transform: translateY(-50%) translateX(-50%);left: 50%;"># Coming soon!</span>
               <div class="flex" style="opacity: 0.1">
                  <div class="mr-3">
                     <img class="rounded-full" style="width: 5rem;height: 5rem;object-fit: cover;max-width: 10000px;" src="../assets/dispatch.png"/>
                  </div>
                  <div>
                     <span class="font-bold text-2xl">Dispatch</span>
                     <br/>
                     <div class="text-xl mb-3">
                        The ultimate push-notification system for Reddit
                     </div>
                  </div>
               </div>
            </div>
            <div class="relative text-white overflow-hidden col-span-1 p-5 border bordered-1 border-gray-700 shadow-xl bg-gradient-to-r from-gray-800 to-gray-900 rounded-3xl">
              <span class="text-white text-3xl font-mono font-bold uppercase absolute" style="text-align: center;top: 50%;transform: translateY(-50%) translateX(-50%);left: 50%;"># Coming soon!</span>
               <div class="flex" style="opacity: 0.1">
                  <div class="mr-3">
                     <img class="rounded-full" style="width: 5rem;height: 5rem;object-fit: cover;max-width: 10000px;" src="../assets/slide2.png"/>
                  </div>
                  <div>
                     <span class="font-bold text-2xl">Slide 2</span>
                     <br/>
                     <div class="text-xl mb-3">
                        A next-generation FOSS Reddit browser for Android
                     </div>
                  </div>
               </div>
            </div>
      </div>
   </div>
   <div class="col-span-2"/>
   </div>
</template>
<script>
   export default {
     name: 'Homepage',
     components: {
     }
   }
</script>
