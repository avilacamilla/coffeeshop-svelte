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