<script>
    import coffee_logo from '$lib/images/coffee-logo.png';
</script>

<nav class="header-container">
    <ul class="header-list-item-container">
        <li class="list-item item-logo">
            <a href="/" class="list-item-ancor-logo">
                <img 
                    src={coffee_logo} 
                    alt="" 
                    class="list-item-ancor-image"
                >
            </a>
        </li>        
        <li class="list-item">
            <a href="/" class="list-item-ancor">Início</a>
        </li>
        <li class="list-item">
            <a href="/about" class="list-item-ancor">Menu</a>
        </li>
        <li class="list-item">
            <a href="/contact" class="list-item-ancor">Contato</a>
        </li>
        <li class="list-item">
            <a href="/contact" class="list-item-ancor">Sobre</a>
        </li>
    </ul>

    <div class="header-btn-act-container">
        <button class="header-btn-act">
            Faça sua reserva!
        </button>
    </div>
</nav>


<style>
    .header-container {
        display: flex;
        justify-content: space-between;
        margin: 0;
        padding: 0;
        width: 100%;
        background-color: antiquewhite;
    }

    .header-list-item-container {
        display: flex;
        width: 100%;
    }

    .list-item {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 8rem;
        list-style-type: none;
        cursor: pointer;
    }

    .list-item-ancor {
        text-decoration: none;
        font-size: 1.1rem;
        color: #3b2525;
        font-family: "Poppins", sans-serif;
        font-weight: 300;
        position: relative;
        text-transform: uppercase;
        letter-spacing: .2rem;  
    }

    .list-item-ancor::after {
        content: '';
        position: absolute;
        width: 0;
        height: 2px;
        display: block;
        margin-top: 5px;
        left: 0;
        background: #3b2525;
        transition: width 0.4s ease, left 0.3s ease;
    }

    .list-item-ancor:hover::after {
        width: 100%;
        left: 0;
    }

    .list-item-ancor:hover {
        color: #3b2525e2;
    }


    .item-logo {
        width: 20rem;
        list-style-type: none;
    }

    .list-item-ancor-image {
        width: 100%;
        transition: transform 0.3s ease;
    }

    .list-item-ancor-image:hover {
        transform: scale(1.1);
    }

    .header-btn-act-container {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 30%;
    }

    .header-btn-act {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 60%;
        height: 4rem;
        border: none;
        border-radius: 2rem;
        background-color: #3b2525;
        color: antiquewhite;
        font-family: 'Poppins', sans-serif;
        font-size: 1.2rem;
        font-weight: 800;
        cursor: pointer;
        transition: background-color 0.3s ease, border 0.3s ease, color 0.3s ease; /* Transições suaves */
    }

    .header-btn-act:hover {
        background-color: antiquewhite;
        border: .2rem solid #3b2525;
        color: #3b2525;
    }

</style>