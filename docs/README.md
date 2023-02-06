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
<svg width="1286pt" height="1873pt"
 viewBox="0.00 0.00 1286.00 1873.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1869)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1869 1282,-1869 1282,4 -4,4"/>
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
<g id="node7" class="node">
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
<g id="edge11" class="edge">
<title>specimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M115.7596,-1414.8544C114.8805,-1374.4704 117.0244,-1275.1315 154.5,-1204 163.1026,-1187.6716 175.0219,-1172.3548 187.9475,-1158.6298"/>
<polygon fill="#000000" stroke="#000000" points="190.7431,-1160.7761 195.2172,-1151.1723 185.7306,-1155.8899 190.7431,-1160.7761"/>
<text text-anchor="middle" x="205" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
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
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M391.6379,-1237.4786C367.7095,-1209.2712 344.6056,-1182.0359 325.0527,-1158.9866"/>
<polygon fill="#000000" stroke="#000000" points="327.6998,-1156.6966 318.5618,-1151.335 322.3618,-1161.2249 327.6998,-1156.6966"/>
<text text-anchor="middle" x="422" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1001,-1715C1001,-1715 1266,-1715 1266,-1715 1272,-1715 1278,-1721 1278,-1727 1278,-1727 1278,-1818 1278,-1818 1278,-1824 1272,-1830 1266,-1830 1266,-1830 1001,-1830 1001,-1830 995,-1830 989,-1824 989,-1818 989,-1818 989,-1727 989,-1727 989,-1721 995,-1715 1001,-1715"/>
<text text-anchor="middle" x="1033.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1078,-1715 1078,-1830 "/>
<text text-anchor="middle" x="1088.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1099,-1715 1099,-1830 "/>
<text text-anchor="middle" x="1178" y="-1814.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1099,-1807 1257,-1807 "/>
<text text-anchor="middle" x="1178" y="-1791.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1099,-1784 1257,-1784 "/>
<text text-anchor="middle" x="1178" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1099,-1761 1257,-1761 "/>
<text text-anchor="middle" x="1178" y="-1745.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1099,-1738 1257,-1738 "/>
<text text-anchor="middle" x="1178" y="-1722.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1257,-1715 1257,-1830 "/>
<text text-anchor="middle" x="1267.5" y="-1768.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
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
<!-- program -->
<g id="node6" class="node">
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
<!-- study&#45;&gt;program -->
<g id="edge3" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M269.5,-190.338C269.5,-175.5265 269.5,-161.5495 269.5,-148.7219"/>
<polygon fill="#000000" stroke="#000000" points="273.0001,-148.6868 269.5,-138.6868 266.0001,-148.6869 273.0001,-148.6868"/>
<text text-anchor="middle" x="311" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- sample -->
<g id="node5" class="node">
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
<!-- sample&#45;&gt;specimen -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M537.6627,-1756.7569C392.2866,-1741.6754 218.1582,-1713.3402 165.5,-1662 110.6956,-1608.5673 109.9976,-1509.8778 113.4653,-1461.3919"/>
<polygon fill="#000000" stroke="#000000" points="116.9642,-1461.5485 114.3019,-1451.2936 109.9881,-1460.9705 116.9642,-1461.5485"/>
<text text-anchor="middle" x="210.5" y="-1650.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M537.9177,-1732.9919C428.2692,-1708.1658 311.4581,-1672.5892 278.5,-1629 251.0019,-1592.6319 260.3572,-1297.643 266.2357,-1161.6783"/>
<polygon fill="#000000" stroke="#000000" points="269.7456,-1161.5268 266.6874,-1151.383 262.7523,-1161.22 269.7456,-1161.5268"/>
<text text-anchor="middle" x="329" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- methylation -->
<g id="node9" class="node">
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
<!-- sample&#45;&gt;methylation -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M805.0796,-1680.1786C844.2915,-1608.6064 896.3081,-1513.6621 923.0231,-1464.9001"/>
<polygon fill="#000000" stroke="#000000" points="926.1275,-1466.518 927.8628,-1456.0662 919.9885,-1463.1546 926.1275,-1466.518"/>
<text text-anchor="middle" x="874" y="-1650.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_methylation</text>
</g>
<!-- genomic_info -->
<g id="node10" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M695,-397.5C695,-397.5 1148,-397.5 1148,-397.5 1154,-397.5 1160,-403.5 1160,-409.5 1160,-409.5 1160,-730.5 1160,-730.5 1160,-736.5 1154,-742.5 1148,-742.5 1148,-742.5 695,-742.5 695,-742.5 689,-742.5 683,-736.5 683,-730.5 683,-730.5 683,-409.5 683,-409.5 683,-403.5 689,-397.5 695,-397.5"/>
<text text-anchor="middle" x="739" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="795,-397.5 795,-742.5 "/>
<text text-anchor="middle" x="805.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="816,-397.5 816,-742.5 "/>
<text text-anchor="middle" x="977.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="816,-719.5 1139,-719.5 "/>
<text text-anchor="middle" x="977.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="816,-696.5 1139,-696.5 "/>
<text text-anchor="middle" x="977.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="816,-673.5 1139,-673.5 "/>
<text text-anchor="middle" x="977.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="816,-650.5 1139,-650.5 "/>
<text text-anchor="middle" x="977.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="816,-627.5 1139,-627.5 "/>
<text text-anchor="middle" x="977.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="816,-604.5 1139,-604.5 "/>
<text text-anchor="middle" x="977.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="816,-581.5 1139,-581.5 "/>
<text text-anchor="middle" x="977.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="816,-558.5 1139,-558.5 "/>
<text text-anchor="middle" x="977.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="816,-535.5 1139,-535.5 "/>
<text text-anchor="middle" x="977.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="816,-512.5 1139,-512.5 "/>
<text text-anchor="middle" x="977.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="816,-489.5 1139,-489.5 "/>
<text text-anchor="middle" x="977.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="816,-466.5 1139,-466.5 "/>
<text text-anchor="middle" x="977.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="816,-443.5 1139,-443.5 "/>
<text text-anchor="middle" x="977.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="816,-420.5 1139,-420.5 "/>
<text text-anchor="middle" x="977.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1139,-397.5 1139,-742.5 "/>
<text text-anchor="middle" x="1149.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;genomic_info -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M748.6377,-1680.462C741.289,-1534.9116 734.3867,-1243.2519 777.5,-1001 792.3801,-917.3894 820.2074,-827.8873 847.4626,-752.2319"/>
<polygon fill="#000000" stroke="#000000" points="850.8358,-753.1963 850.9555,-742.6021 844.2553,-750.8094 850.8358,-753.1963"/>
<text text-anchor="middle" x="811" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_genomic_info</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M269.5,-1035.9788C269.5,-1014.7142 269.5,-988.7061 269.5,-959.9579"/>
<polygon fill="#000000" stroke="#000000" points="273.0001,-959.6783 269.5,-949.6784 266.0001,-959.6784 273.0001,-959.6783"/>
<text text-anchor="middle" x="300" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file -->
<g id="node8" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M798.5,-1001.5C798.5,-1001.5 1178.5,-1001.5 1178.5,-1001.5 1184.5,-1001.5 1190.5,-1007.5 1190.5,-1013.5 1190.5,-1013.5 1190.5,-1173.5 1190.5,-1173.5 1190.5,-1179.5 1184.5,-1185.5 1178.5,-1185.5 1178.5,-1185.5 798.5,-1185.5 798.5,-1185.5 792.5,-1185.5 786.5,-1179.5 786.5,-1173.5 786.5,-1173.5 786.5,-1013.5 786.5,-1013.5 786.5,-1007.5 792.5,-1001.5 798.5,-1001.5"/>
<text text-anchor="middle" x="806" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="825.5,-1001.5 825.5,-1185.5 "/>
<text text-anchor="middle" x="836" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="846.5,-1001.5 846.5,-1185.5 "/>
<text text-anchor="middle" x="1008" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="846.5,-1162.5 1169.5,-1162.5 "/>
<text text-anchor="middle" x="1008" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="846.5,-1139.5 1169.5,-1139.5 "/>
<text text-anchor="middle" x="1008" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="846.5,-1116.5 1169.5,-1116.5 "/>
<text text-anchor="middle" x="1008" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="846.5,-1093.5 1169.5,-1093.5 "/>
<text text-anchor="middle" x="1008" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="846.5,-1070.5 1169.5,-1070.5 "/>
<text text-anchor="middle" x="1008" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="846.5,-1047.5 1169.5,-1047.5 "/>
<text text-anchor="middle" x="1008" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="846.5,-1024.5 1169.5,-1024.5 "/>
<text text-anchor="middle" x="1008" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1169.5,-1001.5 1169.5,-1185.5 "/>
<text text-anchor="middle" x="1180" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1091.5037,-1185.7326C1095.5727,-1191.6517 1099.2813,-1197.7517 1102.5,-1204 1189.0062,-1371.9304 1213.2977,-1472.5047 1107.5,-1629 1073.4336,-1679.3908 1036.869,-1657.1464 980.5,-1680 980.4018,-1680.0398 980.3035,-1680.0797 980.2053,-1680.1195"/>
<polygon fill="#000000" stroke="#000000" points="978.9531,-1676.8504 971.0024,-1683.8531 981.5847,-1683.3369 978.9531,-1676.8504"/>
<text text-anchor="middle" x="1224" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;methylation -->
<g id="edge1" class="edge">
<title>file&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M975.4711,-1185.6521C965.434,-1256.6439 952.1348,-1350.7082 945.185,-1399.8636"/>
<polygon fill="#000000" stroke="#000000" points="941.696,-1399.5402 943.7615,-1409.9317 948.627,-1400.5202 941.696,-1399.5402"/>
<text text-anchor="middle" x="1035" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_methylation</text>
</g>
<!-- file&#45;&gt;genomic_info -->
<g id="edge10" class="edge">
<title>file&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M976.7144,-1001.4142C967.9196,-932.6961 955.6162,-836.5644 944.855,-752.4824"/>
<polygon fill="#000000" stroke="#000000" points="948.3256,-752.0289 943.5843,-742.5542 941.3822,-752.9176 948.3256,-752.0289"/>
<text text-anchor="middle" x="1042" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_genomic_info</text>
</g>
<!-- methylation&#45;&gt;file -->
<g id="edge7" class="edge">
<title>methylation&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M933.7244,-1409.7586C922.6026,-1367.8272 903.5984,-1277.0848 923.5,-1204 924.3073,-1201.0354 925.2165,-1198.0693 926.2143,-1195.1103"/>
<polygon fill="#000000" stroke="#000000" points="929.5099,-1196.2893 929.686,-1185.6959 922.9422,-1193.8673 929.5099,-1196.2893"/>
<text text-anchor="middle" x="945.5" y="-1207.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge6" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M901.6828,-742.5692C898.2004,-817.6804 901.1431,-905.9581 922.5,-983 923.324,-985.9726 924.2511,-988.946 925.2678,-991.9113"/>
<polygon fill="#000000" stroke="#000000" points="922.0158,-993.2077 928.8025,-1001.3436 928.5707,-990.7513 922.0158,-993.2077"/>
<text text-anchor="middle" x="944.5" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
</g>
</svg>
</div>
