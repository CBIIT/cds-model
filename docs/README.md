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
<svg width="1444pt" height="1873pt"
 viewBox="0.00 0.00 1443.50 1873.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1869)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1869 1439.5,-1869 1439.5,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M243,-1715C243,-1715 508,-1715 508,-1715 514,-1715 520,-1721 520,-1727 520,-1727 520,-1818 520,-1818 520,-1824 514,-1830 508,-1830 508,-1830 243,-1830 243,-1830 237,-1830 231,-1824 231,-1818 231,-1818 231,-1727 231,-1727 231,-1721 237,-1715 243,-1715"/>
<text text-anchor="middle" x="275.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="320,-1715 320,-1830 "/>
<text text-anchor="middle" x="330.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="341,-1715 341,-1830 "/>
<text text-anchor="middle" x="420" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="341,-1807 499,-1807 "/>
<text text-anchor="middle" x="420" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="341,-1784 499,-1784 "/>
<text text-anchor="middle" x="420" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="341,-1761 499,-1761 "/>
<text text-anchor="middle" x="420" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="341,-1738 499,-1738 "/>
<text text-anchor="middle" x="420" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="499,-1715 499,-1830 "/>
<text text-anchor="middle" x="509.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen -->
<g id="node2" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M12,-1415C12,-1415 221,-1415 221,-1415 227,-1415 233,-1421 233,-1427 233,-1427 233,-1439 233,-1439 233,-1445 227,-1451 221,-1451 221,-1451 12,-1451 12,-1451 6,-1451 0,-1445 0,-1439 0,-1439 0,-1427 0,-1427 0,-1421 6,-1415 12,-1415"/>
<text text-anchor="middle" x="42.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="85,-1415 85,-1451 "/>
<text text-anchor="middle" x="95.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="106,-1415 106,-1451 "/>
<text text-anchor="middle" x="159" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="212,-1415 212,-1451 "/>
<text text-anchor="middle" x="222.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M291,-1036C291,-1036 550,-1036 550,-1036 556,-1036 562,-1042 562,-1048 562,-1048 562,-1139 562,-1139 562,-1145 556,-1151 550,-1151 550,-1151 291,-1151 291,-1151 285,-1151 279,-1145 279,-1139 279,-1139 279,-1048 279,-1048 279,-1042 285,-1036 291,-1036"/>
<text text-anchor="middle" x="327" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="375,-1036 375,-1151 "/>
<text text-anchor="middle" x="385.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="396,-1036 396,-1151 "/>
<text text-anchor="middle" x="468.5" y="-1135.8" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="396,-1128 541,-1128 "/>
<text text-anchor="middle" x="468.5" y="-1112.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="396,-1105 541,-1105 "/>
<text text-anchor="middle" x="468.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="396,-1082 541,-1082 "/>
<text text-anchor="middle" x="468.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="396,-1059 541,-1059 "/>
<text text-anchor="middle" x="468.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="541,-1036 541,-1151 "/>
<text text-anchor="middle" x="551.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>specimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M125.5743,-1414.9141C144.2727,-1378.6895 189.789,-1295.6854 242.5,-1237 268.2,-1208.3871 299.944,-1180.8771 329.4756,-1157.7339"/>
<polygon fill="#000000" stroke="#000000" points="331.9824,-1160.219 337.7395,-1151.3248 327.6924,-1154.6876 331.9824,-1160.219"/>
<text text-anchor="middle" x="324" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M263.5,-1237.5C263.5,-1237.5 577.5,-1237.5 577.5,-1237.5 583.5,-1237.5 589.5,-1243.5 589.5,-1249.5 589.5,-1249.5 589.5,-1616.5 589.5,-1616.5 589.5,-1622.5 583.5,-1628.5 577.5,-1628.5 577.5,-1628.5 263.5,-1628.5 263.5,-1628.5 257.5,-1628.5 251.5,-1622.5 251.5,-1616.5 251.5,-1616.5 251.5,-1249.5 251.5,-1249.5 251.5,-1243.5 257.5,-1237.5 263.5,-1237.5"/>
<text text-anchor="middle" x="293.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="335.5,-1237.5 335.5,-1628.5 "/>
<text text-anchor="middle" x="346" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="356.5,-1237.5 356.5,-1628.5 "/>
<text text-anchor="middle" x="462.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="356.5,-1605.5 568.5,-1605.5 "/>
<text text-anchor="middle" x="462.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="356.5,-1582.5 568.5,-1582.5 "/>
<text text-anchor="middle" x="462.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="356.5,-1559.5 568.5,-1559.5 "/>
<text text-anchor="middle" x="462.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="356.5,-1536.5 568.5,-1536.5 "/>
<text text-anchor="middle" x="462.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="356.5,-1513.5 568.5,-1513.5 "/>
<text text-anchor="middle" x="462.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="356.5,-1490.5 568.5,-1490.5 "/>
<text text-anchor="middle" x="462.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="356.5,-1467.5 568.5,-1467.5 "/>
<text text-anchor="middle" x="462.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="356.5,-1444.5 568.5,-1444.5 "/>
<text text-anchor="middle" x="462.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="356.5,-1421.5 568.5,-1421.5 "/>
<text text-anchor="middle" x="462.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="356.5,-1398.5 568.5,-1398.5 "/>
<text text-anchor="middle" x="462.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="356.5,-1375.5 568.5,-1375.5 "/>
<text text-anchor="middle" x="462.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="356.5,-1352.5 568.5,-1352.5 "/>
<text text-anchor="middle" x="462.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="356.5,-1329.5 568.5,-1329.5 "/>
<text text-anchor="middle" x="462.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="356.5,-1306.5 568.5,-1306.5 "/>
<text text-anchor="middle" x="462.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="356.5,-1283.5 568.5,-1283.5 "/>
<text text-anchor="middle" x="462.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="356.5,-1260.5 568.5,-1260.5 "/>
<text text-anchor="middle" x="462.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="568.5,-1237.5 568.5,-1628.5 "/>
<text text-anchor="middle" x="579" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M420.5,-1237.4786C420.5,-1210.2523 420.5,-1183.9317 420.5,-1161.4068"/>
<polygon fill="#000000" stroke="#000000" points="424.0001,-1161.3349 420.5,-1151.335 417.0001,-1161.335 424.0001,-1161.3349"/>
<text text-anchor="middle" x="471" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genomic_info -->
<g id="node4" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M795,-1260.5C795,-1260.5 1248,-1260.5 1248,-1260.5 1254,-1260.5 1260,-1266.5 1260,-1272.5 1260,-1272.5 1260,-1593.5 1260,-1593.5 1260,-1599.5 1254,-1605.5 1248,-1605.5 1248,-1605.5 795,-1605.5 795,-1605.5 789,-1605.5 783,-1599.5 783,-1593.5 783,-1593.5 783,-1272.5 783,-1272.5 783,-1266.5 789,-1260.5 795,-1260.5"/>
<text text-anchor="middle" x="839" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="895,-1260.5 895,-1605.5 "/>
<text text-anchor="middle" x="905.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="916,-1260.5 916,-1605.5 "/>
<text text-anchor="middle" x="1077.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="916,-1582.5 1239,-1582.5 "/>
<text text-anchor="middle" x="1077.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="916,-1559.5 1239,-1559.5 "/>
<text text-anchor="middle" x="1077.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="916,-1536.5 1239,-1536.5 "/>
<text text-anchor="middle" x="1077.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="916,-1513.5 1239,-1513.5 "/>
<text text-anchor="middle" x="1077.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="916,-1490.5 1239,-1490.5 "/>
<text text-anchor="middle" x="1077.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="916,-1467.5 1239,-1467.5 "/>
<text text-anchor="middle" x="1077.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="916,-1444.5 1239,-1444.5 "/>
<text text-anchor="middle" x="1077.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="916,-1421.5 1239,-1421.5 "/>
<text text-anchor="middle" x="1077.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="916,-1398.5 1239,-1398.5 "/>
<text text-anchor="middle" x="1077.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="916,-1375.5 1239,-1375.5 "/>
<text text-anchor="middle" x="1077.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="916,-1352.5 1239,-1352.5 "/>
<text text-anchor="middle" x="1077.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="916,-1329.5 1239,-1329.5 "/>
<text text-anchor="middle" x="1077.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="916,-1306.5 1239,-1306.5 "/>
<text text-anchor="middle" x="1077.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="916,-1283.5 1239,-1283.5 "/>
<text text-anchor="middle" x="1077.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1239,-1260.5 1239,-1605.5 "/>
<text text-anchor="middle" x="1249.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node7" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M812.5,-1001.5C812.5,-1001.5 1192.5,-1001.5 1192.5,-1001.5 1198.5,-1001.5 1204.5,-1007.5 1204.5,-1013.5 1204.5,-1013.5 1204.5,-1173.5 1204.5,-1173.5 1204.5,-1179.5 1198.5,-1185.5 1192.5,-1185.5 1192.5,-1185.5 812.5,-1185.5 812.5,-1185.5 806.5,-1185.5 800.5,-1179.5 800.5,-1173.5 800.5,-1173.5 800.5,-1013.5 800.5,-1013.5 800.5,-1007.5 806.5,-1001.5 812.5,-1001.5"/>
<text text-anchor="middle" x="820" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="839.5,-1001.5 839.5,-1185.5 "/>
<text text-anchor="middle" x="850" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="860.5,-1001.5 860.5,-1185.5 "/>
<text text-anchor="middle" x="1022" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="860.5,-1162.5 1183.5,-1162.5 "/>
<text text-anchor="middle" x="1022" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="860.5,-1139.5 1183.5,-1139.5 "/>
<text text-anchor="middle" x="1022" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="860.5,-1116.5 1183.5,-1116.5 "/>
<text text-anchor="middle" x="1022" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="860.5,-1093.5 1183.5,-1093.5 "/>
<text text-anchor="middle" x="1022" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="860.5,-1070.5 1183.5,-1070.5 "/>
<text text-anchor="middle" x="1022" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="860.5,-1047.5 1183.5,-1047.5 "/>
<text text-anchor="middle" x="1022" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="860.5,-1024.5 1183.5,-1024.5 "/>
<text text-anchor="middle" x="1022" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1183.5,-1001.5 1183.5,-1185.5 "/>
<text text-anchor="middle" x="1194" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge2" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M1088.006,-1260.4841C1089.0725,-1241.3406 1087.3361,-1222.1981 1081.5,-1204 1080.5407,-1201.0088 1079.4674,-1198.0297 1078.2944,-1195.0696"/>
<polygon fill="#000000" stroke="#000000" points="1081.4165,-1193.4715 1074.2275,-1185.6889 1074.9941,-1196.256 1081.4165,-1193.4715"/>
<text text-anchor="middle" x="1106.5" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M262.5,-190.5C262.5,-190.5 578.5,-190.5 578.5,-190.5 584.5,-190.5 590.5,-196.5 590.5,-202.5 590.5,-202.5 590.5,-937.5 590.5,-937.5 590.5,-943.5 584.5,-949.5 578.5,-949.5 578.5,-949.5 262.5,-949.5 262.5,-949.5 256.5,-949.5 250.5,-943.5 250.5,-937.5 250.5,-937.5 250.5,-202.5 250.5,-202.5 250.5,-196.5 256.5,-190.5 262.5,-190.5"/>
<text text-anchor="middle" x="278.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="306.5,-190.5 306.5,-949.5 "/>
<text text-anchor="middle" x="317" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="327.5,-190.5 327.5,-949.5 "/>
<text text-anchor="middle" x="448.5" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="327.5,-926.5 569.5,-926.5 "/>
<text text-anchor="middle" x="448.5" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="327.5,-903.5 569.5,-903.5 "/>
<text text-anchor="middle" x="448.5" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="327.5,-880.5 569.5,-880.5 "/>
<text text-anchor="middle" x="448.5" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="327.5,-857.5 569.5,-857.5 "/>
<text text-anchor="middle" x="448.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="327.5,-834.5 569.5,-834.5 "/>
<text text-anchor="middle" x="448.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="327.5,-811.5 569.5,-811.5 "/>
<text text-anchor="middle" x="448.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="327.5,-788.5 569.5,-788.5 "/>
<text text-anchor="middle" x="448.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="327.5,-765.5 569.5,-765.5 "/>
<text text-anchor="middle" x="448.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="327.5,-742.5 569.5,-742.5 "/>
<text text-anchor="middle" x="448.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="327.5,-719.5 569.5,-719.5 "/>
<text text-anchor="middle" x="448.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="327.5,-696.5 569.5,-696.5 "/>
<text text-anchor="middle" x="448.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="327.5,-673.5 569.5,-673.5 "/>
<text text-anchor="middle" x="448.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="327.5,-650.5 569.5,-650.5 "/>
<text text-anchor="middle" x="448.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="327.5,-627.5 569.5,-627.5 "/>
<text text-anchor="middle" x="448.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="327.5,-604.5 569.5,-604.5 "/>
<text text-anchor="middle" x="448.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="327.5,-581.5 569.5,-581.5 "/>
<text text-anchor="middle" x="448.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="327.5,-558.5 569.5,-558.5 "/>
<text text-anchor="middle" x="448.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="327.5,-535.5 569.5,-535.5 "/>
<text text-anchor="middle" x="448.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="327.5,-512.5 569.5,-512.5 "/>
<text text-anchor="middle" x="448.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="327.5,-489.5 569.5,-489.5 "/>
<text text-anchor="middle" x="448.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="327.5,-466.5 569.5,-466.5 "/>
<text text-anchor="middle" x="448.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="327.5,-443.5 569.5,-443.5 "/>
<text text-anchor="middle" x="448.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="327.5,-420.5 569.5,-420.5 "/>
<text text-anchor="middle" x="448.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="327.5,-397.5 569.5,-397.5 "/>
<text text-anchor="middle" x="448.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="327.5,-374.5 569.5,-374.5 "/>
<text text-anchor="middle" x="448.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="327.5,-351.5 569.5,-351.5 "/>
<text text-anchor="middle" x="448.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="327.5,-328.5 569.5,-328.5 "/>
<text text-anchor="middle" x="448.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="327.5,-305.5 569.5,-305.5 "/>
<text text-anchor="middle" x="448.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="327.5,-282.5 569.5,-282.5 "/>
<text text-anchor="middle" x="448.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="327.5,-259.5 569.5,-259.5 "/>
<text text-anchor="middle" x="448.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="327.5,-236.5 569.5,-236.5 "/>
<text text-anchor="middle" x="448.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="327.5,-213.5 569.5,-213.5 "/>
<text text-anchor="middle" x="448.5" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="569.5,-190.5 569.5,-949.5 "/>
<text text-anchor="middle" x="580" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node6" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M266.5,-.5C266.5,-.5 574.5,-.5 574.5,-.5 580.5,-.5 586.5,-6.5 586.5,-12.5 586.5,-12.5 586.5,-126.5 586.5,-126.5 586.5,-132.5 580.5,-138.5 574.5,-138.5 574.5,-138.5 266.5,-138.5 266.5,-138.5 260.5,-138.5 254.5,-132.5 254.5,-126.5 254.5,-126.5 254.5,-12.5 254.5,-12.5 254.5,-6.5 260.5,-.5 266.5,-.5"/>
<text text-anchor="middle" x="293.5" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="332.5,-.5 332.5,-138.5 "/>
<text text-anchor="middle" x="343" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="353.5,-.5 353.5,-138.5 "/>
<text text-anchor="middle" x="459.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="353.5,-115.5 565.5,-115.5 "/>
<text text-anchor="middle" x="459.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="353.5,-92.5 565.5,-92.5 "/>
<text text-anchor="middle" x="459.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="353.5,-69.5 565.5,-69.5 "/>
<text text-anchor="middle" x="459.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="353.5,-46.5 565.5,-46.5 "/>
<text text-anchor="middle" x="459.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="353.5,-23.5 565.5,-23.5 "/>
<text text-anchor="middle" x="459.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="565.5,-.5 565.5,-138.5 "/>
<text text-anchor="middle" x="576" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge9" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M420.5,-190.338C420.5,-175.5265 420.5,-161.5495 420.5,-148.7219"/>
<polygon fill="#000000" stroke="#000000" points="424.0001,-148.6868 420.5,-138.6868 417.0001,-148.6869 424.0001,-148.6868"/>
<text text-anchor="middle" x="462" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- file&#45;&gt;genomic_info -->
<g id="edge12" class="edge">
<title>file&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M941.8084,-1185.7487C939.2176,-1196.6656 938.4667,-1207.884 940.5,-1219 942.4154,-1229.4713 944.8174,-1240.0953 947.583,-1250.7251"/>
<polygon fill="#000000" stroke="#000000" points="944.2329,-1251.7448 950.2215,-1260.4847 950.9903,-1249.9178 944.2329,-1251.7448"/>
<text text-anchor="middle" x="1009" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_genomic_info</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M550,-1680.5C550,-1680.5 959,-1680.5 959,-1680.5 965,-1680.5 971,-1686.5 971,-1692.5 971,-1692.5 971,-1852.5 971,-1852.5 971,-1858.5 965,-1864.5 959,-1864.5 959,-1864.5 550,-1864.5 550,-1864.5 544,-1864.5 538,-1858.5 538,-1852.5 538,-1852.5 538,-1692.5 538,-1692.5 538,-1686.5 544,-1680.5 550,-1680.5"/>
<text text-anchor="middle" x="572" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="606,-1680.5 606,-1864.5 "/>
<text text-anchor="middle" x="616.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="627,-1680.5 627,-1864.5 "/>
<text text-anchor="middle" x="788.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="627,-1841.5 950,-1841.5 "/>
<text text-anchor="middle" x="788.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="627,-1818.5 950,-1818.5 "/>
<text text-anchor="middle" x="788.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="627,-1795.5 950,-1795.5 "/>
<text text-anchor="middle" x="788.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="627,-1772.5 950,-1772.5 "/>
<text text-anchor="middle" x="788.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="627,-1749.5 950,-1749.5 "/>
<text text-anchor="middle" x="788.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="627,-1726.5 950,-1726.5 "/>
<text text-anchor="middle" x="788.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="627,-1703.5 950,-1703.5 "/>
<text text-anchor="middle" x="788.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="950,-1680.5 950,-1864.5 "/>
<text text-anchor="middle" x="960.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1204.5361,-1169.8448C1230.4117,-1187.9902 1253.4332,-1210.1246 1269.5,-1237 1358.8973,-1386.5376 1374.8709,-1490.2544 1269.5,-1629 1233.1905,-1676.81 1102.0701,-1712.944 981.2312,-1736.994"/>
<polygon fill="#000000" stroke="#000000" points="980.203,-1733.6291 971.0667,-1738.9936 981.5543,-1740.4974 980.203,-1733.6291"/>
<text text-anchor="middle" x="1389" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- methylation -->
<g id="node9" class="node">
<title>methylation</title>
<path fill="none" stroke="#000000" d="M790,-547C790,-547 1081,-547 1081,-547 1087,-547 1093,-553 1093,-559 1093,-559 1093,-581 1093,-581 1093,-587 1087,-593 1081,-593 1081,-593 790,-593 790,-593 784,-593 778,-587 778,-581 778,-581 778,-559 778,-559 778,-553 784,-547 790,-547"/>
<text text-anchor="middle" x="829" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation</text>
<polyline fill="none" stroke="#000000" points="880,-547 880,-593 "/>
<text text-anchor="middle" x="890.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="901,-547 901,-593 "/>
<text text-anchor="middle" x="986.5" y="-577.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="901,-570 1072,-570 "/>
<text text-anchor="middle" x="986.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1072,-547 1072,-593 "/>
<text text-anchor="middle" x="1082.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;methylation -->
<g id="edge11" class="edge">
<title>file&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M990.7144,-1001.4142C975.5269,-882.7477 949.8768,-682.3325 939.7732,-603.3883"/>
<polygon fill="#000000" stroke="#000000" points="943.1947,-602.551 938.4534,-593.0762 936.2513,-603.4397 943.1947,-602.551"/>
<text text-anchor="middle" x="1051" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_methylation</text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M537.7026,-1682.7389C534.6223,-1681.8 531.5536,-1680.8863 528.5,-1680 404.5009,-1644.0105 349.9341,-1700.6165 242.5,-1629 180.4891,-1587.663 142.4756,-1504.3146 126.0352,-1460.8302"/>
<polygon fill="#000000" stroke="#000000" points="129.226,-1459.3654 122.4959,-1451.1827 122.6543,-1461.7764 129.226,-1459.3654"/>
<text text-anchor="middle" x="356.5" y="-1650.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- sample&#45;&gt;genomic_info -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M827.1062,-1680.1786C843.4062,-1659.4526 861.2475,-1636.7667 879.3019,-1613.8099"/>
<polygon fill="#000000" stroke="#000000" points="882.264,-1615.7053 885.6947,-1605.6813 876.7617,-1611.3781 882.264,-1615.7053"/>
<text text-anchor="middle" x="906" y="-1650.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_genomic_info</text>
</g>
<!-- sample&#45;&gt;methylation -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M750.1333,-1680.2723C745.1887,-1534.4642 743.2625,-1242.4606 791.5,-1001 822.129,-847.6818 891.6332,-673.4495 921.4677,-602.5653"/>
<polygon fill="#000000" stroke="#000000" points="924.7307,-603.8353 925.406,-593.262 918.2845,-601.1064 924.7307,-603.8353"/>
<text text-anchor="middle" x="815" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_methylation</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M668.2943,-1680.1109C656.9662,-1664.0134 646.781,-1646.718 639.5,-1629 572.9174,-1466.9747 682.2139,-1390.8747 598.5,-1237 581.6662,-1206.0578 555.1145,-1179.3243 527.6048,-1157.5997"/>
<polygon fill="#000000" stroke="#000000" points="529.4977,-1154.6399 519.4386,-1151.3134 525.2277,-1160.1868 529.4977,-1154.6399"/>
<text text-anchor="middle" x="690" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation&#45;&gt;file -->
<g id="edge1" class="edge">
<title>methylation&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M931.3144,-593.4159C920.7834,-657.3394 896.7551,-839.6261 936.5,-983 937.324,-985.9726 938.2511,-988.946 939.2678,-991.9113"/>
<polygon fill="#000000" stroke="#000000" points="936.0158,-993.2077 942.8025,-1001.3436 942.5707,-990.7513 936.0158,-993.2077"/>
<text text-anchor="middle" x="958.5" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M420.5,-1035.9788C420.5,-1014.7142 420.5,-988.7061 420.5,-959.9579"/>
<polygon fill="#000000" stroke="#000000" points="424.0001,-959.6783 420.5,-949.6784 417.0001,-959.6784 424.0001,-959.6783"/>
<text text-anchor="middle" x="451" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
</g>
</svg>
</div>
