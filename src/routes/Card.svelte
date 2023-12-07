<script>
    import img from "$lib/images/me.jpg";
</script>

<div class="card">
    <img src="me.jpg" alt="" />

    <img src={img} alt="Author" />

    <h2>Ashfaqur Rahman</h2>
    <h3>Software Developer</h3>
    <h4><i class="fas fa-map-marker-alt fa-1x"></i> Munich, Germany</h4>
</div>

<style>
    .card {
        height: 300px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: rgb(12, 66, 64);
    }
    .card img {
        width: 150px;
        margin-top: 10px;
        border-radius: 50%;
        transition:
            color 0.25s,
            border-color 0.25s,
            box-shadow 0.25s,
            transform 0.25s;
    }
    .card img:hover {
        border-color: rgb(12, 66, 64);
        color: white;
        box-shadow: 0 0.9em 0.9em -0.4em rgb(12, 66, 64);
        transform: translateY(-0.25em);
        cursor: pointer;
    }
    .card h3 {
        margin-top: 0px;
    }
    .card h4 {
        margin-top: 0px;
    }
</style>
