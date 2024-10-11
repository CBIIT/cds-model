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
<svg width="1692pt" height="2661pt"
 viewBox="0.00 0.00 1691.50 2661.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 2657)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-2657 1687.5,-2657 1687.5,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1385.5,-1283.5C1385.5,-1283.5 1671.5,-1283.5 1671.5,-1283.5 1677.5,-1283.5 1683.5,-1289.5 1683.5,-1295.5 1683.5,-1295.5 1683.5,-1501.5 1683.5,-1501.5 1683.5,-1507.5 1677.5,-1513.5 1671.5,-1513.5 1671.5,-1513.5 1385.5,-1513.5 1385.5,-1513.5 1379.5,-1513.5 1373.5,-1507.5 1373.5,-1501.5 1373.5,-1501.5 1373.5,-1295.5 1373.5,-1295.5 1373.5,-1289.5 1379.5,-1283.5 1385.5,-1283.5"/>
<text text-anchor="middle" x="1407.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1441.5,-1283.5 1441.5,-1513.5 "/>
<text text-anchor="middle" x="1452" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1462.5,-1283.5 1462.5,-1513.5 "/>
<text text-anchor="middle" x="1562.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1490.5 1662.5,-1490.5 "/>
<text text-anchor="middle" x="1562.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1467.5 1662.5,-1467.5 "/>
<text text-anchor="middle" x="1562.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1444.5 1662.5,-1444.5 "/>
<text text-anchor="middle" x="1562.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1421.5 1662.5,-1421.5 "/>
<text text-anchor="middle" x="1562.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1398.5 1662.5,-1398.5 "/>
<text text-anchor="middle" x="1562.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1375.5 1662.5,-1375.5 "/>
<text text-anchor="middle" x="1562.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1352.5 1662.5,-1352.5 "/>
<text text-anchor="middle" x="1562.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1329.5 1662.5,-1329.5 "/>
<text text-anchor="middle" x="1562.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1306.5 1662.5,-1306.5 "/>
<text text-anchor="middle" x="1562.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="1662.5,-1283.5 1662.5,-1513.5 "/>
<text text-anchor="middle" x="1673" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M709.5,-909.5C709.5,-909.5 987.5,-909.5 987.5,-909.5 993.5,-909.5 999.5,-915.5 999.5,-921.5 999.5,-921.5 999.5,-1081.5 999.5,-1081.5 999.5,-1087.5 993.5,-1093.5 987.5,-1093.5 987.5,-1093.5 709.5,-1093.5 709.5,-1093.5 703.5,-1093.5 697.5,-1087.5 697.5,-1081.5 697.5,-1081.5 697.5,-921.5 697.5,-921.5 697.5,-915.5 703.5,-909.5 709.5,-909.5"/>
<text text-anchor="middle" x="745.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="793.5,-909.5 793.5,-1093.5 "/>
<text text-anchor="middle" x="804" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="814.5,-909.5 814.5,-1093.5 "/>
<text text-anchor="middle" x="896.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="814.5,-1070.5 978.5,-1070.5 "/>
<text text-anchor="middle" x="896.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="814.5,-1047.5 978.5,-1047.5 "/>
<text text-anchor="middle" x="896.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="814.5,-1024.5 978.5,-1024.5 "/>
<text text-anchor="middle" x="896.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="814.5,-1001.5 978.5,-1001.5 "/>
<text text-anchor="middle" x="896.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="814.5,-978.5 978.5,-978.5 "/>
<text text-anchor="middle" x="896.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="814.5,-955.5 978.5,-955.5 "/>
<text text-anchor="middle" x="896.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="814.5,-932.5 978.5,-932.5 "/>
<text text-anchor="middle" x="896.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="978.5,-909.5 978.5,-1093.5 "/>
<text text-anchor="middle" x="989" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1476.8971,-1283.392C1449.6067,-1234.3069 1411.6676,-1180.3247 1363.5,-1145 1260.0736,-1069.1502 1118.2473,-1033.3742 1009.6124,-1016.5098"/>
<polygon fill="#000000" stroke="#000000" points="1009.9486,-1013.0209 999.5374,-1014.985 1008.901,-1019.9421 1009.9486,-1013.0209"/>
<text text-anchor="middle" x="1378" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M661.5,-1145.5C661.5,-1145.5 1035.5,-1145.5 1035.5,-1145.5 1041.5,-1145.5 1047.5,-1151.5 1047.5,-1157.5 1047.5,-1157.5 1047.5,-1639.5 1047.5,-1639.5 1047.5,-1645.5 1041.5,-1651.5 1035.5,-1651.5 1035.5,-1651.5 661.5,-1651.5 661.5,-1651.5 655.5,-1651.5 649.5,-1645.5 649.5,-1639.5 649.5,-1639.5 649.5,-1157.5 649.5,-1157.5 649.5,-1151.5 655.5,-1145.5 661.5,-1145.5"/>
<text text-anchor="middle" x="691.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="733.5,-1145.5 733.5,-1651.5 "/>
<text text-anchor="middle" x="744" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="754.5,-1145.5 754.5,-1651.5 "/>
<text text-anchor="middle" x="890.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="754.5,-1628.5 1026.5,-1628.5 "/>
<text text-anchor="middle" x="890.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="754.5,-1605.5 1026.5,-1605.5 "/>
<text text-anchor="middle" x="890.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="754.5,-1582.5 1026.5,-1582.5 "/>
<text text-anchor="middle" x="890.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="754.5,-1559.5 1026.5,-1559.5 "/>
<text text-anchor="middle" x="890.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="754.5,-1536.5 1026.5,-1536.5 "/>
<text text-anchor="middle" x="890.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="754.5,-1513.5 1026.5,-1513.5 "/>
<text text-anchor="middle" x="890.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="754.5,-1490.5 1026.5,-1490.5 "/>
<text text-anchor="middle" x="890.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="754.5,-1467.5 1026.5,-1467.5 "/>
<text text-anchor="middle" x="890.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="754.5,-1444.5 1026.5,-1444.5 "/>
<text text-anchor="middle" x="890.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="754.5,-1421.5 1026.5,-1421.5 "/>
<text text-anchor="middle" x="890.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="754.5,-1398.5 1026.5,-1398.5 "/>
<text text-anchor="middle" x="890.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="754.5,-1375.5 1026.5,-1375.5 "/>
<text text-anchor="middle" x="890.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="754.5,-1352.5 1026.5,-1352.5 "/>
<text text-anchor="middle" x="890.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="754.5,-1329.5 1026.5,-1329.5 "/>
<text text-anchor="middle" x="890.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="754.5,-1306.5 1026.5,-1306.5 "/>
<text text-anchor="middle" x="890.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="754.5,-1283.5 1026.5,-1283.5 "/>
<text text-anchor="middle" x="890.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="754.5,-1260.5 1026.5,-1260.5 "/>
<text text-anchor="middle" x="890.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="754.5,-1237.5 1026.5,-1237.5 "/>
<text text-anchor="middle" x="890.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="754.5,-1214.5 1026.5,-1214.5 "/>
<text text-anchor="middle" x="890.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="754.5,-1191.5 1026.5,-1191.5 "/>
<text text-anchor="middle" x="890.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="754.5,-1168.5 1026.5,-1168.5 "/>
<text text-anchor="middle" x="890.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1026.5,-1145.5 1026.5,-1651.5 "/>
<text text-anchor="middle" x="1037" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M848.5,-1145.3874C848.5,-1131.0731 848.5,-1117.1697 848.5,-1104.0079"/>
<polygon fill="#000000" stroke="#000000" points="852.0001,-1103.6176 848.5,-1093.6177 845.0001,-1103.6177 852.0001,-1103.6176"/>
<text text-anchor="middle" x="899" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genomic_info -->
<g id="node3" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M12,-2112C12,-2112 465,-2112 465,-2112 471,-2112 477,-2118 477,-2124 477,-2124 477,-2583 477,-2583 477,-2589 471,-2595 465,-2595 465,-2595 12,-2595 12,-2595 6,-2595 0,-2589 0,-2583 0,-2583 0,-2124 0,-2124 0,-2118 6,-2112 12,-2112"/>
<text text-anchor="middle" x="56" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="112,-2112 112,-2595 "/>
<text text-anchor="middle" x="122.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="133,-2112 133,-2595 "/>
<text text-anchor="middle" x="294.5" y="-2579.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="133,-2572 456,-2572 "/>
<text text-anchor="middle" x="294.5" y="-2556.8" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="133,-2549 456,-2549 "/>
<text text-anchor="middle" x="294.5" y="-2533.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="133,-2526 456,-2526 "/>
<text text-anchor="middle" x="294.5" y="-2510.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="133,-2503 456,-2503 "/>
<text text-anchor="middle" x="294.5" y="-2487.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="133,-2480 456,-2480 "/>
<text text-anchor="middle" x="294.5" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="133,-2457 456,-2457 "/>
<text text-anchor="middle" x="294.5" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="133,-2434 456,-2434 "/>
<text text-anchor="middle" x="294.5" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="133,-2411 456,-2411 "/>
<text text-anchor="middle" x="294.5" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="133,-2388 456,-2388 "/>
<text text-anchor="middle" x="294.5" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="133,-2365 456,-2365 "/>
<text text-anchor="middle" x="294.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="133,-2342 456,-2342 "/>
<text text-anchor="middle" x="294.5" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="133,-2319 456,-2319 "/>
<text text-anchor="middle" x="294.5" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="133,-2296 456,-2296 "/>
<text text-anchor="middle" x="294.5" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="133,-2273 456,-2273 "/>
<text text-anchor="middle" x="294.5" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="133,-2250 456,-2250 "/>
<text text-anchor="middle" x="294.5" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="133,-2227 456,-2227 "/>
<text text-anchor="middle" x="294.5" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="133,-2204 456,-2204 "/>
<text text-anchor="middle" x="294.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="133,-2181 456,-2181 "/>
<text text-anchor="middle" x="294.5" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="133,-2158 456,-2158 "/>
<text text-anchor="middle" x="294.5" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="133,-2135 456,-2135 "/>
<text text-anchor="middle" x="294.5" y="-2119.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="456,-2112 456,-2595 "/>
<text text-anchor="middle" x="466.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node6" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M340.5,-1703.5C340.5,-1703.5 720.5,-1703.5 720.5,-1703.5 726.5,-1703.5 732.5,-1709.5 732.5,-1715.5 732.5,-1715.5 732.5,-1990.5 732.5,-1990.5 732.5,-1996.5 726.5,-2002.5 720.5,-2002.5 720.5,-2002.5 340.5,-2002.5 340.5,-2002.5 334.5,-2002.5 328.5,-1996.5 328.5,-1990.5 328.5,-1990.5 328.5,-1715.5 328.5,-1715.5 328.5,-1709.5 334.5,-1703.5 340.5,-1703.5"/>
<text text-anchor="middle" x="348" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="367.5,-1703.5 367.5,-2002.5 "/>
<text text-anchor="middle" x="378" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="388.5,-1703.5 388.5,-2002.5 "/>
<text text-anchor="middle" x="550" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="388.5,-1979.5 711.5,-1979.5 "/>
<text text-anchor="middle" x="550" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="388.5,-1956.5 711.5,-1956.5 "/>
<text text-anchor="middle" x="550" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="388.5,-1933.5 711.5,-1933.5 "/>
<text text-anchor="middle" x="550" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="388.5,-1910.5 711.5,-1910.5 "/>
<text text-anchor="middle" x="550" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="388.5,-1887.5 711.5,-1887.5 "/>
<text text-anchor="middle" x="550" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="388.5,-1864.5 711.5,-1864.5 "/>
<text text-anchor="middle" x="550" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="388.5,-1841.5 711.5,-1841.5 "/>
<text text-anchor="middle" x="550" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="388.5,-1818.5 711.5,-1818.5 "/>
<text text-anchor="middle" x="550" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="388.5,-1795.5 711.5,-1795.5 "/>
<text text-anchor="middle" x="550" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="388.5,-1772.5 711.5,-1772.5 "/>
<text text-anchor="middle" x="550" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="388.5,-1749.5 711.5,-1749.5 "/>
<text text-anchor="middle" x="550" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="388.5,-1726.5 711.5,-1726.5 "/>
<text text-anchor="middle" x="550" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="711.5,-1703.5 711.5,-2002.5 "/>
<text text-anchor="middle" x="722" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge9" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M379.5819,-2111.6799C399.4265,-2077.6654 419.3924,-2043.443 438.0109,-2011.5302"/>
<polygon fill="#000000" stroke="#000000" points="441.2091,-2012.9937 443.2253,-2002.5924 435.1629,-2009.4662 441.2091,-2012.9937"/>
<text text-anchor="middle" x="450.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- image -->
<g id="node4" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M507.5,-2054.5C507.5,-2054.5 1139.5,-2054.5 1139.5,-2054.5 1145.5,-2054.5 1151.5,-2060.5 1151.5,-2066.5 1151.5,-2066.5 1151.5,-2640.5 1151.5,-2640.5 1151.5,-2646.5 1145.5,-2652.5 1139.5,-2652.5 1139.5,-2652.5 507.5,-2652.5 507.5,-2652.5 501.5,-2652.5 495.5,-2646.5 495.5,-2640.5 495.5,-2640.5 495.5,-2066.5 495.5,-2066.5 495.5,-2060.5 501.5,-2054.5 507.5,-2054.5"/>
<text text-anchor="middle" x="525.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="555.5,-2054.5 555.5,-2652.5 "/>
<text text-anchor="middle" x="566" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="576.5,-2054.5 576.5,-2652.5 "/>
<text text-anchor="middle" x="853.5" y="-2637.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2629.5 1130.5,-2629.5 "/>
<text text-anchor="middle" x="853.5" y="-2614.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="576.5,-2606.5 1130.5,-2606.5 "/>
<text text-anchor="middle" x="853.5" y="-2591.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="576.5,-2583.5 1130.5,-2583.5 "/>
<text text-anchor="middle" x="853.5" y="-2568.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="576.5,-2560.5 1130.5,-2560.5 "/>
<text text-anchor="middle" x="853.5" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="576.5,-2537.5 1130.5,-2537.5 "/>
<text text-anchor="middle" x="853.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-2514.5 1130.5,-2514.5 "/>
<text text-anchor="middle" x="853.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="576.5,-2491.5 1130.5,-2491.5 "/>
<text text-anchor="middle" x="853.5" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-2468.5 1130.5,-2468.5 "/>
<text text-anchor="middle" x="853.5" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="576.5,-2445.5 1130.5,-2445.5 "/>
<text text-anchor="middle" x="853.5" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2422.5 1130.5,-2422.5 "/>
<text text-anchor="middle" x="853.5" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2399.5 1130.5,-2399.5 "/>
<text text-anchor="middle" x="853.5" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2376.5 1130.5,-2376.5 "/>
<text text-anchor="middle" x="853.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="576.5,-2353.5 1130.5,-2353.5 "/>
<text text-anchor="middle" x="853.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2330.5 1130.5,-2330.5 "/>
<text text-anchor="middle" x="853.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-2307.5 1130.5,-2307.5 "/>
<text text-anchor="middle" x="853.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2284.5 1130.5,-2284.5 "/>
<text text-anchor="middle" x="853.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-2261.5 1130.5,-2261.5 "/>
<text text-anchor="middle" x="853.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="576.5,-2238.5 1130.5,-2238.5 "/>
<text text-anchor="middle" x="853.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-2215.5 1130.5,-2215.5 "/>
<text text-anchor="middle" x="853.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-2192.5 1130.5,-2192.5 "/>
<text text-anchor="middle" x="853.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="576.5,-2169.5 1130.5,-2169.5 "/>
<text text-anchor="middle" x="853.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2146.5 1130.5,-2146.5 "/>
<text text-anchor="middle" x="853.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-2123.5 1130.5,-2123.5 "/>
<text text-anchor="middle" x="853.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2100.5 1130.5,-2100.5 "/>
<text text-anchor="middle" x="853.5" y="-2085.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2077.5 1130.5,-2077.5 "/>
<text text-anchor="middle" x="853.5" y="-2062.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 81 properties</text>
<polyline fill="none" stroke="#000000" points="1130.5,-2054.5 1130.5,-2652.5 "/>
<text text-anchor="middle" x="1141" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge10" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M648.4078,-2054.409C639.805,-2039.7138 631.339,-2025.2523 623.1349,-2011.2381"/>
<polygon fill="#000000" stroke="#000000" points="626.1342,-2009.4337 618.0616,-2002.5719 620.0933,-2012.9702 626.1342,-2009.4337"/>
<text text-anchor="middle" x="656.5" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M312.5,-259.5C312.5,-259.5 628.5,-259.5 628.5,-259.5 634.5,-259.5 640.5,-265.5 640.5,-271.5 640.5,-271.5 640.5,-845.5 640.5,-845.5 640.5,-851.5 634.5,-857.5 628.5,-857.5 628.5,-857.5 312.5,-857.5 312.5,-857.5 306.5,-857.5 300.5,-851.5 300.5,-845.5 300.5,-845.5 300.5,-271.5 300.5,-271.5 300.5,-265.5 306.5,-259.5 312.5,-259.5"/>
<text text-anchor="middle" x="328.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="356.5,-259.5 356.5,-857.5 "/>
<text text-anchor="middle" x="367" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="377.5,-259.5 377.5,-857.5 "/>
<text text-anchor="middle" x="498.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="377.5,-834.5 619.5,-834.5 "/>
<text text-anchor="middle" x="498.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="377.5,-811.5 619.5,-811.5 "/>
<text text-anchor="middle" x="498.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="377.5,-788.5 619.5,-788.5 "/>
<text text-anchor="middle" x="498.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="377.5,-765.5 619.5,-765.5 "/>
<text text-anchor="middle" x="498.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="377.5,-742.5 619.5,-742.5 "/>
<text text-anchor="middle" x="498.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="377.5,-719.5 619.5,-719.5 "/>
<text text-anchor="middle" x="498.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="377.5,-696.5 619.5,-696.5 "/>
<text text-anchor="middle" x="498.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="377.5,-673.5 619.5,-673.5 "/>
<text text-anchor="middle" x="498.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="377.5,-650.5 619.5,-650.5 "/>
<text text-anchor="middle" x="498.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="377.5,-627.5 619.5,-627.5 "/>
<text text-anchor="middle" x="498.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="377.5,-604.5 619.5,-604.5 "/>
<text text-anchor="middle" x="498.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="377.5,-581.5 619.5,-581.5 "/>
<text text-anchor="middle" x="498.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="377.5,-558.5 619.5,-558.5 "/>
<text text-anchor="middle" x="498.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="377.5,-535.5 619.5,-535.5 "/>
<text text-anchor="middle" x="498.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="377.5,-512.5 619.5,-512.5 "/>
<text text-anchor="middle" x="498.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="377.5,-489.5 619.5,-489.5 "/>
<text text-anchor="middle" x="498.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="377.5,-466.5 619.5,-466.5 "/>
<text text-anchor="middle" x="498.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="377.5,-443.5 619.5,-443.5 "/>
<text text-anchor="middle" x="498.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="377.5,-420.5 619.5,-420.5 "/>
<text text-anchor="middle" x="498.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="377.5,-397.5 619.5,-397.5 "/>
<text text-anchor="middle" x="498.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="377.5,-374.5 619.5,-374.5 "/>
<text text-anchor="middle" x="498.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="377.5,-351.5 619.5,-351.5 "/>
<text text-anchor="middle" x="498.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="377.5,-328.5 619.5,-328.5 "/>
<text text-anchor="middle" x="498.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="377.5,-305.5 619.5,-305.5 "/>
<text text-anchor="middle" x="498.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="377.5,-282.5 619.5,-282.5 "/>
<text text-anchor="middle" x="498.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="619.5,-259.5 619.5,-857.5 "/>
<text text-anchor="middle" x="630" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node8" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M316.5,-.5C316.5,-.5 624.5,-.5 624.5,-.5 630.5,-.5 636.5,-6.5 636.5,-12.5 636.5,-12.5 636.5,-195.5 636.5,-195.5 636.5,-201.5 630.5,-207.5 624.5,-207.5 624.5,-207.5 316.5,-207.5 316.5,-207.5 310.5,-207.5 304.5,-201.5 304.5,-195.5 304.5,-195.5 304.5,-12.5 304.5,-12.5 304.5,-6.5 310.5,-.5 316.5,-.5"/>
<text text-anchor="middle" x="343.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="382.5,-.5 382.5,-207.5 "/>
<text text-anchor="middle" x="393" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="403.5,-.5 403.5,-207.5 "/>
<text text-anchor="middle" x="509.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="403.5,-184.5 615.5,-184.5 "/>
<text text-anchor="middle" x="509.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="403.5,-161.5 615.5,-161.5 "/>
<text text-anchor="middle" x="509.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="403.5,-138.5 615.5,-138.5 "/>
<text text-anchor="middle" x="509.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="403.5,-115.5 615.5,-115.5 "/>
<text text-anchor="middle" x="509.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="403.5,-92.5 615.5,-92.5 "/>
<text text-anchor="middle" x="509.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="403.5,-69.5 615.5,-69.5 "/>
<text text-anchor="middle" x="509.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="403.5,-46.5 615.5,-46.5 "/>
<text text-anchor="middle" x="509.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="403.5,-23.5 615.5,-23.5 "/>
<text text-anchor="middle" x="509.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="615.5,-.5 615.5,-207.5 "/>
<text text-anchor="middle" x="626" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge8" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M470.5,-259.4595C470.5,-244.999 470.5,-230.9707 470.5,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="474.0001,-217.5945 470.5,-207.5945 467.0001,-217.5946 474.0001,-217.5945"/>
<text text-anchor="middle" x="512" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M732.9617,-1821.7979C945.7198,-1785.9585 1263.1982,-1722.8946 1363.5,-1652 1409.6217,-1619.4006 1446.1137,-1569.4467 1472.9262,-1522.4752"/>
<polygon fill="#000000" stroke="#000000" points="1475.9837,-1524.1787 1477.8202,-1513.7442 1469.8776,-1520.756 1475.9837,-1524.1787"/>
<text text-anchor="middle" x="1376" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M501.891,-1703.2407C499.3529,-1686.012 497.1314,-1668.6567 495.5,-1652 469.6709,-1388.2793 464.5721,-1087.1581 465.2782,-867.7669"/>
<polygon fill="#000000" stroke="#000000" points="468.7783,-867.7222 465.3149,-857.7095 461.7784,-867.6967 468.7783,-867.7222"/>
<text text-anchor="middle" x="498" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge11" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M732.6809,-1874.8677C743.8527,-1869.55 750.5,-1862.2607 750.5,-1853 750.5,-1846.4885 747.2137,-1840.9518 741.3789,-1836.3897"/>
<polygon fill="#000000" stroke="#000000" points="743.0495,-1833.3098 732.6809,-1831.1323 739.4285,-1839.3005 743.0495,-1833.3098"/>
<text text-anchor="middle" x="808" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M514.2551,-1703.4013C497.7672,-1523.2669 482.0215,-1233.8174 539.5,-1145 573.2135,-1092.9048 631.1883,-1059.408 687.8779,-1038.015"/>
<polygon fill="#000000" stroke="#000000" points="689.1428,-1041.2791 697.3293,-1034.5535 686.7355,-1034.7061 689.1428,-1041.2791"/>
<text text-anchor="middle" x="590" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M769.9487,-909.4411C734.2516,-867.6057 690.4564,-816.2796 647.4921,-765.9273"/>
<polygon fill="#000000" stroke="#000000" points="650.0367,-763.5172 640.8832,-758.1819 644.7117,-768.0609 650.0367,-763.5172"/>
<text text-anchor="middle" x="778" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1078,-1318C1078,-1318 1343,-1318 1343,-1318 1349,-1318 1355,-1324 1355,-1330 1355,-1330 1355,-1467 1355,-1467 1355,-1473 1349,-1479 1343,-1479 1343,-1479 1078,-1479 1078,-1479 1072,-1479 1066,-1473 1066,-1467 1066,-1467 1066,-1330 1066,-1330 1066,-1324 1072,-1318 1078,-1318"/>
<text text-anchor="middle" x="1110.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1155,-1318 1155,-1479 "/>
<text text-anchor="middle" x="1165.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1176,-1318 1176,-1479 "/>
<text text-anchor="middle" x="1255" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1176,-1456 1334,-1456 "/>
<text text-anchor="middle" x="1255" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1176,-1433 1334,-1433 "/>
<text text-anchor="middle" x="1255" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1176,-1410 1334,-1410 "/>
<text text-anchor="middle" x="1255" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1176,-1387 1334,-1387 "/>
<text text-anchor="middle" x="1255" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1176,-1364 1334,-1364 "/>
<text text-anchor="middle" x="1255" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1176,-1341 1334,-1341 "/>
<text text-anchor="middle" x="1255" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1334,-1318 1334,-1479 "/>
<text text-anchor="middle" x="1344.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1172.6936,-1317.7762C1145.3204,-1264.8 1104.7408,-1196.1234 1056.5,-1145 1041.552,-1129.1587 1024.5789,-1114.0647 1006.9285,-1100.024"/>
<polygon fill="#000000" stroke="#000000" points="1008.8093,-1097.0516 998.7761,-1093.648 1004.4969,-1102.5656 1008.8093,-1097.0516"/>
<text text-anchor="middle" x="1088" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
