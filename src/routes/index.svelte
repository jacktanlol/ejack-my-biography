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
</script>

<Header/>
<Section {...myInfo}/>