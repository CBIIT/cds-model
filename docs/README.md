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
<g id="node3" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M1599,-2135C1599,-2135 1964,-2135 1964,-2135 1970,-2135 1976,-2141 1976,-2147 1976,-2147 1976,-2514 1976,-2514 1976,-2520 1970,-2526 1964,-2526 1964,-2526 1599,-2526 1599,-2526 1593,-2526 1587,-2520 1587,-2514 1587,-2514 1587,-2147 1587,-2147 1587,-2141 1593,-2135 1599,-2135"/>
<text text-anchor="middle" x="1617" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="1647,-2135 1647,-2526 "/>
<text text-anchor="middle" x="1657.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1668,-2135 1668,-2526 "/>
<text text-anchor="middle" x="1811.5" y="-2510.8" font-family="Times,serif" font-size="14.00" fill="#000000">citation_or_DOI</text>
<polyline fill="none" stroke="#000000" points="1668,-2503 1955,-2503 "/>
<text text-anchor="middle" x="1811.5" y="-2487.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1668,-2480 1955,-2480 "/>
<text text-anchor="middle" x="1811.5" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_description</text>
<polyline fill="none" stroke="#000000" points="1668,-2457 1955,-2457 "/>
<text text-anchor="middle" x="1811.5" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_type</text>
<polyline fill="none" stroke="#000000" points="1668,-2434 1955,-2434 "/>
<text text-anchor="middle" x="1811.5" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_software</text>
<polyline fill="none" stroke="#000000" points="1668,-2411 1955,-2411 "/>
<text text-anchor="middle" x="1811.5" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1668,-2388 1955,-2388 "/>
<text text-anchor="middle" x="1811.5" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_manufacturer</text>
<polyline fill="none" stroke="#000000" points="1668,-2365 1955,-2365 "/>
<text text-anchor="middle" x="1811.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_model</text>
<polyline fill="none" stroke="#000000" points="1668,-2342 1955,-2342 "/>
<text text-anchor="middle" x="1811.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_protocol</text>
<polyline fill="none" stroke="#000000" points="1668,-2319 1955,-2319 "/>
<text text-anchor="middle" x="1811.5" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_software</text>
<polyline fill="none" stroke="#000000" points="1668,-2296 1955,-2296 "/>
<text text-anchor="middle" x="1811.5" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">license</text>
<polyline fill="none" stroke="#000000" points="1668,-2273 1955,-2273 "/>
<text text-anchor="middle" x="1811.5" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_offset</text>
<polyline fill="none" stroke="#000000" points="1668,-2250 1955,-2250 "/>
<text text-anchor="middle" x="1811.5" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_type</text>
<polyline fill="none" stroke="#000000" points="1668,-2227 1955,-2227 "/>
<text text-anchor="middle" x="1811.5" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">organ_or_tissue</text>
<polyline fill="none" stroke="#000000" points="1668,-2204 1955,-2204 "/>
<text text-anchor="middle" x="1811.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_typeCode</text>
<polyline fill="none" stroke="#000000" points="1668,-2181 1955,-2181 "/>
<text text-anchor="middle" x="1811.5" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1668,-2158 1955,-2158 "/>
<text text-anchor="middle" x="1811.5" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_link_id</text>
<polyline fill="none" stroke="#000000" points="1955,-2135 1955,-2526 "/>
<text text-anchor="middle" x="1965.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMPETimages&#45;&gt;image -->
<g id="edge9" class="edge">
<title>NonDICOMPETimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M376.4788,-2865.231C436.1849,-2799.0815 555.2193,-2678.1811 681.5,-2612 971.3937,-2460.0727 1347.9548,-2386.8059 1576.8265,-2354.0727"/>
<polygon fill="#000000" stroke="#000000" points="1577.5255,-2357.5087 1586.9352,-2352.6396 1576.5429,-2350.578 1577.5255,-2357.5087"/>
<text text-anchor="middle" x="769" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- program -->
<g id="node2" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M2660.5,-.5C2660.5,-.5 2968.5,-.5 2968.5,-.5 2974.5,-.5 2980.5,-6.5 2980.5,-12.5 2980.5,-12.5 2980.5,-195.5 2980.5,-195.5 2980.5,-201.5 2974.5,-207.5 2968.5,-207.5 2968.5,-207.5 2660.5,-207.5 2660.5,-207.5 2654.5,-207.5 2648.5,-201.5 2648.5,-195.5 2648.5,-195.5 2648.5,-12.5 2648.5,-12.5 2648.5,-6.5 2654.5,-.5 2660.5,-.5"/>
<text text-anchor="middle" x="2687.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="2726.5,-.5 2726.5,-207.5 "/>
<text text-anchor="middle" x="2737" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2747.5,-.5 2747.5,-207.5 "/>
<text text-anchor="middle" x="2853.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2747.5,-184.5 2959.5,-184.5 "/>
<text text-anchor="middle" x="2853.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2747.5,-161.5 2959.5,-161.5 "/>
<text text-anchor="middle" x="2853.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="2747.5,-138.5 2959.5,-138.5 "/>
<text text-anchor="middle" x="2853.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="2747.5,-115.5 2959.5,-115.5 "/>
<text text-anchor="middle" x="2853.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="2747.5,-92.5 2959.5,-92.5 "/>
<text text-anchor="middle" x="2853.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="2747.5,-69.5 2959.5,-69.5 "/>
<text text-anchor="middle" x="2853.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="2747.5,-46.5 2959.5,-46.5 "/>
<text text-anchor="middle" x="2853.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="2747.5,-23.5 2959.5,-23.5 "/>
<text text-anchor="middle" x="2853.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="2959.5,-.5 2959.5,-207.5 "/>
<text text-anchor="middle" x="2970" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node10" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M1986.5,-1703.5C1986.5,-1703.5 2366.5,-1703.5 2366.5,-1703.5 2372.5,-1703.5 2378.5,-1709.5 2378.5,-1715.5 2378.5,-1715.5 2378.5,-2036.5 2378.5,-2036.5 2378.5,-2042.5 2372.5,-2048.5 2366.5,-2048.5 2366.5,-2048.5 1986.5,-2048.5 1986.5,-2048.5 1980.5,-2048.5 1974.5,-2042.5 1974.5,-2036.5 1974.5,-2036.5 1974.5,-1715.5 1974.5,-1715.5 1974.5,-1709.5 1980.5,-1703.5 1986.5,-1703.5"/>
<text text-anchor="middle" x="1994" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2013.5,-1703.5 2013.5,-2048.5 "/>
<text text-anchor="middle" x="2024" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2034.5,-1703.5 2034.5,-2048.5 "/>
<text text-anchor="middle" x="2196" y="-2033.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="2034.5,-2025.5 2357.5,-2025.5 "/>
<text text-anchor="middle" x="2196" y="-2010.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="2034.5,-2002.5 2357.5,-2002.5 "/>
<text text-anchor="middle" x="2196" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1979.5 2357.5,-1979.5 "/>
<text text-anchor="middle" x="2196" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1956.5 2357.5,-1956.5 "/>
<text text-anchor="middle" x="2196" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1933.5 2357.5,-1933.5 "/>
<text text-anchor="middle" x="2196" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1910.5 2357.5,-1910.5 "/>
<text text-anchor="middle" x="2196" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1887.5 2357.5,-1887.5 "/>
<text text-anchor="middle" x="2196" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1864.5 2357.5,-1864.5 "/>
<text text-anchor="middle" x="2196" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1841.5 2357.5,-1841.5 "/>
<text text-anchor="middle" x="2196" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1818.5 2357.5,-1818.5 "/>
<text text-anchor="middle" x="2196" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1795.5 2357.5,-1795.5 "/>
<text text-anchor="middle" x="2196" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_supplementary_file</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1772.5 2357.5,-1772.5 "/>
<text text-anchor="middle" x="2196" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1749.5 2357.5,-1749.5 "/>
<text text-anchor="middle" x="2196" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">release_datetime</text>
<polyline fill="none" stroke="#000000" points="2034.5,-1726.5 2357.5,-1726.5 "/>
<text text-anchor="middle" x="2196" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="2357.5,-1703.5 2357.5,-2048.5 "/>
<text text-anchor="middle" x="2368" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge17" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M1951.5947,-2134.7834C1974.2258,-2108.7433 1997.3465,-2082.1399 2019.7369,-2056.3768"/>
<polygon fill="#000000" stroke="#000000" points="2022.427,-2058.617 2026.345,-2048.7733 2017.1435,-2054.0252 2022.427,-2058.617"/>
<text text-anchor="middle" x="2025.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2033.5,-1283.5C2033.5,-1283.5 2319.5,-1283.5 2319.5,-1283.5 2325.5,-1283.5 2331.5,-1289.5 2331.5,-1295.5 2331.5,-1295.5 2331.5,-1501.5 2331.5,-1501.5 2331.5,-1507.5 2325.5,-1513.5 2319.5,-1513.5 2319.5,-1513.5 2033.5,-1513.5 2033.5,-1513.5 2027.5,-1513.5 2021.5,-1507.5 2021.5,-1501.5 2021.5,-1501.5 2021.5,-1295.5 2021.5,-1295.5 2021.5,-1289.5 2027.5,-1283.5 2033.5,-1283.5"/>
<text text-anchor="middle" x="2055.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2089.5,-1283.5 2089.5,-1513.5 "/>
<text text-anchor="middle" x="2100" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2110.5,-1283.5 2110.5,-1513.5 "/>
<text text-anchor="middle" x="2210.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1490.5 2310.5,-1490.5 "/>
<text text-anchor="middle" x="2210.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1467.5 2310.5,-1467.5 "/>
<text text-anchor="middle" x="2210.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1444.5 2310.5,-1444.5 "/>
<text text-anchor="middle" x="2210.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1421.5 2310.5,-1421.5 "/>
<text text-anchor="middle" x="2210.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1398.5 2310.5,-1398.5 "/>
<text text-anchor="middle" x="2210.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1375.5 2310.5,-1375.5 "/>
<text text-anchor="middle" x="2210.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1352.5 2310.5,-1352.5 "/>
<text text-anchor="middle" x="2210.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1329.5 2310.5,-1329.5 "/>
<text text-anchor="middle" x="2210.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2110.5,-1306.5 2310.5,-1306.5 "/>
<text text-anchor="middle" x="2210.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="2310.5,-1283.5 2310.5,-1513.5 "/>
<text text-anchor="middle" x="2321" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M2409.5,-909.5C2409.5,-909.5 2687.5,-909.5 2687.5,-909.5 2693.5,-909.5 2699.5,-915.5 2699.5,-921.5 2699.5,-921.5 2699.5,-1081.5 2699.5,-1081.5 2699.5,-1087.5 2693.5,-1093.5 2687.5,-1093.5 2687.5,-1093.5 2409.5,-1093.5 2409.5,-1093.5 2403.5,-1093.5 2397.5,-1087.5 2397.5,-1081.5 2397.5,-1081.5 2397.5,-921.5 2397.5,-921.5 2397.5,-915.5 2403.5,-909.5 2409.5,-909.5"/>
<text text-anchor="middle" x="2445.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="2493.5,-909.5 2493.5,-1093.5 "/>
<text text-anchor="middle" x="2504" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2514.5,-909.5 2514.5,-1093.5 "/>
<text text-anchor="middle" x="2596.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2514.5,-1070.5 2678.5,-1070.5 "/>
<text text-anchor="middle" x="2596.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="2514.5,-1047.5 2678.5,-1047.5 "/>
<text text-anchor="middle" x="2596.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2514.5,-1024.5 2678.5,-1024.5 "/>
<text text-anchor="middle" x="2596.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="2514.5,-1001.5 2678.5,-1001.5 "/>
<text text-anchor="middle" x="2596.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2514.5,-978.5 2678.5,-978.5 "/>
<text text-anchor="middle" x="2596.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2514.5,-955.5 2678.5,-955.5 "/>
<text text-anchor="middle" x="2596.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="2514.5,-932.5 2678.5,-932.5 "/>
<text text-anchor="middle" x="2596.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="2678.5,-909.5 2678.5,-1093.5 "/>
<text text-anchor="middle" x="2689" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2237.8331,-1283.3325C2265.5556,-1237.3225 2300.9776,-1185.7138 2340.5,-1145 2355.8033,-1129.2354 2373.0791,-1114.1471 2390.9702,-1100.0737"/>
<polygon fill="#000000" stroke="#000000" points="2393.464,-1102.5694 2399.2288,-1093.6803 2389.1788,-1097.0343 2393.464,-1102.5694"/>
<text text-anchor="middle" x="2427" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- NonDICOMpathologyImages -->
<g id="node5" class="node">
<title>NonDICOMpathologyImages</title>
<path fill="none" stroke="#000000" d="M703,-2785C703,-2785 1190,-2785 1190,-2785 1196,-2785 1202,-2791 1202,-2797 1202,-2797 1202,-3026 1202,-3026 1202,-3032 1196,-3038 1190,-3038 1190,-3038 703,-3038 703,-3038 697,-3038 691,-3032 691,-3026 691,-3026 691,-2797 691,-2797 691,-2791 697,-2785 703,-2785"/>
<text text-anchor="middle" x="803" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages</text>
<polyline fill="none" stroke="#000000" points="915,-2785 915,-3038 "/>
<text text-anchor="middle" x="925.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="936,-2785 936,-3038 "/>
<text text-anchor="middle" x="1058.5" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMpathologyImages_id</text>
<polyline fill="none" stroke="#000000" points="936,-3015 1181,-3015 "/>
<text text-anchor="middle" x="1058.5" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="936,-2992 1181,-2992 "/>
<text text-anchor="middle" x="1058.5" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="936,-2969 1181,-2969 "/>
<text text-anchor="middle" x="1058.5" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="936,-2946 1181,-2946 "/>
<text text-anchor="middle" x="1058.5" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="936,-2923 1181,-2923 "/>
<text text-anchor="middle" x="1058.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="936,-2900 1181,-2900 "/>
<text text-anchor="middle" x="1058.5" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="936,-2877 1181,-2877 "/>
<text text-anchor="middle" x="1058.5" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">objective</text>
<polyline fill="none" stroke="#000000" points="936,-2854 1181,-2854 "/>
<text text-anchor="middle" x="1058.5" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="936,-2831 1181,-2831 "/>
<text text-anchor="middle" x="1058.5" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_fixative</text>
<polyline fill="none" stroke="#000000" points="936,-2808 1181,-2808 "/>
<text text-anchor="middle" x="1058.5" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_type</text>
<polyline fill="none" stroke="#000000" points="1181,-2785 1181,-3038 "/>
<text text-anchor="middle" x="1191.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMpathologyImages&#45;&gt;image -->
<g id="edge4" class="edge">
<title>NonDICOMpathologyImages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1039.4159,-2784.9654C1086.196,-2727.2215 1146.5091,-2660.9671 1210.5,-2612 1322.0247,-2526.6591 1463.5035,-2456.6876 1577.7298,-2407.8518"/>
<polygon fill="#000000" stroke="#000000" points="1579.1164,-2411.0655 1586.9488,-2403.9308 1576.3767,-2404.6239 1579.1164,-2411.0655"/>
<text text-anchor="middle" x="1285" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- version -->
<g id="node6" class="node">
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
<!-- proteomic -->
<g id="node7" class="node">
<title>proteomic</title>
<path fill="none" stroke="#000000" d="M2006.5,-2238.5C2006.5,-2238.5 2346.5,-2238.5 2346.5,-2238.5 2352.5,-2238.5 2358.5,-2244.5 2358.5,-2250.5 2358.5,-2250.5 2358.5,-2410.5 2358.5,-2410.5 2358.5,-2416.5 2352.5,-2422.5 2346.5,-2422.5 2346.5,-2422.5 2006.5,-2422.5 2006.5,-2422.5 2000.5,-2422.5 1994.5,-2416.5 1994.5,-2410.5 1994.5,-2410.5 1994.5,-2250.5 1994.5,-2250.5 1994.5,-2244.5 2000.5,-2238.5 2006.5,-2238.5"/>
<text text-anchor="middle" x="2039" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic</text>
<polyline fill="none" stroke="#000000" points="2083.5,-2238.5 2083.5,-2422.5 "/>
<text text-anchor="middle" x="2094" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2104.5,-2238.5 2104.5,-2422.5 "/>
<text text-anchor="middle" x="2221" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_id</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2399.5 2337.5,-2399.5 "/>
<text text-anchor="middle" x="2221" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">analytical_fractions</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2376.5 2337.5,-2376.5 "/>
<text text-anchor="middle" x="2221" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2353.5 2337.5,-2353.5 "/>
<text text-anchor="middle" x="2221" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_make</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2330.5 2337.5,-2330.5 "/>
<text text-anchor="middle" x="2221" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer_model_name</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2307.5 2337.5,-2307.5 "/>
<text text-anchor="middle" x="2221" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_design_description</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2284.5 2337.5,-2284.5 "/>
<text text-anchor="middle" x="2221" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2104.5,-2261.5 2337.5,-2261.5 "/>
<text text-anchor="middle" x="2221" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">proteomic_instrument_model</text>
<polyline fill="none" stroke="#000000" points="2337.5,-2238.5 2337.5,-2422.5 "/>
<text text-anchor="middle" x="2348" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- proteomic&#45;&gt;file -->
<g id="edge18" class="edge">
<title>proteomic&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2176.5,-2238.2514C2176.5,-2186.6364 2176.5,-2120.446 2176.5,-2058.7976"/>
<polygon fill="#000000" stroke="#000000" points="2180.0001,-2058.5472 2176.5,-2048.5472 2173.0001,-2058.5472 2180.0001,-2058.5472"/>
<text text-anchor="middle" x="2198.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2361.5,-1145.5C2361.5,-1145.5 2735.5,-1145.5 2735.5,-1145.5 2741.5,-1145.5 2747.5,-1151.5 2747.5,-1157.5 2747.5,-1157.5 2747.5,-1639.5 2747.5,-1639.5 2747.5,-1645.5 2741.5,-1651.5 2735.5,-1651.5 2735.5,-1651.5 2361.5,-1651.5 2361.5,-1651.5 2355.5,-1651.5 2349.5,-1645.5 2349.5,-1639.5 2349.5,-1639.5 2349.5,-1157.5 2349.5,-1157.5 2349.5,-1151.5 2355.5,-1145.5 2361.5,-1145.5"/>
<text text-anchor="middle" x="2391.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2433.5,-1145.5 2433.5,-1651.5 "/>
<text text-anchor="middle" x="2444" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2454.5,-1145.5 2454.5,-1651.5 "/>
<text text-anchor="middle" x="2590.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1628.5 2726.5,-1628.5 "/>
<text text-anchor="middle" x="2590.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1605.5 2726.5,-1605.5 "/>
<text text-anchor="middle" x="2590.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1582.5 2726.5,-1582.5 "/>
<text text-anchor="middle" x="2590.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1559.5 2726.5,-1559.5 "/>
<text text-anchor="middle" x="2590.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1536.5 2726.5,-1536.5 "/>
<text text-anchor="middle" x="2590.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1513.5 2726.5,-1513.5 "/>
<text text-anchor="middle" x="2590.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1490.5 2726.5,-1490.5 "/>
<text text-anchor="middle" x="2590.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1467.5 2726.5,-1467.5 "/>
<text text-anchor="middle" x="2590.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1444.5 2726.5,-1444.5 "/>
<text text-anchor="middle" x="2590.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1421.5 2726.5,-1421.5 "/>
<text text-anchor="middle" x="2590.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1398.5 2726.5,-1398.5 "/>
<text text-anchor="middle" x="2590.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1375.5 2726.5,-1375.5 "/>
<text text-anchor="middle" x="2590.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1352.5 2726.5,-1352.5 "/>
<text text-anchor="middle" x="2590.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1329.5 2726.5,-1329.5 "/>
<text text-anchor="middle" x="2590.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1306.5 2726.5,-1306.5 "/>
<text text-anchor="middle" x="2590.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1283.5 2726.5,-1283.5 "/>
<text text-anchor="middle" x="2590.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1260.5 2726.5,-1260.5 "/>
<text text-anchor="middle" x="2590.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1237.5 2726.5,-1237.5 "/>
<text text-anchor="middle" x="2590.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1214.5 2726.5,-1214.5 "/>
<text text-anchor="middle" x="2590.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1191.5 2726.5,-1191.5 "/>
<text text-anchor="middle" x="2590.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2454.5,-1168.5 2726.5,-1168.5 "/>
<text text-anchor="middle" x="2590.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="2726.5,-1145.5 2726.5,-1651.5 "/>
<text text-anchor="middle" x="2737" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2548.5,-1145.3874C2548.5,-1131.0731 2548.5,-1117.1697 2548.5,-1104.0079"/>
<polygon fill="#000000" stroke="#000000" points="2552.0001,-1103.6176 2548.5,-1093.6177 2545.0001,-1103.6177 2552.0001,-1103.6176"/>
<text text-anchor="middle" x="2599" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genomic_info -->
<g id="node9" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M2389,-2100.5C2389,-2100.5 2842,-2100.5 2842,-2100.5 2848,-2100.5 2854,-2106.5 2854,-2112.5 2854,-2112.5 2854,-2548.5 2854,-2548.5 2854,-2554.5 2848,-2560.5 2842,-2560.5 2842,-2560.5 2389,-2560.5 2389,-2560.5 2383,-2560.5 2377,-2554.5 2377,-2548.5 2377,-2548.5 2377,-2112.5 2377,-2112.5 2377,-2106.5 2383,-2100.5 2389,-2100.5"/>
<text text-anchor="middle" x="2433" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="2489,-2100.5 2489,-2560.5 "/>
<text text-anchor="middle" x="2499.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2510,-2100.5 2510,-2560.5 "/>
<text text-anchor="middle" x="2671.5" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="2510,-2537.5 2833,-2537.5 "/>
<text text-anchor="middle" x="2671.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="2510,-2514.5 2833,-2514.5 "/>
<text text-anchor="middle" x="2671.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="2510,-2491.5 2833,-2491.5 "/>
<text text-anchor="middle" x="2671.5" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2510,-2468.5 2833,-2468.5 "/>
<text text-anchor="middle" x="2671.5" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="2510,-2445.5 2833,-2445.5 "/>
<text text-anchor="middle" x="2671.5" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="2510,-2422.5 2833,-2422.5 "/>
<text text-anchor="middle" x="2671.5" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="2510,-2399.5 2833,-2399.5 "/>
<text text-anchor="middle" x="2671.5" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="2510,-2376.5 2833,-2376.5 "/>
<text text-anchor="middle" x="2671.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="2510,-2353.5 2833,-2353.5 "/>
<text text-anchor="middle" x="2671.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="2510,-2330.5 2833,-2330.5 "/>
<text text-anchor="middle" x="2671.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="2510,-2307.5 2833,-2307.5 "/>
<text text-anchor="middle" x="2671.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="2510,-2284.5 2833,-2284.5 "/>
<text text-anchor="middle" x="2671.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="2510,-2261.5 2833,-2261.5 "/>
<text text-anchor="middle" x="2671.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="2510,-2238.5 2833,-2238.5 "/>
<text text-anchor="middle" x="2671.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="2510,-2215.5 2833,-2215.5 "/>
<text text-anchor="middle" x="2671.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="2510,-2192.5 2833,-2192.5 "/>
<text text-anchor="middle" x="2671.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="2510,-2169.5 2833,-2169.5 "/>
<text text-anchor="middle" x="2671.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="2510,-2146.5 2833,-2146.5 "/>
<text text-anchor="middle" x="2671.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="2510,-2123.5 2833,-2123.5 "/>
<text text-anchor="middle" x="2671.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="2833,-2100.5 2833,-2560.5 "/>
<text text-anchor="middle" x="2843.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge16" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2393.1063,-2100.2541C2378.8137,-2085.4569 2364.5375,-2070.6766 2350.5201,-2056.1643"/>
<polygon fill="#000000" stroke="#000000" points="2352.6796,-2053.3621 2343.2147,-2048.601 2347.6447,-2058.2253 2352.6796,-2053.3621"/>
<text text-anchor="middle" x="2392.5" y="-2070.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2176.5,-1703.274C2176.5,-1643.9501 2176.5,-1578.7236 2176.5,-1523.8875"/>
<polygon fill="#000000" stroke="#000000" points="2180.0001,-1523.7731 2176.5,-1513.7731 2173.0001,-1523.7731 2180.0001,-1523.7731"/>
<text text-anchor="middle" x="2223" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge1" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M2378.6809,-1900.8839C2389.8527,-1894.8327 2396.5,-1886.5381 2396.5,-1876 2396.5,-1868.4258 2393.066,-1862.0105 2386.9862,-1856.7542"/>
<polygon fill="#000000" stroke="#000000" points="2388.9204,-1853.8369 2378.6809,-1851.1161 2384.9887,-1859.6285 2388.9204,-1853.8369"/>
<text text-anchor="middle" x="2454" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1974.4622,-1740.1434C1948.9797,-1714.0123 1926.5893,-1684.5125 1911.5,-1652 1816.6396,-1447.6067 1770.7584,-1320.9742 1911.5,-1145 1970.0314,-1071.8161 2218.648,-1033.3077 2387.4127,-1015.2105"/>
<polygon fill="#000000" stroke="#000000" points="2387.8251,-1018.6865 2397.4011,-1014.1532 2387.0882,-1011.7254 2387.8251,-1018.6865"/>
<text text-anchor="middle" x="1962" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2656.5,-259.5C2656.5,-259.5 2972.5,-259.5 2972.5,-259.5 2978.5,-259.5 2984.5,-265.5 2984.5,-271.5 2984.5,-271.5 2984.5,-845.5 2984.5,-845.5 2984.5,-851.5 2978.5,-857.5 2972.5,-857.5 2972.5,-857.5 2656.5,-857.5 2656.5,-857.5 2650.5,-857.5 2644.5,-851.5 2644.5,-845.5 2644.5,-845.5 2644.5,-271.5 2644.5,-271.5 2644.5,-265.5 2650.5,-259.5 2656.5,-259.5"/>
<text text-anchor="middle" x="2672.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2700.5,-259.5 2700.5,-857.5 "/>
<text text-anchor="middle" x="2711" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2721.5,-259.5 2721.5,-857.5 "/>
<text text-anchor="middle" x="2842.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="2721.5,-834.5 2963.5,-834.5 "/>
<text text-anchor="middle" x="2842.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="2721.5,-811.5 2963.5,-811.5 "/>
<text text-anchor="middle" x="2842.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="2721.5,-788.5 2963.5,-788.5 "/>
<text text-anchor="middle" x="2842.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="2721.5,-765.5 2963.5,-765.5 "/>
<text text-anchor="middle" x="2842.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="2721.5,-742.5 2963.5,-742.5 "/>
<text text-anchor="middle" x="2842.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="2721.5,-719.5 2963.5,-719.5 "/>
<text text-anchor="middle" x="2842.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="2721.5,-696.5 2963.5,-696.5 "/>
<text text-anchor="middle" x="2842.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="2721.5,-673.5 2963.5,-673.5 "/>
<text text-anchor="middle" x="2842.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2721.5,-650.5 2963.5,-650.5 "/>
<text text-anchor="middle" x="2842.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2721.5,-627.5 2963.5,-627.5 "/>
<text text-anchor="middle" x="2842.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2721.5,-604.5 2963.5,-604.5 "/>
<text text-anchor="middle" x="2842.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="2721.5,-581.5 2963.5,-581.5 "/>
<text text-anchor="middle" x="2842.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="2721.5,-558.5 2963.5,-558.5 "/>
<text text-anchor="middle" x="2842.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="2721.5,-535.5 2963.5,-535.5 "/>
<text text-anchor="middle" x="2842.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2721.5,-512.5 2963.5,-512.5 "/>
<text text-anchor="middle" x="2842.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="2721.5,-489.5 2963.5,-489.5 "/>
<text text-anchor="middle" x="2842.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="2721.5,-466.5 2963.5,-466.5 "/>
<text text-anchor="middle" x="2842.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="2721.5,-443.5 2963.5,-443.5 "/>
<text text-anchor="middle" x="2842.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="2721.5,-420.5 2963.5,-420.5 "/>
<text text-anchor="middle" x="2842.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="2721.5,-397.5 2963.5,-397.5 "/>
<text text-anchor="middle" x="2842.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="2721.5,-374.5 2963.5,-374.5 "/>
<text text-anchor="middle" x="2842.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="2721.5,-351.5 2963.5,-351.5 "/>
<text text-anchor="middle" x="2842.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="2721.5,-328.5 2963.5,-328.5 "/>
<text text-anchor="middle" x="2842.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="2721.5,-305.5 2963.5,-305.5 "/>
<text text-anchor="middle" x="2842.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="2721.5,-282.5 2963.5,-282.5 "/>
<text text-anchor="middle" x="2842.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="2963.5,-259.5 2963.5,-857.5 "/>
<text text-anchor="middle" x="2974" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2378.7141,-1853.3757C2613.0086,-1822.5109 2977.6076,-1758.5166 3060.5,-1652 3243.9914,-1416.2138 3118.8881,-1069.9078 2989.3539,-830.4708"/>
<polygon fill="#000000" stroke="#000000" points="2992.4044,-828.754 2984.5502,-821.6434 2986.2559,-832.1 2992.4044,-828.754"/>
<text text-anchor="middle" x="3144" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- MultiplexMicroscopy -->
<g id="node11" class="node">
<title>MultiplexMicroscopy</title>
<path fill="none" stroke="#000000" d="M1232,-2612.5C1232,-2612.5 1697,-2612.5 1697,-2612.5 1703,-2612.5 1709,-2618.5 1709,-2624.5 1709,-2624.5 1709,-3198.5 1709,-3198.5 1709,-3204.5 1703,-3210.5 1697,-3210.5 1697,-3210.5 1232,-3210.5 1232,-3210.5 1226,-3210.5 1220,-3204.5 1220,-3198.5 1220,-3198.5 1220,-2624.5 1220,-2624.5 1220,-2618.5 1226,-2612.5 1232,-2612.5"/>
<text text-anchor="middle" x="1304" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">MultiplexMicroscopy</text>
<polyline fill="none" stroke="#000000" points="1388,-2612.5 1388,-3210.5 "/>
<text text-anchor="middle" x="1398.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1409,-2612.5 1409,-3210.5 "/>
<text text-anchor="middle" x="1548.5" y="-3195.3" font-family="Times,serif" font-size="14.00" fill="#000000">MultiplexMicroscopy_id</text>
<polyline fill="none" stroke="#000000" points="1409,-3187.5 1688,-3187.5 "/>
<text text-anchor="middle" x="1548.5" y="-3172.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="1409,-3164.5 1688,-3164.5 "/>
<text text-anchor="middle" x="1548.5" y="-3149.3" font-family="Times,serif" font-size="14.00" fill="#000000">antibody_name</text>
<polyline fill="none" stroke="#000000" points="1409,-3141.5 1688,-3141.5 "/>
<text text-anchor="middle" x="1548.5" y="-3126.3" font-family="Times,serif" font-size="14.00" fill="#000000">catalog_number</text>
<polyline fill="none" stroke="#000000" points="1409,-3118.5 1688,-3118.5 "/>
<text text-anchor="middle" x="1548.5" y="-3103.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_id</text>
<polyline fill="none" stroke="#000000" points="1409,-3095.5 1688,-3095.5 "/>
<text text-anchor="middle" x="1548.5" y="-3080.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1409,-3072.5 1688,-3072.5 "/>
<text text-anchor="middle" x="1548.5" y="-3057.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_filename</text>
<polyline fill="none" stroke="#000000" points="1409,-3049.5 1688,-3049.5 "/>
<text text-anchor="middle" x="1548.5" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_name</text>
<polyline fill="none" stroke="#000000" points="1409,-3026.5 1688,-3026.5 "/>
<text text-anchor="middle" x="1548.5" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">clone</text>
<polyline fill="none" stroke="#000000" points="1409,-3003.5 1688,-3003.5 "/>
<text text-anchor="middle" x="1548.5" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">concentration</text>
<polyline fill="none" stroke="#000000" points="1409,-2980.5 1688,-2980.5 "/>
<text text-anchor="middle" x="1548.5" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1409,-2957.5 1688,-2957.5 "/>
<text text-anchor="middle" x="1548.5" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">cycle_number</text>
<polyline fill="none" stroke="#000000" points="1409,-2934.5 1688,-2934.5 "/>
<text text-anchor="middle" x="1548.5" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">dilution</text>
<polyline fill="none" stroke="#000000" points="1409,-2911.5 1688,-2911.5 "/>
<text text-anchor="middle" x="1548.5" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="1409,-2888.5 1688,-2888.5 "/>
<text text-anchor="middle" x="1548.5" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_bandwidth</text>
<polyline fill="none" stroke="#000000" points="1409,-2865.5 1688,-2865.5 "/>
<text text-anchor="middle" x="1548.5" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_wavelength</text>
<polyline fill="none" stroke="#000000" points="1409,-2842.5 1688,-2842.5 "/>
<text text-anchor="middle" x="1548.5" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_bandwidth</text>
<polyline fill="none" stroke="#000000" points="1409,-2819.5 1688,-2819.5 "/>
<text text-anchor="middle" x="1548.5" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_wavelength</text>
<polyline fill="none" stroke="#000000" points="1409,-2796.5 1688,-2796.5 "/>
<text text-anchor="middle" x="1548.5" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">fluorophore</text>
<polyline fill="none" stroke="#000000" points="1409,-2773.5 1688,-2773.5 "/>
<text text-anchor="middle" x="1548.5" y="-2758.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_assay_type</text>
<polyline fill="none" stroke="#000000" points="1409,-2750.5 1688,-2750.5 "/>
<text text-anchor="middle" x="1548.5" y="-2735.3" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="1409,-2727.5 1688,-2727.5 "/>
<text text-anchor="middle" x="1548.5" y="-2712.3" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="1409,-2704.5 1688,-2704.5 "/>
<text text-anchor="middle" x="1548.5" y="-2689.3" font-family="Times,serif" font-size="14.00" fill="#000000">lot</text>
<polyline fill="none" stroke="#000000" points="1409,-2681.5 1688,-2681.5 "/>
<text text-anchor="middle" x="1548.5" y="-2666.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_abbreviation</text>
<polyline fill="none" stroke="#000000" points="1409,-2658.5 1688,-2658.5 "/>
<text text-anchor="middle" x="1548.5" y="-2643.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_mass</text>
<polyline fill="none" stroke="#000000" points="1409,-2635.5 1688,-2635.5 "/>
<text text-anchor="middle" x="1548.5" y="-2620.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="1688,-2612.5 1688,-3210.5 "/>
<text text-anchor="middle" x="1698.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- MultiplexMicroscopy&#45;&gt;image -->
<g id="edge8" class="edge">
<title>MultiplexMicroscopy&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M1627.643,-2612.4903C1641.9597,-2586.2504 1656.226,-2560.1032 1669.9739,-2534.9059"/>
<polygon fill="#000000" stroke="#000000" points="1673.0971,-2536.4892 1674.8143,-2526.0344 1666.9522,-2533.1364 1673.0971,-2536.4892"/>
<text text-anchor="middle" x="1675" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- treatment -->
<g id="node12" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M2777.5,-1329.5C2777.5,-1329.5 3039.5,-1329.5 3039.5,-1329.5 3045.5,-1329.5 3051.5,-1335.5 3051.5,-1341.5 3051.5,-1341.5 3051.5,-1455.5 3051.5,-1455.5 3051.5,-1461.5 3045.5,-1467.5 3039.5,-1467.5 3039.5,-1467.5 2777.5,-1467.5 2777.5,-1467.5 2771.5,-1467.5 2765.5,-1461.5 2765.5,-1455.5 2765.5,-1455.5 2765.5,-1341.5 2765.5,-1341.5 2765.5,-1335.5 2771.5,-1329.5 2777.5,-1329.5"/>
<text text-anchor="middle" x="2810" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="2854.5,-1329.5 2854.5,-1467.5 "/>
<text text-anchor="middle" x="2865" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2875.5,-1329.5 2875.5,-1467.5 "/>
<text text-anchor="middle" x="2953" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2875.5,-1444.5 3030.5,-1444.5 "/>
<text text-anchor="middle" x="2953" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2875.5,-1421.5 3030.5,-1421.5 "/>
<text text-anchor="middle" x="2953" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="2875.5,-1398.5 3030.5,-1398.5 "/>
<text text-anchor="middle" x="2953" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2875.5,-1375.5 3030.5,-1375.5 "/>
<text text-anchor="middle" x="2953" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2875.5,-1352.5 3030.5,-1352.5 "/>
<text text-anchor="middle" x="2953" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="3030.5,-1329.5 3030.5,-1467.5 "/>
<text text-anchor="middle" x="3041" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2877.2308,-1329.4077C2850.4247,-1275.1769 2808.024,-1199.9201 2756.5,-1145 2741.5978,-1129.1156 2724.6529,-1113.9952 2707.018,-1099.9399"/>
<polygon fill="#000000" stroke="#000000" points="2708.9022,-1096.9699 2698.8717,-1093.5581 2704.5853,-1102.4803 2708.9022,-1096.9699"/>
<text text-anchor="middle" x="2788" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2603.7769,-909.4411C2614.6803,-891.2824 2626.6574,-871.3356 2639.1943,-850.4565"/>
<polygon fill="#000000" stroke="#000000" points="2642.2595,-852.1506 2644.4067,-841.7756 2636.2583,-848.5471 2642.2595,-852.1506"/>
<text text-anchor="middle" x="2651" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- NonDICOMCTimages -->
<g id="node14" class="node">
<title>NonDICOMCTimages</title>
<path fill="none" stroke="#000000" d="M1739,-2773.5C1739,-2773.5 2460,-2773.5 2460,-2773.5 2466,-2773.5 2472,-2779.5 2472,-2785.5 2472,-2785.5 2472,-3037.5 2472,-3037.5 2472,-3043.5 2466,-3049.5 2460,-3049.5 2460,-3049.5 1739,-3049.5 1739,-3049.5 1733,-3049.5 1727,-3043.5 1727,-3037.5 1727,-3037.5 1727,-2785.5 1727,-2785.5 1727,-2779.5 1733,-2773.5 1739,-2773.5"/>
<text text-anchor="middle" x="1813.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages</text>
<polyline fill="none" stroke="#000000" points="1900,-2773.5 1900,-3049.5 "/>
<text text-anchor="middle" x="1910.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1921,-2773.5 1921,-3049.5 "/>
<text text-anchor="middle" x="2186" y="-3034.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="1921,-3026.5 2451,-3026.5 "/>
<text text-anchor="middle" x="2186" y="-3011.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="1921,-3003.5 2451,-3003.5 "/>
<text text-anchor="middle" x="2186" y="-2988.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="1921,-2980.5 2451,-2980.5 "/>
<text text-anchor="middle" x="2186" y="-2965.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="1921,-2957.5 2451,-2957.5 "/>
<text text-anchor="middle" x="2186" y="-2942.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="1921,-2934.5 2451,-2934.5 "/>
<text text-anchor="middle" x="2186" y="-2919.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="1921,-2911.5 2451,-2911.5 "/>
<text text-anchor="middle" x="2186" y="-2896.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="1921,-2888.5 2451,-2888.5 "/>
<text text-anchor="middle" x="2186" y="-2873.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="1921,-2865.5 2451,-2865.5 "/>
<text text-anchor="middle" x="2186" y="-2850.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="1921,-2842.5 2451,-2842.5 "/>
<text text-anchor="middle" x="2186" y="-2827.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="1921,-2819.5 2451,-2819.5 "/>
<text text-anchor="middle" x="2186" y="-2804.3" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMCTimages_id</text>
<polyline fill="none" stroke="#000000" points="1921,-2796.5 2451,-2796.5 "/>
<text text-anchor="middle" x="2186" y="-2781.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2451,-2773.5 2451,-3049.5 "/>
<text text-anchor="middle" x="2461.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMCTimages&#45;&gt;image -->
<g id="edge5" class="edge">
<title>NonDICOMCTimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2023.9368,-2773.4428C1984.9812,-2702.2691 1936.7021,-2614.061 1893.5069,-2535.1415"/>
<polygon fill="#000000" stroke="#000000" points="1896.4077,-2533.1515 1888.5362,-2526.0599 1890.2673,-2536.5124 1896.4077,-2533.1515"/>
<text text-anchor="middle" x="1954" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMradiologyAllModalities -->
<g id="node15" class="node">
<title>NonDICOMradiologyAllModalities</title>
<path fill="none" stroke="#000000" d="M2502,-2693C2502,-2693 3275,-2693 3275,-2693 3281,-2693 3287,-2699 3287,-2705 3287,-2705 3287,-3118 3287,-3118 3287,-3124 3281,-3130 3275,-3130 3275,-3130 2502,-3130 2502,-3130 2496,-3130 2490,-3124 2490,-3118 2490,-3118 2490,-2705 2490,-2705 2490,-2699 2496,-2693 2502,-2693"/>
<text text-anchor="middle" x="2621.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities</text>
<polyline fill="none" stroke="#000000" points="2753,-2693 2753,-3130 "/>
<text text-anchor="middle" x="2763.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2774,-2693 2774,-3130 "/>
<text text-anchor="middle" x="3020" y="-3114.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMradiologyAllModalities_id</text>
<polyline fill="none" stroke="#000000" points="2774,-3107 3266,-3107 "/>
<text text-anchor="middle" x="3020" y="-3091.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="2774,-3084 3266,-3084 "/>
<text text-anchor="middle" x="3020" y="-3068.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_acquisitionTypeCode</text>
<polyline fill="none" stroke="#000000" points="2774,-3061 3266,-3061 "/>
<text text-anchor="middle" x="3020" y="-3045.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_admittingDiagnosisCode</text>
<polyline fill="none" stroke="#000000" points="2774,-3038 3266,-3038 "/>
<text text-anchor="middle" x="3020" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_algorithmCode</text>
<polyline fill="none" stroke="#000000" points="2774,-3015 3266,-3015 "/>
<text text-anchor="middle" x="3020" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_bodyPositionCode</text>
<polyline fill="none" stroke="#000000" points="2774,-2992 3266,-2992 "/>
<text text-anchor="middle" x="3020" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_cardiacSynchronizationTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="2774,-2969 3266,-2969 "/>
<text text-anchor="middle" x="3020" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_dataCollectionDiameter</text>
<polyline fill="none" stroke="#000000" points="2774,-2946 3266,-2946 "/>
<text text-anchor="middle" x="3020" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_description</text>
<polyline fill="none" stroke="#000000" points="2774,-2923 3266,-2923 "/>
<text text-anchor="middle" x="3020" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_lossyImageCompressionIndicator</text>
<polyline fill="none" stroke="#000000" points="2774,-2900 3266,-2900 "/>
<text text-anchor="middle" x="3020" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_nonAcquisitionModalitiesInStudyCode</text>
<polyline fill="none" stroke="#000000" points="2774,-2877 3266,-2877 "/>
<text text-anchor="middle" x="3020" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_primaryAnatomicSiteCode</text>
<polyline fill="none" stroke="#000000" points="2774,-2854 3266,-2854 "/>
<text text-anchor="middle" x="3020" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionDiameter</text>
<polyline fill="none" stroke="#000000" points="2774,-2831 3266,-2831 "/>
<text text-anchor="middle" x="3020" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewHeight</text>
<polyline fill="none" stroke="#000000" points="2774,-2808 3266,-2808 "/>
<text text-anchor="middle" x="3020" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewWidth</text>
<polyline fill="none" stroke="#000000" points="2774,-2785 3266,-2785 "/>
<text text-anchor="middle" x="3020" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionInterval</text>
<polyline fill="none" stroke="#000000" points="2774,-2762 3266,-2762 "/>
<text text-anchor="middle" x="3020" y="-2746.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_respiratoryMotionTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="2774,-2739 3266,-2739 "/>
<text text-anchor="middle" x="3020" y="-2723.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_sliceThickness</text>
<polyline fill="none" stroke="#000000" points="2774,-2716 3266,-2716 "/>
<text text-anchor="middle" x="3020" y="-2700.8" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_summary</text>
<polyline fill="none" stroke="#000000" points="3266,-2693 3266,-3130 "/>
<text text-anchor="middle" x="3276.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMradiologyAllModalities&#45;&gt;image -->
<g id="edge6" class="edge">
<title>NonDICOMradiologyAllModalities&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M2632.797,-2692.9321C2584.7084,-2661.0611 2532.9723,-2632.2283 2480.5,-2612 2274.1385,-2532.4469 2182.2316,-2662.0468 1985.5,-2561 1970.0027,-2553.0402 1955.1441,-2543.3695 1941.0129,-2532.5527"/>
<polygon fill="#000000" stroke="#000000" points="1942.7962,-2529.5016 1932.7773,-2526.0558 1938.4607,-2534.9973 1942.7962,-2529.5016"/>
<text text-anchor="middle" x="2455" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- NonDICOMMRimages -->
<g id="node16" class="node">
<title>NonDICOMMRimages</title>
<path fill="none" stroke="#000000" d="M3317,-2693C3317,-2693 4066,-2693 4066,-2693 4072,-2693 4078,-2699 4078,-2705 4078,-2705 4078,-3118 4078,-3118 4078,-3124 4072,-3130 4066,-3130 4066,-3130 3317,-3130 3317,-3130 3311,-3130 3305,-3124 3305,-3118 3305,-3118 3305,-2705 3305,-2705 3305,-2699 3311,-2693 3317,-2693"/>
<text text-anchor="middle" x="3393.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages</text>
<polyline fill="none" stroke="#000000" points="3482,-2693 3482,-3130 "/>
<text text-anchor="middle" x="3492.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3503,-2693 3503,-3130 "/>
<text text-anchor="middle" x="3780" y="-3114.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="3503,-3107 4057,-3107 "/>
<text text-anchor="middle" x="3780" y="-3091.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="3503,-3084 4057,-3084 "/>
<text text-anchor="middle" x="3780" y="-3068.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="3503,-3061 4057,-3061 "/>
<text text-anchor="middle" x="3780" y="-3045.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="3503,-3038 4057,-3038 "/>
<text text-anchor="middle" x="3780" y="-3022.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-3015 4057,-3015 "/>
<text text-anchor="middle" x="3780" y="-2999.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2992 4057,-2992 "/>
<text text-anchor="middle" x="3780" y="-2976.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2969 4057,-2969 "/>
<text text-anchor="middle" x="3780" y="-2953.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="3503,-2946 4057,-2946 "/>
<text text-anchor="middle" x="3780" y="-2930.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2923 4057,-2923 "/>
<text text-anchor="middle" x="3780" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2900 4057,-2900 "/>
<text text-anchor="middle" x="3780" y="-2884.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="3503,-2877 4057,-2877 "/>
<text text-anchor="middle" x="3780" y="-2861.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2854 4057,-2854 "/>
<text text-anchor="middle" x="3780" y="-2838.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2831 4057,-2831 "/>
<text text-anchor="middle" x="3780" y="-2815.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2808 4057,-2808 "/>
<text text-anchor="middle" x="3780" y="-2792.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2785 4057,-2785 "/>
<text text-anchor="middle" x="3780" y="-2769.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_timeOfFlightContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="3503,-2762 4057,-2762 "/>
<text text-anchor="middle" x="3780" y="-2746.8" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageReconstructionProtocolElement_complexImageComponentCode</text>
<polyline fill="none" stroke="#000000" points="3503,-2739 4057,-2739 "/>
<text text-anchor="middle" x="3780" y="-2723.8" font-family="Times,serif" font-size="14.00" fill="#000000">NonDICOMMRimages_id</text>
<polyline fill="none" stroke="#000000" points="3503,-2716 4057,-2716 "/>
<text text-anchor="middle" x="3780" y="-2700.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="4057,-2693 4057,-3130 "/>
<text text-anchor="middle" x="4067.5" y="-2907.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- NonDICOMMRimages&#45;&gt;image -->
<g id="edge7" class="edge">
<title>NonDICOMMRimages&#45;&gt;image</title>
<path fill="none" stroke="#000000" d="M3449.5178,-2692.8157C3401.7076,-2660.1887 3349.7531,-2631.1292 3296.5,-2612 3128.0021,-2551.4734 2670.4081,-2585.8492 2491.5,-2579 2435.2834,-2576.8478 2036.3769,-2585.01 1985.5,-2561 1969.0874,-2553.2545 1953.4393,-2543.5076 1938.6417,-2532.4265"/>
<polygon fill="#000000" stroke="#000000" points="1940.5606,-2529.486 1930.5088,-2526.1374 1936.2784,-2535.0235 1940.5606,-2529.486"/>
<text text-anchor="middle" x="3243" y="-2582.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_image</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge10" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M2814.5,-259.4595C2814.5,-244.999 2814.5,-230.9707 2814.5,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="2818.0001,-217.5945 2814.5,-207.5945 2811.0001,-217.5946 2818.0001,-217.5945"/>
<text text-anchor="middle" x="2856" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
</g>
</svg>
</div>
