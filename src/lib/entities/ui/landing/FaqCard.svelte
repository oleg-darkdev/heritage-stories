<script>
  export let faq;
</script>


<div  class="faq_item">
	<div class="faq_question" on:click={()=> faq.showAnswer = !faq.showAnswer}>
	<h5 class="heading-small">{faq.q}</h5>
	<!-- <div  class="faq-arrow"></div> -->
	</div>
	{#if faq.showAnswer}
		<div class="faq_answer">
		<p class="faq_answer-text">
			<strong>Uw voeten zijn letterlijk de basis van uw lichaam.</strong> Denk er maar eens over na hoeveel een mens loopt. Veel mensen vergeten hun voeten en gaan pas naar een pedicure wanneer ze last krijgen van bijvoorbeeld likdoorns of eeltplekken. Wanneer u regelmatig een pedicure bezoekt, kunnen deze grotendeels klachten voorkomen worden.
		</p>
		</div>
	{/if}
</div>