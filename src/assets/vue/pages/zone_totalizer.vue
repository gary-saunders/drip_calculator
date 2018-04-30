<template>
  <f7-page>
    <f7-navbar title="Zone Totalizer" back-link="Home"></f7-navbar>

    

    <f7-block-title>Zone Totalizer</f7-block-title>
    <f7-block inner class="centered subtitle">
            <p class="white">Enter values in all fields below in order to get results</p>
        </f7-block>
    <f7-block strong>
    <p>Product</p>

    
      <f7-segmented>
        <f7-button tab-link="#tab1" tab-link-active>HDL</f7-button>
        <f7-button tab-link="#tab2">Eco-Wrap</f7-button>
        <f7-button tab-link="#tab3">Eco-Mat</f7-button>
      </f7-segmented>
    



  <div class="tabs">
<div class="row list">
    <div class="col"><div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
              <div class="item-input-wrap">
                <input type="text" placeholder="0">
                <span class="input-clear-button"></span>
              </div></div>
    <div class="col"><div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
              <div class="item-input-wrap">
                <input type="text" placeholder="0">
                <span class="input-clear-button"></span>
              </div></div>
  </div>

    <!-- each tabs is a "page-content" -->
    <div class="tab tab-active" id="tab1">
      <div class="list no-hairlines-md">
        <ul>
          <li class="item-content item-input">
            <div class="item-inner">
              <div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
              <div class="item-input-wrap">
                <input type="text" placeholder="0">
                <span class="input-clear-button"></span>
              </div>
            </div>
          </li>
          <li class="item-content item-input">
            <div class="item-inner">
              <div class="item-title item-label">Emitter Spacing (in)</div>
              <div class="item-input-wrap">
                <input type="text" placeholder="0">
                <span class="input-clear-button"></span>
              </div>
            </div>
          </li>
          <li class="item-content item-input">
            <div class="item-inner">
              <div class="item-title item-label">Row Spacing (in)</div>
              <div class="item-input-wrap">
                <input type="email" placeholder="0">
                <span class="input-clear-button"></span>
              </div>
            </div>
          </li>
          
        </ul>
      </div>

      <p>Emitter Flow (GPH)</p>

    <!--   <div class="list">
        <ul>
          <li>
            <label class="item-radio item-content">
              <input type="radio" name="demo-radio" value="Books" checked />
              <i class="icon icon-radio"></i>
              <div class="item-inner">
                <div class="item-title">Books</div>
              </div>
            </label>
          </li>
          <li>
            <label class="item-radio item-content">
              <input type="radio" name="demo-radio" value="Movies"/>
              <i class="icon icon-radio"></i>
              <div class="item-inner">
                <div class="item-title">Movies</div>
              </div>
            </label>
          </li>
          <li>
            <label class="item-radio item-content">
              <input type="radio" name="demo-radio" value="Food"/>
              <i class="icon icon-radio"></i>
              <div class="item-inner">
                <div class="item-title">Food</div>
              </div>
            </label>
          </li>
          
        </ul>
      </div> -->


   <!--    <p class="segmented">
        <button class="button button-outline" v-bind:class="{ 'button-active': isActive }" v-on:click="isActive = !isActive">0.4</button>
        <button class="button button-outline" v-bind:class="{ 'button-active': isActive }" v-on:click="isActive = !isActive">0.6</button>
        <button class="button button-outline button-active" v-bind:class="{ 'button-active': isActive }" v-on:click="isActive = !isActive">0.9</button>
      </p>
 -->
      <p class="segmented">
        <button data-value="0.4" class="button button-outline" type="button" @click="isActive = 'btn1'" :class="{'button-active': isActive === 'btn1' }">0.4</button>
        <button data-value="0.6" class="button button-outline" type="button" @click="isActive = 'btn2'" :class="{'button-active': isActive === 'btn2' }">0.6</button>
        <button data-value="0.9" class="button button-outline" type="button" @click="isActive = 'btn3'" :class="{'button-active': isActive === 'btn3' }">0.9</button>
      </p>

     <!--  <div class="segmented-button segmented">
        <input type="radio" name="seg-1" value="Organisation" id="seg-Organisation" checked>
        <label for="seg-Organisation" class="button button-outline">0.4</label>
        <input type="radio" name="seg-1" value="Users" id="seg-Users">
        <label for="seg-Users" class="button button-outline">0.6</label>
        <input type="radio" name="seg-1" value="Tags" id="seg-Tags">
        <label for="seg-Tags" class="last button button-outline">0.9</label>
      </div>
 -->


      <button class="col button button-big button-fill">Calculate</button>
    </div>


    <div class="tab" id="tab2">
      <div class="list no-hairlines-md">
        <ul>
          <li class="item-content item-input">
            <div class="item-inner">
              <div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
              <div class="item-input-wrap">
                <input type="text" placeholder="0">
                <span class="input-clear-button"></span>
              </div>
            </div>
          </li>
          <li class="item-content item-input">
            <div class="item-inner">
              <div class="item-title item-label">Row Spacing (in)</div>
              <div class="item-input-wrap">
                <input type="email" placeholder="0">
                <span class="input-clear-button"></span>
              </div>
            </div>
          </li>
          
        </ul>
      </div>
      <button class="col button button-big button-fill">Calculate</button>
    </div>
    <!-- Third tab, should have "tab" class and unique id attribute -->
    <div class="tab" id="tab3">
      <p>Area Type</p>
      <p class="segmented">
        <button class="button button-outline">0.4</button>
        <button class="button button-outline">0.6</button>
        <button class="button button-outline button-active">0.9</button>
      </p>
      <div class="list no-hairlines-md">
        <ul>
          <li class="item-content item-input">
            <div class="item-inner">
              <div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
              <div class="item-input-wrap">
                <input type="text" placeholder="0">
                <span class="input-clear-button"></span>
              </div>
            </div>
          </li>
        </ul>
      </div>
      <button class="col button button-big button-fill">Calculate</button>
    </div>
  </div>





    </f7-block>
  </f7-page>
