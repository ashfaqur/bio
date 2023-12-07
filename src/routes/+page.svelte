<script>
    import LeftPanel from "./LeftPanel.svelte";
    import RightPanel from "./RightPanel.svelte";
</script>

<div class="container">
    <LeftPanel></LeftPanel>
    <RightPanel></RightPanel>
</div>

<style>
    .container {
        background-color: rgb(208, 219, 217);
        width: 100%;
        min-width: 300px;
        max-width: 1200px;
        margin: 10px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    @media (min-width: 860px) {
        .container {
            flex-direction: row;
            align-items: flex-start;
        }
    }
</style>
