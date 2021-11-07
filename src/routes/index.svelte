<script>
    import Header from '$lib/Header.svelte';
    let title="My Biography"
    import Section from '$lib/Section.svelte';
    let myInfo = {
    title: "Info",
    item1: "Ejack Tan",
    item2: 14,
    item3: "SM Han Chiang High School",  
    }
    let myHobby = {
    title: "Hobby",
    item1: "Swimming",
    item2: "Coding",
    item3: "Football",
    }
    let myPersonality = {
    title: "Personality",
    item1: "Shy",
    item2: "Quiet",
    item3: "Stable",
}
    import Footer from '$lib/Footer.svelte'; 
    let gitHub=   "https://github.com/jacktanlol/ejack-my-biography"
</script>


<div class=" bg-dark text-white text-center">
    <Header {title}/>
    <div class="d-flex flex-column bg-info border border-dark ">
        <div class="p-2 bd-highlight">
            <span class="border">
            <Section {...myInfo}/>
        </span>
    </div>
    <div class="p-2 bd-highlight">
        <span class="border">
        <Section {...myHobby}/>
    </span>
    </div>
    <div class="p-2 bd-highlight"> 
        <span class="border">
        <Section {...myPersonality}/>
    </span>
    </div> 
 </div>
    <Footer {gitHub}/>
</div>
