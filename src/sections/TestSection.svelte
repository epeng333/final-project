<script>
    import Scroller from "../lib/Scroller.svelte";
    import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="left">
        {#snippet sticky()}
            <img class="plane-img" src="plane.jpg" alt="plane!" />           
        {/snippet}
    
        {#snippet scrolly()}
            <ArticleText>
                Even if it feels unfamiliar...
            </ArticleText>

            <ArticleText>
                Give it a try.
            </ArticleText>

            <ArticleText>
                The possibilities are endless.
            </ArticleText>
        {/snippet}
    </Scroller> 
</div>