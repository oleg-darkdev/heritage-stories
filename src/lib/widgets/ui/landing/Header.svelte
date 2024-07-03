<script>
	import {BenefitsCard} from '$entities';
</script>

<header class="section-header">
  <div class="page-padding">
    <div class="container-large">
      <div class="padding-vertical padding-huge">
        <div class="header_component"> 
          <div class="margin-bottom margin-large">
            <h1 class="max-width-large "> THE <span class="text-style-link text-[#713f13]"> Heritage </span> Stories. </h1>
          </div>
          <div class="margin-bottom margin-large">
            <p class="text-size-medium max-width-medium"> 
              Research and educational project realized in the form of educational boardgame, enhanced by an interactive web application, about eco-friendly bicycle trip through the World Heritage Cities.
            </p>
            <p />
          </div>
          <!-- <div class="margin-bottom margin-medium">
            <a href="/" class="w-inline-block">
              <p class="text-style-handwritten max-width-medium">is simply dummy</p>
            </a>
          </div> -->
          <div class="header_testomonial p-2">
            <!-- <img src="" loading="lazy" alt="" class="image-9"> -->
            <!-- <div class="text-size-medium max-width-medium"> -->
            <BenefitsCard />
          </div>
        </div>
      </div>
    </div>
  </div>
  </header>



<style>

.header_testomonial{
    max-width:530px;
    color:#fff;
    background-color:#713f13;
    border-radius:50px;
    justify-content:center;
    align-items:center;
    /* padding:25px; */
    display:flex;
    position:absolute;
    bottom:15%;
    right:8%;
    box-shadow:1px 1px 10px rgba(0,0,0,.27)
}

@media screen and (max-width:991px){
    .header_testomonial{
        display:none
    }
  }


@media screen and (max-width:767px){
   .benefits-list.is-products{
        height:auto
    }
  }
</style>