<script lang="ts">
function myFunction(myMessage:String) {
    alert(myMessage);
}
</script>

<!-- #FCFCF8-->
<header style="height: 56px; background-color: #C66D19; color: #9E0003;">
Takuma
    
</header>
<!-- #2A2925-->
<header style="height: 56px; background-color: #E77C1A; color:#9E0003; ">
Takuma

<a href='http://www.google.com' on:click={() => myFunction('test')}>mylink</a>
</header>


<!-- #2A2925-->

<main>
    <slot />
</main>

<style>
	:global(html, body) {
		height: 100%;
		width: 100%;
        background-color:#FCFCF8;
	}

    :global(body){
        margin: 0;
    }
</style>