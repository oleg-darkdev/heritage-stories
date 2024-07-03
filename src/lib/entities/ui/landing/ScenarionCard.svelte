<script>

  export let scenario;
</script>

<div class="service_item">
	<div class="margin-bottom margin-small">
		<h6 class="text-size-large">{scenario.title}</h6>
	</div>
	<div class="margin-bottom margin-small">
		<div>
      
			<!--  of voor <strong>Loewn</strong> -->
      <p>{scenario.desc}</p>
      <!-- {#each scenario.desc as desc}<p>{desc}</p>{/each} -->
		</div>
	</div>
	<!-- <a href="/" class="button w-button">{scenario.country}</a> -->
</div>


<style>
.service_item{
    color:#fff;
    background-color:#713f13;
    border-radius:50px;
    flex-direction:column;
    justify-content:space-between;
    align-items:flex-start;
    padding:40px;
    display:flex
}

</style>