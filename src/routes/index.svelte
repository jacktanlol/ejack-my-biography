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
</script>

<Header/>
<Section {...myInfo}/>
<Section {...myHobby}/>