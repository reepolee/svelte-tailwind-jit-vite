<script>
    let section
</script>

<style>
    main {
        @apply grid place-items-center h-full;
    }
</style>

<main>
    <div>
        <section bind:this={section}>
            <h1 class="text-svelte-500 text-4xl pb-8">Svelte & TailwindCSS JIT on Vite</h1>
        </section>
        <pre>
          {section?.innerHTML}
        </pre>
    </div>
</main>
