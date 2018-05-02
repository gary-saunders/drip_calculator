<template>
  <f7-page>
    
    <f7-navbar class="no-hairline">
      <div class="left" style="">
        <a class="link back">
          <i class="icon icon-back color-white" style=""></i>
          <span class="ios-only">Home</span>
        </a>
      </div>
        <div class="sub-logo sliding">
        <svg  viewBox="0 0 118 26" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <title>Hunter Logo</title>
          <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g transform="translate(-129.000000, -35.000000)" fill="#FFFFFF">
                  <g transform="translate(129.000000, 35.000000)">
                      <path d="M114.528228,5.13833992 L114.528228,4.29051383 L115.135626,4.29051383 C115.439325,4.29051383 115.743024,4.36758893 115.743024,4.75296443 C115.743024,5.21541502 115.439325,5.21541502 115.059701,5.21541502 L114.528228,5.13833992 Z M114.528228,5.52371542 L115.059701,5.52371542 L115.818949,6.83399209 L116.350422,6.83399209 L115.51525,5.52371542 C115.970798,5.44664032 116.274497,5.21541502 116.274497,4.67588933 C116.274497,4.05928854 115.970798,3.82806324 115.287476,3.82806324 L114.148605,3.82806324 L114.148605,6.83399209 L114.604153,6.83399209 L114.528228,5.52371542 Z M113.009734,5.36956522 C113.009734,4.13636364 113.920831,3.21146245 115.059701,3.21146245 C116.198572,3.21146245 117.109669,4.13636364 117.109669,5.36956522 C117.109669,6.6027668 116.198572,7.52766798 115.059701,7.52766798 C113.920831,7.45059289 113.009734,6.6027668 113.009734,5.36956522 L113.009734,5.36956522 Z M115.059701,7.91304348 C116.426347,7.91304348 117.565217,6.83399209 117.565217,5.36956522 C117.565217,3.90513834 116.426347,2.82608696 115.059701,2.82608696 C113.693056,2.82608696 112.478261,3.90513834 112.478261,5.36956522 C112.478261,6.83399209 113.693056,7.91304348 115.059701,7.91304348 L115.059701,7.91304348 Z"></path>
                      <path d="M33.9130435,25.9269777 L33.9130435,6.7826087 L41.826087,6.7826087 L41.826087,20.457158 C41.6196597,26.214863 35.9773157,25.998949 35.9773157,25.998949 L33.9130435,25.998949 L33.9130435,25.9269777 Z" id="Fill-3"></path>
                      <path d="M32.7826087,25.9269777 L32.7826087,6.7826087 L24.8695652,6.7826087 L24.8695652,20.457158 C25.1424288,26.214863 30.7361319,25.998949 30.7361319,25.998949 L32.7826087,25.998949 L32.7826087,25.9269777" id="Fill-5"></path>
                      <polygon points="44.6521739 6.7826087 52.5652174 6.7826087 52.5652174 26 44.6521739 26"></polygon>
                      <path d="M103.434783,10.7391304 C103.434783,8.58102767 105.233202,6.7826087 107.391304,6.7826087 C109.549407,6.7826087 111.347826,8.58102767 111.347826,10.7391304 C111.347826,12.8972332 109.549407,14.6956522 107.391304,14.6956522 C105.233202,14.6956522 103.434783,12.96917 103.434783,10.7391304" id="Fill-9"></path>
                      <polygon points="94.3913043 6.7826087 102.304348 6.7826087 102.304348 26 94.3913043 26"></polygon>
                      <polygon points="64.5199913 26 64.5199913 9.64516129 61.6086957 9.64516129 72.4727988 0 72.4727988 7.61827957 75.7391304 7.61827957 75.7391304 9.64516129 72.4727988 9.64516129 72.4727988 26"></polygon>
                      <path d="M54.826087,6.78293634 L54.826087,26 L62.7391304,26 L62.7391304,12.4180152 C62.4708917,6.63844714 56.9719971,6.78293634 56.9719971,6.78293634 L54.826087,6.78293634 Z"></path>
                      <path d="M83.656392,25.9864488 C78.7149578,25.9864488 74.6086957,21.5365871 74.6086957,16.1383943 C74.6086957,10.7402015 78.4365672,6.50918551 83.447599,6.2173913 L83.447599,23.7250437 C85.4659312,23.9438893 89.9897794,23.2144038 93.2608696,19.6399248 L93.2608696,22.047227 C91.8689163,23.7250437 88.5978261,26.2052944 83.656392,25.9864488" id="Fill-13"></path>
                      <path d="M84.7826087,6.2173913 L84.7826087,16.3913043 L93.8196537,16.3913043 C93.9665976,11.415741 91.6154964,6.36591558 84.7826087,6.2173913"></path>
                      <polygon points="10.1422186 10.6236559 12.396045 10.6236559 12.396045 0 22.6086957 0 22.6086957 26 12.396045 26 12.396045 13.2096774 10.1422186 13.2096774 10.1422186 26 0 26 0 0 10.1422186 0"></polygon>
                  </g>
              </g>
          </g>
      </svg>  
      </div>

        <f7-nav-right>
            <f7-link class="" v-on:click="resetFields">Reset</f7-link>
        </f7-nav-right>

    </f7-navbar>






    <f7-block-title class="blue_bg page-title">Zone Totalizer</f7-block-title>

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
        



        <!-- TAB 1 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * --> 
        <div class="tab tab-active" id="tab1">


          <div class="list no-hairlines-md">
            <ul>
              <li class="item-content item-input">
                <div class="item-inner">
                  <div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
                  <div class="item-input-wrap">
                    <input name="hydrozone_area_hdl" type="number" placeholder="0" v-model="hydrozone_area_hdl">
                    <span class="input-clear-button"></span>
                  </div>
                </div>
              </li>
              <li class="item-content item-input">
                <div class="item-inner">
                  <div class="item-title item-label">Emitter Spacing (in)</div>
                  <div class="item-input-wrap">
                    <input name="emitter_spacing" type="number" placeholder="0" v-model="emitter_spacing">
                    <span class="input-clear-button"></span>
                  </div>
                </div>
              </li>
              <li class="item-content item-input">
                <div class="item-inner">
                  <div class="item-title item-label">Row Spacing (in)</div>
                  <div class="item-input-wrap">
                    <input name="row_spacing_hdl" type="number" placeholder="0" v-model="row_spacing_hdl">
                    <span class="input-clear-button"></span>
                  </div>
                </div>
              </li>
              
            </ul>
          </div>

          <p>Emitter Flow (GPH)</p>

          <p class="segmented">
            <button v-on:click="emitter_flow = 0.4" data-value="0.4" class="button button-outline" type="button" @click="isActive = 'btn_flow_1'" :class="{'button-active': isActive === 'btn_flow_1' }">0.4</button>
            <button v-on:click="emitter_flow = 0.6" data-value="0.6" class="button button-outline" type="button" @click="isActive = 'btn_flow_2'" :class="{'button-active': isActive === 'btn_flow_2' }">0.6</button>
            <button v-on:click="emitter_flow = 0.9" data-value="0.9" class="button button-outline" type="button" @click="isActive = 'btn_flow_3'" :class="{'button-active': isActive === 'btn_flow_3' }">0.9</button>
          </p>

          <p v-if="errors_hdl.length">
            <b>Please correct the following error(s):</b>
            <ul>
              <li v-for="error in errors_hdl">{{ error }}</li>
            </ul>
          </p>

          <button class="col button button-big button-fill" v-on:click="calculate_hdl">Calculate</button>


          <div class="popup totals_hdl block-strong block">
            
            <a class="link popup-close" href="#"><i class="fa fa-times-circle"></i></a>


            <div class="block">

              <div class="block-title">Zone Information</div>

              <div class="row">
                <div class="col-50">Product : HDL</div>
              </div>

              <div class="row">
                <div class="col-50">Hydrozone Area : {{ hydrozone_area_hdl }}</div>
              </div>

              <div class="row">
                <div class="col">Emitter Spacing (in) : {{ emitter_spacing }}</div>
                
              </div>

              <div class="row">
                <div class="col">Row Spacing (in) : {{ row_spacing_hdl }}</div>
              </div>

              <div class="row">
                <div class="col">Emitter Flow (GPH) : {{ emitter_flow }}</div>
              </div>

            </div>

            







           <!--  <div class="block-title">Zone Totals</div> -->

            <div class="gray_bg">
        
              

              <div class="data-table card">
          
                <div class="card-header">
                  <!-- Table title -->
                  <div class="data-table-title">Zone Totals</div>
                </div>
                <table>
                  
                  <tbody>
                    
                    <tr>
                      <td class="label-cell">Total dripline (linear feet)</td>
                      <td class="numeric-cell">{{ feet_of_hdl }}</td>
                    </tr>

                    <tr>
                      <td class="label-cell">Total # of Emitters</td>
                      <td class="numeric-cell">{{ number_of_emitters }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Total flow (GPH)</td>
                      <td class="numeric-cell">{{ total_flow_gph }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Total flow (GPM)</td>
                      <td class="numeric-cell">{{ total_flow_gpm }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Application Rate (inches/hour)</td>
                      <td class="numeric-cell">{{ application_rate }}</td>
                    </tr>
                    
                  </tbody>
                </table>
                
                
              
              </div>

              <a class="col button button-big button-fill" v-on:click="share"><i class="fa fa-envelope"></i>Share</a>

            </div>

          </div>



          
          <!-- <div class="block block-strong gray_bg totals" :class="{ show: showTotals }">
        
            <div class="block-title">Zone Totals</div>



            <div class="data-table card">
              <table>
                
                <tbody>
                  <tr>
                    <td class="label-cell">Total dripline (linear feet)</td>
                    <td class="numeric-cell">{{ feet_of_hdl }}</td>
                  </tr>

                  <tr>
                    <td class="label-cell">Total # of Emitters</td>
                    <td class="numeric-cell">{{ number_of_emitters }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Total flow (GPH)</td>
                    <td class="numeric-cell">{{ total_flow_gph }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Total flow (GPM)</td>
                    <td class="numeric-cell">{{ total_flow_gpm }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Application Rate (inches/hour)</td>
                    <td class="numeric-cell">{{ application_rate }}</td>
                  </tr>
                  
                </tbody>
              </table>
              
              <a class="col button button-big button-fill" v-on:click="share">Share</a>
            
            </div>

          </div> -->


        </div><!-- End of Tab 1 -->










        <!-- Tab 2 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * -->
        <div class="tab" id="tab2"> 
          <div class="list no-hairlines-md">
            <ul>
              <li class="item-content item-input">
                <div class="item-inner">
                  <div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
                  <div class="item-input-wrap">
                    <input name="hydrozone_area_eco_wrap" type="number" placeholder="0" v-model="hydrozone_area_eco_wrap">
                    <span class="input-clear-button"></span>
                  </div>
                </div>
              </li>
              <li class="item-content item-input">
                <div class="item-inner">
                  <div class="item-title item-label">Row Spacing (in)</div>
                  <div class="item-input-wrap">
                    <input name="row_spacing_eco_wrap" type="number" placeholder="0" v-model="row_spacing_eco_wrap">
                    <span class="input-clear-button"></span>
                  </div>
                </div>
              </li>
              
            </ul>

            <div class="row list">
              <div class="col">
                <div class="item-title item-label">Emitter Flow (GPH)</div>
                <div class="item-input-wrap">
                  {{emitter_flow_eco}}
                </div>
              </div>
              <div class="col">
                <div class="item-title item-label">Emitter Spacing (in)</div>
                  <div class="item-input-wrap">
                    {{emitter_spacing_eco}}
                  </div>
              </div>
            </div>


          </div>

          <p v-if="errors_eco_wrap.length">
            <b>Please correct the following error(s):</b>
            <ul>
              <li v-for="error in errors_eco_wrap">{{ error }}</li>
            </ul>
          </p>

          <button class="col button button-big button-fill" v-on:click="calculate_eco_wrap">Calculate</button>

          <div class="popup totals_eco_wrap block-strong block">
            
            <a class="link popup-close" href="#"><i class="fa fa-times-circle"></i></a>

            <div class="block-title">Zone Totals</div>

            <div class="gray_bg">
        
              

              <div class="data-table card">
                <div class="card-header">
                  <!-- Table title -->
                  <div class="data-table-title">ECO-WRAP</div>
                </div>
                <table>
                  
                  <tbody>

                    <tr>
                      <td class="label-cell">Total dripline (linear feet)</td>
                      <td class="numeric-cell">{{ feet_of_hdl }}</td>
                    </tr>

                    <tr>
                      <td class="label-cell">Total # of Emitters</td>
                      <td class="numeric-cell">{{ number_of_emitters }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Total flow (GPH)</td>
                      <td class="numeric-cell">{{ total_flow_gph }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Total flow (GPM)</td>
                      <td class="numeric-cell">{{ total_flow_gpm }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Application Rate (inches/hour)</td>
                      <td class="numeric-cell">{{ application_rate }}</td>
                    </tr>
                    
                  </tbody>
                </table>
                
                
              
              </div>

              <a class="col button button-big button-fill" v-on:click="share"><i class="fa fa-envelope"></i>Share</a>

            </div>

          </div>








          <!-- <div class="block block-strong gray_bg totals" :class="{ show: showTotals }">
        
            <div class="block-title">Zone Totals</div>

            <div class="data-table card">
              <table>
                
                <tbody>
                  <tr>
                    <td class="label-cell">Total dripline (linear feet)</td>
                    <td class="numeric-cell">{{ feet_of_hdl }}</td>
                  </tr>

                  <tr>
                    <td class="label-cell">Total # of Emitters</td>
                    <td class="numeric-cell">{{ number_of_emitters }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Total flow (GPH)</td>
                    <td class="numeric-cell">{{ total_flow_gph }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Total flow (GPM)</td>
                    <td class="numeric-cell">{{ total_flow_gpm }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Application Rate (inches/hour)</td>
                    <td class="numeric-cell">{{ application_rate }}</td>
                  </tr>
                  
                </tbody>
              </table>
              
              <a class="col button button-big button-fill" v-on:click="share">Share</a>

            </div>

          </div> -->
        </div>










        <!-- Tab 3 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * -->
        <!-- Third tab, should have "tab" class and unique id attribute -->
        <div class="tab" id="tab3">
          <p>Area Type</p>

          <p class="segmented">
                                
            <button v-on:click="area_type = irregular" data-value="irregular" class="button button-outline" type="button" @click="isActive = 'btn_area_type_1'" :class="{'button-active': isActive === 'btn_area_type_1' }">Irregular</button>
            <button v-on:click="area_type = rectangular" data-value="rectangular" class="button button-outline" type="button" @click="isActive = 'btn_area_type_2'" :class="{'button-active': isActive === 'btn_area_type_2' }">Rectangular</button>
          </p>

          <div class="list no-hairlines-md">
            <ul>
              <li class="item-content item-input">
                <div class="item-inner">
                  <div class="item-title item-label">Hydrozone Area (ft<sup>2</sup>)</div>
                  <div class="item-input-wrap">
                    <input name="hydrozone_area_eco_mat" type="number" placeholder="0" v-model="hydrozone_area_eco_mat">
                    <span class="input-clear-button"></span>
                  </div>
                </div>
              </li>
            </ul>

            <div class="row list">
              <div class="col">
                <div class="item-title item-label">Emitter Spacing (in)</div>
                <div class="item-input-wrap">
                  {{emitter_spacing_eco}}
                </div>
              </div>
              <div class="col">
                <div class="item-title item-label">Row Spacing (in)</div>
                  <div class="item-input-wrap">
                    {{row_spacing_eco_mat}}
                  </div>
              </div>
              <div class="col">
                <div class="item-title item-label">Emitter Flow (GPH)</div>
                  <div class="item-input-wrap">
                    {{emitter_flow_eco}}
                  </div>
              </div>

            </div>

          </div>

          <p v-if="errors_eco_mat.length">
            <b>Please correct the following error(s):</b>
            <ul>
              <li v-for="error in errors_eco_mat">{{ error }}</li>
            </ul>
          </p>

          <button class="col button button-big button-fill" v-on:click="calculate_eco_mat">Calculate</button>


          <div class="popup totals_eco_mat block-strong block">
            
            <a class="link popup-close" href="#"><i class="fa fa-times-circle"></i></a>

            <div class="block-title">Zone Totals</div>

            <div class="gray_bg">
        
              

              <div class="data-table card">
                <div class="card-header">
                  <!-- Table title -->
                  <div class="data-table-title">ECO-MAT</div>
                </div>
                <table>
                  
                  <tbody>
                    <tr>
                      <td class="label-cell">Total dripline (linear feet)</td>
                      <td class="numeric-cell">{{ feet_of_hdl }}</td>
                    </tr>

                    <tr>
                      <td class="label-cell">Total # of Emitters</td>
                      <td class="numeric-cell">{{ number_of_emitters }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Total flow (GPH)</td>
                      <td class="numeric-cell">{{ total_flow_gph }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Total flow (GPM)</td>
                      <td class="numeric-cell">{{ total_flow_gpm }}</td>
                    </tr>


                    <tr>
                      <td class="label-cell">Application Rate (inches/hour)</td>
                      <td class="numeric-cell">{{ application_rate }}</td>
                    </tr>
                    
                  </tbody>
                </table>
                
                
              
              </div>

              <a class="col button button-big button-fill" v-on:click="share"><i class="fa fa-envelope"></i>Share</a>

            </div>

          </div>




          <!-- <div class="block block-strong gray_bg totals" :class="{ show: showTotals }">
        
            <div class="block-title">Zone Totals</div>

            <div class="data-table card">
              <table>
                
                <tbody>
                  <tr>
                    <td class="label-cell">Total dripline (linear feet)</td>
                    <td class="numeric-cell">{{ feet_of_hdl }}</td>
                  </tr>

                  <tr>
                    <td class="label-cell">Total # of Emitters</td>
                    <td class="numeric-cell">{{ number_of_emitters }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Total flow (GPH)</td>
                    <td class="numeric-cell">{{ total_flow_gph }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Total flow (GPM)</td>
                    <td class="numeric-cell">{{ total_flow_gpm }}</td>
                  </tr>


                  <tr>
                    <td class="label-cell">Application Rate (inches/hour)</td>
                    <td class="numeric-cell">{{ application_rate }}</td>
                  </tr>
                  
                </tbody>
              </table>
               
              <a class="col button button-big button-fill" v-on:click="share">Share</a>
              
            </div>

          </div>
 -->




        </div>
        <!-- End of Tab 3 -->









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
          errors_hdl:[],
          errors_eco_mat:[],
          errors_eco_wrap:[], 
          totals:[],
          isActive: false,
          showTotals: false,

          //HDL
          hydrozone_area_hdl: '',
          emitter_spacing: '',
          row_spacing_hdl: '',
          emitter_flow: '',
          feet_of_hdl: '',
          number_of_emitters: '',
          total_flow_gph: '',
          total_flow_gpm: '',
          application_rate: '',

          emitter_spacing_eco: '12',
          emitter_flow_eco: '0.6',

          //ECO-WRAP
          hydrozone_area_eco_wrap: '',
          row_spacing_eco_wrap: '',
          
          
          //ECO-MAT
          area_type: '',
          hydrozone_area_eco_mat: '',
          row_spacing_eco_mat: '14',


          // monthly_et : '',
          // grass_type: '',
          // zone_pressure: '',
          
          // daily_water_requirement: '',
          // daily_run_time_in_minutes: ''
        }
      },
      // computed: {
      //   daily_et: function(){
      //     return (this.monthly_et / 31).toFixed(2);
      //   },
      //   weekly_et: function(){
      //     return (this.daily_et * 7).toFixed(2);
      //   }

      // },
      methods: {
        myFilter: function(){
          this.isActive = !this.isActive;
        },
        // emitter_flow_value(value){
        //   // value is the clicked button value
        //   this.emitter_flow = value;
        // },
        // area_type_value(value){
        //   this.area_type = value;
        // },
        calculate_hdl: function(){
          
          this.errors_hdl = [];
          
          if(this.hydrozone_area_hdl && this.emitter_spacing && this.row_spacing_hdl){

            this.feet_of_hdl = (this.hydrozone_area_hdl / 1.25).toFixed(2);
            this.number_of_emitters = ((this.feet_of_hdl * 12) / this.emitter_spacing).toFixed(2);
            this.total_flow_gph = (this.emitter_flow * this.number_of_emitters).toFixed(2);
            this.total_flow_gpm = (this.total_flow_gph / 60).toFixed(2);
            this.application_rate = ((this.emitter_flow * 231) / (this.emitter_spacing * this.row_spacing_hdl)).toFixed(2);
            //this.showTotals = true;
            this.$f7.popup.open('.totals_hdl');
            

          }else{
            this.errors_hdl.push('You must enter in all fields');
          }

          

        },
        calculate_eco_wrap: function(){
          this.errors_eco_wrap = [];

          if(this.hydrozone_area_eco_wrap && this.row_spacing_eco_wrap){

            this.feet_of_hdl = (this.hydrozone_area_eco_wrap / 1.25).toFixed(2);
            this.number_of_emitters = ((this.feet_of_hdl * 12) / this.emitter_spacing_eco).toFixed(2);
            this.total_flow_gph = (this.emitter_flow_eco * this.number_of_emitters).toFixed(2);
            this.total_flow_gpm = (this.total_flow_gph / 60).toFixed(2);
            this.application_rate = ((this.emitter_flow_eco * 231) / (this.emitter_spacing_eco * this.row_spacing_eco_wrap)).toFixed(2);
            this.$f7.popup.open('.totals_eco_wrap');

          }else{
            this.errors_eco_wrap.push('You must enter in all fields');
          }

          
          
        },
        calculate_eco_mat: function(){
          this.errors_eco_mat = [];
          if(this.hydrozone_area_eco_mat){

            this.feet_of_hdl = (this.hydrozone_area_eco_mat / 1.25).toFixed(2);
            this.number_of_emitters = ((this.feet_of_hdl * 12) / this.emitter_spacing_eco).toFixed(2);
            this.total_flow_gph = (this.emitter_flow_eco * this.number_of_emitters).toFixed(2);
            this.total_flow_gpm = (this.total_flow_gph / 60).toFixed(2);
            this.application_rate = ((this.emitter_flow_eco * 231) / (this.emitter_spacing_eco * this.row_spacing_eco_mat)).toFixed(2);
            this.$f7.popup.open('.totals_eco_mat');

          }else{
            this.errors_eco_mat.push('You must enter in all fields');
          }

          
          
        },
        share: function(){
          this.totals = [];

          this.totals.push('Total dripline (linear feet) : ' + this.feet_of_hdl)
          window.location.href = "mailto:test@testing.com?subject=Totalizer results&body=" + encodeURIComponent(this.$data.totals);
          //window.location.href = 'mailto:' + email + '?subject=' + subject + '&body=' + encodeURIComponent(data);
        },
        resetFields () {
            Object.assign(this.$data, this.$options.data.call(this));
            this.errors = [];
        }
      }
    
    
  };
</script>
