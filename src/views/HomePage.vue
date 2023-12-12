<script setup>
import navbar from "../components/navbar.vue"
import Footer from "../components/footer.vue"
</script>


<template class="font-[assistant]">
   <!-- Navbar -->
  <section class="font-[assistant]">
    <navbar/>
  </section>

  <!-- First Slider Section -->
    <section class="font-[assistant]">
<div id="default-carousel" class="relative w-full" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="relative h-80 overflow-hidden md:h-96">
         <!-- Item 1 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2021/01/micro1.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 object-cover h-80 " alt="...">
            <div class="relative text-white px-4 mt-8">
                <p class="font-bold text-3xl">Microprixs Solution</p>
                <p class="text-sm pr-8 mt-4">Microprixs is more than an IT company, we're dedicated to revolutionizing the way businesses interact with their target audience through cutting-edge web development solutions. we lay the foundation for success by meticulously crafting strategies that align with your business goals and objectives. Our team delves into the intricacies of your business, ensuring that our solutions are tailored to address your specific needs.</p>
            </div>
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2021/01/business_log.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 object-cover h-80  " alt="...">
            <div class="relative text-white px-4 mt-8">
                <p class="font-bold text-3xl">Business Consulting</p>
                <p class="text-sm pr-8 mt-4">Elevate your company's success with our expert Business Consulting services. We specialize in aligning technological prowess with strategic vision. Our seasoned consultants craft tailored solutions that drive growth and efficiency. From strategic roadmaps to operational excellence, we help you navigate challenges, stand out in the competitive landscape, and adapt to industry trends. With a focus on measurable results, we're your partner in achieving sustainable success.</p>
            </div>
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2021/01/app-d2.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 object-cover h-80 " alt="...">
            <div class="relative text-white px-4 mt-8">
                <p class="font-bold text-3xl">App Development</p>
                <p class="text-sm pr-8 mt-4">Experience the pinnacle of digital innovation through our Web Development services. As a leading IT company, we specialize in crafting dynamic and responsive websites that reflect your brand's uniqueness. Our expert developers blend creativity with coding excellence, ensuring seamless functionality and captivating design. From e-commerce platforms to interactive portfolios, we tailor solutions that resonate with your target audience.</p>
            </div>
        </div>
        
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2021/01/web.png" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 object-cover h-80 " alt="...">
            <div class="relative text-white px-4 mt-8">
                <p class="font-bold text-3xl">Web Development</p>
                <p class="text-sm pr-8 mt-4">Unlock the potential of your ideas with our App Development services. We transform concepts into captivating apps by blending strategic vision with cutting-edge technology. From user-centric design to seamless multi-platform functionality, we craft apps that engage and impress. Our agile approach ensures swift development, while post-launch support guarantees lasting performance. Let us be your partner in turning aspirations into innovative, user-friendly, and impactful applications.</p>
            </div>
        </div>
        <!-- Item 5 -->
        <!-- <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="/docs/images/carousel/carousel-5.svg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div> -->
    </div>
    <!-- Slider indicators -->
    <div class="absolute z-30 flex -translate-x-1/2 bottom-5 left-1/2 space-x-3 rtl:space-x-reverse">
        <button type="button" class="w-3 h-3 rounded-full" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
        <!-- <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button> -->
    </div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none hidden sm:block " data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
            </svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none hidden sm:block" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
            </svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
</div>
</section>


