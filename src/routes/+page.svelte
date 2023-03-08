<script>
    import Icons from "../lib/Icons.svelte";
</script>

<div
    class="snap-center grid items-center w-full h-screen px-5 lg:px-[10%] lg:py-5 gap-5 grid-cols-[auto_1fr]">
    <div class="relative">
        <div class="-bottom-[5rem] h-[10rem] w-[10rem] absolute -left-[6rem]">
            <Icons name="paper" />
        </div>
    </div>

    <div
        class="hidden font-semibold lg:flex absolute text-[#B4B4B4] text-[1.5rem] right-10 top-10 flex-col items-end gap-2">
        <div class="flex justify-end gap-5 pb-2">
            <div class="w-[3rem] lg:w-[4rem]"><Icons name="email" /></div>
            <div class="w-[3rem] lg:w-[4rem]"><Icons name="linkedin" /></div>
            <div class="w-[3rem] lg:w-[4rem]"><Icons name="github" /></div>
        </div>
        <p>jiuvirgil@gmail.com</p>
        <p>in/jiu-virgil</p>
        <p>jiuvirgil</p>
    </div>

    <div class="flex flex-col text-[1.5rem]">
        <h1 class="pb-5 font-bold">
            Virgil Constantin's<br />Portfolio
        </h1>
        <h2>Web Developer & Designer</h2>
    </div>

    <div class="w-[3rem] lg:w-[4rem]">
        <Icons name="book" />
    </div>
    <div class="flex flex-col">
        <h3>Studying at POLITEHNICA University of Bucharest</h3>
        <h3>2021 - present</h3>
    </div>
    <!--  -->
    <div class="self-start w-[3rem] lg:w-[4rem]">
        <Icons name="briefcase" />
    </div>
    <div class="flex flex-col">
        <h3>Worked as a Freelancer on Freelancer.com for 20+ customers</h3>
        <h3>Ian 2020 - Oct 2021</h3>
        <p class="text-[#B4B4B4] font-medium">
            Various projects for individuals and small businesses where I
            developed multithreaded scripts, GUIs for APIs, database models,
            optimized & reviewed code and built fast, static websites.
        </p>
    </div>
    <!--  -->
    <div class="self-start w-[3rem] lg:w-[4rem]"><Icons name="gear" /></div>
    <div class="flex flex-col">
        <h3>My skills:</h3>
        <p class="text-[#B4B4B4] font-medium">
            Svelte, React, Flask, MySQL, MongoDB, Prisma, Javascript, Scss
            Selenium, BeautifulSoup, Python, C#, basic C++ Figma, Illustrator,
            GitHub.
        </p>
    </div>
    <!--  -->
    <div class="w-[3rem] lg:w-[4rem]"><Icons name="resume" /></div>
    <a href="#resume" class="flex gap-2 items-end">
        <h3>My resume</h3>
        <div class="w-[1.5rem]">
            <Icons name="link" />
        </div>
    </a>

    <div>
        <div class="w-[3rem] lg:w-[4rem]"><Icons name="arrow" /></div>
    </div>
    <div>
        <h3>Projects</h3>
        <div class="flex items-center gap-2 text-[#B4B4B4] font-medium">
            <div class="w-[1.5rem] h-[1.5rem]">
                <Icons color="#B4B4B4" name="github" />
            </div>
            <p>jiu-virgil</p>
        </div>
    </div>
</div>
<div class="relative w-full overflow-x-clip">
    <img
        src="asterisk.png"
        alt="a giant asterisk"
        class="-right-[7.5rem] -bottom-[3.5rem] lg:right-10 lg:bottom-10 absolute w-[15rem] h-[15rem] lg:w-[60vh] lg:h-[60vh]" />
</div>

<div
    class="p-5 lg:px-[10%] gap-10 flex flex-col lg:grid lg:grid-cols-[minmax(auto,1fr)_auto]">
    <div class="flex justify-center flex-col gap-2">
        <h3>Scheduler for various small businesses</h3>
        <p class="text-[#B4B4B4] font-medium">
            Built for a tattoo salon so that customers could see how booked the
            artists are before calling for a session.
        </p>
        <p class="text-[#B4B4B4] font-medium">
            Since then I rewrote it to be more modular, so that it could be used
            in other small businesses with similar needs, such as nail salons,
            dentists, dog walkers, etc.
        </p>
        <div class="pt-2 flex gap-5">
            {#each Array(5) as _}
                <div class="w-[2rem] h-[2rem] bg-white rounded-full" />
            {/each}
        </div>
    </div>
    <div class="col-span-3 lg:col-span-1 bg-white rounded-xl">
        <img
            class="-z-10 max-h-[300px] object-cover"
            src="asterisk.png"
            alt="" />
    </div>

    <div class="justify-center flex flex-col gap-2">
        <h3>Landing page and portfolio template</h3>
        <p class="text-[#B4B4B4] font-medium">
            Built for a solar installation company.
        </p>
        <p class="text-[#B4B4B4] font-medium">
            Simple, static, 3 page website, with an almost perfect lighthouse
            score thanks to using one of the latest emerging stacks.
        </p>
        <div class="pt-2 flex gap-5">
            {#each Array(5) as _}
                <div class="w-[2rem] h-[2rem] bg-white rounded-full" />
            {/each}
        </div>
    </div>

    <div class="col-span-3 lg:col-span-1 bg-white rounded-xl">
        <img class="max-h-[300px] object-cover" src="asterisk.png" alt="" />
    </div>
</div>

<div class="h-screen flex flex-col p-5 lg:px-[10%]">
    <div class="grid grid-cols-[auto_1fr] items-center gap-5">
        <div class="w-[3rem] lg:w-[4rem]">
            <Icons name="chat" />
        </div>
        <h3>Let's talk</h3>
        <div class="w-[3rem] lg:w-[4rem]">
            <Icons name="linkedin" />
        </div>
        <p class="font-semibold">
            If you’re a recruiter or just interested in working with me, let’s
            link.
        </p>
        <div class="w-[3rem] lg:w-[4rem]">
            <Icons name="email" />
        </div>
        <p class="font-semibold">Or if it’s easier, just write me an email!</p>
    </div>

    <a href="mailto:jiuvirgil@gmail.com" class="h-full my-10">
        <p
            class="max-w-[600px] mb-5 p-5 h-full text-[#b4b4b4] font-semibold bg-[#383838] rounded-xl">
            Hello, I’ve seen your websites and I would be interested in working
            with you.
        </p>
        <div class="w-[3rem] h-[3rem]">
            <Icons name="send" />
        </div>
    </a>

    <div class="flex items-end w-full justify-between">
        <div class="text-[#B4B4B4] font-semibold flex items-center gap-3">
            <div class="w-[2rem] h-full">
                <Icons color="#B4B4B4" viewbox="0 0 32 32" name="svelte" />
            </div>
            <p>Rebuilt<br />with Svelte</p>
        </div>
        <div
            class="z-10 flex-col lg:flex-row text-right justify-end font-semibold text-black flex items-center gap-2">
            <p>2022</p>
            <div class="w-[2rem]">
                <Icons color="black" name="copyright" />
            </div>
            <p>Constantin Virgil</p>
        </div>
    </div>
</div>

<div class="relative w-full h-0 overflow-x-clip">
    <img
        src="circle.png"
        alt="a giant circle"
        class="absolute -bottom-[20rem] object-contain -right-[10rem] w-[50rem] h-[50rem]" />
</div>
