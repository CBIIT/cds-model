<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

Cancer Data Service Data Model
==============================

[View model on GitHub Pages](https://cbiit.github.io/cds-model)



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/cds-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="4345pt" height="3219pt"
 viewBox="0.00 0.00 4344.50 3219.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3215)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3215 4340.5,-3215 4340.5,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2881.5,-909.5C2881.5,-909.5 3159.5,-909.5 3159.5,-909.5 3165.5,-909.5 3171.5,-915.5 3171.5,-921.5 3171.5,-921.5 3171.5,-1081.5 3171.5,-1081.5 3171.5,-1087.5 3165.5,-1093.5 3159.5,-1093.5 3159.5,-1093.5 2881.5,-1093.5 2881.5,-1093.5 2875.5,-1093.5 2869.5,-1087.5 2869.5,-1081.5 2869.5,-1081.5 2869.5,-921.5 2869.5,-921.5 2869.5,-915.5 2875.5,-909.5 2881.5,-909.5"/>
<text text-anchor="middle" x="2917.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2965.5,-909.5 2965.5,-1093.5 "/>
<text text-anchor="middle" x="2976" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2986.5,-909.5 2986.5,-1093.5 "/>
<text text-anchor="middle" x="3068.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2986.5,-1070.5 3150.5,-1070.5 "/>
<text text-anchor="middle" x="3068.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="2986.5,-1047.5 3150.5,-1047.5 "/>
<text text-anchor="middle" x="3068.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2986.5,-1024.5 3150.5,-1024.5 "/>
<text text-anchor="middle" x="3068.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2986.5,-1001.5 3150.5,-1001.5 "/>
<text text-anchor="middle" x="3068.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2986.5,-978.5 3150.5,-978.5 "/>
<text text-anchor="middle" x="3068.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2986.5,-955.5 3150.5,-955.5 "/>
<text text-anchor="middle" x="3068.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="2986.5,-932.5 3150.5,-932.5 "/>
<text text-anchor="middle" x="3068.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="3150.5,-909.5 3150.5,-1093.5 "/>
<text text-anchor="middle" x="3161" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2379.5,-259.5C2379.5,-259.5 2695.5,-259.5 2695.5,-259.5 2701.5,-259.5 2707.5,-265.5 2707.5,-271.5 2707.5,-271.5 2707.5,-845.5 2707.5,-845.5 2707.5,-851.5 2701.5,-857.5 2695.5,-857.5 2695.5,-857.5 2379.5,-857.5 2379.5,-857.5 2373.5,-857.5 2367.5,-851.5 2367.5,-845.5 2367.5,-845.5 2367.5,-271.5 2367.5,-271.5 2367.5,-265.5 2373.5,-259.5 2379.5,-259.5"/>
<text text-anchor="middle" x="2395.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2423.5,-259.5 2423.5,-857.5 "/>
<text text-anchor="middle" x="2434" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2444.5,-259.5 2444.5,-857.5 "/>
<text text-anchor="middle" x="2565.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2444.5,-834.5 2686.5,-834.5 "/>
<text text-anchor="middle" x="2565.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2444.5,-811.5 2686.5,-811.5 "/>
<text text-anchor="middle" x="2565.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="2444.5,-788.5 2686.5,-788.5 "/>
<text text-anchor="middle" x="2565.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="2444.5,-765.5 2686.5,-765.5 "/>
<text text-anchor="middle" x="2565.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="2444.5,-742.5 2686.5,-742.5 "/>
<text text-anchor="middle" x="2565.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="2444.5,-719.5 2686.5,-719.5 "/>
<text text-anchor="middle" x="2565.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="2444.5,-696.5 2686.5,-696.5 "/>
<text text-anchor="middle" x="2565.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="2444.5,-673.5 2686.5,-673.5 "/>
<text text-anchor="middle" x="2565.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2444.5,-650.5 2686.5,-650.5 "/>
<text text-anchor="middle" x="2565.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2444.5,-627.5 2686.5,-627.5 "/>
<text text-anchor="middle" x="2565.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2444.5,-604.5 2686.5,-604.5 "/>
<text text-anchor="middle" x="2565.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2444.5,-581.5 2686.5,-581.5 "/>
<text text-anchor="middle" x="2565.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="2444.5,-558.5 2686.5,-558.5 "/>
<text text-anchor="middle" x="2565.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="2444.5,-535.5 2686.5,-535.5 "/>
<text text-anchor="middle" x="2565.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2444.5,-512.5 2686.5,-512.5 "/>
<text text-anchor="middle" x="2565.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="2444.5,-489.5 2686.5,-489.5 "/>
<text text-anchor="middle" x="2565.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2444.5,-466.5 2686.5,-466.5 "/>
<text text-anchor="middle" x="2565.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="2444.5,-443.5 2686.5,-443.5 "/>
<text text-anchor="middle" x="2565.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="2444.5,-420.5 2686.5,-420.5 "/>
<text text-anchor="middle" x="2565.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2444.5,-397.5 2686.5,-397.5 "/>
<text text-anchor="middle" x="2565.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="2444.5,-374.5 2686.5,-374.5 "/>
<text text-anchor="middle" x="2565.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2444.5,-351.5 2686.5,-351.5 "/>
<text text-anchor="middle" x="2565.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2444.5,-328.5 2686.5,-328.5 "/>
<text text-anchor="middle" x="2565.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2444.5,-305.5 2686.5,-305.5 "/>
<text text-anchor="middle" x="2565.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="2444.5,-282.5 2686.5,-282.5 "/>
<text text-anchor="middle" x="2565.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="2686.5,-259.5 2686.5,-857.5 "/>
<text text-anchor="middle" x="2697" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2920.1288,-909.4411C2860.9265,-855.1417 2784.2923,-784.854 2715.1728,-721.4587"/>
<polygon fill="#000000" stroke="#000000" points="2717.3838,-718.7374 2707.6484,-714.5574 2712.6523,-723.8962 2717.3838,-718.7374"/>
<text text-anchor="middle" x="2922" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- program -->
<g id="node2" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M2383.5,-.5C2383.5,-.5 2691.5,-.5 2691.5,-.5 2697.5,-.5 2703.5,-6.5 2703.5,-12.5 2703.5,-12.5 2703.5,-195.5 2703.5,-195.5 2703.5,-201.5 2697.5,-207.5 2691.5,-207.5 2691.5,-207.5 2383.5,-207.5 2383.5,-207.5 2377.5,-207.5 2371.5,-201.5 2371.5,-195.5 2371.5,-195.5 2371.5,-12.5 2371.5,-12.5 2371.5,-6.5 2377.5,-.5 2383.5,-.5"/>
<text text-anchor="middle" x="2410.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="2449.5,-.5 2449.5,-207.5 "/>
<text text-anchor="middle" x="2460" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2470.5,-.5 2470.5,-207.5 "/>
<text text-anchor="middle" x="2576.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2470.5,-184.5 2682.5,-184.5 "/>
<text text-anchor="middle" x="2576.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2470.5,-161.5 2682.5,-161.5 "/>
<text text-anchor="middle" x="2576.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="2470.5,-138.5 2682.5,-138.5 "/>
<text text-anchor="middle" x="2576.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="2470.5,-115.5 2682.5,-115.5 "/>
<text text-anchor="middle" x="2576.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="2470.5,-92.5 2682.5,-92.5 "/>
<text text-anchor="middle" x="2576.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="2470.5,-69.5 2682.5,-69.5 "/>
<text text-anchor="middle" x="2576.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="2470.5,-46.5 2682.5,-46.5 "/>
<text text-anchor="middle" x="2576.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="2470.5,-23.5 2682.5,-23.5 "/>
<text text-anchor="middle" x="2576.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="2682.5,-.5 2682.5,-207.5 "/>
<text text-anchor="middle" x="2693" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMCTimages -->
<g id="node3" class="node">
<title>NonDICOMCTimages</title>
<path fill="none" stroke="#000000" d="M12,-2773.5C12,-2773.5 733,-2773.5 733,-2773.5 739,-2773.5 745,-2779.5 745,-2785.5 745,-2785.5 745,-3037.5 745,-3037.5 745,-3043.5 739,-3049.5 733,-3049.5 733,-3049.5 12,-3049.5 12,-3049.5 6,-3049.5 0,-3043.5 0,-3037.5 0,-3037.5 0,-2785.5 0,-2785.5 0,-2779.5 6,-2773.5 12,-2773.5"/>
<text text-anchor="middle" x="86.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages</text>
<polyline fill="none" stroke="#000000" points="173,-2773.5 173,-3049.5 "/>
<text text-anchor="middle" x="183.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="194,-2773.5 194,-3049.5 "/>
<text text-anchor="middle" x="459" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="194,-3026.5 724,-3026.5 "/>
<text text-anchor="middle" x="459" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="194,-3003.5 724,-3003.5 "/>
<text text-anchor="middle" x="459" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="194,-2980.5 724,-2980.5 "/>
<text text-anchor="middle" x="459" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="194,-2957.5 724,-2957.5 "/>
<text text-anchor="middle" x="459" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="194,-2934.5 724,-2934.5 "/>
<text text-anchor="middle" x="459" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="194,-2911.5 724,-2911.5 "/>
<text text-anchor="middle" x="459" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="194,-2888.5 724,-2888.5 "/>
<text text-anchor="middle" x="459" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="194,-2865.5 724,-2865.5 "/>
<text text-anchor="middle" x="459" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="194,-2842.5 724,-2842.5 "/>
<text text-anchor="middle" x="459" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="194,-2819.5 724,-2819.5 "/>
<text text-anchor="middle" x="459" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages_id</text>
<polyline fill="none" stroke="#000000" points="194,-2796.5 724,-2796.5 "/>
<text text-anchor="middle" x="459" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="724,-2773.5 724,-3049.5 "/>
<text text-anchor="middle" x="734.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image -->
<g id="node13" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M2071,-2135C2071,-2135 2436,-2135 2436,-2135 2442,-2135 2448,-2141 2448,-2147 2448,-2147 2448,-2514 2448,-2514 2448,-2520 2442,-2526 2436,-2526 2436,-2526 2071,-2526 2071,-2526 2065,-2526 2059,-2520 2059,-2514 2059,-2514 2059,-2147 2059,-2147 2059,-2141 2065,-2135 2071,-2135"/>
<text text-anchor="middle" x="2089" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="2119,-2135 2119,-2526 "/>
<text text-anchor="middle" x="2129.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2140,-2135 2140,-2526 "/>
<text text-anchor="middle" x="2283.5" y="-2510.8" font-family="Times,serif" font-size="14.00" fill="#000000">citation_or_DOI</text>
<polyline fill="none" stroke="#000000" points="2140,-2503 2427,-2503 "/>
<text text-anchor="middle" x="2283.5" y="-2487.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2140,-2480 2427,-2480 "/>
<text text-anchor="middle" x="2283.5" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_description</text>
<polyline fill="none" stroke="#000000" points="2140,-2457 2427,-2457 "/>
<text text-anchor="middle" x="2283.5" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_type</text>
<polyline fill="none" stroke="#000000" points="2140,-2434 2427,-2434 "/>
<text text-anchor="middle" x="2283.5" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_software</text>
<polyline fill="none" stroke="#000000" points="2140,-2411 2427,-2411 "/>
<text text-anchor="middle" x="2283.5" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="2140,-2388 2427,-2388 "/>
<text text-anchor="middle" x="2283.5" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_manufacturer</text>
<polyline fill="none" stroke="#000000" points="2140,-2365 2427,-2365 "/>
<text text-anchor="middle" x="2283.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_model</text>
<polyline fill="none" stroke="#000000" points="2140,-2342 2427,-2342 "/>
<text text-anchor="middle" x="2283.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_protocol</text>
<polyline fill="none" stroke="#000000" points="2140,-2319 2427,-2319 "/>
<text text-anchor="middle" x="2283.5" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_software</text>
<polyline fill="none" stroke="#000000" points="2140,-2296 2427,-2296 "/>
<text text-anchor="middle" x="2283.5" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">license</text>
<polyline fill="none" stroke="#000000" points="2140,-2273 2427,-2273 "/>
<text text-anchor="middle" x="2283.5" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_offset</text>
<polyline fill="none" stroke="#000000" points="2140,-2250 2427,-2250 "/>
<text text-anchor="middle" x="2283.5" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_type</text>
<polyline fill="none" stroke="#000000" points="2140,-2227 2427,-2227 "/>
<text text-anchor="middle" x="2283.5" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">organ_or_tissue</text>
<polyline fill="none" stroke="#000000" points="2140,-2204 2427,-2204 "/>
<text text-anchor="middle" x="2283.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_typeCode</text>
<polyline fill="none" stroke="#000000" points="2140,-2181 2427,-2181 "/>
<text text-anchor="middle" x="2283.5" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="2140,-2158 2427,-2158 "/>
<text text-anchor="middle" x="2283.5" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_link_id</text>
<polyline fill="none" stroke="#000000" points="2427,-2135 2427,-2526 "/>
<text text-anchor="middle" x="2437.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMCTimages&#45;&gt;image -->
<g id="edge8" class="edge">
<title>NonDICOMCTimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M513.948,-2773.4677C581.4173,-2715.0687 666.3428,-2651.5357 753.5,-2612 1187.1336,-2415.2979 1751.1365,-2356.0412 2048.7844,-2338.1922"/>
<polygon fill="#000000" stroke="#000000" points="2049.0464,-2341.6829 2058.8228,-2337.5999 2048.634,-2334.6951 2049.0464,-2341.6829"/>
<text text-anchor="middle" x="862" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMPETimages -->
<g id="node4" class="node">
<title>NonDICOMPETimages</title>
<path fill="none" stroke="#000000" d="M775,-2865.5C775,-2865.5 1424,-2865.5 1424,-2865.5 1430,-2865.5 1436,-2871.5 1436,-2877.5 1436,-2877.5 1436,-2945.5 1436,-2945.5 1436,-2951.5 1430,-2957.5 1424,-2957.5 1424,-2957.5 775,-2957.5 775,-2957.5 769,-2957.5 763,-2951.5 763,-2945.5 763,-2945.5 763,-2877.5 763,-2877.5 763,-2871.5 769,-2865.5 775,-2865.5"/>
<text text-anchor="middle" x="854" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMPETimages</text>
<polyline fill="none" stroke="#000000" points="945,-2865.5 945,-2957.5 "/>
<text text-anchor="middle" x="955.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="966,-2865.5 966,-2957.5 "/>
<text text-anchor="middle" x="1190.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMPETimages_id</text>
<polyline fill="none" stroke="#000000" points="966,-2934.5 1415,-2934.5 "/>
<text text-anchor="middle" x="1190.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">PETImagingAcquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="966,-2911.5 1415,-2911.5 "/>
<text text-anchor="middle" x="1190.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">Radiopharmaceutical_radionuclideCode</text>
<polyline fill="none" stroke="#000000" points="966,-2888.5 1415,-2888.5 "/>
<text text-anchor="middle" x="1190.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1415,-2865.5 1415,-2957.5 "/>
<text text-anchor="middle" x="1425.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMPETimages&#45;&gt;image -->
<g id="edge9" class="edge">
<title>NonDICOMPETimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1141.5253,-2865.2802C1202.5855,-2800.5676 1321.9791,-2682.9481 1444.5,-2612 1636.5443,-2500.793 1879.5916,-2423.5829 2048.9241,-2378.5225"/>
<polygon fill="#000000" stroke="#000000" points="2049.9299,-2381.8768 2058.7014,-2375.9346 2048.1387,-2375.1099 2049.9299,-2381.8768"/>
<text text-anchor="middle" x="1518" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMradiologyAllModalities -->
<g id="node5" class="node">
<title>NonDICOMradiologyAllModalities</title>
<path fill="none" stroke="#000000" d="M1466,-2693C1466,-2693 2239,-2693 2239,-2693 2245,-2693 2251,-2699 2251,-2705 2251,-2705 2251,-3118 2251,-3118 2251,-3124 2245,-3130 2239,-3130 2239,-3130 1466,-3130 1466,-3130 1460,-3130 1454,-3124 1454,-3118 1454,-3118 1454,-2705 1454,-2705 1454,-2699 1460,-2693 1466,-2693"/>
<text text-anchor="middle" x="1585.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities</text>
<polyline fill="none" stroke="#000000" points="1717,-2693 1717,-3130 "/>
<text text-anchor="middle" x="1727.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1738,-2693 1738,-3130 "/>
<text text-anchor="middle" x="1984" y="-3114.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities_id</text>
<polyline fill="none" stroke="#000000" points="1738,-3107 2230,-3107 "/>
<text text-anchor="middle" x="1984" y="-3091.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1738,-3084 2230,-3084 "/>
<text text-anchor="middle" x="1984" y="-3068.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_acquisitionTypeCode</text>
<polyline fill="none" stroke="#000000" points="1738,-3061 2230,-3061 "/>
<text text-anchor="middle" x="1984" y="-3045.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_admittingDiagnosisCode</text>
<polyline fill="none" stroke="#000000" points="1738,-3038 2230,-3038 "/>
<text text-anchor="middle" x="1984" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_algorithmCode</text>
<polyline fill="none" stroke="#000000" points="1738,-3015 2230,-3015 "/>
<text text-anchor="middle" x="1984" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_bodyPositionCode</text>
<polyline fill="none" stroke="#000000" points="1738,-2992 2230,-2992 "/>
<text text-anchor="middle" x="1984" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_cardiacSynchronizationTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="1738,-2969 2230,-2969 "/>
<text text-anchor="middle" x="1984" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_dataCollectionDiameter</text>
<polyline fill="none" stroke="#000000" points="1738,-2946 2230,-2946 "/>
<text text-anchor="middle" x="1984" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_description</text>
<polyline fill="none" stroke="#000000" points="1738,-2923 2230,-2923 "/>
<text text-anchor="middle" x="1984" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_lossyImageCompressionIndicator</text>
<polyline fill="none" stroke="#000000" points="1738,-2900 2230,-2900 "/>
<text text-anchor="middle" x="1984" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_nonAcquisitionModalitiesInStudyCode</text>
<polyline fill="none" stroke="#000000" points="1738,-2877 2230,-2877 "/>
<text text-anchor="middle" x="1984" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_primaryAnatomicSiteCode</text>
<polyline fill="none" stroke="#000000" points="1738,-2854 2230,-2854 "/>
<text text-anchor="middle" x="1984" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionDiameter</text>
<polyline fill="none" stroke="#000000" points="1738,-2831 2230,-2831 "/>
<text text-anchor="middle" x="1984" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewHeight</text>
<polyline fill="none" stroke="#000000" points="1738,-2808 2230,-2808 "/>
<text text-anchor="middle" x="1984" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewWidth</text>
<polyline fill="none" stroke="#000000" points="1738,-2785 2230,-2785 "/>
<text text-anchor="middle" x="1984" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionInterval</text>
<polyline fill="none" stroke="#000000" points="1738,-2762 2230,-2762 "/>
<text text-anchor="middle" x="1984" y="-2746.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_respiratoryMotionTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="1738,-2739 2230,-2739 "/>
<text text-anchor="middle" x="1984" y="-2723.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_sliceThickness</text>
<polyline fill="none" stroke="#000000" points="1738,-2716 2230,-2716 "/>
<text text-anchor="middle" x="1984" y="-2700.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_summary</text>
<polyline fill="none" stroke="#000000" points="2230,-2693 2230,-3130 "/>
<text text-anchor="middle" x="2240.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMradiologyAllModalities&#45;&gt;image -->
<g id="edge10" class="edge">
<title>NonDICOMradiologyAllModalities&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2003.5295,-2692.6767C2039.2816,-2640.8763 2077.2722,-2585.8326 2112.5563,-2534.7101"/>
<polygon fill="#000000" stroke="#000000" points="2115.6233,-2536.4281 2118.4231,-2526.2099 2109.8623,-2532.4518 2115.6233,-2536.4281"/>
<text text-anchor="middle" x="2110" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- treatment -->
<g id="node6" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M2889.5,-1329.5C2889.5,-1329.5 3151.5,-1329.5 3151.5,-1329.5 3157.5,-1329.5 3163.5,-1335.5 3163.5,-1341.5 3163.5,-1341.5 3163.5,-1455.5 3163.5,-1455.5 3163.5,-1461.5 3157.5,-1467.5 3151.5,-1467.5 3151.5,-1467.5 2889.5,-1467.5 2889.5,-1467.5 2883.5,-1467.5 2877.5,-1461.5 2877.5,-1455.5 2877.5,-1455.5 2877.5,-1341.5 2877.5,-1341.5 2877.5,-1335.5 2883.5,-1329.5 2889.5,-1329.5"/>
<text text-anchor="middle" x="2922" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="2966.5,-1329.5 2966.5,-1467.5 "/>
<text text-anchor="middle" x="2977" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2987.5,-1329.5 2987.5,-1467.5 "/>
<text text-anchor="middle" x="3065" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2987.5,-1444.5 3142.5,-1444.5 "/>
<text text-anchor="middle" x="3065" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2987.5,-1421.5 3142.5,-1421.5 "/>
<text text-anchor="middle" x="3065" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="2987.5,-1398.5 3142.5,-1398.5 "/>
<text text-anchor="middle" x="3065" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2987.5,-1375.5 3142.5,-1375.5 "/>
<text text-anchor="middle" x="3065" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2987.5,-1352.5 3142.5,-1352.5 "/>
<text text-anchor="middle" x="3065" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3142.5,-1329.5 3142.5,-1467.5 "/>
<text text-anchor="middle" x="3153" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3020.5,-1329.3479C3020.5,-1267.096 3020.5,-1174.7818 3020.5,-1103.9586"/>
<polygon fill="#000000" stroke="#000000" points="3024.0001,-1103.6713 3020.5,-1093.6714 3017.0001,-1103.6714 3024.0001,-1103.6713"/>
<text text-anchor="middle" x="3071" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- NonDICOMMRimages -->
<g id="node7" class="node">
<title>NonDICOMMRimages</title>
<path fill="none" stroke="#000000" d="M2281,-2693C2281,-2693 3030,-2693 3030,-2693 3036,-2693 3042,-2699 3042,-2705 3042,-2705 3042,-3118 3042,-3118 3042,-3124 3036,-3130 3030,-3130 3030,-3130 2281,-3130 2281,-3130 2275,-3130 2269,-3124 2269,-3118 2269,-3118 2269,-2705 2269,-2705 2269,-2699 2275,-2693 2281,-2693"/>
<text text-anchor="middle" x="2357.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages</text>
<polyline fill="none" stroke="#000000" points="2446,-2693 2446,-3130 "/>
<text text-anchor="middle" x="2456.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2467,-2693 2467,-3130 "/>
<text text-anchor="middle" x="2744" y="-3114.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="2467,-3107 3021,-3107 "/>
<text text-anchor="middle" x="2744" y="-3091.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="2467,-3084 3021,-3084 "/>
<text text-anchor="middle" x="2744" y="-3068.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="2467,-3061 3021,-3061 "/>
<text text-anchor="middle" x="2744" y="-3045.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="2467,-3038 3021,-3038 "/>
<text text-anchor="middle" x="2744" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="2467,-3015 3021,-3015 "/>
<text text-anchor="middle" x="2744" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="2467,-2992 3021,-2992 "/>
<text text-anchor="middle" x="2744" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="2467,-2969 3021,-2969 "/>
<text text-anchor="middle" x="2744" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="2467,-2946 3021,-2946 "/>
<text text-anchor="middle" x="2744" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="2467,-2923 3021,-2923 "/>
<text text-anchor="middle" x="2744" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="2467,-2900 3021,-2900 "/>
<text text-anchor="middle" x="2744" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="2467,-2877 3021,-2877 "/>
<text text-anchor="middle" x="2744" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="2467,-2854 3021,-2854 "/>
<text text-anchor="middle" x="2744" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="2467,-2831 3021,-2831 "/>
<text text-anchor="middle" x="2744" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="2467,-2808 3021,-2808 "/>
<text text-anchor="middle" x="2744" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="2467,-2785 3021,-2785 "/>
<text text-anchor="middle" x="2744" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_timeOfFlightContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="2467,-2762 3021,-2762 "/>
<text text-anchor="middle" x="2744" y="-2746.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageReconstructionProtocolElement_complexImageComponentCode</text>
<polyline fill="none" stroke="#000000" points="2467,-2739 3021,-2739 "/>
<text text-anchor="middle" x="2744" y="-2723.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages_id</text>
<polyline fill="none" stroke="#000000" points="2467,-2716 3021,-2716 "/>
<text text-anchor="middle" x="2744" y="-2700.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3021,-2693 3021,-3130 "/>
<text text-anchor="middle" x="3031.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMMRimages&#45;&gt;image -->
<g id="edge12" class="edge">
<title>NonDICOMMRimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2504.0939,-2692.6767C2468.2526,-2640.8763 2430.1673,-2585.8326 2394.7951,-2534.7101"/>
<polygon fill="#000000" stroke="#000000" points="2397.4819,-2532.4419 2388.9137,-2526.2099 2391.7254,-2536.4248 2397.4819,-2532.4419"/>
<text text-anchor="middle" x="2463" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMpathologyImages -->
<g id="node8" class="node">
<title>NonDICOMpathologyImages</title>
<path fill="none" stroke="#000000" d="M3072,-2785C3072,-2785 3559,-2785 3559,-2785 3565,-2785 3571,-2791 3571,-2797 3571,-2797 3571,-3026 3571,-3026 3571,-3032 3565,-3038 3559,-3038 3559,-3038 3072,-3038 3072,-3038 3066,-3038 3060,-3032 3060,-3026 3060,-3026 3060,-2797 3060,-2797 3060,-2791 3066,-2785 3072,-2785"/>
<text text-anchor="middle" x="3172" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages</text>
<polyline fill="none" stroke="#000000" points="3284,-2785 3284,-3038 "/>
<text text-anchor="middle" x="3294.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3305,-2785 3305,-3038 "/>
<text text-anchor="middle" x="3427.5" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages_id</text>
<polyline fill="none" stroke="#000000" points="3305,-3015 3550,-3015 "/>
<text text-anchor="middle" x="3427.5" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="3305,-2992 3550,-2992 "/>
<text text-anchor="middle" x="3427.5" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3305,-2969 3550,-2969 "/>
<text text-anchor="middle" x="3427.5" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="3305,-2946 3550,-2946 "/>
<text text-anchor="middle" x="3427.5" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="3305,-2923 3550,-2923 "/>
<text text-anchor="middle" x="3427.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="3305,-2900 3550,-2900 "/>
<text text-anchor="middle" x="3427.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="3305,-2877 3550,-2877 "/>
<text text-anchor="middle" x="3427.5" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">objective</text>
<polyline fill="none" stroke="#000000" points="3305,-2854 3550,-2854 "/>
<text text-anchor="middle" x="3427.5" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="3305,-2831 3550,-2831 "/>
<text text-anchor="middle" x="3427.5" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_fixative</text>
<polyline fill="none" stroke="#000000" points="3305,-2808 3550,-2808 "/>
<text text-anchor="middle" x="3427.5" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_type</text>
<polyline fill="none" stroke="#000000" points="3550,-2785 3550,-3038 "/>
<text text-anchor="middle" x="3560.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMpathologyImages&#45;&gt;image -->
<g id="edge7" class="edge">
<title>NonDICOMpathologyImages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3237.5757,-2784.8209C3191.4662,-2721.5869 3127.0995,-2650.5294 3050.5,-2612 2932.1435,-2552.4669 2574.7876,-2620.6699 2456.5,-2561 2440.7331,-2553.0464 2425.6483,-2543.2932 2411.333,-2532.3391"/>
<polygon fill="#000000" stroke="#000000" points="2413.4801,-2529.575 2403.4597,-2526.1337 2409.1471,-2535.0727 2413.4801,-2529.575"/>
<text text-anchor="middle" x="3021" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge4" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2537.5,-259.4595C2537.5,-244.999 2537.5,-230.9707 2537.5,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="2541.0001,-217.5945 2537.5,-207.5945 2534.0001,-217.5946 2541.0001,-217.5945"/>
<text text-anchor="middle" x="2579" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- MultiplexMicroscopy -->
<g id="node10" class="node">
<title>MultiplexMicroscopy</title>
<path fill="none" stroke="#000000" d="M3601,-2612.5C3601,-2612.5 4066,-2612.5 4066,-2612.5 4072,-2612.5 4078,-2618.5 4078,-2624.5 4078,-2624.5 4078,-3198.5 4078,-3198.5 4078,-3204.5 4072,-3210.5 4066,-3210.5 4066,-3210.5 3601,-3210.5 3601,-3210.5 3595,-3210.5 3589,-3204.5 3589,-3198.5 3589,-3198.5 3589,-2624.5 3589,-2624.5 3589,-2618.5 3595,-2612.5 3601,-2612.5"/>
<text text-anchor="middle" x="3673" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">MultiplexMicroscopy</text>
<polyline fill="none" stroke="#000000" points="3757,-2612.5 3757,-3210.5 "/>
<text text-anchor="middle" x="3767.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3778,-2612.5 3778,-3210.5 "/>
<text text-anchor="middle" x="3917.5" y="-3195.3" font-family="Times,serif" font-size="14.00" fill="#000000">MultiplexMicroscopy_id</text>
<polyline fill="none" stroke="#000000" points="3778,-3187.5 4057,-3187.5 "/>
<text text-anchor="middle" x="3917.5" y="-3172.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="3778,-3164.5 4057,-3164.5 "/>
<text text-anchor="middle" x="3917.5" y="-3149.3" font-family="Times,serif" font-size="14.00" fill="#000000">antibody_name</text>
<polyline fill="none" stroke="#000000" points="3778,-3141.5 4057,-3141.5 "/>
<text text-anchor="middle" x="3917.5" y="-3126.3" font-family="Times,serif" font-size="14.00" fill="#000000">catalog_number</text>
<polyline fill="none" stroke="#000000" points="3778,-3118.5 4057,-3118.5 "/>
<text text-anchor="middle" x="3917.5" y="-3103.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_id</text>
<polyline fill="none" stroke="#000000" points="3778,-3095.5 4057,-3095.5 "/>
<text text-anchor="middle" x="3917.5" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="3778,-3072.5 4057,-3072.5 "/>
<text text-anchor="middle" x="3917.5" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_filename</text>
<polyline fill="none" stroke="#000000" points="3778,-3049.5 4057,-3049.5 "/>
<text text-anchor="middle" x="3917.5" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_name</text>
<polyline fill="none" stroke="#000000" points="3778,-3026.5 4057,-3026.5 "/>
<text text-anchor="middle" x="3917.5" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">clone</text>
<polyline fill="none" stroke="#000000" points="3778,-3003.5 4057,-3003.5 "/>
<text text-anchor="middle" x="3917.5" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">concentration</text>
<polyline fill="none" stroke="#000000" points="3778,-2980.5 4057,-2980.5 "/>
<text text-anchor="middle" x="3917.5" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3778,-2957.5 4057,-2957.5 "/>
<text text-anchor="middle" x="3917.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">cycle_number</text>
<polyline fill="none" stroke="#000000" points="3778,-2934.5 4057,-2934.5 "/>
<text text-anchor="middle" x="3917.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">dilution</text>
<polyline fill="none" stroke="#000000" points="3778,-2911.5 4057,-2911.5 "/>
<text text-anchor="middle" x="3917.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="3778,-2888.5 4057,-2888.5 "/>
<text text-anchor="middle" x="3917.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_bandwidth</text>
<polyline fill="none" stroke="#000000" points="3778,-2865.5 4057,-2865.5 "/>
<text text-anchor="middle" x="3917.5" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_wavelength</text>
<polyline fill="none" stroke="#000000" points="3778,-2842.5 4057,-2842.5 "/>
<text text-anchor="middle" x="3917.5" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_bandwidth</text>
<polyline fill="none" stroke="#000000" points="3778,-2819.5 4057,-2819.5 "/>
<text text-anchor="middle" x="3917.5" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_wavelength</text>
<polyline fill="none" stroke="#000000" points="3778,-2796.5 4057,-2796.5 "/>
<text text-anchor="middle" x="3917.5" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">fluorophore</text>
<polyline fill="none" stroke="#000000" points="3778,-2773.5 4057,-2773.5 "/>
<text text-anchor="middle" x="3917.5" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_assay_type</text>
<polyline fill="none" stroke="#000000" points="3778,-2750.5 4057,-2750.5 "/>
<text text-anchor="middle" x="3917.5" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="3778,-2727.5 4057,-2727.5 "/>
<text text-anchor="middle" x="3917.5" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="3778,-2704.5 4057,-2704.5 "/>
<text text-anchor="middle" x="3917.5" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">lot</text>
<polyline fill="none" stroke="#000000" points="3778,-2681.5 4057,-2681.5 "/>
<text text-anchor="middle" x="3917.5" y="-2666.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_abbreviation</text>
<polyline fill="none" stroke="#000000" points="3778,-2658.5 4057,-2658.5 "/>
<text text-anchor="middle" x="3917.5" y="-2643.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_mass</text>
<polyline fill="none" stroke="#000000" points="3778,-2635.5 4057,-2635.5 "/>
<text text-anchor="middle" x="3917.5" y="-2620.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="4057,-2612.5 4057,-3210.5 "/>
<text text-anchor="middle" x="4067.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- MultiplexMicroscopy&#45;&gt;image -->
<g id="edge11" class="edge">
<title>MultiplexMicroscopy&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3588.654,-2616.2607C3585.9542,-2614.7976 3583.2361,-2613.3768 3580.5,-2612 3476.4736,-2559.656 3173.8276,-2584.4105 3057.5,-2579 3024.1322,-2577.448 2486.7315,-2575.2082 2456.5,-2561 2440.1105,-2553.2972 2424.4969,-2543.5817 2409.7418,-2532.5229"/>
<polygon fill="#000000" stroke="#000000" points="2411.6832,-2529.5996 2401.6334,-2526.2452 2407.3979,-2535.1346 2411.6832,-2529.5996"/>
<text text-anchor="middle" x="3549" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2561.5,-1283.5C2561.5,-1283.5 2847.5,-1283.5 2847.5,-1283.5 2853.5,-1283.5 2859.5,-1289.5 2859.5,-1295.5 2859.5,-1295.5 2859.5,-1501.5 2859.5,-1501.5 2859.5,-1507.5 2853.5,-1513.5 2847.5,-1513.5 2847.5,-1513.5 2561.5,-1513.5 2561.5,-1513.5 2555.5,-1513.5 2549.5,-1507.5 2549.5,-1501.5 2549.5,-1501.5 2549.5,-1295.5 2549.5,-1295.5 2549.5,-1289.5 2555.5,-1283.5 2561.5,-1283.5"/>
<text text-anchor="middle" x="2583.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2617.5,-1283.5 2617.5,-1513.5 "/>
<text text-anchor="middle" x="2628" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2638.5,-1283.5 2638.5,-1513.5 "/>
<text text-anchor="middle" x="2738.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1490.5 2838.5,-1490.5 "/>
<text text-anchor="middle" x="2738.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1467.5 2838.5,-1467.5 "/>
<text text-anchor="middle" x="2738.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1444.5 2838.5,-1444.5 "/>
<text text-anchor="middle" x="2738.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1421.5 2838.5,-1421.5 "/>
<text text-anchor="middle" x="2738.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1398.5 2838.5,-1398.5 "/>
<text text-anchor="middle" x="2738.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1375.5 2838.5,-1375.5 "/>
<text text-anchor="middle" x="2738.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1352.5 2838.5,-1352.5 "/>
<text text-anchor="middle" x="2738.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1329.5 2838.5,-1329.5 "/>
<text text-anchor="middle" x="2738.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2638.5,-1306.5 2838.5,-1306.5 "/>
<text text-anchor="middle" x="2738.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="2838.5,-1283.5 2838.5,-1513.5 "/>
<text text-anchor="middle" x="2849" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2770.8204,-1283.3776C2798.7262,-1238.5055 2832.9532,-1187.7038 2868.5,-1145 2880.8571,-1130.155 2894.6459,-1115.2801 2908.7371,-1101.0293"/>
<polygon fill="#000000" stroke="#000000" points="2911.5322,-1103.1839 2916.1274,-1093.6375 2906.5819,-1098.2347 2911.5322,-1103.1839"/>
<text text-anchor="middle" x="2946" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M3193.5,-1145.5C3193.5,-1145.5 3567.5,-1145.5 3567.5,-1145.5 3573.5,-1145.5 3579.5,-1151.5 3579.5,-1157.5 3579.5,-1157.5 3579.5,-1639.5 3579.5,-1639.5 3579.5,-1645.5 3573.5,-1651.5 3567.5,-1651.5 3567.5,-1651.5 3193.5,-1651.5 3193.5,-1651.5 3187.5,-1651.5 3181.5,-1645.5 3181.5,-1639.5 3181.5,-1639.5 3181.5,-1157.5 3181.5,-1157.5 3181.5,-1151.5 3187.5,-1145.5 3193.5,-1145.5"/>
<text text-anchor="middle" x="3223.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="3265.5,-1145.5 3265.5,-1651.5 "/>
<text text-anchor="middle" x="3276" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3286.5,-1145.5 3286.5,-1651.5 "/>
<text text-anchor="middle" x="3422.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1628.5 3558.5,-1628.5 "/>
<text text-anchor="middle" x="3422.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1605.5 3558.5,-1605.5 "/>
<text text-anchor="middle" x="3422.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1582.5 3558.5,-1582.5 "/>
<text text-anchor="middle" x="3422.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1559.5 3558.5,-1559.5 "/>
<text text-anchor="middle" x="3422.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1536.5 3558.5,-1536.5 "/>
<text text-anchor="middle" x="3422.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1513.5 3558.5,-1513.5 "/>
<text text-anchor="middle" x="3422.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1490.5 3558.5,-1490.5 "/>
<text text-anchor="middle" x="3422.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1467.5 3558.5,-1467.5 "/>
<text text-anchor="middle" x="3422.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1444.5 3558.5,-1444.5 "/>
<text text-anchor="middle" x="3422.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1421.5 3558.5,-1421.5 "/>
<text text-anchor="middle" x="3422.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1398.5 3558.5,-1398.5 "/>
<text text-anchor="middle" x="3422.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1375.5 3558.5,-1375.5 "/>
<text text-anchor="middle" x="3422.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1352.5 3558.5,-1352.5 "/>
<text text-anchor="middle" x="3422.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1329.5 3558.5,-1329.5 "/>
<text text-anchor="middle" x="3422.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1306.5 3558.5,-1306.5 "/>
<text text-anchor="middle" x="3422.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1283.5 3558.5,-1283.5 "/>
<text text-anchor="middle" x="3422.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1260.5 3558.5,-1260.5 "/>
<text text-anchor="middle" x="3422.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1237.5 3558.5,-1237.5 "/>
<text text-anchor="middle" x="3422.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1214.5 3558.5,-1214.5 "/>
<text text-anchor="middle" x="3422.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1191.5 3558.5,-1191.5 "/>
<text text-anchor="middle" x="3422.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1168.5 3558.5,-1168.5 "/>
<text text-anchor="middle" x="3422.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3558.5,-1145.5 3558.5,-1651.5 "/>
<text text-anchor="middle" x="3569" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3181.2578,-1154.4659C3178.3326,-1151.2791 3175.4124,-1148.1222 3172.5,-1145 3158.7787,-1130.2901 3143.8733,-1115.2227 3128.9399,-1100.6422"/>
<polygon fill="#000000" stroke="#000000" points="3131.2245,-1097.9821 3121.6117,-1093.5274 3126.3484,-1103.0044 3131.2245,-1097.9821"/>
<text text-anchor="middle" x="3204" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file -->
<g id="node14" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2514.5,-1703.5C2514.5,-1703.5 2894.5,-1703.5 2894.5,-1703.5 2900.5,-1703.5 2906.5,-1709.5 2906.5,-1715.5 2906.5,-1715.5 2906.5,-2036.5 2906.5,-2036.5 2906.5,-2042.5 2900.5,-2048.5 2894.5,-2048.5 2894.5,-2048.5 2514.5,-2048.5 2514.5,-2048.5 2508.5,-2048.5 2502.5,-2042.5 2502.5,-2036.5 2502.5,-2036.5 2502.5,-1715.5 2502.5,-1715.5 2502.5,-1709.5 2508.5,-1703.5 2514.5,-1703.5"/>
<text text-anchor="middle" x="2522" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2541.5,-1703.5 2541.5,-2048.5 "/>
<text text-anchor="middle" x="2552" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2562.5,-1703.5 2562.5,-2048.5 "/>
<text text-anchor="middle" x="2724" y="-2033.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2562.5,-2025.5 2885.5,-2025.5 "/>
<text text-anchor="middle" x="2724" y="-2010.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2562.5,-2002.5 2885.5,-2002.5 "/>
<text text-anchor="middle" x="2724" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1979.5 2885.5,-1979.5 "/>
<text text-anchor="middle" x="2724" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1956.5 2885.5,-1956.5 "/>
<text text-anchor="middle" x="2724" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1933.5 2885.5,-1933.5 "/>
<text text-anchor="middle" x="2724" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1910.5 2885.5,-1910.5 "/>
<text text-anchor="middle" x="2724" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1887.5 2885.5,-1887.5 "/>
<text text-anchor="middle" x="2724" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1864.5 2885.5,-1864.5 "/>
<text text-anchor="middle" x="2724" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1841.5 2885.5,-1841.5 "/>
<text text-anchor="middle" x="2724" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1818.5 2885.5,-1818.5 "/>
<text text-anchor="middle" x="2724" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1795.5 2885.5,-1795.5 "/>
<text text-anchor="middle" x="2724" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_supplementary_file</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1772.5 2885.5,-1772.5 "/>
<text text-anchor="middle" x="2724" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1749.5 2885.5,-1749.5 "/>
<text text-anchor="middle" x="2724" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_datetime</text>
<polyline fill="none" stroke="#000000" points="2562.5,-1726.5 2885.5,-1726.5 "/>
<text text-anchor="middle" x="2724" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="2885.5,-1703.5 2885.5,-2048.5 "/>
<text text-anchor="middle" x="2896" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge1" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2423.0767,-2134.7625C2434.2454,-2122.8668 2445.4468,-2111.1928 2456.5,-2100 2470.864,-2085.4546 2485.9719,-2070.6699 2501.3469,-2055.9872"/>
<polygon fill="#000000" stroke="#000000" points="2504.0808,-2058.2172 2508.914,-2048.789 2499.2562,-2053.1453 2504.0808,-2058.2172"/>
<text text-anchor="middle" x="2511.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2906.7141,-1853.3757C3141.0086,-1822.5109 3505.6076,-1758.5166 3588.5,-1652 3726.8893,-1474.17 3726.9522,-1322.7811 3588.5,-1145 3538.8262,-1081.2158 3331.812,-1041.3129 3182.0249,-1020.228"/>
<polygon fill="#000000" stroke="#000000" points="3182.1801,-1016.7159 3171.7932,-1018.8043 3181.2154,-1023.6491 3182.1801,-1016.7159"/>
<text text-anchor="middle" x="3742" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2562.7015,-1703.1958C2553.8475,-1686.5708 2546.2154,-1669.4005 2540.5,-1652 2456.9196,-1397.5392 2464.5504,-1091.4367 2488.2437,-867.8947"/>
<polygon fill="#000000" stroke="#000000" points="2491.7565,-867.9639 2489.3473,-857.6466 2484.7967,-867.2144 2491.7565,-867.9639"/>
<text text-anchor="middle" x="2504" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2704.5,-1703.274C2704.5,-1643.9501 2704.5,-1578.7236 2704.5,-1523.8875"/>
<polygon fill="#000000" stroke="#000000" points="2708.0001,-1523.7731 2704.5,-1513.7731 2701.0001,-1523.7731 2708.0001,-1523.7731"/>
<text text-anchor="middle" x="2751" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge18" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2906.6809,-1900.8839C2917.8527,-1894.8327 2924.5,-1886.5381 2924.5,-1876 2924.5,-1868.4258 2921.066,-1862.0105 2914.9862,-1856.7542"/>
<polygon fill="#000000" stroke="#000000" points="2916.9204,-1853.8369 2906.6809,-1851.1161 2912.9887,-1859.6285 2916.9204,-1853.8369"/>
<text text-anchor="middle" x="2982" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- genomic_info -->
<g id="node15" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M2478,-2100.5C2478,-2100.5 2931,-2100.5 2931,-2100.5 2937,-2100.5 2943,-2106.5 2943,-2112.5 2943,-2112.5 2943,-2548.5 2943,-2548.5 2943,-2554.5 2937,-2560.5 2931,-2560.5 2931,-2560.5 2478,-2560.5 2478,-2560.5 2472,-2560.5 2466,-2554.5 2466,-2548.5 2466,-2548.5 2466,-2112.5 2466,-2112.5 2466,-2106.5 2472,-2100.5 2478,-2100.5"/>
<text text-anchor="middle" x="2522" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="2578,-2100.5 2578,-2560.5 "/>
<text text-anchor="middle" x="2588.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2599,-2100.5 2599,-2560.5 "/>
<text text-anchor="middle" x="2760.5" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2599,-2537.5 2922,-2537.5 "/>
<text text-anchor="middle" x="2760.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="2599,-2514.5 2922,-2514.5 "/>
<text text-anchor="middle" x="2760.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2599,-2491.5 2922,-2491.5 "/>
<text text-anchor="middle" x="2760.5" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2599,-2468.5 2922,-2468.5 "/>
<text text-anchor="middle" x="2760.5" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2599,-2445.5 2922,-2445.5 "/>
<text text-anchor="middle" x="2760.5" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2599,-2422.5 2922,-2422.5 "/>
<text text-anchor="middle" x="2760.5" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2599,-2399.5 2922,-2399.5 "/>
<text text-anchor="middle" x="2760.5" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2599,-2376.5 2922,-2376.5 "/>
<text text-anchor="middle" x="2760.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2599,-2353.5 2922,-2353.5 "/>
<text text-anchor="middle" x="2760.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2599,-2330.5 2922,-2330.5 "/>
<text text-anchor="middle" x="2760.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2599,-2307.5 2922,-2307.5 "/>
<text text-anchor="middle" x="2760.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="2599,-2284.5 2922,-2284.5 "/>
<text text-anchor="middle" x="2760.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="2599,-2261.5 2922,-2261.5 "/>
<text text-anchor="middle" x="2760.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2599,-2238.5 2922,-2238.5 "/>
<text text-anchor="middle" x="2760.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2599,-2215.5 2922,-2215.5 "/>
<text text-anchor="middle" x="2760.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2599,-2192.5 2922,-2192.5 "/>
<text text-anchor="middle" x="2760.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2599,-2169.5 2922,-2169.5 "/>
<text text-anchor="middle" x="2760.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2599,-2146.5 2922,-2146.5 "/>
<text text-anchor="middle" x="2760.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2599,-2123.5 2922,-2123.5 "/>
<text text-anchor="middle" x="2760.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2922,-2100.5 2922,-2560.5 "/>
<text text-anchor="middle" x="2932.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge3" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2704.5,-2100.2541C2704.5,-2086.4072 2704.5,-2072.5751 2704.5,-2058.9635"/>
<polygon fill="#000000" stroke="#000000" points="2708.0001,-2058.601 2704.5,-2048.601 2701.0001,-2058.6011 2708.0001,-2058.601"/>
<text text-anchor="middle" x="2726.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- proteomic -->
<g id="node16" class="node">
<title>proteomic</title>
<path fill="none" stroke="#000000" d="M2973.5,-2238.5C2973.5,-2238.5 3313.5,-2238.5 3313.5,-2238.5 3319.5,-2238.5 3325.5,-2244.5 3325.5,-2250.5 3325.5,-2250.5 3325.5,-2410.5 3325.5,-2410.5 3325.5,-2416.5 3319.5,-2422.5 3313.5,-2422.5 3313.5,-2422.5 2973.5,-2422.5 2973.5,-2422.5 2967.5,-2422.5 2961.5,-2416.5 2961.5,-2410.5 2961.5,-2410.5 2961.5,-2250.5 2961.5,-2250.5 2961.5,-2244.5 2967.5,-2238.5 2973.5,-2238.5"/>
<text text-anchor="middle" x="3006" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic</text>
<polyline fill="none" stroke="#000000" points="3050.5,-2238.5 3050.5,-2422.5 "/>
<text text-anchor="middle" x="3061" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3071.5,-2238.5 3071.5,-2422.5 "/>
<text text-anchor="middle" x="3188" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2399.5 3304.5,-2399.5 "/>
<text text-anchor="middle" x="3188" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fractions</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2376.5 3304.5,-2376.5 "/>
<text text-anchor="middle" x="3188" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2353.5 3304.5,-2353.5 "/>
<text text-anchor="middle" x="3188" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_make</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2330.5 3304.5,-2330.5 "/>
<text text-anchor="middle" x="3188" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer_model_name</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2307.5 3304.5,-2307.5 "/>
<text text-anchor="middle" x="3188" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_design_description</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2284.5 3304.5,-2284.5 "/>
<text text-anchor="middle" x="3188" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_info_id</text>
<polyline fill="none" stroke="#000000" points="3071.5,-2261.5 3304.5,-2261.5 "/>
<text text-anchor="middle" x="3188" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3304.5,-2238.5 3304.5,-2422.5 "/>
<text text-anchor="middle" x="3315" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- proteomic&#45;&gt;file -->
<g id="edge2" class="edge">
<title>proteomic&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M3071.779,-2238.4963C3036.84,-2195.2457 2993.4016,-2143.703 2951.5,-2100 2937.4698,-2085.3666 2922.6561,-2070.5451 2907.5357,-2055.8608"/>
<polygon fill="#000000" stroke="#000000" points="2909.7132,-2053.0978 2900.0904,-2048.6646 2904.8483,-2058.131 2909.7132,-2053.0978"/>
<text text-anchor="middle" x="2955.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- version -->
<g id="node17" class="node">
<title>version</title>
<path fill="none" stroke="#000000" d="M4108.5,-2842.5C4108.5,-2842.5 4324.5,-2842.5 4324.5,-2842.5 4330.5,-2842.5 4336.5,-2848.5 4336.5,-2854.5 4336.5,-2854.5 4336.5,-2968.5 4336.5,-2968.5 4336.5,-2974.5 4330.5,-2980.5 4324.5,-2980.5 4324.5,-2980.5 4108.5,-2980.5 4108.5,-2980.5 4102.5,-2980.5 4096.5,-2974.5 4096.5,-2968.5 4096.5,-2968.5 4096.5,-2854.5 4096.5,-2854.5 4096.5,-2848.5 4102.5,-2842.5 4108.5,-2842.5"/>
<text text-anchor="middle" x="4131" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="4165.5,-2842.5 4165.5,-2980.5 "/>
<text text-anchor="middle" x="4176" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4186.5,-2842.5 4186.5,-2980.5 "/>
<text text-anchor="middle" x="4251" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2957.5 4315.5,-2957.5 "/>
<text text-anchor="middle" x="4251" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_version</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2934.5 4315.5,-2934.5 "/>
<text text-anchor="middle" x="4251" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_version_id</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2911.5 4315.5,-2911.5 "/>
<text text-anchor="middle" x="4251" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">datetime</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2888.5 4315.5,-2888.5 "/>
<text text-anchor="middle" x="4251" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">description</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2865.5 4315.5,-2865.5 "/>
<text text-anchor="middle" x="4251" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_version</text>
<polyline fill="none" stroke="#000000" points="4315.5,-2842.5 4315.5,-2980.5 "/>
<text text-anchor="middle" x="4326" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
</g>
</svg>
</div>
