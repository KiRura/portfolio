<script>
    let count = 0;
    function increment() {
        count += 1;
    }
</script>

<button on:click={increment}>Clicked {count} time{(count !== 1) ? "s" : ""}</button>