<template>
    <header class=" p-6 bg-wave">
        <nav>
            <div class="flex flex-row justify-between items-center">
                <div>
                    <RouterLink :to="{name:'Teamiya'}" class="font-rubik text-2xl font-bold text-white">Teamiya</RouterLink>
                </div>
                <div class="flex flex-row gap-10 items-center">
                    <div class="flex flex-col gap-1 group">
                        <a href="#" class="font-gilroyBold text-sm text-white">Demos</a>
                        <div class="hidden mx-auto h-0.5 w-2/3 bg-lightRed group-hover:block"></div>
                    </div>
                    <div class="flex flex-col gap-1 group">
                        <a href="#" class="font-gilroyBold text-sm text-white">Pages</a>
                        <div class="hidden mx-auto h-0.5 w-2/3 bg-lightRed group-hover:block"></div>
                    </div>
                    <div class="flex flex-col gap-1 group">
                        <a href="#" class="font-gilroyBold text-sm text-white">Support</a>
                        <div class="hidden mx-auto h-0.5 w-2/3 bg-lightRed group-hover:block"></div>
                    </div>
                    <div class="flex flex-col gap-1 group">
                        <a href="#" class="font-gilroyBold text-sm text-white">Contact</a>
                        <div class="hidden mx-auto h-0.5 w-2/3 bg-lightRed group-hover:block"></div>
                    </div>
                    <button type="button" class="px-6 py-2 bg-lightRed text-white font-gilroyBold text-base rounded-lg cursor-pointer hover:bg-white hover:text-lightRed">Get Started Now</button>
                </div>
            </div>
        </nav>
        <div class="p-24">
            <div class="flex flex-row gap-6">
                <!-- Hero Content -->
                <div class="flex flex-col gap-8 w-1/2">
                    <h1 class="font-gilroyBold text-white text-4xl max-w-xs">Manage your remote team work</h1>
                    <p class="font-gilroyRegular text-white text-base max-w-sm opacity-65">With lots of unique blocks, 
                        you can easily build a page without coding. 
                        Build your next consultancy website within few minutes.
                    </p>
                    <div>
                        <button type="button" class="px-7 py-3 bg-lightRed text-white font-gilroyBold text-base rounded-lg cursor-pointer hover:bg-white hover:text-lightRed">Explore more</button>
                    </div>
                    <div class="flex flex-col gap-6">
                        <h6 class="font-gilroyBold text-grayieshWhite text-sm">Download our app</h6>
                        <div class="flex flex-row gap-4">
                            <a href="#">
                                <img src="../assets/App Store.svg" alt="App Store">
                            </a>
                            <a href="#">
                                <img src="../assets/Play Store.svg" alt="Play Store">
                            </a>
                        </div>
                    </div>
                </div>
                <!-- Hero Images -->
                 <div class="w-1/2 relative pt-10">
                    <div >
                        <img src="../assets/Dots.png" alt="Dots" class="absolute top-0 right-0" >
                    </div>
                    <div >
                        <img src="../assets/Image.png" alt="Hero Image" class="z-50 relative" >
                    </div>
                 </div>
            </div>
        </div>
    </header>

    <section id="collaborate" class="p-12 bg-softWhite relative -top-2.5">
        <!-- Collaborate Container -->
        <div class="flex flex-row gap-16 mx-auto justify-center">
            <div>
                <img src="../assets/collaborate-image.png" alt="">
            </div>
            <div class="flex flex-col gap-18">
                <div class="flex flex-col gap-4 pt-12">
                    <h2 class="font-gilroyBold text-softBlack text-3xl max-w-xs">Collaborate with team members.</h2>
                    <p class="font-gilroyRegular text-softBlack text-base max-w-sm opacity-70">We share common trends and strategies for improving your rental income.</p>
                </div>
                <div class="flex flex-col gap-6">
                    <div class="flex flex-col gap-2">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs">Project Based Groups</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-sm opacity-70">With lots of unique blocks, you can easily build a page without coding.</p>
                    </div>
                    <div class="flex flex-col gap-2">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs">Unlimited Video Meetings</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-sm opacity-70">With lots of unique blocks, you can easily build a page without coding.</p>
                    </div>
                </div>
                
            </div>
            
        </div>
        
    </section>

    <section id="organize" class="px-18 pb-12 bg-softWhite">
        <!-- Organize Container -->
        <div class="flex flex-row gap-16 mx-auto justify-center">
            <!-- Organize Content -->
            <div  class="flex flex-col gap-18">
                <div class="flex flex-col gap-4 pt-12">
                    <h2 class="font-gilroyBold text-softBlack text-3xl max-w-xs">Organize remote team fast & easily.</h2>
                    <p class="font-gilroyRegular text-softBlack text-base max-w-sm opacity-70">We share common trends and strategies for creating & improving your rental income.</p>
                </div>
                <div class="flex flex-col gap-6">
                    <div class="flex flex-col gap-2">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs">Create Unlimited Teams</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-sm opacity-70">With lots of unique blocks, you can easily build a page without coding.</p>
                    </div>
                    <div class="flex flex-col gap-2">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs">Hasslefree Chat with Everyone</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-sm opacity-70">With lots of unique blocks, you can easily build a page without coding.</p>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/organize-image.png" alt="">
            </div>
        </div>
    </section>
    <section id="how-dose-it-works" class="px-18 pb-12 bg-softWhite">
        <!-- How Dose It Works Container -->
         <div class="flex flex-col gap-16 mx-auto">
            <div class="flex flex-col gap-4 text-center items-center">
                <h2 class="font-gilroyBold text-softBlack text-3xl max-w-xs">How does it work?</h2>
                <p class="font-gilroyRegular text-softBlack text-base max-w-md opacity-70">With lots of unique blocks, you can easily build a page easily without any coding.</p>
            </div>
            <div class="relative flex flex-row gap-16 justify-center">
                <div class="flex flex-col gap-4 items-center">
                    <div class="w-15 py-3.5 px-6 bg-lightRed2 text-white rounded-full font-gilroyBold text-2xl">
                        1
                    </div>
                    <div class="flex flex-col gap-2 items-center">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs text-center">Install App</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-2xs opacity-70 text-center">With lots of unique blocks, you can easily build a page easily without any coding.</p>
                    </div>
                </div>
                <div class="flex flex-col gap-4 items-center">
                    <div class="w-15 py-3.5 px-6 bg-lightGreen text-white rounded-full font-gilroyBold text-2xl">
                        2
                    </div>
                    <div class="flex flex-col gap-2 items-center">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs text-center">Add Team Members</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-2xs opacity-70 text-center">With lots of unique blocks, you can easily build a page easily without any coding.</p>
                    </div>
                </div>
                <div class="flex flex-col gap-4 items-center">
                    <div class="w-15 py-3.5 px-6 bg-carbonyBlue text-white rounded-full font-gilroyBold text-2xl">
                        3
                    </div>
                    <div class="flex flex-col gap-2 items-center">
                        <h4 class="font-gilroyBold text-softBlack text-lg max-w-xs text-center">Start Rolling!</h4>
                        <p class="font-gilroyRegular text-softBlack text-base max-w-2xs opacity-70 text-center">With lots of unique blocks, you can easily build a page easily without any coding.</p>
                    </div>
                </div>
            </div>

         </div>


    </section>

    <section id="we-made" class="mt-24 bg-wave2">
        <div class="relative container mx-auto px-18 pt-56">
            <div class="absolute -top-24 left-1/4 w-1/2 z-40">
                <video src="../assets/Mobile App Presentation Video Template - Renderforest (1080p, h264, youtube).mp4" controls class="rounded-xl"></video>
            </div>
            <div class="hidden lg:block absolute top-64 left-1/5">
                <img src="../assets/Dots.svg" alt="">
            </div>
            <div class="pt-48 pb-24 flex flex-col gap-32">
                <div class="flex flex-col gap-16">
                    <div class="text-center flex justify-center">
                        <h2 class="font-gilroyBold text-white text-3xl max-w-sm">We made this app<br/> to solve your problems.</h2>
                    </div>
                    <div class="flex flex-col gap-12">
                        <div class="flex flex-row gap-8 mx-auto">
                            <div class="w-1/3 flex flex-row gap-4">
                                <div>
                                    <img src="../assets/roadmap.svg" alt="">
                                </div>
                                <div>
                                    <h4 class="font-gilroyBold text-white text-lg max-w-xs">Unlimited Projects</h4>
                                    <p class="font-gilroyRegular text-white text-base max-w-xs opacity-65 mt-2">With lots of unique blocks, you can easily build a page without coding. Build your next landing page.</p>
                                </div>
                            </div>
                            <div class="w-1/3 flex flex-row gap-4">
                                <div>
                                    <img src="../assets/users-wm.svg" alt="">
                                </div>
                                <div>
                                    <h4 class="font-gilroyBold text-white text-lg max-w-xs">Team Management</h4>
                                    <p class="font-gilroyRegular text-white text-base max-w-xs opacity-65 mt-2">With lots of unique blocks, you can easily build a page without coding. Build your next landing page.</p>
                                </div>
                            </div>
                            <div class="w-1/3 flex flex-row gap-4">
                                <div>
                                    <img src="../assets/share-91.svg" alt="">
                                </div>
                                <div>
                                    <h4 class="font-gilroyBold text-white text-lg max-w-xs">File Sharing</h4>
                                    <p class="font-gilroyRegular text-white text-base max-w-xs opacity-65 mt-2">With lots of unique blocks, you can easily build a page without coding. Build your next landing page.</p>
                                </div>
                            </div>
                        </div>
                        <div class="flex flex-row gap-8 mx-auto">
                            <div class="w-1/3 flex flex-row gap-4">
                                <div>
                                    <img src="../assets/video_meeting.svg" alt="">
                                </div>
                                <div>
                                    <h4 class="font-gilroyBold text-white text-lg max-w-xs">Video Meetings</h4>
                                    <p class="font-gilroyRegular text-white text-base max-w-xs opacity-65 mt-2">With lots of unique blocks, you can easily build a page without coding. Build your next landing page.</p>
                                </div>
                            </div>
                            <div class="w-1/3 flex flex-row gap-4">
                                <div>
                                    <img src="../assets/opening-times.svg" alt="">
                                </div>
                                <div>
                                    <h4 class="font-gilroyBold text-white text-lg max-w-xs">Time Tracking</h4>
                                    <p class="font-gilroyRegular text-white text-base max-w-xs opacity-65 mt-2">With lots of unique blocks, you can easily build a page without coding. Build your next landing page.</p>
                                </div>
                            </div>
                            <div class="w-1/3 flex flex-row gap-4">
                                <div>
                                    <img src="../assets/card-favorite.svg" alt="">
                                </div>
                                <div>
                                    <h4 class="font-gilroyBold text-white text-lg max-w-xs">Payment System</h4>
                                    <p class="font-gilroyRegular text-white text-base max-w-xs opacity-65 mt-2">With lots of unique blocks, you can easily build a page without coding. Build your next landing page.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="flex flex-col gap-12 mx-auto">
                    <div class="text-center relative">
                        <h4 class="font-gilroyBold text-white text-xl max-w-md">1,749 remote teams have shared their experience with our app!</h4>
                        <div class="absolute top-5 left-12 mx-auto h-0.5 w-1/3 bg-lightGreen"></div>                        
                    </div>
                    <div class="flex flex-col gap-4">
                        <div class="flex flex-row gap-4 items-center p-6 bg-white rounded-lg">
                            <div class="w-20">
                                <img src="../assets/Oval.jpg" alt="">
                            </div>
                            <div>
                                <p class="font-gilroyRegular text-lg max-w-md text-softBlack">“OMG! I cannot believe that I have got a brand new landing page after getting Omega. It was super easy to edit and publish.”</p>
                                <h6 class="mt-2 font-gilroyRegular text-sm text-softBlack opacity-70">Isaac Olson</h6>
                            </div>
                        </div>
                        <div class="flex flex-row gap-4 items-center p-6 bg-white opacity-70 rounded-lg">
                            <div class="w-20">
                                <img src="../assets/Oval2.jpg" alt="">
                            </div>
                            <div>
                                <p class="font-gilroyRegular text-lg max-w-md text-softBlack">“Simply the best. Better than all the rest. I’d recommend this product to beginners and advanced users who want success.”</p>
                                <h6 class="mt-2 font-gilroyRegular text-sm text-softBlack opacity-70">Barry Young</h6>
                            </div>
                        </div>
                        <div class="flex flex-row gap-4 items-center p-6 bg-white opacity-50 rounded-lg">
                            <div class="w-20">
                                <img src="../assets/Oval3.jpg" alt="">
                            </div>
                            <div>
                                <p class="font-gilroyRegular text-lg max-w-md text-softBlack">“Must have book for all, who want to be Product Designer or Interaction Designer.”</p>
                                <h6 class="mt-2 font-gilroyRegular text-sm text-softBlack opacity-70">Esther Allison</h6>
                            </div>
                        </div>
                    </div>
                    <div class="text-center flex flex-row gap-2 justify-center items-center">
                        <a href="#" class="text-lightGreen font-gilroyBold text-base">Read more reviews</a>
                        <a href="#">
                            <div>
                                <img src="../assets/tail-right.svg" alt="">
                            </div>
                        </a>
                        
                    </div>
                </div>
            </div>
        </div>

    </section>
    <section id="pricing" class="bg-softGray2 lg:bg-wave3">
    <div class="relative container mx-auto px-18 pt-24 pb-38">
      <div class="flex flex-col gap-12">
        <div class="text-center mx-auto">
          <h2 class="font-gilroyBold text-softBlack text-3xl max-w-xs">
            Pricing made easy
          </h2>
          <p
            class="mt-6 font-gilroyRegular text-softBlack text-base max-w-sm opacity-70"
          >
            With lots of unique blocks, you can easily build a page easily
            without any coding.
          </p>
        </div>
        <div class="flex flex-col md:flex-row gap-4 mx-auto text-center">
            <div class="flex flex-col gap-12 px-24 py-6 rounded-lg">
                <div class="flex flex-col gap-6">
                    <h6 class="font-gilroyBold text-xs text-lightRed2">Starter</h6>
                    <div>
                        <h1 class="font-gilroyBold text-softBlack text-4xl max-w-xs">
                            <span class="font-gilroyBold text-softBlack text-lg">$</span>19<span class="font-rubik text-base text-softBlack">/ mo</span>
                        </h1>
                    </div>
                </div>
                <div class="flex flex-col gap-8">
                    <h5 class="font-gilroyRegular text-base text-softBlack">Upto 100 Team Members</h5>
                    <h5 class="font-gilroyRegular text-base text-softBlack">100 GB Cloud Storage</h5>
                    <h5 class="font-gilroyRegular text-base text-softBlack">Unlimited Meetings</h5>
                    <h5 class="font-gilroyRegular text-base text-softBlack">Premium Support</h5>
                    <div>
                        <button class="px-8 py-3 cursor-pointer bg-softBlack text-white rounded-md font-gilroyBold text-base hover:bg-white hover:text-softBlack border border-softBlack">Get Started Now</button>

                    </div>
                </div>
            </div>
            <div class="flex flex-col gap-12 px-24 py-6 bg-white rounded-lg">
                <div class="flex flex-col gap-6">
                    <h6 class="font-gilroyBold text-xs text-lightRed2">Unlimited</h6>
                    <div>
                        <h1 class="font-gilroyBold text-softBlack text-4xl max-w-xs">
                            <span class="font-gilroyBold text-softBlack text-lg">$</span>99<span class="font-rubik text-base text-softBlack">/ mo</span>
                        </h1>
                    </div>
                </div>
                <div class="flex flex-col gap-8">
                    <h5 class="font-gilroyRegular text-base text-softBlack">Unlimited Team Members</h5>
                    <h5 class="font-gilroyRegular text-base text-softBlack">Unlimited Cloud Storage</h5>
                    <h5 class="font-gilroyRegular text-base text-softBlack">Unlimited Meetings</h5>
                    <h5 class="font-gilroyRegular text-base text-softBlack">Premium Support</h5>
                    <div>
                        <button class="px-8 py-3 cursor-pointer bg-lightRed3 text-white rounded-md font-gilroyBold text-base hover:bg-white hover:text-lightRed3 border border-lightRed3">Get Started Now</button>
                    </div>
                </div>
            </div>
        </div>
      </div>
      <div class="hidden lg:block absolute bottom-0 right-0.5">
        <img src="../assets/Fill 1.svg" alt="">
      </div>
    </div>
  </section>
  <footer class="bg-white">
    <div class="container mx-auto px-24 pt-18 pb-24">
        <div class="flex flex-col gap-18">
            <div class="flex flex-col md:flex-row gap-12 md:gap-24 mx-auto justify-around">
                <div class="flex flex-col gap-8 text-center">
                    <h5 class="font-gilroyRegular text-sm text-softBlack opacity-70">Company</h5>
                    <div class="flex flex-col gap-4">
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">About us</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Contact us</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Careers</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Press</a>
                    </div>
                </div>
                <div class="flex flex-col gap-8 text-center">
                    <h5 class="font-gilroyRegular text-sm text-softBlack opacity-70">Product</h5>
                    <div class="flex flex-col gap-4">
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Features</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Pricing</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">News</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Help desk</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Support</a>
                    </div>
                </div>
                <div class="flex flex-col gap-8 text-center">
                    <h5 class="font-gilroyRegular text-sm text-softBlack opacity-70">Legal</h5>
                    <div class="flex flex-col gap-4">
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Privacy Policys</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Terms & Conditions</a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">Return Policy</a>
                    </div>
                </div>
                <div class="md:ml-48 flex flex-col gap-8 text-center">
                    <h5 class="font-gilroyRegular text-sm text-softBlack opacity-70">Download Our App</h5>
                    <div class="flex flex-col gap-4">
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">
                            <img src="../assets/App Store.svg" alt="">
                        </a>
                        <a href="#" class="font-gilroyRegular text-base text-softBlack hover:text-lightRed2">
                            <img src="../assets/Play Store.svg" alt="">
                        </a>
                    </div>
                </div>
            </div>
            <div class="flex flex-col gap-8 md:flex-row justify-between">
                <div class="flex flex-row gap-2 items-center-safe">
                    <h5 class="font-gilroyRegular text-sm text-softBlack opacity-70">© 2025 Copyright, All Right Reserved, Made by <a class="hover:text-lightRed2 hover:underline underline-offset-1" href="mailto:p30gbdev2@gmail.com"> Dr. Mehdi Khairandish</a> with</h5>
                    <div>
                        <img src="../assets/Path.svg" alt="">
                    </div>
                </div>
                <div class="flex flex-row gap-8 items-center">
                    <div>
                        <a href="#"><img class="logo-hover" src="../assets/logo-twitter.svg" alt=""></a>
                    </div>
                    <div>
                        <a href="#"><img class="logo-hover" src="../assets/logo-facebook.svg" alt=""></a>
                    </div>
                    <div>
                        <a href="#"><img class="logo-hover" src="../assets/logo-instagram.svg" alt=""></a>
                    </div>
                    <div>
                        <a href="#"><img class="logo-hover" src="../assets/logo-linkedin.svg" alt=""></a>
                    </div>
                </div>
            </div>

        </div>

    </div>

  </footer>


</template>


<script setup>
import {RouterLink} from "vue-router"

</script>


<style scoped>


</style>9