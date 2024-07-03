<script>
    import {FaqCard} from '$entities';
    import {faq} from '$shared';
</script>

<section class="section-faq">
  <div class="page-padding">
    <div class="container-large">
      <div class="padding-vertical padding-huge">
        <div class="w-layout-grid faq_component">
          <div class="faq_wrapper overflow-hidden">
            <div class="margin-bottom margin-medium">
              <h2 class="faq_title">Frequently Asked <span class="text-style-link text-[#ca8b0c]">Questions.</span>
              </h2>

              <a name='faq' />

            </div>
            {#each faq as faq}
              <FaqCard {faq}/>
            {/each}
        </div>

          <div  class="faq_visual">
            <img src="images/faqImg.svg" loading="lazy" sizes="(max-width: 991px) 100vw, 93vw" alt="F.A.Q. image" class="faq_image">
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<style>


</style>