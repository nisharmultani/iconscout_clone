<template>
  <div>
    <master-header />
    <masterCard />
    <company />
    <div class="d-md-block d-none pattern_7Tx8u"></div>
    <magic-Feature />
    <card />
    <div class="container container_vreq7 mt-5">
      <div class="row">
        <div class="col-md-6 p-5">
          <p>WORLD OF INTEGRATIONS</p>
          <h2>Work faster and Save time with Apps and Plugins</h2>
          <p>
            IconScout has integrations with Figma, Adobe XD, Sketch,
            Illustrator, GSuite, and MS Office. Our plugins let you find assets
            without you leaving the tools you’re using.
          </p>
        </div>
        <div class="col-md-6">
          <div class="p-5">
            <img src="@/assets/images/card/bigcard.png" alt="" />
            <!--<img src="@/assets/images/card/withbigcard.png" alt="">-->
          </div>
        </div>
        <div>
          <h3>Download plugins for:</h3>
          <div class="col-md-12">
            <div class="col-md-1">
              <div class="p-3 plugins">
                <img
                  src="@/assets/images/icon/apple.svg"
                  alt=""
                  height="30px"
                  width="30px"
                />
                <span class="mt-1">Aplle</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <editing />
  </div>
</template>

<script>
import masterHeader from "@/components/masterHeader.vue";
import masterCard from "@/components/masterCard.vue";
import company from "@/components/company.vue";
import magicFeature from "@/components/magicFeature.vue";
import card from "@/components/card.vue";
import editing from "@/components/editing.vue";


export default {
  components: {
    masterHeader,
    masterCard,
    company,
    magicFeature,
    card,
    editing
    
  },
};
</script>
<style>
.pattern_7Tx8u {
  width: 100%;
  height: 582px;
  background-size: cover;
  background-position: center;
  background-image: url(https://cdna.iconscout.com/img/pattern-mockup.3b2e21f.png);
  margin-top: 80px;
}
.container_vreq7 {
  background: linear-gradient(180deg, #eceef5 0%, rgba(245, 246, 250, 0) 100%);
  border-radius: 20px;
}
.plugins {
  border-radius: 20px;
  height: "150px";
  width: "116px";
  background-color: white;
}
</style>
