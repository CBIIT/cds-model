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
<svg width="1283pt" height="1850pt"
 viewBox="0.00 0.00 1282.50 1850.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1846)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1846 1278.5,-1846 1278.5,4 -4,4"/>
<!-- specimen -->
<g id="node1" class="node">
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
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M140,-1036C140,-1036 399,-1036 399,-1036 405,-1036 411,-1042 411,-1048 411,-1048 411,-1139 411,-1139 411,-1145 405,-1151 399,-1151 399,-1151 140,-1151 140,-1151 134,-1151 128,-1145 128,-1139 128,-1139 128,-1048 128,-1048 128,-1042 134,-1036 140,-1036"/>
<text text-anchor="middle" x="176" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="224,-1036 224,-1151 "/>
<text text-anchor="middle" x="234.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="245,-1036 245,-1151 "/>
<text text-anchor="middle" x="317.5" y="-1135.8" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="245,-1128 390,-1128 "/>
<text text-anchor="middle" x="317.5" y="-1112.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="245,-1105 390,-1105 "/>
<text text-anchor="middle" x="317.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="245,-1082 390,-1082 "/>
<text text-anchor="middle" x="317.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="245,-1059 390,-1059 "/>
<text text-anchor="middle" x="317.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="390,-1036 390,-1151 "/>
<text text-anchor="middle" x="400.5" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>specimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M115.7596,-1414.8544C114.8805,-1374.4704 117.0244,-1275.1315 154.5,-1204 163.1026,-1187.6716 175.0219,-1172.3548 187.9475,-1158.6298"/>
<polygon fill="#000000" stroke="#000000" points="190.7431,-1160.7761 195.2172,-1151.1723 185.7306,-1155.8899 190.7431,-1160.7761"/>
<text text-anchor="middle" x="205" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node2" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M940,-1703.5C940,-1703.5 1205,-1703.5 1205,-1703.5 1211,-1703.5 1217,-1709.5 1217,-1715.5 1217,-1715.5 1217,-1806.5 1217,-1806.5 1217,-1812.5 1211,-1818.5 1205,-1818.5 1205,-1818.5 940,-1818.5 940,-1818.5 934,-1818.5 928,-1812.5 928,-1806.5 928,-1806.5 928,-1715.5 928,-1715.5 928,-1709.5 934,-1703.5 940,-1703.5"/>
<text text-anchor="middle" x="972.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1017,-1703.5 1017,-1818.5 "/>
<text text-anchor="middle" x="1027.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1038,-1703.5 1038,-1818.5 "/>
<text text-anchor="middle" x="1117" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1038,-1795.5 1196,-1795.5 "/>
<text text-anchor="middle" x="1117" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1038,-1772.5 1196,-1772.5 "/>
<text text-anchor="middle" x="1117" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1038,-1749.5 1196,-1749.5 "/>
<text text-anchor="middle" x="1117" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1038,-1726.5 1196,-1726.5 "/>
<text text-anchor="middle" x="1117" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1196,-1703.5 1196,-1818.5 "/>
<text text-anchor="middle" x="1206.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M111.5,-190.5C111.5,-190.5 427.5,-190.5 427.5,-190.5 433.5,-190.5 439.5,-196.5 439.5,-202.5 439.5,-202.5 439.5,-937.5 439.5,-937.5 439.5,-943.5 433.5,-949.5 427.5,-949.5 427.5,-949.5 111.5,-949.5 111.5,-949.5 105.5,-949.5 99.5,-943.5 99.5,-937.5 99.5,-937.5 99.5,-202.5 99.5,-202.5 99.5,-196.5 105.5,-190.5 111.5,-190.5"/>
<text text-anchor="middle" x="127.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="155.5,-190.5 155.5,-949.5 "/>
<text text-anchor="middle" x="166" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="176.5,-190.5 176.5,-949.5 "/>
<text text-anchor="middle" x="297.5" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="176.5,-926.5 418.5,-926.5 "/>
<text text-anchor="middle" x="297.5" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="176.5,-903.5 418.5,-903.5 "/>
<text text-anchor="middle" x="297.5" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="176.5,-880.5 418.5,-880.5 "/>
<text text-anchor="middle" x="297.5" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="176.5,-857.5 418.5,-857.5 "/>
<text text-anchor="middle" x="297.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="176.5,-834.5 418.5,-834.5 "/>
<text text-anchor="middle" x="297.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="176.5,-811.5 418.5,-811.5 "/>
<text text-anchor="middle" x="297.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="176.5,-788.5 418.5,-788.5 "/>
<text text-anchor="middle" x="297.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="176.5,-765.5 418.5,-765.5 "/>
<text text-anchor="middle" x="297.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="176.5,-742.5 418.5,-742.5 "/>
<text text-anchor="middle" x="297.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="176.5,-719.5 418.5,-719.5 "/>
<text text-anchor="middle" x="297.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="176.5,-696.5 418.5,-696.5 "/>
<text text-anchor="middle" x="297.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="176.5,-673.5 418.5,-673.5 "/>
<text text-anchor="middle" x="297.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="176.5,-650.5 418.5,-650.5 "/>
<text text-anchor="middle" x="297.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="176.5,-627.5 418.5,-627.5 "/>
<text text-anchor="middle" x="297.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="176.5,-604.5 418.5,-604.5 "/>
<text text-anchor="middle" x="297.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="176.5,-581.5 418.5,-581.5 "/>
<text text-anchor="middle" x="297.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="176.5,-558.5 418.5,-558.5 "/>
<text text-anchor="middle" x="297.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="176.5,-535.5 418.5,-535.5 "/>
<text text-anchor="middle" x="297.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="176.5,-512.5 418.5,-512.5 "/>
<text text-anchor="middle" x="297.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="176.5,-489.5 418.5,-489.5 "/>
<text text-anchor="middle" x="297.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="176.5,-466.5 418.5,-466.5 "/>
<text text-anchor="middle" x="297.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="176.5,-443.5 418.5,-443.5 "/>
<text text-anchor="middle" x="297.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="176.5,-420.5 418.5,-420.5 "/>
<text text-anchor="middle" x="297.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="176.5,-397.5 418.5,-397.5 "/>
<text text-anchor="middle" x="297.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="176.5,-374.5 418.5,-374.5 "/>
<text text-anchor="middle" x="297.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="176.5,-351.5 418.5,-351.5 "/>
<text text-anchor="middle" x="297.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="176.5,-328.5 418.5,-328.5 "/>
<text text-anchor="middle" x="297.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="176.5,-305.5 418.5,-305.5 "/>
<text text-anchor="middle" x="297.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="176.5,-282.5 418.5,-282.5 "/>
<text text-anchor="middle" x="297.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="176.5,-259.5 418.5,-259.5 "/>
<text text-anchor="middle" x="297.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="176.5,-236.5 418.5,-236.5 "/>
<text text-anchor="middle" x="297.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="176.5,-213.5 418.5,-213.5 "/>
<text text-anchor="middle" x="297.5" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="418.5,-190.5 418.5,-949.5 "/>
<text text-anchor="middle" x="429" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M269.5,-1035.9788C269.5,-1014.7142 269.5,-988.7061 269.5,-959.9579"/>
<polygon fill="#000000" stroke="#000000" points="273.0001,-959.6783 269.5,-949.6784 266.0001,-959.6784 273.0001,-959.6783"/>
<text text-anchor="middle" x="300" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- methylation -->
<g id="node4" class="node">
<title>methylation</title>
<path fill="none" stroke="#000000" d="M795,-1410C795,-1410 1086,-1410 1086,-1410 1092,-1410 1098,-1416 1098,-1422 1098,-1422 1098,-1444 1098,-1444 1098,-1450 1092,-1456 1086,-1456 1086,-1456 795,-1456 795,-1456 789,-1456 783,-1450 783,-1444 783,-1444 783,-1422 783,-1422 783,-1416 789,-1410 795,-1410"/>
<text text-anchor="middle" x="834" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation</text>
<polyline fill="none" stroke="#000000" points="885,-1410 885,-1456 "/>
<text text-anchor="middle" x="895.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="906,-1410 906,-1456 "/>
<text text-anchor="middle" x="991.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="906,-1433 1077,-1433 "/>
<text text-anchor="middle" x="991.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1077,-1410 1077,-1456 "/>
<text text-anchor="middle" x="1087.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node10" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M796.5,-1001.5C796.5,-1001.5 1176.5,-1001.5 1176.5,-1001.5 1182.5,-1001.5 1188.5,-1007.5 1188.5,-1013.5 1188.5,-1013.5 1188.5,-1173.5 1188.5,-1173.5 1188.5,-1179.5 1182.5,-1185.5 1176.5,-1185.5 1176.5,-1185.5 796.5,-1185.5 796.5,-1185.5 790.5,-1185.5 784.5,-1179.5 784.5,-1173.5 784.5,-1173.5 784.5,-1013.5 784.5,-1013.5 784.5,-1007.5 790.5,-1001.5 796.5,-1001.5"/>
<text text-anchor="middle" x="804" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="823.5,-1001.5 823.5,-1185.5 "/>
<text text-anchor="middle" x="834" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="844.5,-1001.5 844.5,-1185.5 "/>
<text text-anchor="middle" x="1006" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="844.5,-1162.5 1167.5,-1162.5 "/>
<text text-anchor="middle" x="1006" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="844.5,-1139.5 1167.5,-1139.5 "/>
<text text-anchor="middle" x="1006" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="844.5,-1116.5 1167.5,-1116.5 "/>
<text text-anchor="middle" x="1006" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="844.5,-1093.5 1167.5,-1093.5 "/>
<text text-anchor="middle" x="1006" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="844.5,-1070.5 1167.5,-1070.5 "/>
<text text-anchor="middle" x="1006" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="844.5,-1047.5 1167.5,-1047.5 "/>
<text text-anchor="middle" x="1006" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="844.5,-1024.5 1167.5,-1024.5 "/>
<text text-anchor="middle" x="1006" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1167.5,-1001.5 1167.5,-1185.5 "/>
<text text-anchor="middle" x="1178" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation&#45;&gt;file -->
<g id="edge11" class="edge">
<title>methylation&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M933.3914,-1409.7685C921.6972,-1367.853 901.5848,-1277.1347 921.5,-1204 922.3073,-1201.0354 923.2165,-1198.0693 924.2143,-1195.1103"/>
<polygon fill="#000000" stroke="#000000" points="927.5099,-1196.2893 927.686,-1185.6959 920.9422,-1193.8673 927.5099,-1196.2893"/>
<text text-anchor="middle" x="943.5" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- program -->
<g id="node5" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M115.5,-.5C115.5,-.5 423.5,-.5 423.5,-.5 429.5,-.5 435.5,-6.5 435.5,-12.5 435.5,-12.5 435.5,-126.5 435.5,-126.5 435.5,-132.5 429.5,-138.5 423.5,-138.5 423.5,-138.5 115.5,-138.5 115.5,-138.5 109.5,-138.5 103.5,-132.5 103.5,-126.5 103.5,-126.5 103.5,-12.5 103.5,-12.5 103.5,-6.5 109.5,-.5 115.5,-.5"/>
<text text-anchor="middle" x="142.5" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="181.5,-.5 181.5,-138.5 "/>
<text text-anchor="middle" x="192" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="202.5,-.5 202.5,-138.5 "/>
<text text-anchor="middle" x="308.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="202.5,-115.5 414.5,-115.5 "/>
<text text-anchor="middle" x="308.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="202.5,-92.5 414.5,-92.5 "/>
<text text-anchor="middle" x="308.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="202.5,-69.5 414.5,-69.5 "/>
<text text-anchor="middle" x="308.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="202.5,-46.5 414.5,-46.5 "/>
<text text-anchor="middle" x="308.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="202.5,-23.5 414.5,-23.5 "/>
<text text-anchor="middle" x="308.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="414.5,-.5 414.5,-138.5 "/>
<text text-anchor="middle" x="425" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M611.5,-1680.5C611.5,-1680.5 897.5,-1680.5 897.5,-1680.5 903.5,-1680.5 909.5,-1686.5 909.5,-1692.5 909.5,-1692.5 909.5,-1829.5 909.5,-1829.5 909.5,-1835.5 903.5,-1841.5 897.5,-1841.5 897.5,-1841.5 611.5,-1841.5 611.5,-1841.5 605.5,-1841.5 599.5,-1835.5 599.5,-1829.5 599.5,-1829.5 599.5,-1692.5 599.5,-1692.5 599.5,-1686.5 605.5,-1680.5 611.5,-1680.5"/>
<text text-anchor="middle" x="633.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="667.5,-1680.5 667.5,-1841.5 "/>
<text text-anchor="middle" x="678" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="688.5,-1680.5 688.5,-1841.5 "/>
<text text-anchor="middle" x="788.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="688.5,-1818.5 888.5,-1818.5 "/>
<text text-anchor="middle" x="788.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="688.5,-1795.5 888.5,-1795.5 "/>
<text text-anchor="middle" x="788.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="688.5,-1772.5 888.5,-1772.5 "/>
<text text-anchor="middle" x="788.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="688.5,-1749.5 888.5,-1749.5 "/>
<text text-anchor="middle" x="788.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="688.5,-1726.5 888.5,-1726.5 "/>
<text text-anchor="middle" x="788.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="688.5,-1703.5 888.5,-1703.5 "/>
<text text-anchor="middle" x="788.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="888.5,-1680.5 888.5,-1841.5 "/>
<text text-anchor="middle" x="899" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M599.4825,-1754.2663C446.2743,-1744.3205 226.2367,-1720.1056 165.5,-1662 110.0559,-1608.9576 109.7293,-1509.6647 113.3865,-1461.1418"/>
<polygon fill="#000000" stroke="#000000" points="116.8849,-1461.3108 114.2626,-1451.0456 109.9111,-1460.7056 116.8849,-1461.3108"/>
<text text-anchor="middle" x="210.5" y="-1650.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M599.3422,-1738.3342C476.0866,-1716.8092 318.0573,-1680.1226 278.5,-1629 250.5982,-1592.9407 260.1684,-1297.7874 266.1695,-1161.729"/>
<polygon fill="#000000" stroke="#000000" points="269.6799,-1161.573 266.6305,-1151.4265 262.6869,-1161.26 269.6799,-1161.573"/>
<text text-anchor="middle" x="329" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;methylation -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M800.2389,-1680.3421C839.548,-1611.0229 894.1995,-1514.6481 922.2654,-1465.1556"/>
<polygon fill="#000000" stroke="#000000" points="925.461,-1466.6156 927.3493,-1456.1904 919.3719,-1463.1626 925.461,-1466.6156"/>
<text text-anchor="middle" x="868" y="-1650.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_methylation</text>
</g>
<!-- genomic_info -->
<g id="node8" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M693,-397.5C693,-397.5 1146,-397.5 1146,-397.5 1152,-397.5 1158,-403.5 1158,-409.5 1158,-409.5 1158,-730.5 1158,-730.5 1158,-736.5 1152,-742.5 1146,-742.5 1146,-742.5 693,-742.5 693,-742.5 687,-742.5 681,-736.5 681,-730.5 681,-730.5 681,-409.5 681,-409.5 681,-403.5 687,-397.5 693,-397.5"/>
<text text-anchor="middle" x="737" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="793,-397.5 793,-742.5 "/>
<text text-anchor="middle" x="803.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="814,-397.5 814,-742.5 "/>
<text text-anchor="middle" x="975.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="814,-719.5 1137,-719.5 "/>
<text text-anchor="middle" x="975.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="814,-696.5 1137,-696.5 "/>
<text text-anchor="middle" x="975.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="814,-673.5 1137,-673.5 "/>
<text text-anchor="middle" x="975.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="814,-650.5 1137,-650.5 "/>
<text text-anchor="middle" x="975.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="814,-627.5 1137,-627.5 "/>
<text text-anchor="middle" x="975.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="814,-604.5 1137,-604.5 "/>
<text text-anchor="middle" x="975.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="814,-581.5 1137,-581.5 "/>
<text text-anchor="middle" x="975.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="814,-558.5 1137,-558.5 "/>
<text text-anchor="middle" x="975.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="814,-535.5 1137,-535.5 "/>
<text text-anchor="middle" x="975.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="814,-512.5 1137,-512.5 "/>
<text text-anchor="middle" x="975.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="814,-489.5 1137,-489.5 "/>
<text text-anchor="middle" x="975.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="814,-466.5 1137,-466.5 "/>
<text text-anchor="middle" x="975.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="814,-443.5 1137,-443.5 "/>
<text text-anchor="middle" x="975.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="814,-420.5 1137,-420.5 "/>
<text text-anchor="middle" x="975.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1137,-397.5 1137,-742.5 "/>
<text text-anchor="middle" x="1147.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;genomic_info -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M749.0109,-1680.3415C741.2173,-1540.6885 732.2864,-1245.3586 775.5,-1001 790.289,-917.3733 818.1018,-827.8686 845.3708,-752.2156"/>
<polygon fill="#000000" stroke="#000000" points="848.744,-753.1803 848.8656,-742.5862 842.164,-750.7922 848.744,-753.1803"/>
<text text-anchor="middle" x="809" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_genomic_info</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge1" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M269.5,-190.338C269.5,-175.5265 269.5,-161.5495 269.5,-148.7219"/>
<polygon fill="#000000" stroke="#000000" points="273.0001,-148.6868 269.5,-138.6868 266.0001,-148.6869 273.0001,-148.6868"/>
<text text-anchor="middle" x="311" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge12" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M901.9396,-742.6876C899.2032,-817.7198 902.6663,-905.9042 923.5,-983 924.2696,-985.848 925.1305,-988.6997 926.071,-991.5469"/>
<polygon fill="#000000" stroke="#000000" points="922.8683,-992.9829 929.5585,-1001.1983 929.4517,-990.604 922.8683,-992.9829"/>
<text text-anchor="middle" x="945.5" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M400.5,-1237.5C400.5,-1237.5 714.5,-1237.5 714.5,-1237.5 720.5,-1237.5 726.5,-1243.5 726.5,-1249.5 726.5,-1249.5 726.5,-1616.5 726.5,-1616.5 726.5,-1622.5 720.5,-1628.5 714.5,-1628.5 714.5,-1628.5 400.5,-1628.5 400.5,-1628.5 394.5,-1628.5 388.5,-1622.5 388.5,-1616.5 388.5,-1616.5 388.5,-1249.5 388.5,-1249.5 388.5,-1243.5 394.5,-1237.5 400.5,-1237.5"/>
<text text-anchor="middle" x="430.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="472.5,-1237.5 472.5,-1628.5 "/>
<text text-anchor="middle" x="483" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="493.5,-1237.5 493.5,-1628.5 "/>
<text text-anchor="middle" x="599.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="493.5,-1605.5 705.5,-1605.5 "/>
<text text-anchor="middle" x="599.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="493.5,-1582.5 705.5,-1582.5 "/>
<text text-anchor="middle" x="599.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="493.5,-1559.5 705.5,-1559.5 "/>
<text text-anchor="middle" x="599.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="493.5,-1536.5 705.5,-1536.5 "/>
<text text-anchor="middle" x="599.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="493.5,-1513.5 705.5,-1513.5 "/>
<text text-anchor="middle" x="599.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="493.5,-1490.5 705.5,-1490.5 "/>
<text text-anchor="middle" x="599.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="493.5,-1467.5 705.5,-1467.5 "/>
<text text-anchor="middle" x="599.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="493.5,-1444.5 705.5,-1444.5 "/>
<text text-anchor="middle" x="599.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="493.5,-1421.5 705.5,-1421.5 "/>
<text text-anchor="middle" x="599.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="493.5,-1398.5 705.5,-1398.5 "/>
<text text-anchor="middle" x="599.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="493.5,-1375.5 705.5,-1375.5 "/>
<text text-anchor="middle" x="599.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="493.5,-1352.5 705.5,-1352.5 "/>
<text text-anchor="middle" x="599.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="493.5,-1329.5 705.5,-1329.5 "/>
<text text-anchor="middle" x="599.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="493.5,-1306.5 705.5,-1306.5 "/>
<text text-anchor="middle" x="599.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="493.5,-1283.5 705.5,-1283.5 "/>
<text text-anchor="middle" x="599.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="493.5,-1260.5 705.5,-1260.5 "/>
<text text-anchor="middle" x="599.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="705.5,-1237.5 705.5,-1628.5 "/>
<text text-anchor="middle" x="716" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M391.6379,-1237.4786C367.7095,-1209.2712 344.6056,-1182.0359 325.0527,-1158.9866"/>
<polygon fill="#000000" stroke="#000000" points="327.6998,-1156.6966 318.5618,-1151.335 322.3618,-1161.2249 327.6998,-1156.6966"/>
<text text-anchor="middle" x="422" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;methylation -->
<g id="edge3" class="edge">
<title>file&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M974.014,-1185.6521C964.3951,-1256.6439 951.65,-1350.7082 944.9898,-1399.8636"/>
<polygon fill="#000000" stroke="#000000" points="941.5,-1399.5523 943.6256,-1409.9317 948.4367,-1400.4922 941.5,-1399.5523"/>
<text text-anchor="middle" x="1033" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_methylation</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1088.815,-1185.6243C1093.0939,-1191.5904 1097.0328,-1197.7281 1100.5,-1204 1191.8991,-1369.3327 1222.2713,-1478.9459 1107.5,-1629 1054.9028,-1697.7666 1000.5066,-1649.4511 919.5,-1680 919.3974,-1680.0387 919.2947,-1680.0775 919.192,-1680.1162"/>
<polygon fill="#000000" stroke="#000000" points="917.6465,-1676.9615 909.5875,-1683.8392 920.1765,-1683.4883 917.6465,-1676.9615"/>
<text text-anchor="middle" x="1228" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;genomic_info -->
<g id="edge5" class="edge">
<title>file&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M974.7144,-1001.4142C965.9196,-932.6961 953.6162,-836.5644 942.855,-752.4824"/>
<polygon fill="#000000" stroke="#000000" points="946.3256,-752.0289 941.5843,-742.5542 939.3822,-752.9176 946.3256,-752.0289"/>
<text text-anchor="middle" x="1040" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_genomic_info</text>
</g>
</g>
</svg>
</div>
