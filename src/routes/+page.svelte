<script>
    import image_coffee1 from '$lib/images/3.png';
    import image_coffee2 from '$lib/images/2.png';
</script>

<div class="home-container">
    <div class="home-header-hero-container">
        <div class="home-header-hero-image">
            <img 
                src={image_coffee1} 
                alt="" 
                class="header-hero-image"
            >
        </div>
        <div class="home-header-hero-subtitle">
            <h2 class="header-hero-subtitle">
                A <b>melhor</b> qualidade de grãos de café <br />para o melhor café.
            </h2>
        </div>
        <!-- <div class="home-header-hero-image">
            <img 
                src={image_coffee2} 
                alt="" 
                class="header-hero-image"
            >
        </div> -->
    </div>
    
    <div class="home-products-container">
        teste
    </div>
</div>

<style>
    .home-container {
        display: flex;
        flex-direction: column;
        margin: 0;
        padding: 0;
        background-color: #3b2525;
    }

    .home-header-hero-container {
        display: flex;
        width: 100%;
    }

    .home-header-hero-image {
        display: flex;
        width: 40%;
    }

    .header-hero-image {
        width: 100%;
    }

    .home-header-hero-subtitle {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 60%;
    }

    .home-header-hero-subtitle {
        display: flex;
        /* justify-content: flex-start; */
    }

    .header-hero-subtitle {
        font-family: 'Poppins', sans-serif;
        font-size: 4.5rem;
        font-weight: 500;
        line-height: 6rem;
        color: antiquewhite;
        width: 75%;
    }
</style>