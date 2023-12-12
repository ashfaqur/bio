<script>
    import Card from "./Card.svelte";
    import Contact from "./Contact.svelte";
    import Abilities from "./Abilities.svelte";
    import Language from "./Language.svelte";
</script>

<div class="left-panel">
    <Card></Card>
    <Contact></Contact>
    <Abilities></Abilities>
    <Language></Language>
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