<!-- Second Section -->
    <section class=" pt-12 bg-[#fafafa]  font-[assistant]">
        <p class="font-bold text-4xl pr-10 leading-tight text-[#282828] px-4">Welcome to Microprixs</p>
        <hr class="w-2/12 text-black h-0.5 bg-black mt-4 ml-4" >

        <div class="pt-12">
            <!-- inner 1st div -->
            <div class="px-4">
                <img class="object-cover py-4" src="https://www.microprixs.com/wp-content/uploads/2023/08/about_us.jpg"/>
                <p class="font-bold text-3xl  text-[#282828] py-4">About Company</p>
                <p class="text-[16px]"><strong>Microprixs</strong> is a global IT services company providing software development services to enterprises worldwide. We are technology brains striving to be growth enablers for our customers. We're fusing real-world expertise with innovation to make businesses work better.We help identify the best technical solutions to meet your software development and budgetary needs. Regarded as experts in the various industries we provide our services, Microprixs has designed, developed, and deployed a wide variety of technological software solutions for niche markets. When it comes to Web-services, we are best.</p>
                <button class="mt-4 px-6 py-2 bg-[#33cf9f] text-white font-medium rounded-sm ">View Details</button>
            </div>

            <!-- inner 2nd div -->
            <div class="pt-6 px-4 pb-20">
                <div class="flex">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-white h-12 w-12 text-center text-xl font-semibold shadow-[0_0_10px_-5px_rgb(146,146,146)] rounded-full my-2 ">1</p>
                   </div>
                    <div class="pl-4 pt-1">
                        <p class="font-bold text-xl text-[#282828]">TECHNOLOGY SERVICES</p>
                        <p class="text-base pt-2 ">Microprixs is a global provider of high-quality software development services that delivers world -class software solutions to clients of every size.</p>
                    </div>
                </div>
                <div class="flex mt-8">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-white h-12 w-12 text-center text-xl font-semibold shadow-[0_0_10px_-5px_rgb(146,146,146)] rounded-full my-2 ">2</p>
                   </div>
                    <div class="pl-4 pt-1">
                        <p class="font-bold text-xl text-[#282828]">APPLICATION SERVICES</p>
                        <p class="text-base pt-2 ">Microprixs excels in providing industry specific and niche technology solutions for businesses in every industry.</p>
                    </div>
                </div>
                <div class="flex mt-8">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-white h-12 w-12 text-center text-xl font-semibold shadow-[0_0_10px_-5px_rgb(146,146,146)] rounded-full my-2 ">3</p>
                   </div>
                    <div class="pl-4 pt-1">
                        <p class="font-bold text-xl text-[#282828]">CRM</p>
                        <p class="text-base pt-2 ">Our expertise spans a cross the entire software technology spectrum.</p>
                    </div>
                </div>
                <div class="flex mt-8">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-white h-12 w-12 text-center text-xl font-semibold shadow-[0_0_10px_-5px_rgb(146,146,146)] rounded-full my-2 ">4</p>
                   </div>
                    <div class="pl-4 pt-1">
                        <p class="font-bold text-xl text-[#282828]">INFRASTRUCTURE SUPPORT</p>
                        <p class="text-base pt-2 ">Our identity is founded on a deep-rooted culture of excellence and a continued commitment to delivering high-quality software services to our customers.</p>
                    </div>
                </div>
            </div>

            <!-- inner 3rd div -->
        <div class="py-14 px-0 pb-52" style="background-image: url('https://www.microprixs.com/wp-content/themes/biz-pro/blocks/home_section2/assets/img/team-column-bg.jpg');">
            <div id="default-carousel" class="relative w-full" data-carousel="slide">
            <!-- Carousel wrapper -->
            <div class="relative h-[30rem] overflow-hidden ">
        <!-- Item 1 -->
        <div class="duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/Airson-6.png" class=" w-44 h-44 border-8 border-[#886af8]  object-cover rounded-full" alt="...">
            <div class="text-white px-4 mt-5">
                <p class="font-bold uppercase text-xl">Airson Telecom Solution</p>
                <p class="text-[#738ab0] pt-1">- CEO, Hanuman prasad Gowala</p>
                <p class="text-base  mt-4 italic pb-6 pt-4">“I and my company were in great hands and had a great experience working with Microprixs. They not only hear us but also try to work according to our needs.”</p>
                <span class="">Great work guys!”</span>
            </div>
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/pixvix-1-2.png" class="w-44 h-44  border-8 border-[#ccc] object-cover rounded-full" alt="...">
            <div class="text-white px-4 mt-5">
                <p class="font-bold  text-xl">Pixvix</p>
                <p class="text-[#738ab0] pt-1">- CEO, Vishal Singh</p>
                <p class="text-base  mt-4 italic pb-6 pt-4">“One thing is for sure to say to Microprixs “Great Work”. We really love the way you consider my project to be yours and work accordingly.”</p>
                <span class="">Keep up the great work guys! ”</span>
            </div>
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/ezeerides-1-2.png" class="w-44 h-44  border-8 border-[#f58231] object-cover rounded-full" alt="...">
            <div class="text-white px-4 mt-5">
                <p class="font-bold uppercase text-xl">Ezee rides</p>
                <p class="text-[#738ab0] pt-1">- Founder, Vishal Singh</p>
                <p class="text-base  mt-4 italic pb-6 pt-4">“When it comes to Microprixs, there is nothing else to see. It was really great working with you guys. You’ve matched up to our expectations. Will definitely work with you again!”</p>
                <!-- <span class="">Great work guys!”</span> -->
            </div>
        </div>
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/vayadubai12-1.jpeg" class="w-44 h-44 border-8 border-[#fff]  object-cover rounded-full" alt="...">
            <div class="text-white px-4 mt-5">
                <p class="font-bold text-xl">Next Trip Travel</p>
                <p class="text-[#738ab0] pt-1">- CEO, Mukesh Choudhary</p>
                <p class="text-base  mt-4 italic pb-6 pt-4">“According to me, my project was difficult, yet Microprixs has by far delivered and complete it in an efficient way. In one word, you’ve surpassed our expectations Microprixs. Thanks!”</p>
                <!-- <span class="">Great work guys!”</span> -->
            </div>
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="absolute z-30 flex -translate-x-1/2 pt-[8rem] left-1/2 space-x-3 rtl:space-x-reverse">
        <button type="button" class="w-3 h-3 rounded-full" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
        <!-- <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button> -->
    </div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none hidden sm:block " data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
            </svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none hidden sm:block" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
            </svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
    </div>
    </div>
</div>
</section>


<!-- third Section -->
    <section class="py-10 pb-32 font-[assistant] bg-cover bg-center" style="background-image: url('https://www.microprixs.com/wp-content/uploads/2023/08/background-rotated.jpg');">
        <div class="w-full flex justify-center " >
        <hr class="w-3/12 text-black h-1 bg-black ml-4">
    </div>
        <div>
            <!-- inner 1st div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5 mt-8 rounded-lg">
                <div class="flex justify-center ">
                <img class="h-[150px] w-[150px] rounded-full border-4 my-3" src="https://www.microprixs.com/wp-content/uploads/2023/08/SEO1.jpg"/>
            </div>
                <p class="pt-5 font-semibold text-xl">SEO</p>
                <p class="text-base leading-relaxed pt-3 text-[#374151]">Search Engine Optimization (SEO) is the key to unlocking your digital potential. In this presentation, we'll explore the art and science of SEO, guiding you through strategies that propel your website to the top of search engine rankings. </p>
            </div>

            <!-- inner 2nd div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5 mt-8 rounded-lg">
                <div class="flex justify-center ">
                <img class="h-[150px] w-[150px] rounded-full border-4 my-3" src="https://www.microprixs.com/wp-content/uploads/2023/08/app-Development-ui.jpg"/>
            </div>
                <p class="pt-5 font-semibold text-xl">MOBILE APP &  UI/UX DESIGN</p>
                <p class="text-base leading-relaxed pt-3 text-[#374151]">we involves creating software applications for various digital platforms, such as mobile devices, web browsers, and desktop computers. It encompasses from coding and programming languages to user interface design and user experience (UI/UX) optimization</p>
            </div>

            <!-- inner 3rd div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5 mt-8 rounded-lg">
                <div class="flex justify-center ">
                <img class="h-[150px] w-[150px] rounded-full border-4 my-3" src="https://www.microprixs.com/wp-content/uploads/2023/08/IVR.jpg"/>
            </div>
                <p class="pt-5 font-semibold text-xl">IVR</p>
                <p class="text-base leading-relaxed pt-3 text-[#374151]">Our Web IVR (Interactive Voice Response) service brings an innovative and user-friendly communication solution to businesses of all sizes. By combining the power of traditional IVR technology with web-based interfaces, we offer seamless and efficient customer interactions.</p>
            </div>

            <!-- inner 4th div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5 mt-8 rounded-lg">
                <div class="flex justify-center ">
                <img class="h-[150px] w-[150px] rounded-full border-4 my-3" src="https://www.microprixs.com/wp-content/uploads/2023/08/IOT.png"/>
            </div>
                <p class="pt-5 font-semibold text-xl">IOT </p>
                <p class="text-base leading-relaxed pt-3 text-[#374151]">IoT (Internet of Things) services are at the forefront of digital innovation, revolutionizing the way we interact with the world around us. By connecting everyday devices and objects to the internet, we create smart ecosystems that enhance efficiency, convenience & productivity. </p>
            </div>

            <!-- inner 5th div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5 mt-8 rounded-lg">
                <div class="flex justify-center ">
                <img class="h-[150px] w-[150px] rounded-full border-4 my-3" src="https://www.microprixs.com/wp-content/uploads/2023/08/WEb-1.png"/>
            </div>
                <p class="pt-5 font-semibold text-xl">WEB DEVELOPMENT</p>
                <p class="text-base leading-relaxed pt-3 text-[#374151]">Our web development services are designed to empower businesses and individuals with a strong online presence and a competitive edge in the digital world. Utilizing the latest technologies and industry best practices.</p>
            </div>

            <!-- inner 6th div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5 mt-8 rounded-lg">
                <div class="flex justify-center ">
                <img class="h-[150px] w-[150px] rounded-full border-4 my-3" src="https://www.microprixs.com/wp-content/uploads/2023/08/CRM.png"/>
            </div>
                <p class="pt-5 font-semibold text-xl">CRM & ERP</p>
                <p class="text-base leading-relaxed pt-3 text-[#374151]">Our CRM (Customer Relationship Management) and ERP (Enterprise Resource Planning) services are integral components of modern business management, seamlessly integrated to streamline operations and enhance customer experiences. </p>
            </div>   

        </div>
    </section>


    <!-- Fourth Section -->
    <section class="bg-[#1f365c] font-[assistant] pb-12" >
        <div class="py-12">
            <!-- inner div -->
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5  rounded-lg">
                <span><i class="fa fa-industry text-5xl border-[6px] p-3 rounded-full border-[#282828] text-[#282828]"></i></span>
                <p class="py-6 text-xl font-bold">INDUSTRY SPECIFIC</p>
                <p class="text-[#3e3d3c] leading-relaxed">Experience-Microprixs works across a myriad of industry segments. Our teams are organized in virtual divisions that have the domain expertise and know-how within each industry to offer exceptional technology solutions.</p>
            </div>
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5  rounded-lg mt-8">
                <span><i class="fa fa-life-bouy text-5xl border-[6px] p-3 rounded-full border-[#282828] text-[#282828]"></i></span>
                <p class="py-6 text-xl font-bold">SCALABILITY AND SUPPRT</p>
                <p class="text-[#3e3d3c] leading-relaxed">Microprixs collaborates closely with you to align with your software objectives. Our expertise guides us in identifying the most promising avenues for investment, ensuring your resources are wisely allocated. </p>
            </div>
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5  rounded-lg mt-8">
                <span><i class="fa fa-plug text-5xl border-[6px] p-3 rounded-full border-[#282828] text-[#282828]"></i></span>
                <p class="py-6 text-xl font-bold">YOU OWN THE SOURCE CODE AND IP</p>
                <p class="text-[#3e3d3c] leading-relaxed">Microprixs fully customizable software solutions require no licensing fees at project completion. Under our agreement,you will own the source code and intellectual property of your proprietary software.</p>
            </div>
            <div class=" py-8 flex justify-center text-center flex-col bg-[#fff] px-3 mx-5  rounded-lg mt-8">
                <span><i class="fa fa-clock-o text-5xl border-[6px] py-3 px-4 rounded-full border-[#282828] text-[#282828]"></i></span>
                <p class="py-6 text-xl font-bold">REAL-TIME COMMUNICATION AND COLLABORATION</p>
                <p class="text-[#3e3d3c] leading-relaxed">Microprixs has always followed a “customer comes first” philosophy. Our governance is simple, flexible, and focused on providing end results to our clientele.</p>
            </div>
        </div>
    </section>

    <!-- fifth section -->
    <section class="font-[assistant] bg-fixed bg-white bg-cover bg-top pb-6" style="background-image: url('https://www.microprixs.com/wp-content/uploads/2023/08/new-1.jpg'); background-position:bottom" >
        <div class="px-4 py-10 text-white flex flex-col justify-center">
            <button class="bg-[#ffffff00] leading-normal py-2 text-2xl px-6 border-2 rounded-full my-8">Hurry up! Look Into Your Project Today</button>
            <p class="text-4xl font-bold text-center mt-10">Free Consultation With Our Experts</p>
            <div class="w-full flex justify-center mt-10" >
            <hr class="w-3/12 text-black h-1 bg-black ml-4">
            </div>
            <button class="bg-[#33cf9f] text-[#fff] mt-8  py-4 text-xl rounded-full font-semibold">Consult Your Project Today</button>
        </div>
    </section>

    <!-- sixth section -->
    <section class="font-[assistant] px-4 bg-center bg-cover" style="background-image:url('https://www.microprixs.com/wp-content/uploads/2023/08/about-rotated.jpg')">
        <p class="pt-4 text-center font-bold text-4xl justify-center">Why Work With Us </p>
        <div class="w-full flex justify-center mt-8" >
            <hr class="w-2/12 text-black h-0.5 bg-black ml-4">
            </div>
            <p class="text-2xl font-bold pt-8">Main Reasons To Choose Us</p>
        <div>
        </div>

        <!-- inner 1st div -->
        <div>
            <div class="flex pt-8">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-[#1f365c] text-white h-10 w-10 text-center text-xl font-semibold  rounded-full my-2 mt-4">1</p>
                   </div>
                    <div class="pl-6 pt-1">
                        <p class="text-[17px] pt-2 text-[#4c4c4c]">At Microprixs, what truly sets us apart is our unwavering focus on meticulous details, precision in managing timelines, and expert project supervision. </p>
                    </div>
                </div>

                <div class="flex py-4">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-[#1f365c] text-white h-10 w-10 text-center text-xl font-semibold  rounded-full my-2 mt-4">2</p>
                   </div>
                    <div class="pl-6 pt-1">
                        <p class="text-[17px] pt-2 text-[#4c4c4c]">our methodology is rooted in thorough preliminary research. By immersing ourselves in understanding your company, competitors, target audience, and customer psychographics, we lay the foundation for a customized success strategy.</p>
                    </div>
                </div>

                <div class="flex py-4">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-[#1f365c] text-white h-10 w-10 text-center text-xl font-semibold  rounded-full my-2 mt-4">3</p>
                   </div>
                    <div class="pl-6 pt-1">
                        <p class="text-[17px] pt-2 text-[#4c4c4c]">Our team leverages a diverse skill set spanning advertising, design, branding, public relations, research, and strategic planning. This fusion of expertise is dedicated to not only enhancing aesthetics but also ensuring concrete, measurable outcomes.</p>
                    </div>
                </div>

                <div class="flex py-4">
                    <div class="ce">
                    <p class="flex items-center justify-center bg-[#1f365c] text-white h-10 w-10 text-center text-xl font-semibold  rounded-full my-2 mt-4">4</p>
                   </div>
                    <div class="pl-6 pt-1">
                        <p class="text-[17px] pt-2 text-[#4c4c4c]">Transparency and fairness define our pricing model. You can trust that unexpected charges won't disrupt your budget; any unforeseen costs require your pre-approval. </p>
                    </div>
                </div>
        </div>

        <!-- inner 2nd div -->
        <div class="py-16 flex flex-col mt-10 block">
            <div class=" flex justify-center items-center">
                <div class="bg-[#1f365c] w-fit p-2 rounded-full absolute">
                    <img class="border-4 border-white rounded-full w-16 h-16" src="https://www.microprixs.com/wp-content/uploads/2023/04/istockphoto-47373319reg8-170667a-1.png"/>
                </div>
            </div>
                <div class="bg-[#1f365c] w-fit p-2 rounded-full absolute left-6 mt-14">
                    <img class="border-4 border-white rounded-full w-16 h-16" src="https://www.microprixs.com/wp-content/uploads/2023/04/istockphoto-473733198-170667a.png"/>
                </div>
                <div class="bg-[#1f365c] w-fit p-2 rounded-full absolute right-6 mt-14">
                    <img class="border-4 border-white rounded-full w-16 h-16" src="https://www.microprixs.com/wp-content/uploads/2023/04/istockphoto-4dsbgdrgh73rtfjr73319reg8-170667a.png"/>
                </div>
                <div class="bg-[#1f365c] w-fit p-2 rounded-full absolute left-10 mt-52">
                    <img class="border-4 border-white rounded-full w-16 h-16" src="https://www.microprixs.com/wp-content/uploads/2023/04/istockphoto-4dsbg7373319reg8-170667a.png"/>
                </div>
                <div class="bg-[#1f365c] w-fit p-2 rounded-full absolute right-10 mt-52">
                    <img class="border-4 border-white rounded-full w-16 h-16" src="https://www.microprixs.com/wp-content/uploads/2023/04/istockphoto-4dsbg73rtfjr73319reg8-170667a.png"/>
                </div>
            <div class="flex w-full justify-center pt-2 ">
            <div class="bg-white rounded-full text-center h-[300px] w-[300px] pt-10">
                <p class="font-['playfor-display'] pb-4 text-lg">Industry Experience</p>
                <p class="px-8 text-sm text-[#4c4c4c]">We have gathered over 6 years experience in web-development, Crafting excellent applications and building cloud softwares as a solution.  We host enthusiastic coder and developers and many have over 10 years of experience in their field. </p>
                <p class="mt-6 text-sm"><a class="uppercase text-[#1f365c]" >Learn More</a></p>  
            </div>
        </div>
        </div>
    </section>

    <section class=" bg-[#f3f3f3d6]">
        <p class="pt-8 font-bold text-4xl text-center">Our Clients</p> 
        <div class="px-0 mt-4 pb-10">
            <div id="default-carousel" class="relative w-full" data-carousel="slide">
            <div class="relative h-72  overflow-hidden ">
        <!-- Item 1 -->
        <div class="duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/Airson-6.png" class=" w-44 h-44 object-cover rounded-full" alt="...">
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/pixvix-1-2.png" class="w-44 h-44  object-cover rounded-full" alt="...">
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/ezeerides-1-2.png" class="w-44 h-44  object-cover rounded-full" alt="...">
        </div>
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out flex flex-col justify-center items-center text-center" data-carousel-item>
            <img src="https://www.microprixs.com/wp-content/uploads/2023/08/vayadubai12-1.jpeg" class="w-44 h-44  object-cover rounded-full" alt="...">
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="absolute z-30 flex -translate-x-1/2 bottom-4 left-1/2 space-x-3 ">
        <button type="button" class="w-3 h-3 rounded-full bg-black/50 dark:bg-gray-800/50 hover:bg-black dark:hover:bg-gray-800" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-black/50 dark:bg-gray-800/50 hover:bg-black dark:hover:bg-gray-800" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-black/50 dark:bg-gray-800/50 hover:bg-black dark:hover:bg-gray-800" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full bg-black/50 dark:bg-gray-800/50 hover:bg-black dark:hover:bg-gray-800" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
        <!-- <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button> -->
    </div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none hidden sm:block " data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
            </svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none hidden sm:block" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
            </svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
    </div>
    </div>
    </section>


    <!-- footer -->
    <div>
    <Footer/>
    </div>
</template>



