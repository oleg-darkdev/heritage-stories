<script>
  import {ScenarionCard} from '$entities';

  const scenarios = [
    {
      id: 0,
      title: `lorem Ipsum is simply dummy text`,
      desc: [`lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.`, ` and scrambled it to make a type specimen book.`],
      country: `lorem Ipsum `,
      content: [
        ``, ``, ``
      ]
    },
    {
      id: 0,
      title: `lorem Ipsum is simply dummy text`,
      desc: [`lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.`, ` and scrambled it to make a type specimen book.`],
      country: `lorem Ipsum `,
      content: [
        ``, ``, ``
      ]
    },
    {
      id: 0,
      title: `lorem Ipsum is simply dummy text`,
      desc: [`lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.`, ` and scrambled it to make a type specimen book.`],
      country: `lorem Ipsum `,
      content: [
        ``, ``, ``
      ]
    },
    {
      id: 0,
      title: `lorem Ipsum is simply dummy text`,
      desc: [`lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.`, ` and scrambled it to make a type specimen book.`],
      country: `lorem Ipsum `,
      content: [
        ``, ``, ``
      ]
    },
    {
      id: 0,
      title: `lorem Ipsum is simply dummy text`,
      desc: [`lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.`, ` and scrambled it to make a type specimen book.`],
      country: `lorem Ipsum `,
      content: [
        ``, ``, ``
      ]
    },
    {
      id: 0,
      title: `lorem Ipsum is simply dummy text`,
      desc: [`lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type.`, ` and scrambled it to make a type specimen book.`],
      country: `lorem Ipsum `,
      content: [
        ``, ``, ``
      ]
    },
  ]
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
