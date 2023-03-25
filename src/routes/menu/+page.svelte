<script>
    const listMenu  =[
        'Latte',
        'esspresso',
        'Hotchcoloate',
        'Vanilla latte',
        'motcha Latte'
        ];
</script>

<main>
    <h1>Menu</h1>
    <ol>
        {#each listMenu as Menu}
        <li>{Menu}</li>
        {/each}
    </ol>
</main>