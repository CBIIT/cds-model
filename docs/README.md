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
<svg width="4345pt" height="3196pt"
 viewBox="0.00 0.00 4344.50 3196.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3192)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3192 4340.5,-3192 4340.5,4 -4,4"/>
<!-- NonDICOMPETimages -->
<g id="node1" class="node">
<title>NonDICOMPETimages</title>
<path fill="none" stroke="#000000" d="M12,-2854C12,-2854 661,-2854 661,-2854 667,-2854 673,-2860 673,-2866 673,-2866 673,-2911 673,-2911 673,-2917 667,-2923 661,-2923 661,-2923 12,-2923 12,-2923 6,-2923 0,-2917 0,-2911 0,-2911 0,-2866 0,-2866 0,-2860 6,-2854 12,-2854"/>
<text text-anchor="middle" x="91" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMPETimages</text>
<polyline fill="none" stroke="#000000" points="182,-2854 182,-2923 "/>
<text text-anchor="middle" x="192.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="203,-2854 203,-2923 "/>
<text text-anchor="middle" x="427.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMPETimages_id</text>
<polyline fill="none" stroke="#000000" points="203,-2900 652,-2900 "/>
<text text-anchor="middle" x="427.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">PETImagingAcquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="203,-2877 652,-2877 "/>
<text text-anchor="middle" x="427.5" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">Radiopharmaceutical_radionuclideCode</text>
<polyline fill="none" stroke="#000000" points="652,-2854 652,-2923 "/>
<text text-anchor="middle" x="662.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image -->
<g id="node13" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M1776,-2112C1776,-2112 2141,-2112 2141,-2112 2147,-2112 2153,-2118 2153,-2124 2153,-2124 2153,-2468 2153,-2468 2153,-2474 2147,-2480 2141,-2480 2141,-2480 1776,-2480 1776,-2480 1770,-2480 1764,-2474 1764,-2468 1764,-2468 1764,-2124 1764,-2124 1764,-2118 1770,-2112 1776,-2112"/>
<text text-anchor="middle" x="1794" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="1824,-2112 1824,-2480 "/>
<text text-anchor="middle" x="1834.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1845,-2112 1845,-2480 "/>
<text text-anchor="middle" x="1988.5" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">citation_or_DOI</text>
<polyline fill="none" stroke="#000000" points="1845,-2457 2132,-2457 "/>
<text text-anchor="middle" x="1988.5" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_description</text>
<polyline fill="none" stroke="#000000" points="1845,-2434 2132,-2434 "/>
<text text-anchor="middle" x="1988.5" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_type</text>
<polyline fill="none" stroke="#000000" points="1845,-2411 2132,-2411 "/>
<text text-anchor="middle" x="1988.5" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_software</text>
<polyline fill="none" stroke="#000000" points="1845,-2388 2132,-2388 "/>
<text text-anchor="middle" x="1988.5" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1845,-2365 2132,-2365 "/>
<text text-anchor="middle" x="1988.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_manufacturer</text>
<polyline fill="none" stroke="#000000" points="1845,-2342 2132,-2342 "/>
<text text-anchor="middle" x="1988.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_model</text>
<polyline fill="none" stroke="#000000" points="1845,-2319 2132,-2319 "/>
<text text-anchor="middle" x="1988.5" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_protocol</text>
<polyline fill="none" stroke="#000000" points="1845,-2296 2132,-2296 "/>
<text text-anchor="middle" x="1988.5" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_software</text>
<polyline fill="none" stroke="#000000" points="1845,-2273 2132,-2273 "/>
<text text-anchor="middle" x="1988.5" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">license</text>
<polyline fill="none" stroke="#000000" points="1845,-2250 2132,-2250 "/>
<text text-anchor="middle" x="1988.5" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_offset</text>
<polyline fill="none" stroke="#000000" points="1845,-2227 2132,-2227 "/>
<text text-anchor="middle" x="1988.5" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_type</text>
<polyline fill="none" stroke="#000000" points="1845,-2204 2132,-2204 "/>
<text text-anchor="middle" x="1988.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">organ_or_tissue</text>
<polyline fill="none" stroke="#000000" points="1845,-2181 2132,-2181 "/>
<text text-anchor="middle" x="1988.5" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_typeCode</text>
<polyline fill="none" stroke="#000000" points="1845,-2158 2132,-2158 "/>
<text text-anchor="middle" x="1988.5" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1845,-2135 2132,-2135 "/>
<text text-anchor="middle" x="1988.5" y="-2119.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_link_id</text>
<polyline fill="none" stroke="#000000" points="2132,-2112 2132,-2480 "/>
<text text-anchor="middle" x="2142.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMPETimages&#45;&gt;image -->
<g id="edge5" class="edge">
<title>NonDICOMPETimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M365.8104,-2853.6557C420.8724,-2790.5752 546.4476,-2657.6409 681.5,-2589 1032.476,-2410.615 1492.6143,-2339.5078 1753.8564,-2312.1597"/>
<polygon fill="#000000" stroke="#000000" points="1754.2484,-2315.6379 1763.8346,-2311.1263 1753.5273,-2308.6752 1754.2484,-2315.6379"/>
<text text-anchor="middle" x="778" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- MultiplexMicroscopy -->
<g id="node2" class="node">
<title>MultiplexMicroscopy</title>
<path fill="none" stroke="#000000" d="M703,-2589.5C703,-2589.5 1168,-2589.5 1168,-2589.5 1174,-2589.5 1180,-2595.5 1180,-2601.5 1180,-2601.5 1180,-3175.5 1180,-3175.5 1180,-3181.5 1174,-3187.5 1168,-3187.5 1168,-3187.5 703,-3187.5 703,-3187.5 697,-3187.5 691,-3181.5 691,-3175.5 691,-3175.5 691,-2601.5 691,-2601.5 691,-2595.5 697,-2589.5 703,-2589.5"/>
<text text-anchor="middle" x="775" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">MultiplexMicroscopy</text>
<polyline fill="none" stroke="#000000" points="859,-2589.5 859,-3187.5 "/>
<text text-anchor="middle" x="869.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="880,-2589.5 880,-3187.5 "/>
<text text-anchor="middle" x="1019.5" y="-3172.3" font-family="Times,serif" font-size="14.00" fill="#000000">MultiplexMicroscopy_id</text>
<polyline fill="none" stroke="#000000" points="880,-3164.5 1159,-3164.5 "/>
<text text-anchor="middle" x="1019.5" y="-3149.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="880,-3141.5 1159,-3141.5 "/>
<text text-anchor="middle" x="1019.5" y="-3126.3" font-family="Times,serif" font-size="14.00" fill="#000000">antibody_name</text>
<polyline fill="none" stroke="#000000" points="880,-3118.5 1159,-3118.5 "/>
<text text-anchor="middle" x="1019.5" y="-3103.3" font-family="Times,serif" font-size="14.00" fill="#000000">catalog_number</text>
<polyline fill="none" stroke="#000000" points="880,-3095.5 1159,-3095.5 "/>
<text text-anchor="middle" x="1019.5" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_id</text>
<polyline fill="none" stroke="#000000" points="880,-3072.5 1159,-3072.5 "/>
<text text-anchor="middle" x="1019.5" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="880,-3049.5 1159,-3049.5 "/>
<text text-anchor="middle" x="1019.5" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_filename</text>
<polyline fill="none" stroke="#000000" points="880,-3026.5 1159,-3026.5 "/>
<text text-anchor="middle" x="1019.5" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_name</text>
<polyline fill="none" stroke="#000000" points="880,-3003.5 1159,-3003.5 "/>
<text text-anchor="middle" x="1019.5" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">clone</text>
<polyline fill="none" stroke="#000000" points="880,-2980.5 1159,-2980.5 "/>
<text text-anchor="middle" x="1019.5" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">concentration</text>
<polyline fill="none" stroke="#000000" points="880,-2957.5 1159,-2957.5 "/>
<text text-anchor="middle" x="1019.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">cycle_number</text>
<polyline fill="none" stroke="#000000" points="880,-2934.5 1159,-2934.5 "/>
<text text-anchor="middle" x="1019.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">dilution</text>
<polyline fill="none" stroke="#000000" points="880,-2911.5 1159,-2911.5 "/>
<text text-anchor="middle" x="1019.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="880,-2888.5 1159,-2888.5 "/>
<text text-anchor="middle" x="1019.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_bandwidth</text>
<polyline fill="none" stroke="#000000" points="880,-2865.5 1159,-2865.5 "/>
<text text-anchor="middle" x="1019.5" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_wavelength</text>
<polyline fill="none" stroke="#000000" points="880,-2842.5 1159,-2842.5 "/>
<text text-anchor="middle" x="1019.5" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_bandwidth</text>
<polyline fill="none" stroke="#000000" points="880,-2819.5 1159,-2819.5 "/>
<text text-anchor="middle" x="1019.5" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_wavelength</text>
<polyline fill="none" stroke="#000000" points="880,-2796.5 1159,-2796.5 "/>
<text text-anchor="middle" x="1019.5" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">fluorophore</text>
<polyline fill="none" stroke="#000000" points="880,-2773.5 1159,-2773.5 "/>
<text text-anchor="middle" x="1019.5" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_assay_type</text>
<polyline fill="none" stroke="#000000" points="880,-2750.5 1159,-2750.5 "/>
<text text-anchor="middle" x="1019.5" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="880,-2727.5 1159,-2727.5 "/>
<text text-anchor="middle" x="1019.5" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="880,-2704.5 1159,-2704.5 "/>
<text text-anchor="middle" x="1019.5" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">lot</text>
<polyline fill="none" stroke="#000000" points="880,-2681.5 1159,-2681.5 "/>
<text text-anchor="middle" x="1019.5" y="-2666.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_abbreviation</text>
<polyline fill="none" stroke="#000000" points="880,-2658.5 1159,-2658.5 "/>
<text text-anchor="middle" x="1019.5" y="-2643.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_mass</text>
<polyline fill="none" stroke="#000000" points="880,-2635.5 1159,-2635.5 "/>
<text text-anchor="middle" x="1019.5" y="-2620.3" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="880,-2612.5 1159,-2612.5 "/>
<text text-anchor="middle" x="1019.5" y="-2597.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 19 properties</text>
<polyline fill="none" stroke="#000000" points="1159,-2589.5 1159,-3187.5 "/>
<text text-anchor="middle" x="1169.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- MultiplexMicroscopy&#45;&gt;image -->
<g id="edge3" class="edge">
<title>MultiplexMicroscopy&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1180.2061,-2595.013C1182.9584,-2592.9727 1185.7232,-2590.9677 1188.5,-2589 1360.8492,-2466.8714 1590.6013,-2388.1416 1754.1688,-2343.3824"/>
<polygon fill="#000000" stroke="#000000" points="1755.1317,-2346.7478 1763.864,-2340.748 1753.2961,-2339.9927 1755.1317,-2346.7478"/>
<text text-anchor="middle" x="1258" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- genomic_info -->
<g id="node3" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M2183,-2054.5C2183,-2054.5 2636,-2054.5 2636,-2054.5 2642,-2054.5 2648,-2060.5 2648,-2066.5 2648,-2066.5 2648,-2525.5 2648,-2525.5 2648,-2531.5 2642,-2537.5 2636,-2537.5 2636,-2537.5 2183,-2537.5 2183,-2537.5 2177,-2537.5 2171,-2531.5 2171,-2525.5 2171,-2525.5 2171,-2066.5 2171,-2066.5 2171,-2060.5 2177,-2054.5 2183,-2054.5"/>
<text text-anchor="middle" x="2227" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="2283,-2054.5 2283,-2537.5 "/>
<text text-anchor="middle" x="2293.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2304,-2054.5 2304,-2537.5 "/>
<text text-anchor="middle" x="2465.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2304,-2514.5 2627,-2514.5 "/>
<text text-anchor="middle" x="2465.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="2304,-2491.5 2627,-2491.5 "/>
<text text-anchor="middle" x="2465.5" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2304,-2468.5 2627,-2468.5 "/>
<text text-anchor="middle" x="2465.5" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2304,-2445.5 2627,-2445.5 "/>
<text text-anchor="middle" x="2465.5" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2304,-2422.5 2627,-2422.5 "/>
<text text-anchor="middle" x="2465.5" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2304,-2399.5 2627,-2399.5 "/>
<text text-anchor="middle" x="2465.5" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2304,-2376.5 2627,-2376.5 "/>
<text text-anchor="middle" x="2465.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2304,-2353.5 2627,-2353.5 "/>
<text text-anchor="middle" x="2465.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2304,-2330.5 2627,-2330.5 "/>
<text text-anchor="middle" x="2465.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2304,-2307.5 2627,-2307.5 "/>
<text text-anchor="middle" x="2465.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2304,-2284.5 2627,-2284.5 "/>
<text text-anchor="middle" x="2465.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2304,-2261.5 2627,-2261.5 "/>
<text text-anchor="middle" x="2465.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="2304,-2238.5 2627,-2238.5 "/>
<text text-anchor="middle" x="2465.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="2304,-2215.5 2627,-2215.5 "/>
<text text-anchor="middle" x="2465.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2304,-2192.5 2627,-2192.5 "/>
<text text-anchor="middle" x="2465.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2304,-2169.5 2627,-2169.5 "/>
<text text-anchor="middle" x="2465.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2304,-2146.5 2627,-2146.5 "/>
<text text-anchor="middle" x="2465.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2304,-2123.5 2627,-2123.5 "/>
<text text-anchor="middle" x="2465.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2304,-2100.5 2627,-2100.5 "/>
<text text-anchor="middle" x="2465.5" y="-2085.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2304,-2077.5 2627,-2077.5 "/>
<text text-anchor="middle" x="2465.5" y="-2062.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2627,-2054.5 2627,-2537.5 "/>
<text text-anchor="middle" x="2637.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node5" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2219.5,-1703.5C2219.5,-1703.5 2599.5,-1703.5 2599.5,-1703.5 2605.5,-1703.5 2611.5,-1709.5 2611.5,-1715.5 2611.5,-1715.5 2611.5,-1990.5 2611.5,-1990.5 2611.5,-1996.5 2605.5,-2002.5 2599.5,-2002.5 2599.5,-2002.5 2219.5,-2002.5 2219.5,-2002.5 2213.5,-2002.5 2207.5,-1996.5 2207.5,-1990.5 2207.5,-1990.5 2207.5,-1715.5 2207.5,-1715.5 2207.5,-1709.5 2213.5,-1703.5 2219.5,-1703.5"/>
<text text-anchor="middle" x="2227" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2246.5,-1703.5 2246.5,-2002.5 "/>
<text text-anchor="middle" x="2257" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2267.5,-1703.5 2267.5,-2002.5 "/>
<text text-anchor="middle" x="2429" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1979.5 2590.5,-1979.5 "/>
<text text-anchor="middle" x="2429" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1956.5 2590.5,-1956.5 "/>
<text text-anchor="middle" x="2429" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1933.5 2590.5,-1933.5 "/>
<text text-anchor="middle" x="2429" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1910.5 2590.5,-1910.5 "/>
<text text-anchor="middle" x="2429" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1887.5 2590.5,-1887.5 "/>
<text text-anchor="middle" x="2429" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1864.5 2590.5,-1864.5 "/>
<text text-anchor="middle" x="2429" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1841.5 2590.5,-1841.5 "/>
<text text-anchor="middle" x="2429" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1818.5 2590.5,-1818.5 "/>
<text text-anchor="middle" x="2429" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1795.5 2590.5,-1795.5 "/>
<text text-anchor="middle" x="2429" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1772.5 2590.5,-1772.5 "/>
<text text-anchor="middle" x="2429" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1749.5 2590.5,-1749.5 "/>
<text text-anchor="middle" x="2429" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2267.5,-1726.5 2590.5,-1726.5 "/>
<text text-anchor="middle" x="2429" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="2590.5,-1703.5 2590.5,-2002.5 "/>
<text text-anchor="middle" x="2601" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge10" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2409.5,-2054.4079C2409.5,-2040.3712 2409.5,-2026.4431 2409.5,-2012.8514"/>
<polygon fill="#000000" stroke="#000000" points="2413.0001,-2012.5272 2409.5,-2002.5272 2406.0001,-2012.5272 2413.0001,-2012.5272"/>
<text text-anchor="middle" x="2431.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2540.5,-1145.5C2540.5,-1145.5 2914.5,-1145.5 2914.5,-1145.5 2920.5,-1145.5 2926.5,-1151.5 2926.5,-1157.5 2926.5,-1157.5 2926.5,-1639.5 2926.5,-1639.5 2926.5,-1645.5 2920.5,-1651.5 2914.5,-1651.5 2914.5,-1651.5 2540.5,-1651.5 2540.5,-1651.5 2534.5,-1651.5 2528.5,-1645.5 2528.5,-1639.5 2528.5,-1639.5 2528.5,-1157.5 2528.5,-1157.5 2528.5,-1151.5 2534.5,-1145.5 2540.5,-1145.5"/>
<text text-anchor="middle" x="2570.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2612.5,-1145.5 2612.5,-1651.5 "/>
<text text-anchor="middle" x="2623" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2633.5,-1145.5 2633.5,-1651.5 "/>
<text text-anchor="middle" x="2769.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1628.5 2905.5,-1628.5 "/>
<text text-anchor="middle" x="2769.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1605.5 2905.5,-1605.5 "/>
<text text-anchor="middle" x="2769.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1582.5 2905.5,-1582.5 "/>
<text text-anchor="middle" x="2769.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1559.5 2905.5,-1559.5 "/>
<text text-anchor="middle" x="2769.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1536.5 2905.5,-1536.5 "/>
<text text-anchor="middle" x="2769.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1513.5 2905.5,-1513.5 "/>
<text text-anchor="middle" x="2769.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1490.5 2905.5,-1490.5 "/>
<text text-anchor="middle" x="2769.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1467.5 2905.5,-1467.5 "/>
<text text-anchor="middle" x="2769.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1444.5 2905.5,-1444.5 "/>
<text text-anchor="middle" x="2769.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1421.5 2905.5,-1421.5 "/>
<text text-anchor="middle" x="2769.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1398.5 2905.5,-1398.5 "/>
<text text-anchor="middle" x="2769.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1375.5 2905.5,-1375.5 "/>
<text text-anchor="middle" x="2769.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1352.5 2905.5,-1352.5 "/>
<text text-anchor="middle" x="2769.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1329.5 2905.5,-1329.5 "/>
<text text-anchor="middle" x="2769.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1306.5 2905.5,-1306.5 "/>
<text text-anchor="middle" x="2769.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1283.5 2905.5,-1283.5 "/>
<text text-anchor="middle" x="2769.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1260.5 2905.5,-1260.5 "/>
<text text-anchor="middle" x="2769.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1237.5 2905.5,-1237.5 "/>
<text text-anchor="middle" x="2769.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1214.5 2905.5,-1214.5 "/>
<text text-anchor="middle" x="2769.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1191.5 2905.5,-1191.5 "/>
<text text-anchor="middle" x="2769.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2633.5,-1168.5 2905.5,-1168.5 "/>
<text text-anchor="middle" x="2769.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2905.5,-1145.5 2905.5,-1651.5 "/>
<text text-anchor="middle" x="2916" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2588.5,-909.5C2588.5,-909.5 2866.5,-909.5 2866.5,-909.5 2872.5,-909.5 2878.5,-915.5 2878.5,-921.5 2878.5,-921.5 2878.5,-1081.5 2878.5,-1081.5 2878.5,-1087.5 2872.5,-1093.5 2866.5,-1093.5 2866.5,-1093.5 2588.5,-1093.5 2588.5,-1093.5 2582.5,-1093.5 2576.5,-1087.5 2576.5,-1081.5 2576.5,-1081.5 2576.5,-921.5 2576.5,-921.5 2576.5,-915.5 2582.5,-909.5 2588.5,-909.5"/>
<text text-anchor="middle" x="2624.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2672.5,-909.5 2672.5,-1093.5 "/>
<text text-anchor="middle" x="2683" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2693.5,-909.5 2693.5,-1093.5 "/>
<text text-anchor="middle" x="2775.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2693.5,-1070.5 2857.5,-1070.5 "/>
<text text-anchor="middle" x="2775.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="2693.5,-1047.5 2857.5,-1047.5 "/>
<text text-anchor="middle" x="2775.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2693.5,-1024.5 2857.5,-1024.5 "/>
<text text-anchor="middle" x="2775.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2693.5,-1001.5 2857.5,-1001.5 "/>
<text text-anchor="middle" x="2775.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2693.5,-978.5 2857.5,-978.5 "/>
<text text-anchor="middle" x="2775.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2693.5,-955.5 2857.5,-955.5 "/>
<text text-anchor="middle" x="2775.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2693.5,-932.5 2857.5,-932.5 "/>
<text text-anchor="middle" x="2775.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="2857.5,-909.5 2857.5,-1093.5 "/>
<text text-anchor="middle" x="2868" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2727.5,-1145.3874C2727.5,-1131.0731 2727.5,-1117.1697 2727.5,-1104.0079"/>
<polygon fill="#000000" stroke="#000000" points="2731.0001,-1103.6176 2727.5,-1093.6177 2724.0001,-1103.6177 2731.0001,-1103.6176"/>
<text text-anchor="middle" x="2778" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge8" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2611.6809,-1874.8677C2622.8527,-1869.55 2629.5,-1862.2607 2629.5,-1853 2629.5,-1846.4885 2626.2137,-1840.9518 2620.3789,-1836.3897"/>
<polygon fill="#000000" stroke="#000000" points="2622.0495,-1833.3098 2611.6809,-1831.1323 2618.4285,-1839.3005 2622.0495,-1833.3098"/>
<text text-anchor="middle" x="2687" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2403.0235,-1703.3331C2395.9087,-1509.3756 2389.0512,-1190.5052 2418.5,-1145 2452.2135,-1092.9048 2510.1883,-1059.408 2566.8779,-1038.015"/>
<polygon fill="#000000" stroke="#000000" points="2568.1428,-1041.2791 2576.3293,-1034.5535 2565.7355,-1034.7061 2568.1428,-1041.2791"/>
<text text-anchor="middle" x="2469" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2075.5,-1283.5C2075.5,-1283.5 2361.5,-1283.5 2361.5,-1283.5 2367.5,-1283.5 2373.5,-1289.5 2373.5,-1295.5 2373.5,-1295.5 2373.5,-1501.5 2373.5,-1501.5 2373.5,-1507.5 2367.5,-1513.5 2361.5,-1513.5 2361.5,-1513.5 2075.5,-1513.5 2075.5,-1513.5 2069.5,-1513.5 2063.5,-1507.5 2063.5,-1501.5 2063.5,-1501.5 2063.5,-1295.5 2063.5,-1295.5 2063.5,-1289.5 2069.5,-1283.5 2075.5,-1283.5"/>
<text text-anchor="middle" x="2097.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2131.5,-1283.5 2131.5,-1513.5 "/>
<text text-anchor="middle" x="2142" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2152.5,-1283.5 2152.5,-1513.5 "/>
<text text-anchor="middle" x="2252.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1490.5 2352.5,-1490.5 "/>
<text text-anchor="middle" x="2252.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1467.5 2352.5,-1467.5 "/>
<text text-anchor="middle" x="2252.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1444.5 2352.5,-1444.5 "/>
<text text-anchor="middle" x="2252.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1421.5 2352.5,-1421.5 "/>
<text text-anchor="middle" x="2252.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1398.5 2352.5,-1398.5 "/>
<text text-anchor="middle" x="2252.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1375.5 2352.5,-1375.5 "/>
<text text-anchor="middle" x="2252.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1352.5 2352.5,-1352.5 "/>
<text text-anchor="middle" x="2252.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1329.5 2352.5,-1329.5 "/>
<text text-anchor="middle" x="2252.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2152.5,-1306.5 2352.5,-1306.5 "/>
<text text-anchor="middle" x="2252.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="2352.5,-1283.5 2352.5,-1513.5 "/>
<text text-anchor="middle" x="2363" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2311.4048,-1703.4965C2308.271,-1697.3194 2305.2874,-1691.14 2302.5,-1685 2279.301,-1633.8984 2260.6998,-1574.7744 2246.9571,-1523.5547"/>
<polygon fill="#000000" stroke="#000000" points="2250.3049,-1522.5244 2244.3606,-1513.7543 2243.5384,-1524.3172 2250.3049,-1522.5244"/>
<text text-anchor="middle" x="2349" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2835.5,-259.5C2835.5,-259.5 3151.5,-259.5 3151.5,-259.5 3157.5,-259.5 3163.5,-265.5 3163.5,-271.5 3163.5,-271.5 3163.5,-845.5 3163.5,-845.5 3163.5,-851.5 3157.5,-857.5 3151.5,-857.5 3151.5,-857.5 2835.5,-857.5 2835.5,-857.5 2829.5,-857.5 2823.5,-851.5 2823.5,-845.5 2823.5,-845.5 2823.5,-271.5 2823.5,-271.5 2823.5,-265.5 2829.5,-259.5 2835.5,-259.5"/>
<text text-anchor="middle" x="2851.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2879.5,-259.5 2879.5,-857.5 "/>
<text text-anchor="middle" x="2890" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2900.5,-259.5 2900.5,-857.5 "/>
<text text-anchor="middle" x="3021.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2900.5,-834.5 3142.5,-834.5 "/>
<text text-anchor="middle" x="3021.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2900.5,-811.5 3142.5,-811.5 "/>
<text text-anchor="middle" x="3021.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="2900.5,-788.5 3142.5,-788.5 "/>
<text text-anchor="middle" x="3021.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="2900.5,-765.5 3142.5,-765.5 "/>
<text text-anchor="middle" x="3021.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="2900.5,-742.5 3142.5,-742.5 "/>
<text text-anchor="middle" x="3021.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="2900.5,-719.5 3142.5,-719.5 "/>
<text text-anchor="middle" x="3021.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="2900.5,-696.5 3142.5,-696.5 "/>
<text text-anchor="middle" x="3021.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="2900.5,-673.5 3142.5,-673.5 "/>
<text text-anchor="middle" x="3021.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2900.5,-650.5 3142.5,-650.5 "/>
<text text-anchor="middle" x="3021.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2900.5,-627.5 3142.5,-627.5 "/>
<text text-anchor="middle" x="3021.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2900.5,-604.5 3142.5,-604.5 "/>
<text text-anchor="middle" x="3021.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2900.5,-581.5 3142.5,-581.5 "/>
<text text-anchor="middle" x="3021.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="2900.5,-558.5 3142.5,-558.5 "/>
<text text-anchor="middle" x="3021.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="2900.5,-535.5 3142.5,-535.5 "/>
<text text-anchor="middle" x="3021.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2900.5,-512.5 3142.5,-512.5 "/>
<text text-anchor="middle" x="3021.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="2900.5,-489.5 3142.5,-489.5 "/>
<text text-anchor="middle" x="3021.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2900.5,-466.5 3142.5,-466.5 "/>
<text text-anchor="middle" x="3021.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="2900.5,-443.5 3142.5,-443.5 "/>
<text text-anchor="middle" x="3021.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="2900.5,-420.5 3142.5,-420.5 "/>
<text text-anchor="middle" x="3021.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2900.5,-397.5 3142.5,-397.5 "/>
<text text-anchor="middle" x="3021.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="2900.5,-374.5 3142.5,-374.5 "/>
<text text-anchor="middle" x="3021.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2900.5,-351.5 3142.5,-351.5 "/>
<text text-anchor="middle" x="3021.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2900.5,-328.5 3142.5,-328.5 "/>
<text text-anchor="middle" x="3021.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2900.5,-305.5 3142.5,-305.5 "/>
<text text-anchor="middle" x="3021.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="2900.5,-282.5 3142.5,-282.5 "/>
<text text-anchor="middle" x="3021.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="3142.5,-259.5 3142.5,-857.5 "/>
<text text-anchor="middle" x="3153" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2611.9578,-1832.4112C2832.0791,-1805.3552 3162.8382,-1749.4428 3239.5,-1652 3424.4585,-1416.9041 3298.5812,-1069.851 3168.4816,-830.0715"/>
<polygon fill="#000000" stroke="#000000" points="3171.52,-828.3326 3163.657,-821.2316 3165.3755,-831.6861 3171.52,-828.3326"/>
<text text-anchor="middle" x="3323" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- program -->
<g id="node6" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M2839.5,-.5C2839.5,-.5 3147.5,-.5 3147.5,-.5 3153.5,-.5 3159.5,-6.5 3159.5,-12.5 3159.5,-12.5 3159.5,-195.5 3159.5,-195.5 3159.5,-201.5 3153.5,-207.5 3147.5,-207.5 3147.5,-207.5 2839.5,-207.5 2839.5,-207.5 2833.5,-207.5 2827.5,-201.5 2827.5,-195.5 2827.5,-195.5 2827.5,-12.5 2827.5,-12.5 2827.5,-6.5 2833.5,-.5 2839.5,-.5"/>
<text text-anchor="middle" x="2866.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="2905.5,-.5 2905.5,-207.5 "/>
<text text-anchor="middle" x="2916" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2926.5,-.5 2926.5,-207.5 "/>
<text text-anchor="middle" x="3032.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2926.5,-184.5 3138.5,-184.5 "/>
<text text-anchor="middle" x="3032.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2926.5,-161.5 3138.5,-161.5 "/>
<text text-anchor="middle" x="3032.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="2926.5,-138.5 3138.5,-138.5 "/>
<text text-anchor="middle" x="3032.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="2926.5,-115.5 3138.5,-115.5 "/>
<text text-anchor="middle" x="3032.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="2926.5,-92.5 3138.5,-92.5 "/>
<text text-anchor="middle" x="3032.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="2926.5,-69.5 3138.5,-69.5 "/>
<text text-anchor="middle" x="3032.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="2926.5,-46.5 3138.5,-46.5 "/>
<text text-anchor="middle" x="3032.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="2926.5,-23.5 3138.5,-23.5 "/>
<text text-anchor="middle" x="3032.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="3138.5,-.5 3138.5,-207.5 "/>
<text text-anchor="middle" x="3149" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2782.7769,-909.4411C2793.6803,-891.2824 2805.6574,-871.3356 2818.1943,-850.4565"/>
<polygon fill="#000000" stroke="#000000" points="2821.2595,-852.1506 2823.4067,-841.7756 2815.2583,-848.5471 2821.2595,-852.1506"/>
<text text-anchor="middle" x="2830" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- version -->
<g id="node8" class="node">
<title>version</title>
<path fill="none" stroke="#000000" d="M4108.5,-2831C4108.5,-2831 4324.5,-2831 4324.5,-2831 4330.5,-2831 4336.5,-2837 4336.5,-2843 4336.5,-2843 4336.5,-2934 4336.5,-2934 4336.5,-2940 4330.5,-2946 4324.5,-2946 4324.5,-2946 4108.5,-2946 4108.5,-2946 4102.5,-2946 4096.5,-2940 4096.5,-2934 4096.5,-2934 4096.5,-2843 4096.5,-2843 4096.5,-2837 4102.5,-2831 4108.5,-2831"/>
<text text-anchor="middle" x="4131" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="4165.5,-2831 4165.5,-2946 "/>
<text text-anchor="middle" x="4176" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="4186.5,-2831 4186.5,-2946 "/>
<text text-anchor="middle" x="4251" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_version</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2923 4315.5,-2923 "/>
<text text-anchor="middle" x="4251" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_version_id</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2900 4315.5,-2900 "/>
<text text-anchor="middle" x="4251" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">datetime</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2877 4315.5,-2877 "/>
<text text-anchor="middle" x="4251" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">description</text>
<polyline fill="none" stroke="#000000" points="4186.5,-2854 4315.5,-2854 "/>
<text text-anchor="middle" x="4251" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">model_version</text>
<polyline fill="none" stroke="#000000" points="4315.5,-2831 4315.5,-2946 "/>
<text text-anchor="middle" x="4326" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMCTimages -->
<g id="node9" class="node">
<title>NonDICOMCTimages</title>
<path fill="none" stroke="#000000" d="M1210,-2762C1210,-2762 1931,-2762 1931,-2762 1937,-2762 1943,-2768 1943,-2774 1943,-2774 1943,-3003 1943,-3003 1943,-3009 1937,-3015 1931,-3015 1931,-3015 1210,-3015 1210,-3015 1204,-3015 1198,-3009 1198,-3003 1198,-3003 1198,-2774 1198,-2774 1198,-2768 1204,-2762 1210,-2762"/>
<text text-anchor="middle" x="1284.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages</text>
<polyline fill="none" stroke="#000000" points="1371,-2762 1371,-3015 "/>
<text text-anchor="middle" x="1381.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1392,-2762 1392,-3015 "/>
<text text-anchor="middle" x="1657" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="1392,-2992 1922,-2992 "/>
<text text-anchor="middle" x="1657" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="1392,-2969 1922,-2969 "/>
<text text-anchor="middle" x="1657" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="1392,-2946 1922,-2946 "/>
<text text-anchor="middle" x="1657" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="1392,-2923 1922,-2923 "/>
<text text-anchor="middle" x="1657" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="1392,-2900 1922,-2900 "/>
<text text-anchor="middle" x="1657" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="1392,-2877 1922,-2877 "/>
<text text-anchor="middle" x="1657" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="1392,-2854 1922,-2854 "/>
<text text-anchor="middle" x="1657" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="1392,-2831 1922,-2831 "/>
<text text-anchor="middle" x="1657" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="1392,-2808 1922,-2808 "/>
<text text-anchor="middle" x="1657" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="1392,-2785 1922,-2785 "/>
<text text-anchor="middle" x="1657" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages_id</text>
<polyline fill="none" stroke="#000000" points="1922,-2762 1922,-3015 "/>
<text text-anchor="middle" x="1932.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMCTimages&#45;&gt;image -->
<g id="edge2" class="edge">
<title>NonDICOMCTimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1653.4977,-2761.7574C1705.5255,-2682.3077 1773.6062,-2578.3442 1832.244,-2488.8007"/>
<polygon fill="#000000" stroke="#000000" points="1835.3379,-2490.4648 1837.8883,-2480.1815 1829.4818,-2486.6299 1835.3379,-2490.4648"/>
<text text-anchor="middle" x="1821" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMMRimages -->
<g id="node10" class="node">
<title>NonDICOMMRimages</title>
<path fill="none" stroke="#000000" d="M1973,-2681.5C1973,-2681.5 2722,-2681.5 2722,-2681.5 2728,-2681.5 2734,-2687.5 2734,-2693.5 2734,-2693.5 2734,-3083.5 2734,-3083.5 2734,-3089.5 2728,-3095.5 2722,-3095.5 2722,-3095.5 1973,-3095.5 1973,-3095.5 1967,-3095.5 1961,-3089.5 1961,-3083.5 1961,-3083.5 1961,-2693.5 1961,-2693.5 1961,-2687.5 1967,-2681.5 1973,-2681.5"/>
<text text-anchor="middle" x="2049.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages</text>
<polyline fill="none" stroke="#000000" points="2138,-2681.5 2138,-3095.5 "/>
<text text-anchor="middle" x="2148.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2159,-2681.5 2159,-3095.5 "/>
<text text-anchor="middle" x="2436" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="2159,-3072.5 2713,-3072.5 "/>
<text text-anchor="middle" x="2436" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="2159,-3049.5 2713,-3049.5 "/>
<text text-anchor="middle" x="2436" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="2159,-3026.5 2713,-3026.5 "/>
<text text-anchor="middle" x="2436" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="2159,-3003.5 2713,-3003.5 "/>
<text text-anchor="middle" x="2436" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="2159,-2980.5 2713,-2980.5 "/>
<text text-anchor="middle" x="2436" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="2159,-2957.5 2713,-2957.5 "/>
<text text-anchor="middle" x="2436" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="2159,-2934.5 2713,-2934.5 "/>
<text text-anchor="middle" x="2436" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="2159,-2911.5 2713,-2911.5 "/>
<text text-anchor="middle" x="2436" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="2159,-2888.5 2713,-2888.5 "/>
<text text-anchor="middle" x="2436" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="2159,-2865.5 2713,-2865.5 "/>
<text text-anchor="middle" x="2436" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="2159,-2842.5 2713,-2842.5 "/>
<text text-anchor="middle" x="2436" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="2159,-2819.5 2713,-2819.5 "/>
<text text-anchor="middle" x="2436" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="2159,-2796.5 2713,-2796.5 "/>
<text text-anchor="middle" x="2436" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="2159,-2773.5 2713,-2773.5 "/>
<text text-anchor="middle" x="2436" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="2159,-2750.5 2713,-2750.5 "/>
<text text-anchor="middle" x="2436" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_timeOfFlightContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="2159,-2727.5 2713,-2727.5 "/>
<text text-anchor="middle" x="2436" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageReconstructionProtocolElement_complexImageComponentCode</text>
<polyline fill="none" stroke="#000000" points="2159,-2704.5 2713,-2704.5 "/>
<text text-anchor="middle" x="2436" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages_id</text>
<polyline fill="none" stroke="#000000" points="2713,-2681.5 2713,-3095.5 "/>
<text text-anchor="middle" x="2723.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMMRimages&#45;&gt;image -->
<g id="edge6" class="edge">
<title>NonDICOMMRimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2211.4467,-2681.2723C2170.4332,-2618.8032 2125.5975,-2550.5122 2085.2169,-2489.0071"/>
<polygon fill="#000000" stroke="#000000" points="2087.9635,-2486.8133 2079.5494,-2480.3748 2082.112,-2490.6551 2087.9635,-2486.8133"/>
<text text-anchor="middle" x="2163" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- treatment -->
<g id="node11" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M2956.5,-1329.5C2956.5,-1329.5 3218.5,-1329.5 3218.5,-1329.5 3224.5,-1329.5 3230.5,-1335.5 3230.5,-1341.5 3230.5,-1341.5 3230.5,-1455.5 3230.5,-1455.5 3230.5,-1461.5 3224.5,-1467.5 3218.5,-1467.5 3218.5,-1467.5 2956.5,-1467.5 2956.5,-1467.5 2950.5,-1467.5 2944.5,-1461.5 2944.5,-1455.5 2944.5,-1455.5 2944.5,-1341.5 2944.5,-1341.5 2944.5,-1335.5 2950.5,-1329.5 2956.5,-1329.5"/>
<text text-anchor="middle" x="2989" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="3033.5,-1329.5 3033.5,-1467.5 "/>
<text text-anchor="middle" x="3044" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3054.5,-1329.5 3054.5,-1467.5 "/>
<text text-anchor="middle" x="3132" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3054.5,-1444.5 3209.5,-1444.5 "/>
<text text-anchor="middle" x="3132" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="3054.5,-1421.5 3209.5,-1421.5 "/>
<text text-anchor="middle" x="3132" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="3054.5,-1398.5 3209.5,-1398.5 "/>
<text text-anchor="middle" x="3132" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="3054.5,-1375.5 3209.5,-1375.5 "/>
<text text-anchor="middle" x="3132" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="3054.5,-1352.5 3209.5,-1352.5 "/>
<text text-anchor="middle" x="3132" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3209.5,-1329.5 3209.5,-1467.5 "/>
<text text-anchor="middle" x="3220" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3056.2308,-1329.4077C3029.4247,-1275.1769 2987.024,-1199.9201 2935.5,-1145 2920.5978,-1129.1156 2903.6529,-1113.9952 2886.018,-1099.9399"/>
<polygon fill="#000000" stroke="#000000" points="2887.9022,-1096.9699 2877.8717,-1093.5581 2883.5853,-1102.4803 2887.9022,-1096.9699"/>
<text text-anchor="middle" x="2967" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2222.2654,-1283.2873C2230.1531,-1224.6998 2249.4412,-1156.6357 2294.5,-1112 2333.2505,-1073.6134 2460.0627,-1044.0589 2566.5088,-1025.215"/>
<polygon fill="#000000" stroke="#000000" points="2567.1682,-1028.6529 2576.4153,-1023.4815 2565.9616,-1021.7577 2567.1682,-1028.6529"/>
<text text-anchor="middle" x="2345" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge11" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2106.4512,-2111.9272C2124.453,-2091.8712 2143.0241,-2072.1666 2161.5,-2054 2176.6643,-2039.0896 2192.8546,-2024.133 2209.4227,-2009.4791"/>
<polygon fill="#000000" stroke="#000000" points="2211.8576,-2011.9988 2217.0593,-2002.7688 2207.2371,-2006.7404 2211.8576,-2011.9988"/>
<text text-anchor="middle" x="2215.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- NonDICOMpathologyImages -->
<g id="node14" class="node">
<title>NonDICOMpathologyImages</title>
<path fill="none" stroke="#000000" d="M2764,-2773.5C2764,-2773.5 3251,-2773.5 3251,-2773.5 3257,-2773.5 3263,-2779.5 3263,-2785.5 3263,-2785.5 3263,-2991.5 3263,-2991.5 3263,-2997.5 3257,-3003.5 3251,-3003.5 3251,-3003.5 2764,-3003.5 2764,-3003.5 2758,-3003.5 2752,-2997.5 2752,-2991.5 2752,-2991.5 2752,-2785.5 2752,-2785.5 2752,-2779.5 2758,-2773.5 2764,-2773.5"/>
<text text-anchor="middle" x="2864" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages</text>
<polyline fill="none" stroke="#000000" points="2976,-2773.5 2976,-3003.5 "/>
<text text-anchor="middle" x="2986.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2997,-2773.5 2997,-3003.5 "/>
<text text-anchor="middle" x="3119.5" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages_id</text>
<polyline fill="none" stroke="#000000" points="2997,-2980.5 3242,-2980.5 "/>
<text text-anchor="middle" x="3119.5" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="2997,-2957.5 3242,-2957.5 "/>
<text text-anchor="middle" x="3119.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="2997,-2934.5 3242,-2934.5 "/>
<text text-anchor="middle" x="3119.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="2997,-2911.5 3242,-2911.5 "/>
<text text-anchor="middle" x="3119.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="2997,-2888.5 3242,-2888.5 "/>
<text text-anchor="middle" x="3119.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="2997,-2865.5 3242,-2865.5 "/>
<text text-anchor="middle" x="3119.5" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">objective</text>
<polyline fill="none" stroke="#000000" points="2997,-2842.5 3242,-2842.5 "/>
<text text-anchor="middle" x="3119.5" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="2997,-2819.5 3242,-2819.5 "/>
<text text-anchor="middle" x="3119.5" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_fixative</text>
<polyline fill="none" stroke="#000000" points="2997,-2796.5 3242,-2796.5 "/>
<text text-anchor="middle" x="3119.5" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_type</text>
<polyline fill="none" stroke="#000000" points="3242,-2773.5 3242,-3003.5 "/>
<text text-anchor="middle" x="3252.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMpathologyImages&#45;&gt;image -->
<g id="edge4" class="edge">
<title>NonDICOMpathologyImages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2937.7449,-2773.3011C2891.2008,-2707.4129 2823.7123,-2629.9467 2742.5,-2589 2511.0405,-2472.2996 2391.4003,-2657.7428 2161.5,-2538 2136.3747,-2524.9136 2113.1234,-2507.2543 2092.0128,-2487.4005"/>
<polygon fill="#000000" stroke="#000000" points="2094.2646,-2484.7098 2084.6355,-2480.2904 2089.407,-2489.75 2094.2646,-2484.7098"/>
<text text-anchor="middle" x="2722" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge9" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2993.5,-259.4595C2993.5,-244.999 2993.5,-230.9707 2993.5,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="2997.0001,-217.5945 2993.5,-207.5945 2990.0001,-217.5946 2997.0001,-217.5945"/>
<text text-anchor="middle" x="3035" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- NonDICOMradiologyAllModalities -->
<g id="node16" class="node">
<title>NonDICOMradiologyAllModalities</title>
<path fill="none" stroke="#000000" d="M3293,-2681.5C3293,-2681.5 4066,-2681.5 4066,-2681.5 4072,-2681.5 4078,-2687.5 4078,-2693.5 4078,-2693.5 4078,-3083.5 4078,-3083.5 4078,-3089.5 4072,-3095.5 4066,-3095.5 4066,-3095.5 3293,-3095.5 3293,-3095.5 3287,-3095.5 3281,-3089.5 3281,-3083.5 3281,-3083.5 3281,-2693.5 3281,-2693.5 3281,-2687.5 3287,-2681.5 3293,-2681.5"/>
<text text-anchor="middle" x="3412.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities</text>
<polyline fill="none" stroke="#000000" points="3544,-2681.5 3544,-3095.5 "/>
<text text-anchor="middle" x="3554.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3565,-2681.5 3565,-3095.5 "/>
<text text-anchor="middle" x="3811" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities_id</text>
<polyline fill="none" stroke="#000000" points="3565,-3072.5 4057,-3072.5 "/>
<text text-anchor="middle" x="3811" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_acquisitionTypeCode</text>
<polyline fill="none" stroke="#000000" points="3565,-3049.5 4057,-3049.5 "/>
<text text-anchor="middle" x="3811" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_admittingDiagnosisCode</text>
<polyline fill="none" stroke="#000000" points="3565,-3026.5 4057,-3026.5 "/>
<text text-anchor="middle" x="3811" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_algorithmCode</text>
<polyline fill="none" stroke="#000000" points="3565,-3003.5 4057,-3003.5 "/>
<text text-anchor="middle" x="3811" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_bodyPositionCode</text>
<polyline fill="none" stroke="#000000" points="3565,-2980.5 4057,-2980.5 "/>
<text text-anchor="middle" x="3811" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_cardiacSynchronizationTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="3565,-2957.5 4057,-2957.5 "/>
<text text-anchor="middle" x="3811" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_dataCollectionDiameter</text>
<polyline fill="none" stroke="#000000" points="3565,-2934.5 4057,-2934.5 "/>
<text text-anchor="middle" x="3811" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_description</text>
<polyline fill="none" stroke="#000000" points="3565,-2911.5 4057,-2911.5 "/>
<text text-anchor="middle" x="3811" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_lossyImageCompressionIndicator</text>
<polyline fill="none" stroke="#000000" points="3565,-2888.5 4057,-2888.5 "/>
<text text-anchor="middle" x="3811" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_nonAcquisitionModalitiesInStudyCode</text>
<polyline fill="none" stroke="#000000" points="3565,-2865.5 4057,-2865.5 "/>
<text text-anchor="middle" x="3811" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_primaryAnatomicSiteCode</text>
<polyline fill="none" stroke="#000000" points="3565,-2842.5 4057,-2842.5 "/>
<text text-anchor="middle" x="3811" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionDiameter</text>
<polyline fill="none" stroke="#000000" points="3565,-2819.5 4057,-2819.5 "/>
<text text-anchor="middle" x="3811" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewHeight</text>
<polyline fill="none" stroke="#000000" points="3565,-2796.5 4057,-2796.5 "/>
<text text-anchor="middle" x="3811" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewWidth</text>
<polyline fill="none" stroke="#000000" points="3565,-2773.5 4057,-2773.5 "/>
<text text-anchor="middle" x="3811" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionInterval</text>
<polyline fill="none" stroke="#000000" points="3565,-2750.5 4057,-2750.5 "/>
<text text-anchor="middle" x="3811" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_respiratoryMotionTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="3565,-2727.5 4057,-2727.5 "/>
<text text-anchor="middle" x="3811" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_sliceThickness</text>
<polyline fill="none" stroke="#000000" points="3565,-2704.5 4057,-2704.5 "/>
<text text-anchor="middle" x="3811" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_summary</text>
<polyline fill="none" stroke="#000000" points="4057,-2681.5 4057,-3095.5 "/>
<text text-anchor="middle" x="4067.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMradiologyAllModalities&#45;&gt;image -->
<g id="edge7" class="edge">
<title>NonDICOMradiologyAllModalities&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3443.971,-2681.3921C3390.458,-2644.4592 3331.577,-2610.8436 3271.5,-2589 3056.7812,-2510.9297 2986.7169,-2566.7776 2758.5,-2556 2725.3552,-2554.4347 2191.357,-2552.4771 2161.5,-2538 2135.344,-2525.3175 2111.3163,-2507.5114 2089.6569,-2487.2474"/>
<polygon fill="#000000" stroke="#000000" points="2092.0409,-2484.6843 2082.4027,-2480.2849 2087.1937,-2489.7346 2092.0409,-2484.6843"/>
<text text-anchor="middle" x="3244" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- proteomic -->
<g id="node17" class="node">
<title>proteomic</title>
<path fill="none" stroke="#000000" d="M2678.5,-2215.5C2678.5,-2215.5 3018.5,-2215.5 3018.5,-2215.5 3024.5,-2215.5 3030.5,-2221.5 3030.5,-2227.5 3030.5,-2227.5 3030.5,-2364.5 3030.5,-2364.5 3030.5,-2370.5 3024.5,-2376.5 3018.5,-2376.5 3018.5,-2376.5 2678.5,-2376.5 2678.5,-2376.5 2672.5,-2376.5 2666.5,-2370.5 2666.5,-2364.5 2666.5,-2364.5 2666.5,-2227.5 2666.5,-2227.5 2666.5,-2221.5 2672.5,-2215.5 2678.5,-2215.5"/>
<text text-anchor="middle" x="2711" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic</text>
<polyline fill="none" stroke="#000000" points="2755.5,-2215.5 2755.5,-2376.5 "/>
<text text-anchor="middle" x="2766" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2776.5,-2215.5 2776.5,-2376.5 "/>
<text text-anchor="middle" x="2893" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="2776.5,-2353.5 3009.5,-2353.5 "/>
<text text-anchor="middle" x="2893" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fractions</text>
<polyline fill="none" stroke="#000000" points="2776.5,-2330.5 3009.5,-2330.5 "/>
<text text-anchor="middle" x="2893" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_make</text>
<polyline fill="none" stroke="#000000" points="2776.5,-2307.5 3009.5,-2307.5 "/>
<text text-anchor="middle" x="2893" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer_model_name</text>
<polyline fill="none" stroke="#000000" points="2776.5,-2284.5 3009.5,-2284.5 "/>
<text text-anchor="middle" x="2893" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_design_description</text>
<polyline fill="none" stroke="#000000" points="2776.5,-2261.5 3009.5,-2261.5 "/>
<text text-anchor="middle" x="2893" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2776.5,-2238.5 3009.5,-2238.5 "/>
<text text-anchor="middle" x="2893" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3009.5,-2215.5 3009.5,-2376.5 "/>
<text text-anchor="middle" x="3020" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- proteomic&#45;&gt;file -->
<g id="edge12" class="edge">
<title>proteomic&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2791.3939,-2215.2849C2755.1771,-2166.4205 2705.9646,-2104.0809 2656.5,-2054 2641.6761,-2038.9914 2625.7839,-2023.9915 2609.4713,-2009.3312"/>
<polygon fill="#000000" stroke="#000000" points="2611.7412,-2006.6658 2601.9491,-2002.6204 2607.0812,-2011.8893 2611.7412,-2006.6658"/>
<text text-anchor="middle" x="2660.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
</g>
</svg>
</div>
