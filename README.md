<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://unpkg.com/@tailwindcss/browser@4"></script>
</head>

<body>

    <div class="">
        <!-- nav-bar start -->
        <nav class="nav conatiner">
            <ul class="flex justify-between px-[100px]   bg-white ">
                <li class="flex items-center w-40 h-full"><img
                        src="https://logos-world.net/wp-content/uploads/2021/10/Pizza-Hut-Emblem.png"></li>
                <li
                    class="flex justify-center items-center underline decoration-dotted decoration-black text-slate-600 ">
                    Sign in</li>
            </ul>
        </nav>
        <!-- end nav-bar -->
        <div class="body flex relative border-e-4 border-red-500">
            <div class="">
                <div class="h-[60vh] w-[100vw]"><img
                        src="https://i.pinimg.com/originals/19/eb/c6/19ebc658a3624aa26f61c2660685c897.jpg"
                        class="size-full"></div>
                <div class=" flex box justify-center items-center absolute-bottom-20 bg-white left-[32.5%]">
                    <div
                        class="border-2 rounded-lg absolute top-2/2 left-1/2 -translate-x-1/2 -translate-y-1/2 bg-white p-4 shadow-lg">
                        <div class=" space-x-3 h-[250px]">
                            <ul class="flex pe-6 justify-between">
                                <li class="hover:text-2xl text-red-500 hover:bg-gray-400">Delivery</li>
                                <li class="text-black bg-gray-400 py-3 hover:text-2xl">Collect from store</li>
                            </ul>
                            <div class="py-6">
                                <h1 class="font-bold">FIND YOUR NEAREST HUT</h1>
                                <H2>Enter your address to see your local deals ,coupons and offers .</H2>
                                <input class="bg-white w-[100%] mt-4 py-3 border-whitesmoke shadow-lg " type="text"
                                    placeholder="Enter Your location">
                                <input class="bg-white w-[100%] mt-4 py-3 border-whitesmoke shadow-lg " type="text"
                                    placeholder="Find current location">
                            </div>
                        </div>
                    </div>
                </div>
            </div>



        </div>

        <!-- 2nd part of website  -->
        <div class="flex hustify-center my-10 items-center pt-[200px]">
            <span class=" flex border-b border-2 border-slate-700 w-[40%] mx-5"> </span>
            <span class="  font-bold text-2xl items-center ">
                our popular
            </span>
            <span class=" flex mx-2 border-t border-2  my-10 w-[40%]"></span>
        </div>
        <div class="w-[70vw] mx-auto space-x-3 py-2">
            <div class=" h-[70vh] w-[60%] flex  pe-16 space-x-3 mt-[10px]"> <img class="size-full flex justify-center"
                    src="https://api.pizzahut.io/v1/content/en-in/in-1/images/promo/hut100.90e4d53d30d88b599cb2c3d2d5387112.1.jpg"
                    alt="">


                <!-- <div class="im h-[70vh] w-[60%] flex mx-auto items-center">-->
                <img class="size-full flex justify-center"
                    src="https://api.pizzahut.io/v1/content/en-in/in-1/images/promo/hut125.5893dee123b1a79e089241a83f936067.1.jpg"
                    alt="">

            </div>
            <div class="w-[110%] border-2  rounded-lg flex justify-center py-3 bg-green-800 text-white">View all deals
            </div>
        </div>

    </div>
    <footer class="bg-black h-80 pt-10">
        <div class="flex justify-between mx-[50px] text-white">
            <ul class="px-3">
                <li class="text-2xl font-bold">Order Now</li>
                <li>Deals</li>
                <li>Pizza</li>
                <li>Sides</li>
                <li>my</li>
            </ul>
            <ul>
                <li class="text-2xl font-bold">About</li>
                <li>About us</li>
                <li>About us</li>
                <li>About us</li>
                <li>About us</li>

            </ul>
            <ul>
                <li class="text-2xl font-bold">Our policies</li>
                <li>Our policies</li>
                <li>Our policies</li>
                <li>Our policies</li>
                <li>Our policies</li>
            </ul>
            <ul>
                <li class="text-2xl font-bold">Visit Pizza HUt</li>
                <li>policies</li>
                <li>policies</li>
                <li>policies</li>
                <li>policies</li>
                <li>policies</li>
            </ul>
        </div>

    </footer>
</body>

</html>