</template>
<script>
import { f7Navbar, f7Page, f7BlockTitle } from 'framework7-vue';
 export default {

    components: {
      f7Navbar,
      f7Page,
      f7BlockTitle,
    },
      data() {
        return{
          isActive: false,
          monthly_et : '',
          grass_type: '',
          hydrozone_area: '',
          zone_pressure: '',
          emitter_gph: '',
          emitter_spacing: '',
          row_spacing: '',
          daily_water_requirement: '',
          application_rate: '',
          feet_of_pld: '',
          text_of_emitters: '',
          gph_per_zone: '',
          gpm_per_zone: '',
          daily_run_time_in_minutes: '',
        }
      },
      computed: {
        daily_et: function(){
          return (this.monthly_et / 31).toFixed(2);
        },
        weekly_et: function(){
          return (this.daily_et * 7).toFixed(2);
        }

      },
      methods: {
        myFilter: function(){
          this.isActive = !this.isActive;
        },
        calculate: function(){
          this.daily_water_requirement = (this.daily_et * this.grass_type).toFixed(2);
          this.application_rate = ((this.emitter_gph * 231) / (this.emitter_spacing * this.row_spacing)).toFixed(2);
          this.feet_of_pld = (this.hydrozone_area / 1.25).toFixed(2);
          this.text_of_emitters = ((this.feet_of_pld * 12) / this.emitter_spacing).toFixed(2);
          this.gph_per_zone = (this.emitter_gph * this.text_of_emitters).toFixed(2);
          this.gpm_per_zone = (this.gph_per_zone / 60).toFixed(2);
          this.daily_run_time_in_minutes = ((this.daily_water_requirement / this.application_rate) * (60 / 0.95)).toFixed(2);
        }
      }
    
    
  };
</script>
