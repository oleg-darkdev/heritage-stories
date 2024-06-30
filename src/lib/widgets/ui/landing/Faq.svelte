<script>
    import {FaqCard} from '$entities';

const faqData = [
  {
    q: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
    a: [
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`,
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.` 
    ]
  },
  {
    q: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
    a: [
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`,
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.` 
    ]
  },
  {
    q: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
    a: [
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`,
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.` 
    ]
  },
  {
    q: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
    a: [
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`,
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.` 
    ]
  },
  {
    q: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
    a: [
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`,
      `Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.` 
    ]
  },
]
</script>

<section class="section-faq">
          <div class="page-padding">
            <div class="container-large">
              <div class="padding-vertical padding-huge">
                <div class="w-layout-grid faq_component">
                  <div class="faq_wrapper overflow-hidden">
                    <div class="margin-bottom margin-medium">
                      <h2 class="faq_title">frequently asked <span class="text-style-link">questions.</span>
                      </h2>

                      <a name='faq' /> 

                    </div>
                    {#each faqData as faq}
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
