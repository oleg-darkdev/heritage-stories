<script>
  	import Carousel from 'svelte-carousel'
    import { browser } from '$app/environment'

  const slides = [{
    img: '/images/scenarios/italy.svg',
    altText: 'lorem impsum'
  }, {
    img: '/images/scenarios/india.svg',
    altText: 'lorem impsum'
  }, {
    img: '/images/scenarios/russia.svg',
    altText: 'lorem impsum'
  }, {
    img: '/images/scenarios/uk.svg',
    altText: 'lorem impsum'
  }, {
    img: '/images/scenarios/france.svg',
    altText: 'lorem impsum'
  }, {
    img: '/images/scenarios/germany.svg',
    altText: 'lorem impsum'
  }, ]
</script>
<section class="section-slider">
  <section class="section-2 is--slider">
    <div class="slider__wave w-embed">
      <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 804 50.167" enable-background="new 0 0 804 50.167" xml:space="preserve">
        <path fill="#FFECD9" d="M804,0v16.671c0,0-204.974,33.496-401.995,33.496C204.974,50.167,0,16.671,0,16.671V0H804z"></path>
      </svg>
    </div>
    <a name='scenarios' />
    <div class="container-2 is--slider">
      <div class="splide">
        <div class="splide__track w-dyn-list">
          <div role="list" class="splide__list w-dyn-items">
						{#if browser}
								<Carousel
                  particlesToShow={3}
                  particlesToScroll={1}
									duration={800}
									autoplay
									timingFunction="linear"
									dots={false}
									arrows={false}
									swiping={true}
									>
                  {#each slides as slide}
                    <div role="listitem" class="splide__slide w-dyn-item">
                      <img src="{slide.img}" loading="lazy" sizes="(max-width: 479px) 100vw, (max-width: 767px) 88vw, 28vw" alt='{slide.altText}' class="splide__img">
                    </div>
                  {/each}
                </Carousel>
							{/if}
						</div>
					</div>
				</div>
			</div>
			<div class="slider__wave is--bottom w-embed">
				<svg version="1.1" id="Layer_1"
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 804 50.167" enable-background="new 0 0 804 50.167" xml:space="preserve">
					<path fill="#FFECD9" d="M804,0v16.671c0,0-204.974,33.496-401.995,33.496C204.974,50.167,0,16.671,0,16.671V0H804z"></path>
				</svg>
			</div>
			<!-- <div class="controls">
				<div slot="prev" on:click={showPrevPage} class="control prev-splide w-inline-block">
					<div class="control__fill"></div>
					<div class="control__arrow w-embed">
						<svg version="1.1" id="Layer_1"
							xmlns="http://www.w3.org/2000/svg"
							xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
							<path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
						</svg>
					</div>
				</div>
				<div slot="next" on:click={showPrevPage} class="control next-splide w-inline-block">
					<div class="control__fill"></div>
					<div class="control__arrow is--flipped w-embed">
						<svg version="1.1" id="Layer_1"
							xmlns="http://www.w3.org/2000/svg"
							xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
							<path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
						</svg>
					</div>
				</div>
			</div> -->
		</section>
	</section>
	<style>

.controls{
    z-index:4;
    width:13em;
    justify-content:center;
    align-items:center;
    margin-left:auto;
    margin-right:auto;
    display:flex;
    position:absolute;
    top:auto;
    bottom:0%;
    left:0%;
    right:0%
}
</style>
