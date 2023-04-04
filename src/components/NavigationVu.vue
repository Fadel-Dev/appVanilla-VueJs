<script>
    export default{}
</script>

<template>
     <header class=" mx-40header  w-full h-16 drop-shadow-lg ,x" id="header">
        <div class="container  px-4 md:px-0 h-full mx-auto flex justify-between items-center" data-aos="fade-down" data-aos-easing="linear" data-aos-duration="900">
            <!-- Logo Here -->
            <a href="#banner"><img class="w-14 " src="../assets/logo7.png" alt=""></a>

            <!-- Menu links here -->
            <ul id="menu" class="hidden fixed top-0 right-0 px-10 py-8 backdrop-blur-sm backdrop-blur-md bg-violet-900/30  z-50
                    md:relative md:flex md:p-0 md:bg-transparent md:flex-row md:space-x-6">

                <li class="md:hidden z-90 fixed top-4 right-6">
                    <a href="javascript:void(0)" class="text-right text-white text-4xl"
                        onclick="toggleMenu()">&times;</a>
                </li>

                <li>
                    <a class="text-violet-900  hover:opacity-100 duration-300" href="#home"><i class="fa fa-home"></i>
                        Acceuil</a>
                </li>
                <li>
                    <a class="text-violet-900   hover:opacity-100 duration-300" href="#presentation"><i
                            class="fa fa-person"></i> Presentation</a>
                </li>
                <li>
                    <a class="text-violet-900   hover:opacity-100 duration-300" href="#service"><i class="fa fa-refresh"
                            aria-hidden="true"></i> Service</a>
                </li>
                <!-- 
                <li>
                    <a class="text-violet-900 hover:opacity-100 duration-300" href="#galery"><i
                            class='far fa-file-image'></i> Galerie</a>
                </li> -->
                <li>
                    <a class="text-violet-900   hover:opacity-100 duration-300" href="#contact"><i
                            class="fa fa-envelope" aria-hidden="true"></i> Contact</a>
                </li>
            </ul>

            <!-- This is used to open the menu on mobile devices -->
            <div class="flex items-center md:hidden">
                <button class="text-white text-4xl font-bold opacity-70 hover:opacity-100 duration-300"
                    onclick="toggleMenu()">
                    &#9776;
                </button>
            </div>
        </div>

    </header>
</template>

<style>
     .banner {
            background-color: rgb(46, 2, 73);
            color: #fff;
        }

        .header {
            position: fixed;
            background-color: rgba(8, 8, 9, 0.759);
            z-index: 1;
            padding: 0;
        }

        #header {
            background-color: rgb(235, 229, 229);
            padding-top: 9px;
            padding-bottom: 9px;
        }
          /* ANIMATIOM MENU */

          ul li a {

position: relative;
}

ul li a::after {
position: absolute;
bottom: -6px;
content: "";
width: 0%;
height: 2px;
background-color: rgb(234, 19, 253);
left: 3px;
box-shadow: 6px 9px 7px rgb(234, 19, 253);


}

ul li a:hover::after {
width: 100%;
transition: 3s;
background-color: rgba(46, 2, 73, 1);
}

ul li a:hover {
color: gba(46, 2, 73, 1);
transition: 1s;
}

#galery {
display: none;
}


/* *****************  For the mobile navBar                     ************************ */
@media (max-width: 767px) {

#header li {
margin-top: 12px;
}

#header li:hover {
margin-left: 5%;
color: rgb(211, 193, 34);
}



}
</style>