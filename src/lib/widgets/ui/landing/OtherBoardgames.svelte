<script>
  const otherBoardgames = [
	{
		title: 'PALEO-STORIES',
		img: '/images/boardgames/paleo-stories.svg',
		link: '/',
		anchor: '#paleo-stories',
		desc: `Paleo Stories - educational boardgame, enhanced by the interactive web application, that introduces players to the world of paleontological expeditions and the science of paleontology. `
	},
	{
		title: 'ARCHAEO-STORIES',
		img: '/images/boardgames/archaeo-stories.svg',
		link: 'https://archaeo-stories.vercel.app/',
		anchor: '#archaeo-stories',
		desc: `Archaeo stories - educational boardgame, enhanced by an interactive web application, offers you to explore ancient grounds, unearth artifacts, and  become a real archaeologist! `
	},
	{
		title: 'HERITAGE-STORIES',
		img: '/images/boardgames/heritage-stories.svg',
		link: '/',
		anchor: '#heritage-stories',
		desc: `Heritage stories - educational boardgame, enhanced by an interactive web application, about eco-friendly bicycle trip through the World Heritage Cities.`
	},
	{
		title: 'CASTLE-STORIES',
		img: '/images/boardgames/castle-stories.svg',
		link: '/',
		anchor: '#castle-stories',
		desc: `Castle stories - educational boardgame, enhanced by an interactive web application, which will take you to the world of grand castles and ancient fortifications! Collect historical facts, complete tasks and unlock the secrets of ancient buildings to become a true connoisseur of medieval architecture.`
	},
	{
		title: '12262-STORIES',
		img: '/images/boardgames/12262-stories.svg',
		link: '/',
		anchor: '#12262-stories',
		desc: `Explore the Kolskaya ultra-deep borehole, one of the deepest man-made facilities on the planet, drilled to a record depth of 12,262 meters. Discover a symbol of scientific and technical progress that has provided unique data for geological and geophysical research and generated many myths and legends and it's been called "the well to Hell."`
  },	{
		title: 'pyramid-stories',
		img: '/images/boardgames/pyramid-stories.svg',
		link: '/',
		anchor: '#pyramid-stories',
		desc: ``
  },


	{
		title: 'Belarus/Poland-STORIES',
		img: '/images/boardgames/by-pl-stories.svg',
		link: 'https://by-pl.vercel.app/',
		anchor: '#12262-stories',
		desc: `"Cultures of Belarus and Poland" - through the materials prepared as part of this project, you will learn more about the relationship between these two neighboring countries, their history, culture and traditions.`	}
];

</script>

<section id="products" class="section-products">
          <div class="page-padding">
            <div class="container-large">
              <div class="padding-vertical padding-huge">
                <div class="products_component">
                  <div class="products_info">
                    <div class="div-block-12">
                      <div class="margin-bottom margin-medium">
                        <h2 class="heading-xlarge">Lorem Ipsum is  <span class="text-style-link"> dummy</span>  dummy text </h2>
                      </div>
                      <div class="margin-bottom margin-xlarge">
                        <div class="text-size-medium max-width-medium">
                          <strong>Lorem Ipsum is simply dummy text </strong> of the printing and typesetting industry. Lorem Ipsum has been the industry's standard
                        </div>
                      </div>
                    </div>
                  </div>
                  <div   class="benefits-list is-products">
                    <div  class="margin-right margin-medium">
                      <div class="margin-bottom margin-medium">
                        <div class="icon-wrapper">
                          <div class="margin-right margin-small">
                            <div class="icon-1x1-small w-embed">
                              <svg role="img" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <title>Check icon</title>
                                <g>
                                  <rect fill="none" height="24" width="24"></rect>
                                  <rect fill="none" height="24" width="24"></rect>
                                </g>
                                <g>
                                  <path d="M23,12l-2.44-2.79l0.34-3.69l-3.61-0.82L15.4,1.5L12,2.96L8.6,1.5L6.71,4.69L3.1,5.5L3.44,9.2L1,12l2.44,2.79l-0.34,3.7 l3.61,0.82L8.6,22.5l3.4-1.47l3.4,1.46l1.89-3.19l3.61-0.82l-0.34-3.69L23,12z M9.38,16.01L7,13.61c-0.39-0.39-0.39-1.02,0-1.41 l0.07-0.07c0.39-0.39,1.03-0.39,1.42,0l1.61,1.62l5.15-5.16c0.39-0.39,1.03-0.39,1.42,0l0.07,0.07c0.39,0.39,0.39,1.02,0,1.41 l-5.92,5.94C10.41,16.4,9.78,16.4,9.38,16.01z"></path>
                                </g>
                              </svg>
                            </div>
                          </div>
                          <div class="text-size-medium">Lorem impsum</div>
                        </div>
                      </div>
                      
                    </div>
                    <div class="div-block-11">
                      <img src="images/favicon.svg" loading="lazy" sizes="(max-width: 767px) 100vw, (max-width: 991px) 100px, 8vw" alt="Logo THE Heritage Stories boardgame" class="image-8">
                    </div>
                  </div>
                </div>



                <div class="slider-wrapper w-dyn-list">
                  <div role="list" class="slider-list w-dyn-items">
                    {#each otherBoardgames as boardgame}
                    <div role="listitem" class="slider-item w-dyn-item">
                      <div class="div-block-9">
                        <img src="{boardgame.img}" loading="lazy" alt="Ureum crème" sizes="(max-width: 479px) 100vw, (max-width: 767px) 95vw, (max-width: 991px) 45vw, 46vw" class="image-7">
                      </div>
                      <div class="div-block-13">
                        <h3 class="heading-large margin-bottom margin-medium">{boardgame.title}</h3>
                        <p class="text-size-medium is-product">{boardgame.desc}</p>
                      </div>
                    </div>
                    {/each}
                  
                  </div>
                </div>
                <div class="slider-navigation-wrapper">
                  <div class="controls">
                    <a href="#" class="control slider-navigation prev-slide w-inline-block">
                      <div class="control__fill"></div>
                      <div class="control__arrow w-embed">
                        <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
                          <path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
                        </svg>
                      </div>
                    </a>
                    <a href="#" class="control slider-navigation next-slide w-inline-block">
                      <div class="control__fill"></div>
                      <div class="control__arrow is--flipped w-embed">
                        <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
                          <path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
                        </svg>
                      </div>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        