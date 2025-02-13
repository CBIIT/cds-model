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
<!-- NonDICOMPETimages -->
<g id="node1" class="node">
<title>NonDICOMPETimages</title>
<path fill="none" stroke="#000000" d="M12,-2865.5C12,-2865.5 661,-2865.5 661,-2865.5 667,-2865.5 673,-2871.5 673,-2877.5 673,-2877.5 673,-2945.5 673,-2945.5 673,-2951.5 667,-2957.5 661,-2957.5 661,-2957.5 12,-2957.5 12,-2957.5 6,-2957.5 0,-2951.5 0,-2945.5 0,-2945.5 0,-2877.5 0,-2877.5 0,-2871.5 6,-2865.5 12,-2865.5"/>
<text text-anchor="middle" x="91" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMPETimages</text>
<polyline fill="none" stroke="#000000" points="182,-2865.5 182,-2957.5 "/>
<text text-anchor="middle" x="192.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="203,-2865.5 203,-2957.5 "/>
<text text-anchor="middle" x="427.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMPETimages_id</text>
<polyline fill="none" stroke="#000000" points="203,-2934.5 652,-2934.5 "/>
<text text-anchor="middle" x="427.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">PETImagingAcquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="203,-2911.5 652,-2911.5 "/>
<text text-anchor="middle" x="427.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">Radiopharmaceutical_radionuclideCode</text>
<polyline fill="none" stroke="#000000" points="203,-2888.5 652,-2888.5 "/>
<text text-anchor="middle" x="427.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="652,-2865.5 652,-2957.5 "/>
<text text-anchor="middle" x="662.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image -->
<g id="node11" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M1909,-2135C1909,-2135 2274,-2135 2274,-2135 2280,-2135 2286,-2141 2286,-2147 2286,-2147 2286,-2514 2286,-2514 2286,-2520 2280,-2526 2274,-2526 2274,-2526 1909,-2526 1909,-2526 1903,-2526 1897,-2520 1897,-2514 1897,-2514 1897,-2147 1897,-2147 1897,-2141 1903,-2135 1909,-2135"/>
<text text-anchor="middle" x="1927" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="1957,-2135 1957,-2526 "/>
<text text-anchor="middle" x="1967.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1978,-2135 1978,-2526 "/>
<text text-anchor="middle" x="2121.5" y="-2510.8" font-family="Times,serif" font-size="14.00" fill="#000000">citation_or_DOI</text>
<polyline fill="none" stroke="#000000" points="1978,-2503 2265,-2503 "/>
<text text-anchor="middle" x="2121.5" y="-2487.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1978,-2480 2265,-2480 "/>
<text text-anchor="middle" x="2121.5" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_description</text>
<polyline fill="none" stroke="#000000" points="1978,-2457 2265,-2457 "/>
<text text-anchor="middle" x="2121.5" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_type</text>
<polyline fill="none" stroke="#000000" points="1978,-2434 2265,-2434 "/>
<text text-anchor="middle" x="2121.5" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_software</text>
<polyline fill="none" stroke="#000000" points="1978,-2411 2265,-2411 "/>
<text text-anchor="middle" x="2121.5" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1978,-2388 2265,-2388 "/>
<text text-anchor="middle" x="2121.5" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_manufacturer</text>
<polyline fill="none" stroke="#000000" points="1978,-2365 2265,-2365 "/>
<text text-anchor="middle" x="2121.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_model</text>
<polyline fill="none" stroke="#000000" points="1978,-2342 2265,-2342 "/>
<text text-anchor="middle" x="2121.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_protocol</text>
<polyline fill="none" stroke="#000000" points="1978,-2319 2265,-2319 "/>
<text text-anchor="middle" x="2121.5" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_software</text>
<polyline fill="none" stroke="#000000" points="1978,-2296 2265,-2296 "/>
<text text-anchor="middle" x="2121.5" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">license</text>
<polyline fill="none" stroke="#000000" points="1978,-2273 2265,-2273 "/>
<text text-anchor="middle" x="2121.5" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_offset</text>
<polyline fill="none" stroke="#000000" points="1978,-2250 2265,-2250 "/>
<text text-anchor="middle" x="2121.5" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_type</text>
<polyline fill="none" stroke="#000000" points="1978,-2227 2265,-2227 "/>
<text text-anchor="middle" x="2121.5" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">organ_or_tissue</text>
<polyline fill="none" stroke="#000000" points="1978,-2204 2265,-2204 "/>
<text text-anchor="middle" x="2121.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_typeCode</text>
<polyline fill="none" stroke="#000000" points="1978,-2181 2265,-2181 "/>
<text text-anchor="middle" x="2121.5" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1978,-2158 2265,-2158 "/>
<text text-anchor="middle" x="2121.5" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_link_id</text>
<polyline fill="none" stroke="#000000" points="2265,-2135 2265,-2526 "/>
<text text-anchor="middle" x="2275.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMPETimages&#45;&gt;image -->
<g id="edge8" class="edge">
<title>NonDICOMPETimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M375.0384,-2865.4437C433.8414,-2798.4185 552.7829,-2675.1305 681.5,-2612 1079.0772,-2417.0045 1602.7114,-2357.0827 1886.7876,-2338.6688"/>
<polygon fill="#000000" stroke="#000000" points="1887.0344,-2342.1603 1896.7914,-2338.0311 1886.589,-2335.1744 1887.0344,-2342.1603"/>
<text text-anchor="middle" x="785" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMradiologyAllModalities -->
<g id="node2" class="node">
<title>NonDICOMradiologyAllModalities</title>
<path fill="none" stroke="#000000" d="M703,-2693C703,-2693 1476,-2693 1476,-2693 1482,-2693 1488,-2699 1488,-2705 1488,-2705 1488,-3118 1488,-3118 1488,-3124 1482,-3130 1476,-3130 1476,-3130 703,-3130 703,-3130 697,-3130 691,-3124 691,-3118 691,-3118 691,-2705 691,-2705 691,-2699 697,-2693 703,-2693"/>
<text text-anchor="middle" x="822.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities</text>
<polyline fill="none" stroke="#000000" points="954,-2693 954,-3130 "/>
<text text-anchor="middle" x="964.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="975,-2693 975,-3130 "/>
<text text-anchor="middle" x="1221" y="-3114.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities_id</text>
<polyline fill="none" stroke="#000000" points="975,-3107 1467,-3107 "/>
<text text-anchor="middle" x="1221" y="-3091.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="975,-3084 1467,-3084 "/>
<text text-anchor="middle" x="1221" y="-3068.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_acquisitionTypeCode</text>
<polyline fill="none" stroke="#000000" points="975,-3061 1467,-3061 "/>
<text text-anchor="middle" x="1221" y="-3045.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_admittingDiagnosisCode</text>
<polyline fill="none" stroke="#000000" points="975,-3038 1467,-3038 "/>
<text text-anchor="middle" x="1221" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_algorithmCode</text>
<polyline fill="none" stroke="#000000" points="975,-3015 1467,-3015 "/>
<text text-anchor="middle" x="1221" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_bodyPositionCode</text>
<polyline fill="none" stroke="#000000" points="975,-2992 1467,-2992 "/>
<text text-anchor="middle" x="1221" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_cardiacSynchronizationTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="975,-2969 1467,-2969 "/>
<text text-anchor="middle" x="1221" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_dataCollectionDiameter</text>
<polyline fill="none" stroke="#000000" points="975,-2946 1467,-2946 "/>
<text text-anchor="middle" x="1221" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_description</text>
<polyline fill="none" stroke="#000000" points="975,-2923 1467,-2923 "/>
<text text-anchor="middle" x="1221" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_lossyImageCompressionIndicator</text>
<polyline fill="none" stroke="#000000" points="975,-2900 1467,-2900 "/>
<text text-anchor="middle" x="1221" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_nonAcquisitionModalitiesInStudyCode</text>
<polyline fill="none" stroke="#000000" points="975,-2877 1467,-2877 "/>
<text text-anchor="middle" x="1221" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_primaryAnatomicSiteCode</text>
<polyline fill="none" stroke="#000000" points="975,-2854 1467,-2854 "/>
<text text-anchor="middle" x="1221" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionDiameter</text>
<polyline fill="none" stroke="#000000" points="975,-2831 1467,-2831 "/>
<text text-anchor="middle" x="1221" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewHeight</text>
<polyline fill="none" stroke="#000000" points="975,-2808 1467,-2808 "/>
<text text-anchor="middle" x="1221" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewWidth</text>
<polyline fill="none" stroke="#000000" points="975,-2785 1467,-2785 "/>
<text text-anchor="middle" x="1221" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionInterval</text>
<polyline fill="none" stroke="#000000" points="975,-2762 1467,-2762 "/>
<text text-anchor="middle" x="1221" y="-2746.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_respiratoryMotionTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="975,-2739 1467,-2739 "/>
<text text-anchor="middle" x="1221" y="-2723.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_sliceThickness</text>
<polyline fill="none" stroke="#000000" points="975,-2716 1467,-2716 "/>
<text text-anchor="middle" x="1221" y="-2700.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_summary</text>
<polyline fill="none" stroke="#000000" points="1467,-2693 1467,-3130 "/>
<text text-anchor="middle" x="1477.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMradiologyAllModalities&#45;&gt;image -->
<g id="edge4" class="edge">
<title>NonDICOMradiologyAllModalities&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1372.1502,-2692.8805C1413.0394,-2664.406 1455.2571,-2636.6187 1496.5,-2612 1621.7726,-2537.2223 1770.0764,-2467.0182 1887.2842,-2415.4234"/>
<polygon fill="#000000" stroke="#000000" points="1888.988,-2418.4979 1896.7372,-2411.2728 1886.1738,-2412.0885 1888.988,-2418.4979"/>
<text text-anchor="middle" x="1576" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2161.5,-259.5C2161.5,-259.5 2477.5,-259.5 2477.5,-259.5 2483.5,-259.5 2489.5,-265.5 2489.5,-271.5 2489.5,-271.5 2489.5,-845.5 2489.5,-845.5 2489.5,-851.5 2483.5,-857.5 2477.5,-857.5 2477.5,-857.5 2161.5,-857.5 2161.5,-857.5 2155.5,-857.5 2149.5,-851.5 2149.5,-845.5 2149.5,-845.5 2149.5,-271.5 2149.5,-271.5 2149.5,-265.5 2155.5,-259.5 2161.5,-259.5"/>
<text text-anchor="middle" x="2177.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2205.5,-259.5 2205.5,-857.5 "/>
<text text-anchor="middle" x="2216" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2226.5,-259.5 2226.5,-857.5 "/>
<text text-anchor="middle" x="2347.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2226.5,-834.5 2468.5,-834.5 "/>
<text text-anchor="middle" x="2347.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2226.5,-811.5 2468.5,-811.5 "/>
<text text-anchor="middle" x="2347.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="2226.5,-788.5 2468.5,-788.5 "/>
<text text-anchor="middle" x="2347.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="2226.5,-765.5 2468.5,-765.5 "/>
<text text-anchor="middle" x="2347.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="2226.5,-742.5 2468.5,-742.5 "/>
<text text-anchor="middle" x="2347.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="2226.5,-719.5 2468.5,-719.5 "/>
<text text-anchor="middle" x="2347.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="2226.5,-696.5 2468.5,-696.5 "/>
<text text-anchor="middle" x="2347.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="2226.5,-673.5 2468.5,-673.5 "/>
<text text-anchor="middle" x="2347.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2226.5,-650.5 2468.5,-650.5 "/>
<text text-anchor="middle" x="2347.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2226.5,-627.5 2468.5,-627.5 "/>
<text text-anchor="middle" x="2347.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2226.5,-604.5 2468.5,-604.5 "/>
<text text-anchor="middle" x="2347.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2226.5,-581.5 2468.5,-581.5 "/>
<text text-anchor="middle" x="2347.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="2226.5,-558.5 2468.5,-558.5 "/>
<text text-anchor="middle" x="2347.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="2226.5,-535.5 2468.5,-535.5 "/>
<text text-anchor="middle" x="2347.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2226.5,-512.5 2468.5,-512.5 "/>
<text text-anchor="middle" x="2347.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="2226.5,-489.5 2468.5,-489.5 "/>
<text text-anchor="middle" x="2347.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2226.5,-466.5 2468.5,-466.5 "/>
<text text-anchor="middle" x="2347.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="2226.5,-443.5 2468.5,-443.5 "/>
<text text-anchor="middle" x="2347.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="2226.5,-420.5 2468.5,-420.5 "/>
<text text-anchor="middle" x="2347.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2226.5,-397.5 2468.5,-397.5 "/>
<text text-anchor="middle" x="2347.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="2226.5,-374.5 2468.5,-374.5 "/>
<text text-anchor="middle" x="2347.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2226.5,-351.5 2468.5,-351.5 "/>
<text text-anchor="middle" x="2347.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2226.5,-328.5 2468.5,-328.5 "/>
<text text-anchor="middle" x="2347.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2226.5,-305.5 2468.5,-305.5 "/>
<text text-anchor="middle" x="2347.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="2226.5,-282.5 2468.5,-282.5 "/>
<text text-anchor="middle" x="2347.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="2468.5,-259.5 2468.5,-857.5 "/>
<text text-anchor="middle" x="2479" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node13" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M2165.5,-.5C2165.5,-.5 2473.5,-.5 2473.5,-.5 2479.5,-.5 2485.5,-6.5 2485.5,-12.5 2485.5,-12.5 2485.5,-195.5 2485.5,-195.5 2485.5,-201.5 2479.5,-207.5 2473.5,-207.5 2473.5,-207.5 2165.5,-207.5 2165.5,-207.5 2159.5,-207.5 2153.5,-201.5 2153.5,-195.5 2153.5,-195.5 2153.5,-12.5 2153.5,-12.5 2153.5,-6.5 2159.5,-.5 2165.5,-.5"/>
<text text-anchor="middle" x="2192.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="2231.5,-.5 2231.5,-207.5 "/>
<text text-anchor="middle" x="2242" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2252.5,-.5 2252.5,-207.5 "/>
<text text-anchor="middle" x="2358.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2252.5,-184.5 2464.5,-184.5 "/>
<text text-anchor="middle" x="2358.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2252.5,-161.5 2464.5,-161.5 "/>
<text text-anchor="middle" x="2358.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="2252.5,-138.5 2464.5,-138.5 "/>
<text text-anchor="middle" x="2358.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="2252.5,-115.5 2464.5,-115.5 "/>
<text text-anchor="middle" x="2358.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="2252.5,-92.5 2464.5,-92.5 "/>
<text text-anchor="middle" x="2358.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="2252.5,-69.5 2464.5,-69.5 "/>
<text text-anchor="middle" x="2358.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="2252.5,-46.5 2464.5,-46.5 "/>
<text text-anchor="middle" x="2358.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="2252.5,-23.5 2464.5,-23.5 "/>
<text text-anchor="middle" x="2358.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="2464.5,-.5 2464.5,-207.5 "/>
<text text-anchor="middle" x="2475" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge11" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2319.5,-259.4595C2319.5,-244.999 2319.5,-230.9707 2319.5,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="2323.0001,-217.5945 2319.5,-207.5945 2316.0001,-217.5946 2323.0001,-217.5945"/>
<text text-anchor="middle" x="2361" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- NonDICOMpathologyImages -->
<g id="node4" class="node">
<title>NonDICOMpathologyImages</title>
<path fill="none" stroke="#000000" d="M1518,-2785C1518,-2785 2005,-2785 2005,-2785 2011,-2785 2017,-2791 2017,-2797 2017,-2797 2017,-3026 2017,-3026 2017,-3032 2011,-3038 2005,-3038 2005,-3038 1518,-3038 1518,-3038 1512,-3038 1506,-3032 1506,-3026 1506,-3026 1506,-2797 1506,-2797 1506,-2791 1512,-2785 1518,-2785"/>
<text text-anchor="middle" x="1618" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages</text>
<polyline fill="none" stroke="#000000" points="1730,-2785 1730,-3038 "/>
<text text-anchor="middle" x="1740.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1751,-2785 1751,-3038 "/>
<text text-anchor="middle" x="1873.5" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages_id</text>
<polyline fill="none" stroke="#000000" points="1751,-3015 1996,-3015 "/>
<text text-anchor="middle" x="1873.5" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="1751,-2992 1996,-2992 "/>
<text text-anchor="middle" x="1873.5" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1751,-2969 1996,-2969 "/>
<text text-anchor="middle" x="1873.5" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="1751,-2946 1996,-2946 "/>
<text text-anchor="middle" x="1873.5" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="1751,-2923 1996,-2923 "/>
<text text-anchor="middle" x="1873.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="1751,-2900 1996,-2900 "/>
<text text-anchor="middle" x="1873.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="1751,-2877 1996,-2877 "/>
<text text-anchor="middle" x="1873.5" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">objective</text>
<polyline fill="none" stroke="#000000" points="1751,-2854 1996,-2854 "/>
<text text-anchor="middle" x="1873.5" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="1751,-2831 1996,-2831 "/>
<text text-anchor="middle" x="1873.5" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_fixative</text>
<polyline fill="none" stroke="#000000" points="1751,-2808 1996,-2808 "/>
<text text-anchor="middle" x="1873.5" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_type</text>
<polyline fill="none" stroke="#000000" points="1996,-2785 1996,-3038 "/>
<text text-anchor="middle" x="2006.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMpathologyImages&#45;&gt;image -->
<g id="edge6" class="edge">
<title>NonDICOMpathologyImages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1833.5121,-2784.715C1874.9988,-2711.6732 1928.1306,-2618.1291 1975.3829,-2534.9364"/>
<polygon fill="#000000" stroke="#000000" points="1978.4813,-2536.5682 1980.3768,-2526.1443 1972.3945,-2533.111 1978.4813,-2536.5682"/>
<text text-anchor="middle" x="1979" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- proteomic -->
<g id="node5" class="node">
<title>proteomic</title>
<path fill="none" stroke="#000000" d="M2316.5,-2238.5C2316.5,-2238.5 2656.5,-2238.5 2656.5,-2238.5 2662.5,-2238.5 2668.5,-2244.5 2668.5,-2250.5 2668.5,-2250.5 2668.5,-2410.5 2668.5,-2410.5 2668.5,-2416.5 2662.5,-2422.5 2656.5,-2422.5 2656.5,-2422.5 2316.5,-2422.5 2316.5,-2422.5 2310.5,-2422.5 2304.5,-2416.5 2304.5,-2410.5 2304.5,-2410.5 2304.5,-2250.5 2304.5,-2250.5 2304.5,-2244.5 2310.5,-2238.5 2316.5,-2238.5"/>
<text text-anchor="middle" x="2349" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic</text>
<polyline fill="none" stroke="#000000" points="2393.5,-2238.5 2393.5,-2422.5 "/>
<text text-anchor="middle" x="2404" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2414.5,-2238.5 2414.5,-2422.5 "/>
<text text-anchor="middle" x="2531" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2399.5 2647.5,-2399.5 "/>
<text text-anchor="middle" x="2531" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fractions</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2376.5 2647.5,-2376.5 "/>
<text text-anchor="middle" x="2531" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2353.5 2647.5,-2353.5 "/>
<text text-anchor="middle" x="2531" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_make</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2330.5 2647.5,-2330.5 "/>
<text text-anchor="middle" x="2531" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer_model_name</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2307.5 2647.5,-2307.5 "/>
<text text-anchor="middle" x="2531" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_design_description</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2284.5 2647.5,-2284.5 "/>
<text text-anchor="middle" x="2531" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2414.5,-2261.5 2647.5,-2261.5 "/>
<text text-anchor="middle" x="2531" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2647.5,-2238.5 2647.5,-2422.5 "/>
<text text-anchor="middle" x="2658" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node8" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2296.5,-1703.5C2296.5,-1703.5 2676.5,-1703.5 2676.5,-1703.5 2682.5,-1703.5 2688.5,-1709.5 2688.5,-1715.5 2688.5,-1715.5 2688.5,-2036.5 2688.5,-2036.5 2688.5,-2042.5 2682.5,-2048.5 2676.5,-2048.5 2676.5,-2048.5 2296.5,-2048.5 2296.5,-2048.5 2290.5,-2048.5 2284.5,-2042.5 2284.5,-2036.5 2284.5,-2036.5 2284.5,-1715.5 2284.5,-1715.5 2284.5,-1709.5 2290.5,-1703.5 2296.5,-1703.5"/>
<text text-anchor="middle" x="2304" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2323.5,-1703.5 2323.5,-2048.5 "/>
<text text-anchor="middle" x="2334" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2344.5,-1703.5 2344.5,-2048.5 "/>
<text text-anchor="middle" x="2506" y="-2033.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2344.5,-2025.5 2667.5,-2025.5 "/>
<text text-anchor="middle" x="2506" y="-2010.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2344.5,-2002.5 2667.5,-2002.5 "/>
<text text-anchor="middle" x="2506" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1979.5 2667.5,-1979.5 "/>
<text text-anchor="middle" x="2506" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1956.5 2667.5,-1956.5 "/>
<text text-anchor="middle" x="2506" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1933.5 2667.5,-1933.5 "/>
<text text-anchor="middle" x="2506" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1910.5 2667.5,-1910.5 "/>
<text text-anchor="middle" x="2506" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1887.5 2667.5,-1887.5 "/>
<text text-anchor="middle" x="2506" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1864.5 2667.5,-1864.5 "/>
<text text-anchor="middle" x="2506" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1841.5 2667.5,-1841.5 "/>
<text text-anchor="middle" x="2506" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1818.5 2667.5,-1818.5 "/>
<text text-anchor="middle" x="2506" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1795.5 2667.5,-1795.5 "/>
<text text-anchor="middle" x="2506" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_supplementary_file</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1772.5 2667.5,-1772.5 "/>
<text text-anchor="middle" x="2506" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1749.5 2667.5,-1749.5 "/>
<text text-anchor="middle" x="2506" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_datetime</text>
<polyline fill="none" stroke="#000000" points="2344.5,-1726.5 2667.5,-1726.5 "/>
<text text-anchor="middle" x="2506" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="2667.5,-1703.5 2667.5,-2048.5 "/>
<text text-anchor="middle" x="2678" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- proteomic&#45;&gt;file -->
<g id="edge18" class="edge">
<title>proteomic&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2486.5,-2238.2514C2486.5,-2186.6364 2486.5,-2120.446 2486.5,-2058.7976"/>
<polygon fill="#000000" stroke="#000000" points="2490.0001,-2058.5472 2486.5,-2048.5472 2483.0001,-2058.5472 2490.0001,-2058.5472"/>
<text text-anchor="middle" x="2508.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- NonDICOMMRimages -->
<g id="node6" class="node">
<title>NonDICOMMRimages</title>
<path fill="none" stroke="#000000" d="M2047,-2693C2047,-2693 2796,-2693 2796,-2693 2802,-2693 2808,-2699 2808,-2705 2808,-2705 2808,-3118 2808,-3118 2808,-3124 2802,-3130 2796,-3130 2796,-3130 2047,-3130 2047,-3130 2041,-3130 2035,-3124 2035,-3118 2035,-3118 2035,-2705 2035,-2705 2035,-2699 2041,-2693 2047,-2693"/>
<text text-anchor="middle" x="2123.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages</text>
<polyline fill="none" stroke="#000000" points="2212,-2693 2212,-3130 "/>
<text text-anchor="middle" x="2222.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2233,-2693 2233,-3130 "/>
<text text-anchor="middle" x="2510" y="-3114.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="2233,-3107 2787,-3107 "/>
<text text-anchor="middle" x="2510" y="-3091.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="2233,-3084 2787,-3084 "/>
<text text-anchor="middle" x="2510" y="-3068.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="2233,-3061 2787,-3061 "/>
<text text-anchor="middle" x="2510" y="-3045.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="2233,-3038 2787,-3038 "/>
<text text-anchor="middle" x="2510" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="2233,-3015 2787,-3015 "/>
<text text-anchor="middle" x="2510" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="2233,-2992 2787,-2992 "/>
<text text-anchor="middle" x="2510" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="2233,-2969 2787,-2969 "/>
<text text-anchor="middle" x="2510" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="2233,-2946 2787,-2946 "/>
<text text-anchor="middle" x="2510" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="2233,-2923 2787,-2923 "/>
<text text-anchor="middle" x="2510" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="2233,-2900 2787,-2900 "/>
<text text-anchor="middle" x="2510" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="2233,-2877 2787,-2877 "/>
<text text-anchor="middle" x="2510" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="2233,-2854 2787,-2854 "/>
<text text-anchor="middle" x="2510" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="2233,-2831 2787,-2831 "/>
<text text-anchor="middle" x="2510" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="2233,-2808 2787,-2808 "/>
<text text-anchor="middle" x="2510" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="2233,-2785 2787,-2785 "/>
<text text-anchor="middle" x="2510" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_timeOfFlightContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="2233,-2762 2787,-2762 "/>
<text text-anchor="middle" x="2510" y="-2746.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageReconstructionProtocolElement_complexImageComponentCode</text>
<polyline fill="none" stroke="#000000" points="2233,-2739 2787,-2739 "/>
<text text-anchor="middle" x="2510" y="-2723.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages_id</text>
<polyline fill="none" stroke="#000000" points="2233,-2716 2787,-2716 "/>
<text text-anchor="middle" x="2510" y="-2700.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2787,-2693 2787,-3130 "/>
<text text-anchor="middle" x="2797.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMMRimages&#45;&gt;image -->
<g id="edge7" class="edge">
<title>NonDICOMMRimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2297.2114,-2692.6767C2267.8501,-2640.9831 2236.6543,-2586.0596 2207.6682,-2535.0264"/>
<polygon fill="#000000" stroke="#000000" points="2210.6427,-2533.1766 2202.6605,-2526.2099 2204.556,-2536.6338 2210.6427,-2533.1766"/>
<text text-anchor="middle" x="2270" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMCTimages -->
<g id="node7" class="node">
<title>NonDICOMCTimages</title>
<path fill="none" stroke="#000000" d="M2838,-2773.5C2838,-2773.5 3559,-2773.5 3559,-2773.5 3565,-2773.5 3571,-2779.5 3571,-2785.5 3571,-2785.5 3571,-3037.5 3571,-3037.5 3571,-3043.5 3565,-3049.5 3559,-3049.5 3559,-3049.5 2838,-3049.5 2838,-3049.5 2832,-3049.5 2826,-3043.5 2826,-3037.5 2826,-3037.5 2826,-2785.5 2826,-2785.5 2826,-2779.5 2832,-2773.5 2838,-2773.5"/>
<text text-anchor="middle" x="2912.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages</text>
<polyline fill="none" stroke="#000000" points="2999,-2773.5 2999,-3049.5 "/>
<text text-anchor="middle" x="3009.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3020,-2773.5 3020,-3049.5 "/>
<text text-anchor="middle" x="3285" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="3020,-3026.5 3550,-3026.5 "/>
<text text-anchor="middle" x="3285" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="3020,-3003.5 3550,-3003.5 "/>
<text text-anchor="middle" x="3285" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="3020,-2980.5 3550,-2980.5 "/>
<text text-anchor="middle" x="3285" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="3020,-2957.5 3550,-2957.5 "/>
<text text-anchor="middle" x="3285" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="3020,-2934.5 3550,-2934.5 "/>
<text text-anchor="middle" x="3285" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="3020,-2911.5 3550,-2911.5 "/>
<text text-anchor="middle" x="3285" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="3020,-2888.5 3550,-2888.5 "/>
<text text-anchor="middle" x="3285" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="3020,-2865.5 3550,-2865.5 "/>
<text text-anchor="middle" x="3285" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="3020,-2842.5 3550,-2842.5 "/>
<text text-anchor="middle" x="3285" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="3020,-2819.5 3550,-2819.5 "/>
<text text-anchor="middle" x="3285" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages_id</text>
<polyline fill="none" stroke="#000000" points="3020,-2796.5 3550,-2796.5 "/>
<text text-anchor="middle" x="3285" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3550,-2773.5 3550,-3049.5 "/>
<text text-anchor="middle" x="3560.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMCTimages&#45;&gt;image -->
<g id="edge5" class="edge">
<title>NonDICOMCTimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3062.1305,-2773.3881C2994.1772,-2713.2776 2907.2375,-2648.3736 2816.5,-2612 2600.543,-2525.4302 2502.729,-2666.7728 2295.5,-2561 2279.9825,-2553.0796 2265.1089,-2543.4383 2250.9667,-2532.6429"/>
<polygon fill="#000000" stroke="#000000" points="2252.7483,-2529.5911 2242.7252,-2526.1576 2248.4194,-2535.0922 2252.7483,-2529.5911"/>
<text text-anchor="middle" x="2788" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2344.7015,-1703.1958C2335.8475,-1686.5708 2328.2154,-1669.4005 2322.5,-1652 2238.9196,-1397.5392 2246.5504,-1091.4367 2270.2437,-867.8947"/>
<polygon fill="#000000" stroke="#000000" points="2273.7565,-867.9639 2271.3473,-857.6466 2266.7967,-867.2144 2273.7565,-867.9639"/>
<text text-anchor="middle" x="2286" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge10" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2688.6809,-1900.8839C2699.8527,-1894.8327 2706.5,-1886.5381 2706.5,-1876 2706.5,-1868.4258 2703.066,-1862.0105 2696.9862,-1856.7542"/>
<polygon fill="#000000" stroke="#000000" points="2698.9204,-1853.8369 2688.6809,-1851.1161 2694.9887,-1859.6285 2698.9204,-1853.8369"/>
<text text-anchor="middle" x="2764" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2343.5,-1283.5C2343.5,-1283.5 2629.5,-1283.5 2629.5,-1283.5 2635.5,-1283.5 2641.5,-1289.5 2641.5,-1295.5 2641.5,-1295.5 2641.5,-1501.5 2641.5,-1501.5 2641.5,-1507.5 2635.5,-1513.5 2629.5,-1513.5 2629.5,-1513.5 2343.5,-1513.5 2343.5,-1513.5 2337.5,-1513.5 2331.5,-1507.5 2331.5,-1501.5 2331.5,-1501.5 2331.5,-1295.5 2331.5,-1295.5 2331.5,-1289.5 2337.5,-1283.5 2343.5,-1283.5"/>
<text text-anchor="middle" x="2365.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2399.5,-1283.5 2399.5,-1513.5 "/>
<text text-anchor="middle" x="2410" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2420.5,-1283.5 2420.5,-1513.5 "/>
<text text-anchor="middle" x="2520.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1490.5 2620.5,-1490.5 "/>
<text text-anchor="middle" x="2520.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1467.5 2620.5,-1467.5 "/>
<text text-anchor="middle" x="2520.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1444.5 2620.5,-1444.5 "/>
<text text-anchor="middle" x="2520.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1421.5 2620.5,-1421.5 "/>
<text text-anchor="middle" x="2520.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1398.5 2620.5,-1398.5 "/>
<text text-anchor="middle" x="2520.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1375.5 2620.5,-1375.5 "/>
<text text-anchor="middle" x="2520.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1352.5 2620.5,-1352.5 "/>
<text text-anchor="middle" x="2520.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1329.5 2620.5,-1329.5 "/>
<text text-anchor="middle" x="2520.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2420.5,-1306.5 2620.5,-1306.5 "/>
<text text-anchor="middle" x="2520.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="2620.5,-1283.5 2620.5,-1513.5 "/>
<text text-anchor="middle" x="2631" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2486.5,-1703.274C2486.5,-1643.9501 2486.5,-1578.7236 2486.5,-1523.8875"/>
<polygon fill="#000000" stroke="#000000" points="2490.0001,-1523.7731 2486.5,-1513.7731 2483.0001,-1523.7731 2490.0001,-1523.7731"/>
<text text-anchor="middle" x="2533" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- participant -->
<g id="node17" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2538.5,-909.5C2538.5,-909.5 2816.5,-909.5 2816.5,-909.5 2822.5,-909.5 2828.5,-915.5 2828.5,-921.5 2828.5,-921.5 2828.5,-1081.5 2828.5,-1081.5 2828.5,-1087.5 2822.5,-1093.5 2816.5,-1093.5 2816.5,-1093.5 2538.5,-1093.5 2538.5,-1093.5 2532.5,-1093.5 2526.5,-1087.5 2526.5,-1081.5 2526.5,-1081.5 2526.5,-921.5 2526.5,-921.5 2526.5,-915.5 2532.5,-909.5 2538.5,-909.5"/>
<text text-anchor="middle" x="2574.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2622.5,-909.5 2622.5,-1093.5 "/>
<text text-anchor="middle" x="2633" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2643.5,-909.5 2643.5,-1093.5 "/>
<text text-anchor="middle" x="2725.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2643.5,-1070.5 2807.5,-1070.5 "/>
<text text-anchor="middle" x="2725.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="2643.5,-1047.5 2807.5,-1047.5 "/>
<text text-anchor="middle" x="2725.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2643.5,-1024.5 2807.5,-1024.5 "/>
<text text-anchor="middle" x="2725.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2643.5,-1001.5 2807.5,-1001.5 "/>
<text text-anchor="middle" x="2725.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2643.5,-978.5 2807.5,-978.5 "/>
<text text-anchor="middle" x="2725.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2643.5,-955.5 2807.5,-955.5 "/>
<text text-anchor="middle" x="2725.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="2643.5,-932.5 2807.5,-932.5 "/>
<text text-anchor="middle" x="2725.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="2807.5,-909.5 2807.5,-1093.5 "/>
<text text-anchor="middle" x="2818" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2627.3896,-1703.2749C2636.4767,-1686.6015 2644.4089,-1669.4003 2650.5,-1652 2684.8507,-1553.872 2683.7751,-1260.8664 2680.4496,-1103.7318"/>
<polygon fill="#000000" stroke="#000000" points="2683.9455,-1103.5027 2680.2276,-1093.5817 2676.9472,-1103.6558 2683.9455,-1103.5027"/>
<text text-anchor="middle" x="2733" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2502.2179,-1283.4106C2513.2835,-1228.7285 2531.8115,-1164.0987 2562.5,-1112 2564.441,-1108.7048 2566.5074,-1105.4434 2568.6799,-1102.2219"/>
<polygon fill="#000000" stroke="#000000" points="2571.7301,-1103.9716 2574.6655,-1093.7915 2566.0224,-1099.9192 2571.7301,-1103.9716"/>
<text text-anchor="middle" x="2613" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
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
<g id="edge9" class="edge">
<title>MultiplexMicroscopy&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3588.6923,-2616.1837C3585.9802,-2614.7454 3583.2493,-2613.3502 3580.5,-2612 3429.559,-2537.8746 2992.5333,-2585.526 2824.5,-2579 2765.7325,-2576.7176 2348.706,-2586.0589 2295.5,-2561 2279.0815,-2553.2672 2263.429,-2543.5296 2248.6282,-2532.4552"/>
<polygon fill="#000000" stroke="#000000" points="2250.5467,-2529.5144 2240.4937,-2526.1694 2246.2665,-2535.0534 2250.5467,-2529.5144"/>
<text text-anchor="middle" x="3559" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge16" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2261.5947,-2134.7834C2284.2258,-2108.7433 2307.3465,-2082.1399 2329.7369,-2056.3768"/>
<polygon fill="#000000" stroke="#000000" points="2332.427,-2058.617 2336.345,-2048.7733 2327.1435,-2054.0252 2332.427,-2058.617"/>
<text text-anchor="middle" x="2335.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- genomic_info -->
<g id="node12" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M2699,-2100.5C2699,-2100.5 3152,-2100.5 3152,-2100.5 3158,-2100.5 3164,-2106.5 3164,-2112.5 3164,-2112.5 3164,-2548.5 3164,-2548.5 3164,-2554.5 3158,-2560.5 3152,-2560.5 3152,-2560.5 2699,-2560.5 2699,-2560.5 2693,-2560.5 2687,-2554.5 2687,-2548.5 2687,-2548.5 2687,-2112.5 2687,-2112.5 2687,-2106.5 2693,-2100.5 2699,-2100.5"/>
<text text-anchor="middle" x="2743" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="2799,-2100.5 2799,-2560.5 "/>
<text text-anchor="middle" x="2809.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2820,-2100.5 2820,-2560.5 "/>
<text text-anchor="middle" x="2981.5" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2820,-2537.5 3143,-2537.5 "/>
<text text-anchor="middle" x="2981.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="2820,-2514.5 3143,-2514.5 "/>
<text text-anchor="middle" x="2981.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2820,-2491.5 3143,-2491.5 "/>
<text text-anchor="middle" x="2981.5" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2820,-2468.5 3143,-2468.5 "/>
<text text-anchor="middle" x="2981.5" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2820,-2445.5 3143,-2445.5 "/>
<text text-anchor="middle" x="2981.5" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2820,-2422.5 3143,-2422.5 "/>
<text text-anchor="middle" x="2981.5" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2820,-2399.5 3143,-2399.5 "/>
<text text-anchor="middle" x="2981.5" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2820,-2376.5 3143,-2376.5 "/>
<text text-anchor="middle" x="2981.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2820,-2353.5 3143,-2353.5 "/>
<text text-anchor="middle" x="2981.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2820,-2330.5 3143,-2330.5 "/>
<text text-anchor="middle" x="2981.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2820,-2307.5 3143,-2307.5 "/>
<text text-anchor="middle" x="2981.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="2820,-2284.5 3143,-2284.5 "/>
<text text-anchor="middle" x="2981.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="2820,-2261.5 3143,-2261.5 "/>
<text text-anchor="middle" x="2981.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2820,-2238.5 3143,-2238.5 "/>
<text text-anchor="middle" x="2981.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2820,-2215.5 3143,-2215.5 "/>
<text text-anchor="middle" x="2981.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2820,-2192.5 3143,-2192.5 "/>
<text text-anchor="middle" x="2981.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2820,-2169.5 3143,-2169.5 "/>
<text text-anchor="middle" x="2981.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2820,-2146.5 3143,-2146.5 "/>
<text text-anchor="middle" x="2981.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2820,-2123.5 3143,-2123.5 "/>
<text text-anchor="middle" x="2981.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="3143,-2100.5 3143,-2560.5 "/>
<text text-anchor="middle" x="3153.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge17" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2703.1063,-2100.2541C2688.8137,-2085.4569 2674.5375,-2070.6766 2660.5201,-2056.1643"/>
<polygon fill="#000000" stroke="#000000" points="2662.6796,-2053.3621 2653.2147,-2048.601 2657.6447,-2058.2253 2662.6796,-2053.3621"/>
<text text-anchor="middle" x="2702.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2808.5,-1145.5C2808.5,-1145.5 3182.5,-1145.5 3182.5,-1145.5 3188.5,-1145.5 3194.5,-1151.5 3194.5,-1157.5 3194.5,-1157.5 3194.5,-1639.5 3194.5,-1639.5 3194.5,-1645.5 3188.5,-1651.5 3182.5,-1651.5 3182.5,-1651.5 2808.5,-1651.5 2808.5,-1651.5 2802.5,-1651.5 2796.5,-1645.5 2796.5,-1639.5 2796.5,-1639.5 2796.5,-1157.5 2796.5,-1157.5 2796.5,-1151.5 2802.5,-1145.5 2808.5,-1145.5"/>
<text text-anchor="middle" x="2838.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2880.5,-1145.5 2880.5,-1651.5 "/>
<text text-anchor="middle" x="2891" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2901.5,-1145.5 2901.5,-1651.5 "/>
<text text-anchor="middle" x="3037.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1628.5 3173.5,-1628.5 "/>
<text text-anchor="middle" x="3037.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1605.5 3173.5,-1605.5 "/>
<text text-anchor="middle" x="3037.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1582.5 3173.5,-1582.5 "/>
<text text-anchor="middle" x="3037.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1559.5 3173.5,-1559.5 "/>
<text text-anchor="middle" x="3037.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1536.5 3173.5,-1536.5 "/>
<text text-anchor="middle" x="3037.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1513.5 3173.5,-1513.5 "/>
<text text-anchor="middle" x="3037.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1490.5 3173.5,-1490.5 "/>
<text text-anchor="middle" x="3037.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1467.5 3173.5,-1467.5 "/>
<text text-anchor="middle" x="3037.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1444.5 3173.5,-1444.5 "/>
<text text-anchor="middle" x="3037.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1421.5 3173.5,-1421.5 "/>
<text text-anchor="middle" x="3037.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1398.5 3173.5,-1398.5 "/>
<text text-anchor="middle" x="3037.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1375.5 3173.5,-1375.5 "/>
<text text-anchor="middle" x="3037.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1352.5 3173.5,-1352.5 "/>
<text text-anchor="middle" x="3037.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1329.5 3173.5,-1329.5 "/>
<text text-anchor="middle" x="3037.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1306.5 3173.5,-1306.5 "/>
<text text-anchor="middle" x="3037.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1283.5 3173.5,-1283.5 "/>
<text text-anchor="middle" x="3037.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1260.5 3173.5,-1260.5 "/>
<text text-anchor="middle" x="3037.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1237.5 3173.5,-1237.5 "/>
<text text-anchor="middle" x="3037.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1214.5 3173.5,-1214.5 "/>
<text text-anchor="middle" x="3037.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1191.5 3173.5,-1191.5 "/>
<text text-anchor="middle" x="3037.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2901.5,-1168.5 3173.5,-1168.5 "/>
<text text-anchor="middle" x="3037.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3173.5,-1145.5 3173.5,-1651.5 "/>
<text text-anchor="middle" x="3184" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2796.3637,-1149.8927C2782.9336,-1133.1262 2769.9123,-1116.87 2757.7182,-1101.6466"/>
<polygon fill="#000000" stroke="#000000" points="2760.4026,-1099.3994 2751.4191,-1093.7827 2754.9392,-1103.7757 2760.4026,-1099.3994"/>
<text text-anchor="middle" x="2822" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- version -->
<g id="node15" class="node">
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
<!-- treatment -->
<g id="node16" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M3224.5,-1329.5C3224.5,-1329.5 3486.5,-1329.5 3486.5,-1329.5 3492.5,-1329.5 3498.5,-1335.5 3498.5,-1341.5 3498.5,-1341.5 3498.5,-1455.5 3498.5,-1455.5 3498.5,-1461.5 3492.5,-1467.5 3486.5,-1467.5 3486.5,-1467.5 3224.5,-1467.5 3224.5,-1467.5 3218.5,-1467.5 3212.5,-1461.5 3212.5,-1455.5 3212.5,-1455.5 3212.5,-1341.5 3212.5,-1341.5 3212.5,-1335.5 3218.5,-1329.5 3224.5,-1329.5"/>
<text text-anchor="middle" x="3257" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="3301.5,-1329.5 3301.5,-1467.5 "/>
<text text-anchor="middle" x="3312" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3322.5,-1329.5 3322.5,-1467.5 "/>
<text text-anchor="middle" x="3400" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3322.5,-1444.5 3477.5,-1444.5 "/>
<text text-anchor="middle" x="3400" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="3322.5,-1421.5 3477.5,-1421.5 "/>
<text text-anchor="middle" x="3400" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="3322.5,-1398.5 3477.5,-1398.5 "/>
<text text-anchor="middle" x="3400" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="3322.5,-1375.5 3477.5,-1375.5 "/>
<text text-anchor="middle" x="3400" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="3322.5,-1352.5 3477.5,-1352.5 "/>
<text text-anchor="middle" x="3400" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3477.5,-1329.5 3477.5,-1467.5 "/>
<text text-anchor="middle" x="3488" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3331.0497,-1329.451C3307.1808,-1271.8525 3265.3583,-1191.8787 3203.5,-1145 3146.0929,-1101.4947 2971.0398,-1059.0001 2838.5104,-1031.6905"/>
<polygon fill="#000000" stroke="#000000" points="2839.1421,-1028.2473 2828.6431,-1029.669 2837.7371,-1035.1049 2839.1421,-1028.2473"/>
<text text-anchor="middle" x="3216" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2603.1048,-909.4411C2571.7641,-870.6592 2533.8324,-823.7214 2496.0465,-776.964"/>
<polygon fill="#000000" stroke="#000000" points="2498.7461,-774.736 2489.7384,-769.1581 2493.3016,-779.1358 2498.7461,-774.736"/>
<text text-anchor="middle" x="2612" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
</g>
</svg>
</div>
