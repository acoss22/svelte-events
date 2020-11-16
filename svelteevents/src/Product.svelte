<script>
export let productTitle;

</script>
<article on:click="{() => console.log('hello')}">
    <h1>{productTitle}</h1>
    <button on:click>Add to Cart</button> 
    <button>Delete</button>
</article>