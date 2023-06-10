<template>
  <div>
    <div class="relative">
        <div>
            <img src="/image/about_1.jpg" class="w-full">
        </div>
        <div class="absolute top-0 left-0 p-20 grid grid-cols-2 w-full h-full">
            <div class="flex flex-col items-center gap-5 tracking-wider justify-self-start">
                <div class="text-6xl font-bold text-white">
                    Our Team
                </div>
                <div class="bg-[#FF9900] w-56 h-2 rounded-full">
                </div>
            </div>
            <div class="flex flex-col text-white text-5xl items-center gap-5 tracking-wide justify-self-end self-end">
                <div class="">
                    Committed to Value,
                    <br />
                    Committed to <span class=" text-[#FF9900] font-bold">You</span>
                </div>
            </div>
        </div>
    </div>
    <div>
        <div class=" flex justify-center text-4xl font-bold py-5">
            <div class="flex flex-col items-center gap-2">
                <div>Leadership</div>
                <div class="bg-[#FF9900] w-28 h-2 rounded-full"></div>
            </div>
        </div>
        <div>
            <Card></Card>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>