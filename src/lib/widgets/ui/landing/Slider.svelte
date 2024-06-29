<script>
  const slides = [
   {
     img: 'https://wallpaperset.com/w/full/c/9/0/522708.jpg',
    altText: 'lorem impsum'
   },
   {
     img: 'https://wallpaperset.com/w/full/c/9/0/522708.jpg',
    altText: 'lorem impsum'
   },
   {
     img: 'https://wallpaperset.com/w/full/c/9/0/522708.jpg',
    altText: 'lorem impsum'
   },
   {
     img: 'https://wallpaperset.com/w/full/c/9/0/522708.jpg',
    altText: 'lorem impsum'
   },
   {
     img: 'https://wallpaperset.com/w/full/c/9/0/522708.jpg',
    altText: 'lorem impsum'
   },
  ]
</script>

<section id="slider" class="section-slider">
          <section class="section-2 is--slider">
            <div class="slider__wave w-embed">
              <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 804 50.167" enable-background="new 0 0 804 50.167" xml:space="preserve">
                <path fill="#FFECD9" d="M804,0v16.671c0,0-204.974,33.496-401.995,33.496C204.974,50.167,0,16.671,0,16.671V0H804z"></path>
              </svg>
            </div>
            <div class="container-2 is--slider">
              <div class="splide">
                <div class="splide__track w-dyn-list">
                  <div role="list" class="splide__list w-dyn-items">
                    {#each slides as slide}
                    <div role="listitem" class="splide__slide w-dyn-item">
                      <img src="{slide.img}" loading="lazy" sizes="(max-width: 479px) 100vw, (max-width: 767px) 88vw, 28vw" alt='{slide.altText}' class="splide__img">
                    </div>
                    {/each}
                  </div>
                </div>
              </div>
            </div>
            <div class="slider__wave is--bottom w-embed">
              <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 804 50.167" enable-background="new 0 0 804 50.167" xml:space="preserve">
                <path fill="#FFECD9" d="M804,0v16.671c0,0-204.974,33.496-401.995,33.496C204.974,50.167,0,16.671,0,16.671V0H804z"></path>
              </svg>
            </div>
            <div class="controls">
              <a data-w-id="3f46071e-d553-bc13-3526-d5674b8fc3ef" href="#" class="control prev-splide w-inline-block">
                <div class="control__fill"></div>
                <div class="control__arrow w-embed">
                  <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
                    <path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
                  </svg>
                </div>
              </a>
              <a href="#" class="control next-splide w-inline-block">
                <div class="control__fill"></div>
                <div class="control__arrow is--flipped w-embed">
                  <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 24 18">
                    <path fill="currentColor" d="M23.999,8H5.481c5.009-2.91,6.349-7.311,6.416-7.548L9.976-0.102C9.9,0.156,8.03,6.213-0.073,8.024L0.146,9
	l-0.218,0.976C8.03,11.787,9.9,17.844,9.976,18.101l1.922-0.554C11.83,17.31,10.49,12.91,5.481,10h18.518V8z"></path>
                  </svg>
                </div>
              </a>
            </div>
          </section>
        </section>