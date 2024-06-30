<script>
	// import {  } from '$lib/shared';
	import { Nav, Header, About, TheStories, Scenarios, OtherBoardgames, Slider, Faq, Footer } from '$lib/widgets';
  // import {  } from '$lib/entities'
</script>


<svelte:head>
  <title>Heritage Stories</title>
</svelte:head>

<div class="page-wrapper">
  <Nav />

  <main class="main-wrapper">
    <Header />

    <About />
    
    <TheStories />

    <Scenarios />

    <OtherBoardgames />

    <Slider />

    <Faq />
    <!-- <section id="contact" class="section-contact">
      <div class="page-padding">
        <div class="container-large">
          <div class="padding-vertical padding-huge">
            <div class="contact_component">
              <div class="contact_form">
                <h2>Contact <span class="text-style-link">opnemen</span>
                </h2>
                <div class="w-form">
                  <form id="wf-form-Contact" name="wf-form-Contact" data-name="Contact" method="post" data-wf-page-id="618694973f27c55b82200de9" data-wf-element-id="739f7f5f-ce83-41dc-b0a4-df7775a93020">
                    <div class="contact-form-grid">
                      <div>
                        <input class="form-input w-input" maxlength="256" name="Name" data-name="Name" placeholder="Uw naam" type="text" id="Name" required="">
                      </div>
                      <div>
                        <input class="form-input w-input" maxlength="256" name="Email" data-name="Email" placeholder="Uw e-mailadres" type="email" id="Email" required="">
                      </div>
                      <div>
                        <textarea data-name="Message" maxlength="5000" id="Message" name="Message" placeholder="Typ hier uw bericht" required="" class="form-message w-input"></textarea>
                      </div>
                      <input type="submit" data-wait="Een moment..." class="button is-submit w-button" value="Verzenden">
                    </div>
                  </form>
                  <div class="success-message margin-top margin-medium w-form-done">
                    <div class="text-style-handwritten is-contact">Bedankt voor uw inzending! <br>Ik reageer zo spoedig mogelijk. </div>
                  </div>
                  <div class="margin-top margin-medium w-form-fail">
                    <div>Oeps! Er is iets misgegaan bij het verzenden van het formulier.</div>
                  </div>
                </div>
              </div>
              <div class="div-block-3"></div>
            </div>
          </div>
        </div>
      </div>
    </section> -->

    <!-- <section id="contact" class="section-map">
      <div class="page-padding">
        <div class="container-large">
          <div class="padding-vertical padding-huge">
            <div class="map_component">
              <div class="map_widget w-embed">
                <div class="elfsight-app-2e924cc2-4147-4340-9b25-3f0c477a2000"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section> -->
  </main>  
</div>


<Footer />


<style>
</style>
