<script>
    let message = ''

    export let color = 'red'
</script>

<button class=" bg-violet-500 hover:bg-violet-600 active:bg-violet-700 focus:outline-none focus:ring focus:ring-violet-300"
    on:click={() => message+='hello! '} 
    style="background: {color}; padding 1rem;">
    hello
</button>

{message}