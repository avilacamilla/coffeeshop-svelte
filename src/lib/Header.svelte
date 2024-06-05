<script>
    import coffee_logo from '$lib/images/coffee-logo.png';
</script>

<nav class="header-container">
    <ul class="header-list-item-container">
        <li class="list-item item-logo">
            <a href="/" class="list-item-ancor">
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
            <a href="/about" class="list-item-ancor">Quem é a Coffee?</a>
        </li>
        <li class="list-item">
            <a href="/contact" class="list-item-ancor">Contato</a>
        </li>
    </ul>
</nav>


<style>
    .header-container {
        display: flex;
        width: 100%;
    }

    .header-list-item-container {
        display: flex;
        gap: 1rem;
        width: 100%;
    }

    .list-item {
        display: flex;
        align-items: center;
        list-style-type: none;        
    }

    .item-logo {
        width: 40%;
    }

    .list-item-ancor {
        text-decoration: none;
    }

    .list-item-ancor-image {
        width: 20rem;
    }
</style>