<template>
    <div>
        <div
            className="flex items-center text-center justify-center bg-cover bg-no-repeat w-[100%] bg-[url('/src/assets/MainPageImage/mainpagebg.png')]">
            <div className='mt-44 text-center'>
                <h1 className="text-white text-[32px] font-bold">Everything You Love About Coffee</h1>
                <LogoCoffeLight />
                <div className='text-white text-26 text-center leading-8'>We makes every day full of energy and
                    taste<br />Want to try our beans?</div>
                <button
                    className="rounded-md border border-solid border-white text-white px-10 py-2 bg-transparent shadow-md mt-6 mb-32 transition duration-500 ease-in-out hover:bg-white hover:text-black"
                    type="submit">More</button>
            </div>
        </div>
    </div>
</template>
<script>
import LogoCoffeLight from '../LogoCoffeLight/LogoCoffeLight.vue';
export default {
    name: 'MoreInfo',
    components: {
        LogoCoffeLight,
    }
}
</script>
<style lang="">
    
</style>