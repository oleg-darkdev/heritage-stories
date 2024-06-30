<script>
  import {ScenarionCard} from '$entities';

  const scenarios = [
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


<section id="services" class="section-services">
    <div class="page-padding">
    <div class="container-large">
        <div class="padding-vertical padding-huge">
        <div class="services_component">
          {#each scenarios as scenario}
            <ScenarionCard {scenario} />
          {/each}

        </div>
        </div>
    </div>
    </div>
</section>
