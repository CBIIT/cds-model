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
<g id="node3" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M1782,-2112C1782,-2112 2147,-2112 2147,-2112 2153,-2112 2159,-2118 2159,-2124 2159,-2124 2159,-2468 2159,-2468 2159,-2474 2153,-2480 2147,-2480 2147,-2480 1782,-2480 1782,-2480 1776,-2480 1770,-2474 1770,-2468 1770,-2468 1770,-2124 1770,-2124 1770,-2118 1776,-2112 1782,-2112"/>
<text text-anchor="middle" x="1800" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="1830,-2112 1830,-2480 "/>
<text text-anchor="middle" x="1840.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1851,-2112 1851,-2480 "/>
<text text-anchor="middle" x="1994.5" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">citation_or_DOI</text>
<polyline fill="none" stroke="#000000" points="1851,-2457 2138,-2457 "/>
<text text-anchor="middle" x="1994.5" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_description</text>
<polyline fill="none" stroke="#000000" points="1851,-2434 2138,-2434 "/>
<text text-anchor="middle" x="1994.5" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_type</text>
<polyline fill="none" stroke="#000000" points="1851,-2411 2138,-2411 "/>
<text text-anchor="middle" x="1994.5" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_software</text>
<polyline fill="none" stroke="#000000" points="1851,-2388 2138,-2388 "/>
<text text-anchor="middle" x="1994.5" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1851,-2365 2138,-2365 "/>
<text text-anchor="middle" x="1994.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_manufacturer</text>
<polyline fill="none" stroke="#000000" points="1851,-2342 2138,-2342 "/>
<text text-anchor="middle" x="1994.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_model</text>
<polyline fill="none" stroke="#000000" points="1851,-2319 2138,-2319 "/>
<text text-anchor="middle" x="1994.5" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_protocol</text>
<polyline fill="none" stroke="#000000" points="1851,-2296 2138,-2296 "/>
<text text-anchor="middle" x="1994.5" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_software</text>
<polyline fill="none" stroke="#000000" points="1851,-2273 2138,-2273 "/>
<text text-anchor="middle" x="1994.5" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">license</text>
<polyline fill="none" stroke="#000000" points="1851,-2250 2138,-2250 "/>
<text text-anchor="middle" x="1994.5" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_offset</text>
<polyline fill="none" stroke="#000000" points="1851,-2227 2138,-2227 "/>
<text text-anchor="middle" x="1994.5" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_type</text>
<polyline fill="none" stroke="#000000" points="1851,-2204 2138,-2204 "/>
<text text-anchor="middle" x="1994.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">organ_or_tissue</text>
<polyline fill="none" stroke="#000000" points="1851,-2181 2138,-2181 "/>
<text text-anchor="middle" x="1994.5" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_typeCode</text>
<polyline fill="none" stroke="#000000" points="1851,-2158 2138,-2158 "/>
<text text-anchor="middle" x="1994.5" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1851,-2135 2138,-2135 "/>
<text text-anchor="middle" x="1994.5" y="-2119.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_link_id</text>
<polyline fill="none" stroke="#000000" points="2138,-2112 2138,-2480 "/>
<text text-anchor="middle" x="2148.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMPETimages&#45;&gt;image -->
<g id="edge11" class="edge">
<title>NonDICOMPETimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M365.8036,-2853.6423C420.8546,-2790.5402 546.4126,-2657.5721 681.5,-2589 1034.5112,-2409.807 1497.4202,-2338.9569 1759.7391,-2311.8787"/>
<polygon fill="#000000" stroke="#000000" points="1760.1654,-2315.3535 1769.7581,-2310.8557 1759.4543,-2308.3897 1760.1654,-2315.3535"/>
<text text-anchor="middle" x="778" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- version -->
<g id="node2" class="node">
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
<!-- file -->
<g id="node17" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2225.5,-1703.5C2225.5,-1703.5 2605.5,-1703.5 2605.5,-1703.5 2611.5,-1703.5 2617.5,-1709.5 2617.5,-1715.5 2617.5,-1715.5 2617.5,-1990.5 2617.5,-1990.5 2617.5,-1996.5 2611.5,-2002.5 2605.5,-2002.5 2605.5,-2002.5 2225.5,-2002.5 2225.5,-2002.5 2219.5,-2002.5 2213.5,-1996.5 2213.5,-1990.5 2213.5,-1990.5 2213.5,-1715.5 2213.5,-1715.5 2213.5,-1709.5 2219.5,-1703.5 2225.5,-1703.5"/>
<text text-anchor="middle" x="2233" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2252.5,-1703.5 2252.5,-2002.5 "/>
<text text-anchor="middle" x="2263" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2273.5,-1703.5 2273.5,-2002.5 "/>
<text text-anchor="middle" x="2435" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1979.5 2596.5,-1979.5 "/>
<text text-anchor="middle" x="2435" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1956.5 2596.5,-1956.5 "/>
<text text-anchor="middle" x="2435" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1933.5 2596.5,-1933.5 "/>
<text text-anchor="middle" x="2435" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1910.5 2596.5,-1910.5 "/>
<text text-anchor="middle" x="2435" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1887.5 2596.5,-1887.5 "/>
<text text-anchor="middle" x="2435" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1864.5 2596.5,-1864.5 "/>
<text text-anchor="middle" x="2435" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1841.5 2596.5,-1841.5 "/>
<text text-anchor="middle" x="2435" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1818.5 2596.5,-1818.5 "/>
<text text-anchor="middle" x="2435" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1795.5 2596.5,-1795.5 "/>
<text text-anchor="middle" x="2435" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1772.5 2596.5,-1772.5 "/>
<text text-anchor="middle" x="2435" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1749.5 2596.5,-1749.5 "/>
<text text-anchor="middle" x="2435" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2273.5,-1726.5 2596.5,-1726.5 "/>
<text text-anchor="middle" x="2435" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="2596.5,-1703.5 2596.5,-2002.5 "/>
<text text-anchor="middle" x="2607" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge15" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2112.4512,-2111.9272C2130.453,-2091.8712 2149.0241,-2072.1666 2167.5,-2054 2182.6643,-2039.0896 2198.8546,-2024.133 2215.4227,-2009.4791"/>
<polygon fill="#000000" stroke="#000000" points="2217.8576,-2011.9988 2223.0593,-2002.7688 2213.2371,-2006.7404 2217.8576,-2011.9988"/>
<text text-anchor="middle" x="2221.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- program -->
<g id="node4" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M2201.5,-.5C2201.5,-.5 2509.5,-.5 2509.5,-.5 2515.5,-.5 2521.5,-6.5 2521.5,-12.5 2521.5,-12.5 2521.5,-195.5 2521.5,-195.5 2521.5,-201.5 2515.5,-207.5 2509.5,-207.5 2509.5,-207.5 2201.5,-207.5 2201.5,-207.5 2195.5,-207.5 2189.5,-201.5 2189.5,-195.5 2189.5,-195.5 2189.5,-12.5 2189.5,-12.5 2189.5,-6.5 2195.5,-.5 2201.5,-.5"/>
<text text-anchor="middle" x="2228.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="2267.5,-.5 2267.5,-207.5 "/>
<text text-anchor="middle" x="2278" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2288.5,-.5 2288.5,-207.5 "/>
<text text-anchor="middle" x="2394.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2288.5,-184.5 2500.5,-184.5 "/>
<text text-anchor="middle" x="2394.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2288.5,-161.5 2500.5,-161.5 "/>
<text text-anchor="middle" x="2394.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="2288.5,-138.5 2500.5,-138.5 "/>
<text text-anchor="middle" x="2394.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="2288.5,-115.5 2500.5,-115.5 "/>
<text text-anchor="middle" x="2394.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="2288.5,-92.5 2500.5,-92.5 "/>
<text text-anchor="middle" x="2394.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="2288.5,-69.5 2500.5,-69.5 "/>
<text text-anchor="middle" x="2394.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="2288.5,-46.5 2500.5,-46.5 "/>
<text text-anchor="middle" x="2394.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="2288.5,-23.5 2500.5,-23.5 "/>
<text text-anchor="middle" x="2394.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="2500.5,-.5 2500.5,-207.5 "/>
<text text-anchor="middle" x="2511" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- MultiplexMicroscopy -->
<g id="node5" class="node">
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
<g id="edge8" class="edge">
<title>MultiplexMicroscopy&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1180.1988,-2595.0027C1182.9534,-2592.9657 1185.7207,-2590.9641 1188.5,-2589 1362.7574,-2465.8556 1595.2629,-2387.1052 1760.21,-2342.613"/>
<polygon fill="#000000" stroke="#000000" points="1761.2319,-2345.9627 1769.986,-2339.9948 1759.4209,-2339.201 1761.2319,-2345.9627"/>
<text text-anchor="middle" x="1258" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMCTimages -->
<g id="node6" class="node">
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
<g id="edge9" class="edge">
<title>NonDICOMCTimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1654.7811,-2761.7574C1707.6668,-2682.2276 1776.8864,-2578.1346 1836.4717,-2488.5299"/>
<polygon fill="#000000" stroke="#000000" points="1839.4003,-2490.4466 1842.0232,-2480.1815 1833.5714,-2486.5705 1839.4003,-2490.4466"/>
<text text-anchor="middle" x="1824" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2874.5,-1145.5C2874.5,-1145.5 3248.5,-1145.5 3248.5,-1145.5 3254.5,-1145.5 3260.5,-1151.5 3260.5,-1157.5 3260.5,-1157.5 3260.5,-1639.5 3260.5,-1639.5 3260.5,-1645.5 3254.5,-1651.5 3248.5,-1651.5 3248.5,-1651.5 2874.5,-1651.5 2874.5,-1651.5 2868.5,-1651.5 2862.5,-1645.5 2862.5,-1639.5 2862.5,-1639.5 2862.5,-1157.5 2862.5,-1157.5 2862.5,-1151.5 2868.5,-1145.5 2874.5,-1145.5"/>
<text text-anchor="middle" x="2904.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2946.5,-1145.5 2946.5,-1651.5 "/>
<text text-anchor="middle" x="2957" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2967.5,-1145.5 2967.5,-1651.5 "/>
<text text-anchor="middle" x="3103.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1628.5 3239.5,-1628.5 "/>
<text text-anchor="middle" x="3103.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1605.5 3239.5,-1605.5 "/>
<text text-anchor="middle" x="3103.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1582.5 3239.5,-1582.5 "/>
<text text-anchor="middle" x="3103.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1559.5 3239.5,-1559.5 "/>
<text text-anchor="middle" x="3103.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1536.5 3239.5,-1536.5 "/>
<text text-anchor="middle" x="3103.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1513.5 3239.5,-1513.5 "/>
<text text-anchor="middle" x="3103.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1490.5 3239.5,-1490.5 "/>
<text text-anchor="middle" x="3103.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1467.5 3239.5,-1467.5 "/>
<text text-anchor="middle" x="3103.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1444.5 3239.5,-1444.5 "/>
<text text-anchor="middle" x="3103.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1421.5 3239.5,-1421.5 "/>
<text text-anchor="middle" x="3103.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1398.5 3239.5,-1398.5 "/>
<text text-anchor="middle" x="3103.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1375.5 3239.5,-1375.5 "/>
<text text-anchor="middle" x="3103.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1352.5 3239.5,-1352.5 "/>
<text text-anchor="middle" x="3103.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1329.5 3239.5,-1329.5 "/>
<text text-anchor="middle" x="3103.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1306.5 3239.5,-1306.5 "/>
<text text-anchor="middle" x="3103.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1283.5 3239.5,-1283.5 "/>
<text text-anchor="middle" x="3103.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1260.5 3239.5,-1260.5 "/>
<text text-anchor="middle" x="3103.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1237.5 3239.5,-1237.5 "/>
<text text-anchor="middle" x="3103.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1214.5 3239.5,-1214.5 "/>
<text text-anchor="middle" x="3103.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1191.5 3239.5,-1191.5 "/>
<text text-anchor="middle" x="3103.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1168.5 3239.5,-1168.5 "/>
<text text-anchor="middle" x="3103.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3239.5,-1145.5 3239.5,-1651.5 "/>
<text text-anchor="middle" x="3250" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2550.5,-909.5C2550.5,-909.5 2828.5,-909.5 2828.5,-909.5 2834.5,-909.5 2840.5,-915.5 2840.5,-921.5 2840.5,-921.5 2840.5,-1081.5 2840.5,-1081.5 2840.5,-1087.5 2834.5,-1093.5 2828.5,-1093.5 2828.5,-1093.5 2550.5,-1093.5 2550.5,-1093.5 2544.5,-1093.5 2538.5,-1087.5 2538.5,-1081.5 2538.5,-1081.5 2538.5,-921.5 2538.5,-921.5 2538.5,-915.5 2544.5,-909.5 2550.5,-909.5"/>
<text text-anchor="middle" x="2586.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2634.5,-909.5 2634.5,-1093.5 "/>
<text text-anchor="middle" x="2645" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2655.5,-909.5 2655.5,-1093.5 "/>
<text text-anchor="middle" x="2737.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2655.5,-1070.5 2819.5,-1070.5 "/>
<text text-anchor="middle" x="2737.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="2655.5,-1047.5 2819.5,-1047.5 "/>
<text text-anchor="middle" x="2737.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2655.5,-1024.5 2819.5,-1024.5 "/>
<text text-anchor="middle" x="2737.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="2655.5,-1001.5 2819.5,-1001.5 "/>
<text text-anchor="middle" x="2737.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2655.5,-978.5 2819.5,-978.5 "/>
<text text-anchor="middle" x="2737.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2655.5,-955.5 2819.5,-955.5 "/>
<text text-anchor="middle" x="2737.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2655.5,-932.5 2819.5,-932.5 "/>
<text text-anchor="middle" x="2737.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="2819.5,-909.5 2819.5,-1093.5 "/>
<text text-anchor="middle" x="2830" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2862.4232,-1154.3087C2859.4462,-1151.1711 2856.4709,-1148.0666 2853.5,-1145 2839.1346,-1130.1718 2823.4416,-1115.1447 2807.6397,-1100.6774"/>
<polygon fill="#000000" stroke="#000000" points="2809.6331,-1097.7596 2799.8789,-1093.6235 2804.9249,-1102.9396 2809.6331,-1097.7596"/>
<text text-anchor="middle" x="2884" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genomic_info -->
<g id="node8" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M2189,-2054.5C2189,-2054.5 2642,-2054.5 2642,-2054.5 2648,-2054.5 2654,-2060.5 2654,-2066.5 2654,-2066.5 2654,-2525.5 2654,-2525.5 2654,-2531.5 2648,-2537.5 2642,-2537.5 2642,-2537.5 2189,-2537.5 2189,-2537.5 2183,-2537.5 2177,-2531.5 2177,-2525.5 2177,-2525.5 2177,-2066.5 2177,-2066.5 2177,-2060.5 2183,-2054.5 2189,-2054.5"/>
<text text-anchor="middle" x="2233" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="2289,-2054.5 2289,-2537.5 "/>
<text text-anchor="middle" x="2299.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2310,-2054.5 2310,-2537.5 "/>
<text text-anchor="middle" x="2471.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2310,-2514.5 2633,-2514.5 "/>
<text text-anchor="middle" x="2471.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="2310,-2491.5 2633,-2491.5 "/>
<text text-anchor="middle" x="2471.5" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2310,-2468.5 2633,-2468.5 "/>
<text text-anchor="middle" x="2471.5" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2310,-2445.5 2633,-2445.5 "/>
<text text-anchor="middle" x="2471.5" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2310,-2422.5 2633,-2422.5 "/>
<text text-anchor="middle" x="2471.5" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2310,-2399.5 2633,-2399.5 "/>
<text text-anchor="middle" x="2471.5" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2310,-2376.5 2633,-2376.5 "/>
<text text-anchor="middle" x="2471.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2310,-2353.5 2633,-2353.5 "/>
<text text-anchor="middle" x="2471.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2310,-2330.5 2633,-2330.5 "/>
<text text-anchor="middle" x="2471.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2310,-2307.5 2633,-2307.5 "/>
<text text-anchor="middle" x="2471.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2310,-2284.5 2633,-2284.5 "/>
<text text-anchor="middle" x="2471.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="2310,-2261.5 2633,-2261.5 "/>
<text text-anchor="middle" x="2471.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="2310,-2238.5 2633,-2238.5 "/>
<text text-anchor="middle" x="2471.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="2310,-2215.5 2633,-2215.5 "/>
<text text-anchor="middle" x="2471.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2310,-2192.5 2633,-2192.5 "/>
<text text-anchor="middle" x="2471.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2310,-2169.5 2633,-2169.5 "/>
<text text-anchor="middle" x="2471.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2310,-2146.5 2633,-2146.5 "/>
<text text-anchor="middle" x="2471.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2310,-2123.5 2633,-2123.5 "/>
<text text-anchor="middle" x="2471.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2310,-2100.5 2633,-2100.5 "/>
<text text-anchor="middle" x="2471.5" y="-2085.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2310,-2077.5 2633,-2077.5 "/>
<text text-anchor="middle" x="2471.5" y="-2062.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2633,-2054.5 2633,-2537.5 "/>
<text text-anchor="middle" x="2643.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge13" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2415.5,-2054.4079C2415.5,-2040.3712 2415.5,-2026.4431 2415.5,-2012.8514"/>
<polygon fill="#000000" stroke="#000000" points="2419.0001,-2012.5272 2415.5,-2002.5272 2412.0001,-2012.5272 2419.0001,-2012.5272"/>
<text text-anchor="middle" x="2437.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2197.5,-259.5C2197.5,-259.5 2513.5,-259.5 2513.5,-259.5 2519.5,-259.5 2525.5,-265.5 2525.5,-271.5 2525.5,-271.5 2525.5,-845.5 2525.5,-845.5 2525.5,-851.5 2519.5,-857.5 2513.5,-857.5 2513.5,-857.5 2197.5,-857.5 2197.5,-857.5 2191.5,-857.5 2185.5,-851.5 2185.5,-845.5 2185.5,-845.5 2185.5,-271.5 2185.5,-271.5 2185.5,-265.5 2191.5,-259.5 2197.5,-259.5"/>
<text text-anchor="middle" x="2213.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2241.5,-259.5 2241.5,-857.5 "/>
<text text-anchor="middle" x="2252" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2262.5,-259.5 2262.5,-857.5 "/>
<text text-anchor="middle" x="2383.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2262.5,-834.5 2504.5,-834.5 "/>
<text text-anchor="middle" x="2383.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2262.5,-811.5 2504.5,-811.5 "/>
<text text-anchor="middle" x="2383.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="2262.5,-788.5 2504.5,-788.5 "/>
<text text-anchor="middle" x="2383.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="2262.5,-765.5 2504.5,-765.5 "/>
<text text-anchor="middle" x="2383.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="2262.5,-742.5 2504.5,-742.5 "/>
<text text-anchor="middle" x="2383.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="2262.5,-719.5 2504.5,-719.5 "/>
<text text-anchor="middle" x="2383.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="2262.5,-696.5 2504.5,-696.5 "/>
<text text-anchor="middle" x="2383.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="2262.5,-673.5 2504.5,-673.5 "/>
<text text-anchor="middle" x="2383.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2262.5,-650.5 2504.5,-650.5 "/>
<text text-anchor="middle" x="2383.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2262.5,-627.5 2504.5,-627.5 "/>
<text text-anchor="middle" x="2383.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2262.5,-604.5 2504.5,-604.5 "/>
<text text-anchor="middle" x="2383.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2262.5,-581.5 2504.5,-581.5 "/>
<text text-anchor="middle" x="2383.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="2262.5,-558.5 2504.5,-558.5 "/>
<text text-anchor="middle" x="2383.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="2262.5,-535.5 2504.5,-535.5 "/>
<text text-anchor="middle" x="2383.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2262.5,-512.5 2504.5,-512.5 "/>
<text text-anchor="middle" x="2383.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="2262.5,-489.5 2504.5,-489.5 "/>
<text text-anchor="middle" x="2383.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2262.5,-466.5 2504.5,-466.5 "/>
<text text-anchor="middle" x="2383.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="2262.5,-443.5 2504.5,-443.5 "/>
<text text-anchor="middle" x="2383.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="2262.5,-420.5 2504.5,-420.5 "/>
<text text-anchor="middle" x="2383.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2262.5,-397.5 2504.5,-397.5 "/>
<text text-anchor="middle" x="2383.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="2262.5,-374.5 2504.5,-374.5 "/>
<text text-anchor="middle" x="2383.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2262.5,-351.5 2504.5,-351.5 "/>
<text text-anchor="middle" x="2383.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2262.5,-328.5 2504.5,-328.5 "/>
<text text-anchor="middle" x="2383.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2262.5,-305.5 2504.5,-305.5 "/>
<text text-anchor="middle" x="2383.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="2262.5,-282.5 2504.5,-282.5 "/>
<text text-anchor="middle" x="2383.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="2504.5,-259.5 2504.5,-857.5 "/>
<text text-anchor="middle" x="2515" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge18" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2355.5,-259.4595C2355.5,-244.999 2355.5,-230.9707 2355.5,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="2359.0001,-217.5945 2355.5,-207.5945 2352.0001,-217.5946 2359.0001,-217.5945"/>
<text text-anchor="middle" x="2397" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- NonDICOMradiologyAllModalities -->
<g id="node10" class="node">
<title>NonDICOMradiologyAllModalities</title>
<path fill="none" stroke="#000000" d="M1973,-2681.5C1973,-2681.5 2746,-2681.5 2746,-2681.5 2752,-2681.5 2758,-2687.5 2758,-2693.5 2758,-2693.5 2758,-3083.5 2758,-3083.5 2758,-3089.5 2752,-3095.5 2746,-3095.5 2746,-3095.5 1973,-3095.5 1973,-3095.5 1967,-3095.5 1961,-3089.5 1961,-3083.5 1961,-3083.5 1961,-2693.5 1961,-2693.5 1961,-2687.5 1967,-2681.5 1973,-2681.5"/>
<text text-anchor="middle" x="2092.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities</text>
<polyline fill="none" stroke="#000000" points="2224,-2681.5 2224,-3095.5 "/>
<text text-anchor="middle" x="2234.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2245,-2681.5 2245,-3095.5 "/>
<text text-anchor="middle" x="2491" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities_id</text>
<polyline fill="none" stroke="#000000" points="2245,-3072.5 2737,-3072.5 "/>
<text text-anchor="middle" x="2491" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_acquisitionTypeCode</text>
<polyline fill="none" stroke="#000000" points="2245,-3049.5 2737,-3049.5 "/>
<text text-anchor="middle" x="2491" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_admittingDiagnosisCode</text>
<polyline fill="none" stroke="#000000" points="2245,-3026.5 2737,-3026.5 "/>
<text text-anchor="middle" x="2491" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_algorithmCode</text>
<polyline fill="none" stroke="#000000" points="2245,-3003.5 2737,-3003.5 "/>
<text text-anchor="middle" x="2491" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_bodyPositionCode</text>
<polyline fill="none" stroke="#000000" points="2245,-2980.5 2737,-2980.5 "/>
<text text-anchor="middle" x="2491" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_cardiacSynchronizationTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="2245,-2957.5 2737,-2957.5 "/>
<text text-anchor="middle" x="2491" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_dataCollectionDiameter</text>
<polyline fill="none" stroke="#000000" points="2245,-2934.5 2737,-2934.5 "/>
<text text-anchor="middle" x="2491" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_description</text>
<polyline fill="none" stroke="#000000" points="2245,-2911.5 2737,-2911.5 "/>
<text text-anchor="middle" x="2491" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_lossyImageCompressionIndicator</text>
<polyline fill="none" stroke="#000000" points="2245,-2888.5 2737,-2888.5 "/>
<text text-anchor="middle" x="2491" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_nonAcquisitionModalitiesInStudyCode</text>
<polyline fill="none" stroke="#000000" points="2245,-2865.5 2737,-2865.5 "/>
<text text-anchor="middle" x="2491" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_primaryAnatomicSiteCode</text>
<polyline fill="none" stroke="#000000" points="2245,-2842.5 2737,-2842.5 "/>
<text text-anchor="middle" x="2491" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionDiameter</text>
<polyline fill="none" stroke="#000000" points="2245,-2819.5 2737,-2819.5 "/>
<text text-anchor="middle" x="2491" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewHeight</text>
<polyline fill="none" stroke="#000000" points="2245,-2796.5 2737,-2796.5 "/>
<text text-anchor="middle" x="2491" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewWidth</text>
<polyline fill="none" stroke="#000000" points="2245,-2773.5 2737,-2773.5 "/>
<text text-anchor="middle" x="2491" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionInterval</text>
<polyline fill="none" stroke="#000000" points="2245,-2750.5 2737,-2750.5 "/>
<text text-anchor="middle" x="2491" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_respiratoryMotionTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="2245,-2727.5 2737,-2727.5 "/>
<text text-anchor="middle" x="2491" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_sliceThickness</text>
<polyline fill="none" stroke="#000000" points="2245,-2704.5 2737,-2704.5 "/>
<text text-anchor="middle" x="2491" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_summary</text>
<polyline fill="none" stroke="#000000" points="2737,-2681.5 2737,-3095.5 "/>
<text text-anchor="middle" x="2747.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMradiologyAllModalities&#45;&gt;image -->
<g id="edge7" class="edge">
<title>NonDICOMradiologyAllModalities&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2221.3482,-2681.2723C2179.7021,-2618.8032 2134.1748,-2550.5122 2093.1714,-2489.0071"/>
<polygon fill="#000000" stroke="#000000" points="2095.8758,-2486.7538 2087.4165,-2480.3748 2090.0514,-2490.6368 2095.8758,-2486.7538"/>
<text text-anchor="middle" x="2171" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- treatment -->
<g id="node11" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M3290.5,-1329.5C3290.5,-1329.5 3552.5,-1329.5 3552.5,-1329.5 3558.5,-1329.5 3564.5,-1335.5 3564.5,-1341.5 3564.5,-1341.5 3564.5,-1455.5 3564.5,-1455.5 3564.5,-1461.5 3558.5,-1467.5 3552.5,-1467.5 3552.5,-1467.5 3290.5,-1467.5 3290.5,-1467.5 3284.5,-1467.5 3278.5,-1461.5 3278.5,-1455.5 3278.5,-1455.5 3278.5,-1341.5 3278.5,-1341.5 3278.5,-1335.5 3284.5,-1329.5 3290.5,-1329.5"/>
<text text-anchor="middle" x="3323" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="3367.5,-1329.5 3367.5,-1467.5 "/>
<text text-anchor="middle" x="3378" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3388.5,-1329.5 3388.5,-1467.5 "/>
<text text-anchor="middle" x="3466" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="3388.5,-1444.5 3543.5,-1444.5 "/>
<text text-anchor="middle" x="3466" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="3388.5,-1421.5 3543.5,-1421.5 "/>
<text text-anchor="middle" x="3466" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="3388.5,-1398.5 3543.5,-1398.5 "/>
<text text-anchor="middle" x="3466" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="3388.5,-1375.5 3543.5,-1375.5 "/>
<text text-anchor="middle" x="3466" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="3388.5,-1352.5 3543.5,-1352.5 "/>
<text text-anchor="middle" x="3466" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3543.5,-1329.5 3543.5,-1467.5 "/>
<text text-anchor="middle" x="3554" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3397.445,-1329.3664C3373.7714,-1271.5126 3332.0147,-1191.2159 3269.5,-1145 3203.6579,-1096.3242 2998.4465,-1053.1102 2850.8012,-1027.1332"/>
<polygon fill="#000000" stroke="#000000" points="2851.1708,-1023.6448 2840.7174,-1025.3701 2849.9651,-1030.5402 2851.1708,-1023.6448"/>
<text text-anchor="middle" x="3288" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2620.0922,-909.4411C2594.0564,-874.9086 2563.1452,-833.9096 2531.7958,-792.3294"/>
<polygon fill="#000000" stroke="#000000" points="2534.5451,-790.1621 2525.7302,-784.2843 2528.9557,-794.3762 2534.5451,-790.1621"/>
<text text-anchor="middle" x="2631" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- proteomic -->
<g id="node13" class="node">
<title>proteomic</title>
<path fill="none" stroke="#000000" d="M2684.5,-2215.5C2684.5,-2215.5 3024.5,-2215.5 3024.5,-2215.5 3030.5,-2215.5 3036.5,-2221.5 3036.5,-2227.5 3036.5,-2227.5 3036.5,-2364.5 3036.5,-2364.5 3036.5,-2370.5 3030.5,-2376.5 3024.5,-2376.5 3024.5,-2376.5 2684.5,-2376.5 2684.5,-2376.5 2678.5,-2376.5 2672.5,-2370.5 2672.5,-2364.5 2672.5,-2364.5 2672.5,-2227.5 2672.5,-2227.5 2672.5,-2221.5 2678.5,-2215.5 2684.5,-2215.5"/>
<text text-anchor="middle" x="2717" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic</text>
<polyline fill="none" stroke="#000000" points="2761.5,-2215.5 2761.5,-2376.5 "/>
<text text-anchor="middle" x="2772" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2782.5,-2215.5 2782.5,-2376.5 "/>
<text text-anchor="middle" x="2899" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="2782.5,-2353.5 3015.5,-2353.5 "/>
<text text-anchor="middle" x="2899" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fractions</text>
<polyline fill="none" stroke="#000000" points="2782.5,-2330.5 3015.5,-2330.5 "/>
<text text-anchor="middle" x="2899" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_make</text>
<polyline fill="none" stroke="#000000" points="2782.5,-2307.5 3015.5,-2307.5 "/>
<text text-anchor="middle" x="2899" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer_model_name</text>
<polyline fill="none" stroke="#000000" points="2782.5,-2284.5 3015.5,-2284.5 "/>
<text text-anchor="middle" x="2899" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_design_description</text>
<polyline fill="none" stroke="#000000" points="2782.5,-2261.5 3015.5,-2261.5 "/>
<text text-anchor="middle" x="2899" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2782.5,-2238.5 3015.5,-2238.5 "/>
<text text-anchor="middle" x="2899" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_instrument_model</text>
<polyline fill="none" stroke="#000000" points="3015.5,-2215.5 3015.5,-2376.5 "/>
<text text-anchor="middle" x="3026" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- proteomic&#45;&gt;file -->
<g id="edge14" class="edge">
<title>proteomic&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2797.3939,-2215.2849C2761.1771,-2166.4205 2711.9646,-2104.0809 2662.5,-2054 2647.6761,-2038.9914 2631.7839,-2023.9915 2615.4713,-2009.3312"/>
<polygon fill="#000000" stroke="#000000" points="2617.7412,-2006.6658 2607.9491,-2002.6204 2613.0812,-2011.8893 2617.7412,-2006.6658"/>
<text text-anchor="middle" x="2666.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- NonDICOMpathologyImages -->
<g id="node14" class="node">
<title>NonDICOMpathologyImages</title>
<path fill="none" stroke="#000000" d="M2788,-2773.5C2788,-2773.5 3275,-2773.5 3275,-2773.5 3281,-2773.5 3287,-2779.5 3287,-2785.5 3287,-2785.5 3287,-2991.5 3287,-2991.5 3287,-2997.5 3281,-3003.5 3275,-3003.5 3275,-3003.5 2788,-3003.5 2788,-3003.5 2782,-3003.5 2776,-2997.5 2776,-2991.5 2776,-2991.5 2776,-2785.5 2776,-2785.5 2776,-2779.5 2782,-2773.5 2788,-2773.5"/>
<text text-anchor="middle" x="2888" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages</text>
<polyline fill="none" stroke="#000000" points="3000,-2773.5 3000,-3003.5 "/>
<text text-anchor="middle" x="3010.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3021,-2773.5 3021,-3003.5 "/>
<text text-anchor="middle" x="3143.5" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages_id</text>
<polyline fill="none" stroke="#000000" points="3021,-2980.5 3266,-2980.5 "/>
<text text-anchor="middle" x="3143.5" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="3021,-2957.5 3266,-2957.5 "/>
<text text-anchor="middle" x="3143.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="3021,-2934.5 3266,-2934.5 "/>
<text text-anchor="middle" x="3143.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="3021,-2911.5 3266,-2911.5 "/>
<text text-anchor="middle" x="3143.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="3021,-2888.5 3266,-2888.5 "/>
<text text-anchor="middle" x="3143.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="3021,-2865.5 3266,-2865.5 "/>
<text text-anchor="middle" x="3143.5" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">objective</text>
<polyline fill="none" stroke="#000000" points="3021,-2842.5 3266,-2842.5 "/>
<text text-anchor="middle" x="3143.5" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="3021,-2819.5 3266,-2819.5 "/>
<text text-anchor="middle" x="3143.5" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_fixative</text>
<polyline fill="none" stroke="#000000" points="3021,-2796.5 3266,-2796.5 "/>
<text text-anchor="middle" x="3143.5" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_type</text>
<polyline fill="none" stroke="#000000" points="3266,-2773.5 3266,-3003.5 "/>
<text text-anchor="middle" x="3276.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMpathologyImages&#45;&gt;image -->
<g id="edge10" class="edge">
<title>NonDICOMpathologyImages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2961.7832,-2773.225C2915.2531,-2707.3091 2847.7659,-2629.8404 2766.5,-2589 2647.1332,-2529.0119 2286.0653,-2599.5571 2167.5,-2538 2142.2488,-2524.89 2118.8947,-2507.154 2097.706,-2487.2056"/>
<polygon fill="#000000" stroke="#000000" points="2099.9285,-2484.4864 2090.3021,-2480.0613 2095.0679,-2489.5237 2099.9285,-2484.4864"/>
<text text-anchor="middle" x="2736" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMMRimages -->
<g id="node15" class="node">
<title>NonDICOMMRimages</title>
<path fill="none" stroke="#000000" d="M3317,-2681.5C3317,-2681.5 4066,-2681.5 4066,-2681.5 4072,-2681.5 4078,-2687.5 4078,-2693.5 4078,-2693.5 4078,-3083.5 4078,-3083.5 4078,-3089.5 4072,-3095.5 4066,-3095.5 4066,-3095.5 3317,-3095.5 3317,-3095.5 3311,-3095.5 3305,-3089.5 3305,-3083.5 3305,-3083.5 3305,-2693.5 3305,-2693.5 3305,-2687.5 3311,-2681.5 3317,-2681.5"/>
<text text-anchor="middle" x="3393.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages</text>
<polyline fill="none" stroke="#000000" points="3482,-2681.5 3482,-3095.5 "/>
<text text-anchor="middle" x="3492.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3503,-2681.5 3503,-3095.5 "/>
<text text-anchor="middle" x="3780" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="3503,-3072.5 4057,-3072.5 "/>
<text text-anchor="middle" x="3780" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="3503,-3049.5 4057,-3049.5 "/>
<text text-anchor="middle" x="3780" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="3503,-3026.5 4057,-3026.5 "/>
<text text-anchor="middle" x="3780" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="3503,-3003.5 4057,-3003.5 "/>
<text text-anchor="middle" x="3780" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2980.5 4057,-2980.5 "/>
<text text-anchor="middle" x="3780" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2957.5 4057,-2957.5 "/>
<text text-anchor="middle" x="3780" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2934.5 4057,-2934.5 "/>
<text text-anchor="middle" x="3780" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="3503,-2911.5 4057,-2911.5 "/>
<text text-anchor="middle" x="3780" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2888.5 4057,-2888.5 "/>
<text text-anchor="middle" x="3780" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2865.5 4057,-2865.5 "/>
<text text-anchor="middle" x="3780" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="3503,-2842.5 4057,-2842.5 "/>
<text text-anchor="middle" x="3780" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2819.5 4057,-2819.5 "/>
<text text-anchor="middle" x="3780" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2796.5 4057,-2796.5 "/>
<text text-anchor="middle" x="3780" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2773.5 4057,-2773.5 "/>
<text text-anchor="middle" x="3780" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2750.5 4057,-2750.5 "/>
<text text-anchor="middle" x="3780" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_timeOfFlightContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2727.5 4057,-2727.5 "/>
<text text-anchor="middle" x="3780" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageReconstructionProtocolElement_complexImageComponentCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2704.5 4057,-2704.5 "/>
<text text-anchor="middle" x="3780" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages_id</text>
<polyline fill="none" stroke="#000000" points="4057,-2681.5 4057,-3095.5 "/>
<text text-anchor="middle" x="4067.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMMRimages&#45;&gt;image -->
<g id="edge12" class="edge">
<title>NonDICOMMRimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3463.6414,-2681.3454C3411.6512,-2644.4157 3354.2934,-2610.8132 3295.5,-2589 3077.1378,-2507.9846 3005.1563,-2566.798 2772.5,-2556 2738.9102,-2554.441 2197.7597,-2552.6649 2167.5,-2538 2141.2306,-2525.269 2117.1087,-2507.3687 2095.3769,-2486.9995"/>
<polygon fill="#000000" stroke="#000000" points="2097.7331,-2484.4096 2088.099,-2480.001 2092.8811,-2489.4552 2097.7331,-2484.4096"/>
<text text-anchor="middle" x="3267" y="-2559.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2546.5,-1283.5C2546.5,-1283.5 2832.5,-1283.5 2832.5,-1283.5 2838.5,-1283.5 2844.5,-1289.5 2844.5,-1295.5 2844.5,-1295.5 2844.5,-1501.5 2844.5,-1501.5 2844.5,-1507.5 2838.5,-1513.5 2832.5,-1513.5 2832.5,-1513.5 2546.5,-1513.5 2546.5,-1513.5 2540.5,-1513.5 2534.5,-1507.5 2534.5,-1501.5 2534.5,-1501.5 2534.5,-1295.5 2534.5,-1295.5 2534.5,-1289.5 2540.5,-1283.5 2546.5,-1283.5"/>
<text text-anchor="middle" x="2568.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2602.5,-1283.5 2602.5,-1513.5 "/>
<text text-anchor="middle" x="2613" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2623.5,-1283.5 2623.5,-1513.5 "/>
<text text-anchor="middle" x="2723.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1490.5 2823.5,-1490.5 "/>
<text text-anchor="middle" x="2723.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1467.5 2823.5,-1467.5 "/>
<text text-anchor="middle" x="2723.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1444.5 2823.5,-1444.5 "/>
<text text-anchor="middle" x="2723.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1421.5 2823.5,-1421.5 "/>
<text text-anchor="middle" x="2723.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1398.5 2823.5,-1398.5 "/>
<text text-anchor="middle" x="2723.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1375.5 2823.5,-1375.5 "/>
<text text-anchor="middle" x="2723.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1352.5 2823.5,-1352.5 "/>
<text text-anchor="middle" x="2723.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1329.5 2823.5,-1329.5 "/>
<text text-anchor="middle" x="2723.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2623.5,-1306.5 2823.5,-1306.5 "/>
<text text-anchor="middle" x="2723.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="2823.5,-1283.5 2823.5,-1513.5 "/>
<text text-anchor="middle" x="2834" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2689.5,-1283.4046C2689.5,-1226.6063 2689.5,-1158.6722 2689.5,-1103.7253"/>
<polygon fill="#000000" stroke="#000000" points="2693.0001,-1103.6223 2689.5,-1093.6223 2686.0001,-1103.6223 2693.0001,-1103.6223"/>
<text text-anchor="middle" x="2740" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2388.6145,-1703.4722C2386.1963,-1686.1614 2384.0717,-1668.7237 2382.5,-1652 2357.7046,-1388.1685 2351.9183,-1087.0573 2351.785,-867.6981"/>
<polygon fill="#000000" stroke="#000000" points="2355.2851,-867.6414 2351.7829,-857.6422 2348.2851,-867.643 2355.2851,-867.6414"/>
<text text-anchor="middle" x="2386" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2400.0759,-1703.1742C2384.5326,-1523.5594 2369.8605,-1235.4121 2424.5,-1145 2448.6394,-1105.0564 2488.1324,-1075.526 2529.3479,-1054.0017"/>
<polygon fill="#000000" stroke="#000000" points="2531.1055,-1057.0349 2538.4429,-1049.3921 2527.9409,-1050.791 2531.1055,-1057.0349"/>
<text text-anchor="middle" x="2475" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2505.7872,-1703.2352C2541.0877,-1644.6803 2581.0886,-1578.3284 2614.7316,-1522.5228"/>
<polygon fill="#000000" stroke="#000000" points="2617.9092,-1524.0308 2620.0748,-1513.6597 2611.9144,-1520.4167 2617.9092,-1524.0308"/>
<text text-anchor="middle" x="2567" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge1" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2617.6809,-1874.8677C2628.8527,-1869.55 2635.5,-1862.2607 2635.5,-1853 2635.5,-1846.4885 2632.2137,-1840.9518 2626.3789,-1836.3897"/>
<polygon fill="#000000" stroke="#000000" points="2628.0495,-1833.3098 2617.6809,-1831.1323 2624.4285,-1839.3005 2628.0495,-1833.3098"/>
<text text-anchor="middle" x="2693" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
</g>
</svg>
</div>
