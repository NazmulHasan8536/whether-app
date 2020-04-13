<template>
<div class="text-white mb-8">
    <div class="places-input text-gray-800">
        <input type="text" class="w-full">

    </div>

    <div class="whether-container font-sans w-128 max-w-lg overflow-hidden bg-gray-900 shadow-lg mt-4">  <!-- wheather container start -->
         <div class="whether-content flex justify-between content-center px-6 py-8">  <!-- wheather content start -->
                <div class="flex items-center">
                    <div>
                        <div class="text-6xl font-semibold">
                            0°C
                        </div>
                        <div>
                            feels like 2°C
                        </div>
                    </div>
                </div>
                 <div class="mx-5">
                    <div class="font-semibold">
                        cloudy
                    </div>
                    <div>Toronto, Canada</div>
                </div>
               <div>icon</div>
        </div> <!-- wheather content end -->

        <div class="future-weather text-sm bg-gray-800 px-6 py-8 overflow-hidden"><!--future wheather  start -->
            <div class="flex items-center">
                <div class="w-1/6 text-lg text-gray-200">Mon</div>
                <div class="w-4/6 px-4 flex items-center">Cloudy With a sun of Showers</div>
                <div class="w-1/6">
                    <div>5°C</div>
                    <div>2°C</div>
                </div>
            </div>

            <div class="flex items-center mt-8">
                <div class="w-1/6 text-lg text-gray-200">Mon</div>
                <div class="w-4/6 px-4 flex items-center">Cloudy With a sun of Showers</div>
                <div class="w-1/6">
                    <div>5°C</div>
                    <div>2°C</div>
                </div>
            </div>

            <div class="flex items-center mt-8">
                <div class="w-1/6 text-lg text-gray-200">Mon</div>
                <div class="w-4/6 px-4 flex items-center">Cloudy With a sun of Showers</div>
                <div class="w-1/6">
                    <div>5°C</div>
                    <div>2°C</div>
                </div>
            </div>
        </div><!--future wheather  end -->
       
     </div>
</div> <!-- wheather container end -->
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>