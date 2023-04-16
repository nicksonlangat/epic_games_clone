<template>
  <div>
   <Navbar />

   <div class="container mx-auto mt-4">
    <div class="flex gap-x-4">
      <div class="relative flex items-center mt-2">
        <span class="absolute">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="text-white w-4 h-4 mx-3">
              <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
            </svg>
        </span>

        <input type="text" placeholder="Search store" class="block w-full py-2.5 text-white text-xs placeholder-[#CCCCCC] bg-[#2A2A2A] border border-[#2A2A2A] rounded-full pl-11 pr-5 rtl:pr-11 rtl:pl-5 focus:ring-0 focus:outline-none">
    </div>
      <p class="mt-4 text-white">Discover</p>
    <p class="text-[#CCCCCC] mt-4 hover:text-white">Browse</p>
    <p class="text-[#CCCCCC] mt-4 hover:text-white">News</p>
    </div>
   </div>

   <div class="container mx-auto mt-8">
    <div class="flex gap-12">
      <div class="w-2/3 bg-center bg-cover rounded-lg" :style="{ 'background-image': 'url(' + require('../assets/star.avif') +')', 'height':'60vh'}">

      </div>

      <div class="w-1/3 grid grid-cols-1 gap-4">
        <div class="bg-[#2A2A2A] rounded-lg w-96 h-28">
          <div class="flex gap-2 mt-4 ml-4">
          <img class="h-20 w-15 rounded-lg" src="../assets/4.avif" alt="">
          <p class="text-white mt-6">Star wars</p>
        </div>
        </div>
        <div class="bg-[#2A2A2A] rounded-lg w-96 h-28">
          <div class="flex gap-2 mt-4 ml-4">
          <img class="h-20 w-15 rounded-lg" src="../assets/1.avif" alt="">
          <p class="text-white mt-6">Star wars</p>
        </div>
        </div>
        <div class="bg-[#2A2A2A] rounded-lg w-96 h-28">
          <div class="flex gap-2 mt-4 ml-4">
          <img class="h-20 w-15 rounded-lg" src="../assets/3.avif" alt="">
          <p class="text-white mt-6">Star wars</p>
        </div>
        </div>
        <div class="bg-[#2A2A2A] rounded-lg w-96 h-28">
          <div class="flex gap-2 mt-4 ml-4">
          <img class="h-20 w-15 rounded-lg" src="../assets/2.avif" alt="">
          <p class="text-white mt-6">Star wars</p>
        </div>
        </div>

      </div>
    </div>
   </div>


   <div class="container mx-auto mt-4">
    <div class="flex text-white justify-between">
      <p>Spring Sale Spotlight</p>
      <div class="flex gap-2 mr-4">
        <span class="rounded-full px-1 bg-[#2A2A2A] py-1">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
        </svg>
      </span>
      
      <span class="rounded-full px-1 bg-[#2A2A2A] py-1">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
      </svg>
      </span>
      </div>
    </div>

    <div class="mt-8 grid grid-cols-6 gap-2 pb-12">
      <div>
        <img class="h-64" src="../assets/dead.avif" alt="">
        <p class="mt-2 uppercase text-xs text-gray-400">base game</p>
        <p class="text-white">Dead Space</p>
        <div class="flex gap-2 mt-4">
          <span class="bg-[#0078F2] rounded px-2 text-white text-xs py-2">
            -25%
          </span>
          <p class="text-gray-400 line-through">$59.99</p>
          <p class="text-white">$47.99</p>
        </div>
      </div>
      <div>
        <img class="h-64" src="../assets/far.avif" alt="">
        <p class="mt-2 uppercase text-xs text-gray-400">base game</p>
        <p class="text-white">Far Cry</p>
        <div class="flex gap-2 mt-4">
          <span class="bg-[#0078F2] rounded px-2 text-white text-xs py-2">
            -25%
          </span>
          <p class="text-gray-400 line-through">$59.99</p>
          <p class="text-white">$47.99</p>
        </div>
      </div>
      <div>
        <img class="h-64" src="../assets/punk.avif" alt="">
        <p class="mt-2 uppercase text-xs text-gray-400">base game</p>
        <p class="text-white">Cyberpunk 2077</p>
        <div class="flex gap-2 mt-4">
          <span class="bg-[#0078F2] rounded px-2 text-white text-xs py-2">
            -25%
          </span>
          <p class="text-gray-400 line-through">$59.99</p>
          <p class="text-white">$47.99</p>
        </div>
      </div>
      <div>
        <img class="h-64" src="../assets/fifa.avif" alt="">
        <p class="mt-2 uppercase text-xs text-gray-400">base game</p>
        <p class="text-white">Fifa 23</p>
        <div class="flex gap-2 mt-4">
          <span class="bg-[#0078F2] rounded px-2 text-white text-xs py-2">
            -25%
          </span>
          <p class="text-gray-400 line-through">$59.99</p>
          <p class="text-white">$47.99</p>
        </div>
      </div>
      <div>
        <img class="h-64" src="../assets/witcher.avif" alt="">
        <p class="mt-2 uppercase text-xs text-gray-400">base game</p>
        <p class="text-white">Witcher 3</p>
        <div class="flex gap-2 mt-4">
          <span class="bg-[#0078F2] rounded px-2 text-white text-xs py-2">
            -25%
          </span>
          <p class="text-gray-400 line-through">$59.99</p>
          <p class="text-white">$47.99</p>
        </div>
      </div>
      <div>
        <img class="h-64" src="../assets/battle.avif" alt="">
        <p class="mt-2 uppercase text-xs text-gray-400">base game</p>
        <p class="text-white">Battlefield 2042</p>
        <div class="flex gap-2 mt-4">
          <span class="bg-[#0078F2] rounded px-2 text-white text-xs py-2">
            -25%
          </span>
          <p class="text-gray-400 line-through">$59.99</p>
          <p class="text-white">$47.99</p>
        </div>
      </div>
    </div>


    <div class="mt-8 grid grid-cols-3 gap-6 pb-12">
      <div>
        <img class="rounded-lg" src="../assets/60.avif" alt="">
        <h3 class="mt-4 text-white">Plug In Digital, PID Games & Dear Villagers Week 2023</h3>
        <p class="text-gray-400 mt-2">Enjoy crazy discounts on the latest indie gems from Dear Villagers, PID Games and more.</p>
        <h3 class="text-white text-xl underline decoration-gray-600 cursor-pointer mt-4">Save Now</h3>
      </div>
      <div>
        <img class="rounded-lg" src="../assets/ride.avif" alt="">
        <h3 class="mt-4 text-white">RIDE 5</h3>
        <p class="text-gray-400 mt-2">
          Get ready to go beyond racing with the motorbikes of your dreams and to experience the most realistic races ever.
        </p>
        <h3 class="text-white text-xl mt-4">$59.99</h3>
      </div>
      <div>
        <img class="rounded-lg" src="../assets/hogwarts.avif" alt="">
        <h3 class="mt-4 text-white">Hogwarts Legacy</h3>
        <p class="text-gray-400 mt-2">
          Take control and be at the center of your own adventure in the wizarding world.
        </p>
        <h3 class="text-white text-xl mt-4">$59.99</h3>
      </div>
    </div>



    <div class="mt-8 grid grid-cols-3 gap-4 divide pb-12">
      <div>
        <div class="flex gap-32">
          <h3 class="text-white text-2xl">Top Sellers</h3>
          <span class="text-white px-4 border border-gray-400 hover:bg-[#2a2a2a] cursor-pointer uppercase py-1.5 text-xs">View more</span>
        </div>

        <div class="flex mt-4 gap-y-4 flex-col">
          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/fifa23.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/rdd.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/gta.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/vert.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>
          
        </div>

        
      </div>
      <div>
        <div class="flex gap-32">
          <h3 class="text-white text-2xl">Most Played</h3>
          <span class="text-white px-4 border border-gray-400 hover:bg-[#2a2a2a] cursor-pointer uppercase py-1.5 text-xs">View more</span>
        </div>

        <div class="flex mt-4 gap-y-4 flex-col">
          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/fifa23.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/rdd.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/gta.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/vert.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>
          
        </div>

        
      </div>
      <div>
        <div class="flex gap-32">
          <h3 class="text-white text-2xl">Top Upcoming</h3>
          <span class="text-white px-4 border border-gray-400 hover:bg-[#2a2a2a] cursor-pointer uppercase py-1.5 text-xs">View more</span>
        </div>

        <div class="flex mt-4 gap-y-4 flex-col">
          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/fifa23.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/rdd.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/gta.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>

          <div class="flex gap-2">
            <img class="h-20 w-15 rounded-lg" src="../assets/vert.avif" alt="">
            <div class="flex flex-col">
              <p class="text-white">EA Sports FIFA 23</p> <br> 
              <div class="flex gap-2">
                <span class="bg-[#0078F2] rounded px-0.5 text-white text-xs py-1">
                  -25%
                </span>
                <p class="text-gray-400 text-xs line-through">$59.99</p>
                <p class="text-white text-xs">$47.99</p>
              </div>
            </div>
          </div>
          
        </div>

        
      </div>

      

      
    </div>


    <div class="mt-8 grid grid-cols-2 gap-4  pb-12">
      <div>
        <img class="rounded-lg" src="../assets/fort.avif" alt="">
        <h3 class="mt-4 text-white">Fortnite</h3>
        <p class="text-gray-400">
          The Coachella Music and Arts Festival is back, bringing even more melodic festivities and cosmetic items to enjoy.
        </p>
        <p class="text-white mt-4 text-2xl cursor-pointer underline decoration-gray-600">Play for free</p>
      </div>

      <div>
        <img class="rounded-lg" src="../assets/fall.avif" alt="">
        <h3 class="mt-4 text-white">Fall Guys</h3>
        <p class="text-gray-400">
          Can Ellen Ripley keep Earth safe, or will it be game over, man? Drop into the Fall Guys Store and get ready for action.
         </p>
        <p class="text-white mt-4 text-2xl cursor-pointer underline decoration-gray-600">Play for free</p>
      </div>
    </div>

    <div class="mt-8 grid grid-cols-2 gap-6 pb-12">
      <div>
        <img class="rounded-lg" src="../assets/all.avif" alt="">
      </div>
      <div class="mt-6 ml-6">
        <h3 class="text-white text-2xl mt-12">Explore our Catalog</h3>
        <p class="text-gray-300 mt-4">
          Browse by genre, features, price, and more to find your next favorite game.
        </p>
        <button class="bg-white py-4 px-4 mt-12 rounded uppercase">
          browse all
        </button>
      </div>
    </div>


<!-- end -->
   </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'Home',
  components: {
    Navbar
  }
}
</script>
