<script>
  import {ScenarionCard, BenefitsCard} from '$entities';


  const features = [
	{
		title: 'Education 4.0 goals',
		desc: `The use of gamification and technology allows the educational process to be adapted to the individual needs of students and stimulates the development of core 21st century competencies such as critical thinking, creativity and collaboration, which is completely in accordance with the goals of Education 4.0.`
	},
	{
		title: 'Eco-friendly materials',
		desc: `The board games included in the stories are made of eco-friendly and 100% recyclable materials: wood, metal and eco-paper printed with eco-friendly ink.`
	},
	{
		title: 'OPEN SOURCE',
		desc: `The board game print materials and web application source code are free and publicly available in the repository for download and modification.`
	}
];
  
</script>


<section class="">
    <div class="page-padding">
    <div class="container-large">

        <a name='features' /> 
        <div class="products_component">
          <div class="products_info">
            <div class="">
              <div class="margin-bottom margin-medium">
                <h2 class="heading-xlarge">THE Heritage Stories - <span class="text-style-link">boardgame with modern technologies</span> </h2>
              </div>
              <div class="margin-bottom margin-xlarge">
                <div class="text-size-medium max-width-medium">
                  <strong>Lorem Ipsum is simply dummy text </strong> of the printing and typesetting industry. Lorem Ipsum has been the industry's standard
                </div>
              </div>
            </div>
          </div>
          
          <div class='benefits-wrap mb-20'>
            <BenefitsCard />
          </div>
        </div>
        
        <div class="lg:mb-40 md:mb-40 mb-20">
          <div class="services_component">
            {#each features as scenario}
              <ScenarionCard {scenario} />
            {/each}
          </div>
        </div>
    </div>
</section>


<style>
  @media screen and (min-width:991px){
    .benefits-wrap{
        display:none
    }
  }
</style>