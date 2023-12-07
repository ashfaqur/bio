<script>
    import Card from "./Card.svelte";
</script>

<div class="left-panel">
    <Card></Card>
</div>

<style>
    .left-panel {
        background-color: rgb(197, 237, 230);
        display: flex;
        flex-direction: column;
        align-items: center;
        border-radius: 12px;
        width: 100%;
    }
    @media (min-width: 860px) {
        .left-panel {
            margin-right: 0.3rem;
            height: 100%;
        }
    }
</style>
