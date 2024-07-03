<script>
  export let faq;
</script>


<div class="faq_item" on:click={()=> faq.showAnswer = !faq.showAnswer}>
	<div class="faq_question" >
	<h5 class="heading-small">{faq.q}</h5>
	<!-- <div  class="faq-arrow"></div> -->
	</div>
	{#if faq.showAnswer}
		<div class="faq_answer">
      {#each faq.a as answer}
      <p class="faq_answer-text">
        <!-- <strong>Lorem impsum</strong> -->
        {answer}
      </p>
      {/each}
		</div>
	{/if}
</div>


<style>
  .faq_answer-text{
      margin-bottom:30px
  }

</style>