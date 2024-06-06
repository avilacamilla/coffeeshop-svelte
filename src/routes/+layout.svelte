<script>
  import Header from "$lib/Header.svelte";
</script>

<div class="layout-container">
    <header class="layout-header-container">
        <Header />
    </header>
    <!-- espaço para o componente header que será fixo -->

    <main class="layout-main-container">
        <slot />
    </main>
</div>

<style>
    .layout-container {
        display: flex;
        flex-direction: column;
        gap: 0;
        margin: 0;
        padding: 0;
        height: 100vh;
        background-color: #3b2525;
    }
</style>