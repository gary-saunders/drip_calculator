<template>
    <f7-page class="homepage">
        <f7-navbar>
            <f7-nav-left>
                <f7-link class="panel-open" open-panel="left" icon="fa fa-bars"></f7-link>
            </f7-nav-left>
            <div class="title">Drip Calculator</div>
            <f7-nav-right>
                <f7-link class="searchbar-enable" data-searchbar=".searchbar-components" icon="fa fa-search"></f7-link>
            </f7-nav-right>
            <f7-searchbar class="searchbar-components" search-container=".components-list" search-in="a" expandable></f7-searchbar>
        </f7-navbar>
        <f7-block-title class="centered">
            <svg x="0px" y="0px" width="239px" height="67px" viewBox="-124 351 239 67">
            <g>
                <path fill="#FFFFFF" d="M104.3,374c2.5,0,4.6-1.9,4.6-4.5s-2.1-4.5-4.6-4.5s-4.6,1.9-4.6,4.5C99.7,372,101.8,374,104.3,374
                     M100.7,369.4c0-2.1,1.6-3.8,3.7-3.8c2.1,0,3.7,1.6,3.7,3.8c0,2.2-1.6,3.8-3.7,3.8C102.2,373.2,100.7,371.6,100.7,369.4
                     M103.3,369.8h0.9l1.4,2.3h0.9l-1.5-2.3c0.8-0.1,1.4-0.5,1.4-1.4c0-1-0.6-1.5-1.8-1.5h-2v5.1h0.8L103.3,369.8L103.3,369.8z
                     M103.3,369.1v-1.6h1.1c0.6,0,1.1,0.1,1.1,0.8c0,0.8-0.6,0.9-1.3,0.9h-0.9V369.1z"/>
                <path fill="#FFFFFF" d="M-50.5,409.3v-36.4h15.8v25.9c-0.5,11-11.7,10.5-11.7,10.5H-50.5z"/>
                <path fill="#FFFFFF" d="M-53.8,409.3v-36.4h-15.8v25.9c0.5,11,11.7,10.5,11.7,10.5H-53.8z"/>
                <rect x="-31.3" y="372.9" fill="#FFFFFF" width="15.8" height="36.4"/>
                <path fill="#FFFFFF" d="M81.7,380.6c0-4.1,3.4-7.5,7.5-7.5c4.2,0,7.5,3.4,7.5,7.5s-3.4,7.5-7.5,7.5S81.7,384.7,81.7,380.6"/>
                <rect x="64.7" y="372.9" fill="#FFFFFF" width="15.7" height="36.4"/>
                <polygon fill="#FFFFFF" points="7.5,409.3 7.5,377.2 2,377.2 22.8,358.4 22.8,373.3 29.1,373.3 29.1,377.2 22.8,377.2 22.8,409.3   
                    "/>
                <path fill="#FFFFFF" d="M-12.3,372.9v36.4H3.8v-25.8C3.3,372.6-8,372.9-8,372.9H-12.3z"/>
                <path fill="#FFFFFF" d="M43.3,409.5c-9.7,0-17.8-8.3-17.8-18.5c0-10.2,7.5-18.1,17.4-18.6v32.8c3.9,0.4,12.9-0.9,19.3-7.6v4.5
                    C59.5,405.3,53.2,409.9,43.3,409.5"/>
                <path fill="#FFFFFF" d="M45.5,372.4v18.8h16.8C62.7,382,58.2,372.7,45.5,372.4"/>
                <polygon fill="#FFFFFF" points="-97.2,379.2 -92.9,379.2 -92.9,358.4 -73.2,358.4 -73.2,409.3 -92.9,409.3 -92.9,384.2 
                    -97.2,384.2 -97.2,409.3 -117,409.3 -117,358.4 -97.2,358.4   "/>
            </g>
            </svg>
        </f7-block-title>

        <f7-block inner class="centered subtitle">
            <p class="white">Dripline <br />Calculator</p>
        </f7-block>

        <!-- <f7-block-title class="searchbar-found">Links</f7-block-title> -->

        <div class="block">

          <p class="row">
            <a class="col button button-big button-fill" href="/zone-totalizer/">Zone Totalizer</a>            
            Calculate how much material is needed for your project.
          </p>
          <p class="row">
              <a class="col button button-big button-fill" href="/form/">Product Recommender</a>
              Determine which product you need based on soil type, slope or plant variety.
          </p>
          <p class="row">
              <a class="col button button-big button-fill" href="/about/">Run Time Calculator</a>
              Determine run time based on watering requirements.
          </p>
          
        </div>


<!-- 
        <f7-list class="components-list searchbar-found">
            <f7-list-item link="/about/" title="About" panel-close>
                <f7-icon slot="media" icon="fa fa-info fa-fw"></f7-icon>
            </f7-list-item>

            <f7-list-item link="/form/" title="Form" panel-close>
                <f7-icon slot="media" icon="fa fa-info fa-fw"></f7-icon>
            </f7-list-item>
            
            <f7-list-item link="/vuex/" title="Vuex" panel-close>
                <f7-icon slot="media" icon="fa fa-battery fa-fw"></f7-icon>
            </f7-list-item>
        </f7-list>

 -->

        <f7-list class="searchbar-not-found">
            <f7-list-item title="Nothing found"></f7-list-item>
        </f7-list>
        
        
    </f7-page>
</template>
<script>
export default {};

</script>
