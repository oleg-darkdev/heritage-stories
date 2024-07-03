<script>
  const otherBoardgames = [{
    title: 'PALEO-STORIES',
    img: '/images/boardgames/paleo-stories.svg',
    link: '/',
    anchor: '#paleo-stories',
    desc: `Paleo Stories - educational boardgame, enhanced by the interactive web application, that introduces players to the world of paleontological expeditions and the science of paleontology. `
  }, {
    title: 'ARCHAEO-STORIES',
    img: '/images/boardgames/archaeo-stories.svg',
    link: 'https://archaeo-stories.vercel.app/',
    anchor: '#archaeo-stories',
    desc: `Archaeo stories - educational boardgame, enhanced by an interactive web application, offers you to explore ancient grounds, unearth artifacts, and  become a real archaeologist! `
  }, {
    title: 'CASTLE-STORIES',
    img: '/images/boardgames/castle-stories.svg',
    link: '/',
    anchor: '#castle-stories',
    desc: `Castle stories - educational boardgame, enhanced by an interactive web application, which will take you to the world of grand castles and ancient fortifications! Collect historical facts, complete tasks and unlock the secrets of ancient buildings to become a true connoisseur of medieval architecture.`
  }, {
    title: '12262-STORIES',
    img: '/images/boardgames/12262-stories.svg',
    link: '/',
    anchor: '#12262-stories',
    desc: `Explore the Kolskaya ultra-deep borehole, one of the deepest man-made facilities on the planet, drilled to a record depth of 12,262 meters. Discover a symbol of scientific and technical progress that has provided unique data for geological and geophysical research and generated many myths and legends and it's been called "the well to Hell."`
  }, {
    title: 'pyramid-stories',
    img: '/images/boardgames/pyramid-stories.svg',
    link: '/',
    anchor: '#pyramid-stories',
    desc: `Explore the Kolskaya ultra-deep borehole, one of the deepest man-made facilities on the planet, drilled to a record depth of 12,262 meters. Discover a symbol of scientific and technical progress that has provided unique data for geological and geophysical research and generated many myths and legends and it's been called "the well to Hell."`
  }, {
    title: 'Belarus/Poland-STORIES',
    img: '/images/boardgames/by-pl-stories.svg',
    link: 'https://by-pl.vercel.app/',
    anchor: '#12262-stories',
    desc: `"Cultures of Belarus and Poland" - through the materials prepared as part of this project, you will learn more about the relationship between these two neighboring countries, their history, culture and traditions.`
  }];


  let step = 0;
const prevBoardgame = () => step > 0 ? step-- : step;
const nextBoardgame = () => step <= otherBoardgames.length - 2 ? step++ : step;


  $: actualBoardgame = otherBoardgames[step];
</script>
<section class="section-products">
  <div class="page-padding">
    <div class="container-large">
      <div class="padding-vertical padding-huge">




        <div class="slider-wrapper w-dyn-list">
          <div role="list" class="slider-list w-dyn-items">
            <!-- {#each otherBoardgames as boardgame} -->
							<div role="listitem" class="slider-item w-dyn-item">
								<div class="div-block-9">
									<img src="{actualBoardgame.img}" loading="lazy" alt="Ureum crème" sizes="(max-width: 479px) 100vw, (max-width: 767px) 95vw, (max-width: 991px) 45vw, 46vw" class="image-7">
									</div>
									<div class="div-block-13">
										<h3 class="heading-large margin-bottom margin-medium">{actualBoardgame.title}</h3>
										<p class="text-size-medium is-product">{actualBoardgame.desc}</p>
									</div>
								</div>
            <!-- {/each} -->


							</div>
						</div>
						<div class=" ">
							<div class="mt-6 controls-otherboardgames">
                {#if step > 0}
								<button on:click={()=> prevBoardgame()} class="control slider-navigation prev-slide w-inline-block">
									<div class="control__fill"></div>
									<div class="control__arrow w-embed">
										<svg version="1.1" id="Layer_1"
											xmlns="http://www.w3.org/2000/svg"
											xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
											<path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
										</svg>
									</div>
								</button>
                {/if}
                {#if step < otherBoardgames.length - 1}
								<button  on:click={()=> nextBoardgame()} class="control slider-navigation next-slide w-inline-block">
									<div class="control__fill"></div>
									<div class="control__arrow is--flipped w-embed">
										<svg version="1.1" id="Layer_1"
											xmlns="http://www.w3.org/2000/svg"
											xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
											<path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
										</svg>
									</div>
								</button>
                {/if}
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>



    <style>
      .controls-otherboardgames {
    z-index:4;
    width:13em;
    justify-content:center;
    align-items:center;
    margin-left:auto;
    margin-right:auto;
    display:flex;

}
    </style>
