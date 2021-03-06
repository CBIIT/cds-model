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
<svg width="1454pt" height="1637pt"
 viewBox="0.00 0.00 1453.91 1637.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1633)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1633 1449.9134,-1633 1449.9134,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M448.9134,-1024.5C448.9134,-1024.5 762.9134,-1024.5 762.9134,-1024.5 768.9134,-1024.5 774.9134,-1030.5 774.9134,-1036.5 774.9134,-1036.5 774.9134,-1403.5 774.9134,-1403.5 774.9134,-1409.5 768.9134,-1415.5 762.9134,-1415.5 762.9134,-1415.5 448.9134,-1415.5 448.9134,-1415.5 442.9134,-1415.5 436.9134,-1409.5 436.9134,-1403.5 436.9134,-1403.5 436.9134,-1036.5 436.9134,-1036.5 436.9134,-1030.5 442.9134,-1024.5 448.9134,-1024.5"/>
<text text-anchor="middle" x="478.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="520.9134,-1024.5 520.9134,-1415.5 "/>
<text text-anchor="middle" x="531.4134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="541.9134,-1024.5 541.9134,-1415.5 "/>
<text text-anchor="middle" x="647.9134" y="-1400.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1392.5 753.9134,-1392.5 "/>
<text text-anchor="middle" x="647.9134" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1369.5 753.9134,-1369.5 "/>
<text text-anchor="middle" x="647.9134" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1346.5 753.9134,-1346.5 "/>
<text text-anchor="middle" x="647.9134" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1323.5 753.9134,-1323.5 "/>
<text text-anchor="middle" x="647.9134" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1300.5 753.9134,-1300.5 "/>
<text text-anchor="middle" x="647.9134" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1277.5 753.9134,-1277.5 "/>
<text text-anchor="middle" x="647.9134" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1254.5 753.9134,-1254.5 "/>
<text text-anchor="middle" x="647.9134" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1231.5 753.9134,-1231.5 "/>
<text text-anchor="middle" x="647.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1208.5 753.9134,-1208.5 "/>
<text text-anchor="middle" x="647.9134" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1185.5 753.9134,-1185.5 "/>
<text text-anchor="middle" x="647.9134" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1162.5 753.9134,-1162.5 "/>
<text text-anchor="middle" x="647.9134" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1139.5 753.9134,-1139.5 "/>
<text text-anchor="middle" x="647.9134" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1116.5 753.9134,-1116.5 "/>
<text text-anchor="middle" x="647.9134" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1093.5 753.9134,-1093.5 "/>
<text text-anchor="middle" x="647.9134" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1070.5 753.9134,-1070.5 "/>
<text text-anchor="middle" x="647.9134" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="541.9134,-1047.5 753.9134,-1047.5 "/>
<text text-anchor="middle" x="647.9134" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="753.9134,-1024.5 753.9134,-1415.5 "/>
<text text-anchor="middle" x="764.4134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M172.4134,-834.5C172.4134,-834.5 431.4134,-834.5 431.4134,-834.5 437.4134,-834.5 443.4134,-840.5 443.4134,-846.5 443.4134,-846.5 443.4134,-937.5 443.4134,-937.5 443.4134,-943.5 437.4134,-949.5 431.4134,-949.5 431.4134,-949.5 172.4134,-949.5 172.4134,-949.5 166.4134,-949.5 160.4134,-943.5 160.4134,-937.5 160.4134,-937.5 160.4134,-846.5 160.4134,-846.5 160.4134,-840.5 166.4134,-834.5 172.4134,-834.5"/>
<text text-anchor="middle" x="208.4134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="256.4134,-834.5 256.4134,-949.5 "/>
<text text-anchor="middle" x="266.9134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="277.4134,-834.5 277.4134,-949.5 "/>
<text text-anchor="middle" x="349.9134" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="277.4134,-926.5 422.4134,-926.5 "/>
<text text-anchor="middle" x="349.9134" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="277.4134,-903.5 422.4134,-903.5 "/>
<text text-anchor="middle" x="349.9134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="277.4134,-880.5 422.4134,-880.5 "/>
<text text-anchor="middle" x="349.9134" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="277.4134,-857.5 422.4134,-857.5 "/>
<text text-anchor="middle" x="349.9134" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="422.4134,-834.5 422.4134,-949.5 "/>
<text text-anchor="middle" x="432.9134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M438.1189,-1024.2344C427.6738,-1012.8853 417.2192,-1001.7327 406.9134,-991 395.9919,-979.6261 384.0941,-967.861 372.3601,-956.5845"/>
<polygon fill="#000000" stroke="#000000" points="374.7337,-954.0116 365.0854,-949.6342 369.8981,-959.0729 374.7337,-954.0116"/>
<text text-anchor="middle" x="468.4134" y="-994.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genomic_info -->
<g id="node2" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M805.4134,-1047.5C805.4134,-1047.5 1258.4134,-1047.5 1258.4134,-1047.5 1264.4134,-1047.5 1270.4134,-1053.5 1270.4134,-1059.5 1270.4134,-1059.5 1270.4134,-1380.5 1270.4134,-1380.5 1270.4134,-1386.5 1264.4134,-1392.5 1258.4134,-1392.5 1258.4134,-1392.5 805.4134,-1392.5 805.4134,-1392.5 799.4134,-1392.5 793.4134,-1386.5 793.4134,-1380.5 793.4134,-1380.5 793.4134,-1059.5 793.4134,-1059.5 793.4134,-1053.5 799.4134,-1047.5 805.4134,-1047.5"/>
<text text-anchor="middle" x="849.4134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="905.4134,-1047.5 905.4134,-1392.5 "/>
<text text-anchor="middle" x="915.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="926.4134,-1047.5 926.4134,-1392.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1369.5 1249.4134,-1369.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1346.5 1249.4134,-1346.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1323.5 1249.4134,-1323.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1300.5 1249.4134,-1300.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1277.5 1249.4134,-1277.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1254.5 1249.4134,-1254.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1231.5 1249.4134,-1231.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1208.5 1249.4134,-1208.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1185.5 1249.4134,-1185.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1162.5 1249.4134,-1162.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1139.5 1249.4134,-1139.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1116.5 1249.4134,-1116.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1093.5 1249.4134,-1093.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="926.4134,-1070.5 1249.4134,-1070.5 "/>
<text text-anchor="middle" x="1087.9134" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1249.4134,-1047.5 1249.4134,-1392.5 "/>
<text text-anchor="middle" x="1259.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node8" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M1006.4134,-811.5C1006.4134,-811.5 1191.4134,-811.5 1191.4134,-811.5 1197.4134,-811.5 1203.4134,-817.5 1203.4134,-823.5 1203.4134,-823.5 1203.4134,-960.5 1203.4134,-960.5 1203.4134,-966.5 1197.4134,-972.5 1191.4134,-972.5 1191.4134,-972.5 1006.4134,-972.5 1006.4134,-972.5 1000.4134,-972.5 994.4134,-966.5 994.4134,-960.5 994.4134,-960.5 994.4134,-823.5 994.4134,-823.5 994.4134,-817.5 1000.4134,-811.5 1006.4134,-811.5"/>
<text text-anchor="middle" x="1013.9134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="1033.4134,-811.5 1033.4134,-972.5 "/>
<text text-anchor="middle" x="1043.9134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1054.4134,-811.5 1054.4134,-972.5 "/>
<text text-anchor="middle" x="1118.4134" y="-957.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1054.4134,-949.5 1182.4134,-949.5 "/>
<text text-anchor="middle" x="1118.4134" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="1054.4134,-926.5 1182.4134,-926.5 "/>
<text text-anchor="middle" x="1118.4134" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1054.4134,-903.5 1182.4134,-903.5 "/>
<text text-anchor="middle" x="1118.4134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1054.4134,-880.5 1182.4134,-880.5 "/>
<text text-anchor="middle" x="1118.4134" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1054.4134,-857.5 1182.4134,-857.5 "/>
<text text-anchor="middle" x="1118.4134" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1054.4134,-834.5 1182.4134,-834.5 "/>
<text text-anchor="middle" x="1118.4134" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1182.4134,-811.5 1182.4134,-972.5 "/>
<text text-anchor="middle" x="1192.9134" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge1" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M1021.8866,-1047.3646C1023.9375,-1028.1034 1027.4305,-1008.9674 1032.9134,-991 1033.8334,-987.9855 1034.8781,-984.9786 1036.0294,-981.9892"/>
<polygon fill="#000000" stroke="#000000" points="1039.3658,-983.0864 1040.047,-972.5135 1032.9211,-980.3539 1039.3658,-983.0864"/>
<text text-anchor="middle" x="1054.9134" y="-994.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M103.4134,-.5C103.4134,-.5 500.4134,-.5 500.4134,-.5 506.4134,-.5 512.4134,-6.5 512.4134,-12.5 512.4134,-12.5 512.4134,-747.5 512.4134,-747.5 512.4134,-753.5 506.4134,-759.5 500.4134,-759.5 500.4134,-759.5 103.4134,-759.5 103.4134,-759.5 97.4134,-759.5 91.4134,-753.5 91.4134,-747.5 91.4134,-747.5 91.4134,-12.5 91.4134,-12.5 91.4134,-6.5 97.4134,-.5 103.4134,-.5"/>
<text text-anchor="middle" x="119.4134" y="-376.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="147.4134,-.5 147.4134,-759.5 "/>
<text text-anchor="middle" x="157.9134" y="-376.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="168.4134,-.5 168.4134,-759.5 "/>
<text text-anchor="middle" x="329.9134" y="-744.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="168.4134,-736.5 491.4134,-736.5 "/>
<text text-anchor="middle" x="329.9134" y="-721.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="168.4134,-713.5 491.4134,-713.5 "/>
<text text-anchor="middle" x="329.9134" y="-698.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="168.4134,-690.5 491.4134,-690.5 "/>
<text text-anchor="middle" x="329.9134" y="-675.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="168.4134,-667.5 491.4134,-667.5 "/>
<text text-anchor="middle" x="329.9134" y="-652.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="168.4134,-644.5 491.4134,-644.5 "/>
<text text-anchor="middle" x="329.9134" y="-629.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="168.4134,-621.5 491.4134,-621.5 "/>
<text text-anchor="middle" x="329.9134" y="-606.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="168.4134,-598.5 491.4134,-598.5 "/>
<text text-anchor="middle" x="329.9134" y="-583.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="168.4134,-575.5 491.4134,-575.5 "/>
<text text-anchor="middle" x="329.9134" y="-560.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="168.4134,-552.5 491.4134,-552.5 "/>
<text text-anchor="middle" x="329.9134" y="-537.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="168.4134,-529.5 491.4134,-529.5 "/>
<text text-anchor="middle" x="329.9134" y="-514.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="168.4134,-506.5 491.4134,-506.5 "/>
<text text-anchor="middle" x="329.9134" y="-491.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="168.4134,-483.5 491.4134,-483.5 "/>
<text text-anchor="middle" x="329.9134" y="-468.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="168.4134,-460.5 491.4134,-460.5 "/>
<text text-anchor="middle" x="329.9134" y="-445.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="168.4134,-437.5 491.4134,-437.5 "/>
<text text-anchor="middle" x="329.9134" y="-422.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="168.4134,-414.5 491.4134,-414.5 "/>
<text text-anchor="middle" x="329.9134" y="-399.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="168.4134,-391.5 491.4134,-391.5 "/>
<text text-anchor="middle" x="329.9134" y="-376.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="168.4134,-368.5 491.4134,-368.5 "/>
<text text-anchor="middle" x="329.9134" y="-353.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="168.4134,-345.5 491.4134,-345.5 "/>
<text text-anchor="middle" x="329.9134" y="-330.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="168.4134,-322.5 491.4134,-322.5 "/>
<text text-anchor="middle" x="329.9134" y="-307.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="168.4134,-299.5 491.4134,-299.5 "/>
<text text-anchor="middle" x="329.9134" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="168.4134,-276.5 491.4134,-276.5 "/>
<text text-anchor="middle" x="329.9134" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="168.4134,-253.5 491.4134,-253.5 "/>
<text text-anchor="middle" x="329.9134" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="168.4134,-230.5 491.4134,-230.5 "/>
<text text-anchor="middle" x="329.9134" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="168.4134,-207.5 491.4134,-207.5 "/>
<text text-anchor="middle" x="329.9134" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="168.4134,-184.5 491.4134,-184.5 "/>
<text text-anchor="middle" x="329.9134" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="168.4134,-161.5 491.4134,-161.5 "/>
<text text-anchor="middle" x="329.9134" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="168.4134,-138.5 491.4134,-138.5 "/>
<text text-anchor="middle" x="329.9134" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="168.4134,-115.5 491.4134,-115.5 "/>
<text text-anchor="middle" x="329.9134" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="168.4134,-92.5 491.4134,-92.5 "/>
<text text-anchor="middle" x="329.9134" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="168.4134,-69.5 491.4134,-69.5 "/>
<text text-anchor="middle" x="329.9134" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="168.4134,-46.5 491.4134,-46.5 "/>
<text text-anchor="middle" x="329.9134" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="168.4134,-23.5 491.4134,-23.5 "/>
<text text-anchor="middle" x="329.9134" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="491.4134,-.5 491.4134,-759.5 "/>
<text text-anchor="middle" x="501.9134" y="-376.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M301.9134,-834.2624C301.9134,-815.8164 301.9134,-793.8319 301.9134,-769.6339"/>
<polygon fill="#000000" stroke="#000000" points="305.4135,-769.5094 301.9134,-759.5094 298.4135,-769.5094 305.4135,-769.5094"/>
<text text-anchor="middle" x="332.4134" y="-781.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M943.4134,-1490.5C943.4134,-1490.5 1208.4134,-1490.5 1208.4134,-1490.5 1214.4134,-1490.5 1220.4134,-1496.5 1220.4134,-1502.5 1220.4134,-1502.5 1220.4134,-1593.5 1220.4134,-1593.5 1220.4134,-1599.5 1214.4134,-1605.5 1208.4134,-1605.5 1208.4134,-1605.5 943.4134,-1605.5 943.4134,-1605.5 937.4134,-1605.5 931.4134,-1599.5 931.4134,-1593.5 931.4134,-1593.5 931.4134,-1502.5 931.4134,-1502.5 931.4134,-1496.5 937.4134,-1490.5 943.4134,-1490.5"/>
<text text-anchor="middle" x="975.9134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1020.4134,-1490.5 1020.4134,-1605.5 "/>
<text text-anchor="middle" x="1030.9134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1041.4134,-1490.5 1041.4134,-1605.5 "/>
<text text-anchor="middle" x="1120.4134" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="1041.4134,-1582.5 1199.4134,-1582.5 "/>
<text text-anchor="middle" x="1120.4134" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1041.4134,-1559.5 1199.4134,-1559.5 "/>
<text text-anchor="middle" x="1120.4134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1041.4134,-1536.5 1199.4134,-1536.5 "/>
<text text-anchor="middle" x="1120.4134" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1041.4134,-1513.5 1199.4134,-1513.5 "/>
<text text-anchor="middle" x="1120.4134" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1199.4134,-1490.5 1199.4134,-1605.5 "/>
<text text-anchor="middle" x="1209.9134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen -->
<g id="node5" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M197.4134,-1202C197.4134,-1202 406.4134,-1202 406.4134,-1202 412.4134,-1202 418.4134,-1208 418.4134,-1214 418.4134,-1214 418.4134,-1226 418.4134,-1226 418.4134,-1232 412.4134,-1238 406.4134,-1238 406.4134,-1238 197.4134,-1238 197.4134,-1238 191.4134,-1238 185.4134,-1232 185.4134,-1226 185.4134,-1226 185.4134,-1214 185.4134,-1214 185.4134,-1208 191.4134,-1202 197.4134,-1202"/>
<text text-anchor="middle" x="227.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="270.4134,-1202 270.4134,-1238 "/>
<text text-anchor="middle" x="280.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="291.4134,-1202 291.4134,-1238 "/>
<text text-anchor="middle" x="344.4134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="397.4134,-1202 397.4134,-1238 "/>
<text text-anchor="middle" x="407.9134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>specimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M301.9134,-1201.8981C301.9134,-1156.5915 301.9134,-1036.45 301.9134,-959.7595"/>
<polygon fill="#000000" stroke="#000000" points="305.4135,-959.7032 301.9134,-949.7032 298.4135,-959.7032 305.4135,-959.7032"/>
<text text-anchor="middle" x="352.4134" y="-994.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M614.9134,-1467.5C614.9134,-1467.5 900.9134,-1467.5 900.9134,-1467.5 906.9134,-1467.5 912.9134,-1473.5 912.9134,-1479.5 912.9134,-1479.5 912.9134,-1616.5 912.9134,-1616.5 912.9134,-1622.5 906.9134,-1628.5 900.9134,-1628.5 900.9134,-1628.5 614.9134,-1628.5 614.9134,-1628.5 608.9134,-1628.5 602.9134,-1622.5 602.9134,-1616.5 602.9134,-1616.5 602.9134,-1479.5 602.9134,-1479.5 602.9134,-1473.5 608.9134,-1467.5 614.9134,-1467.5"/>
<text text-anchor="middle" x="636.9134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="670.9134,-1467.5 670.9134,-1628.5 "/>
<text text-anchor="middle" x="681.4134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="691.9134,-1467.5 691.9134,-1628.5 "/>
<text text-anchor="middle" x="791.9134" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="691.9134,-1605.5 891.9134,-1605.5 "/>
<text text-anchor="middle" x="791.9134" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="691.9134,-1582.5 891.9134,-1582.5 "/>
<text text-anchor="middle" x="791.9134" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="691.9134,-1559.5 891.9134,-1559.5 "/>
<text text-anchor="middle" x="791.9134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="691.9134,-1536.5 891.9134,-1536.5 "/>
<text text-anchor="middle" x="791.9134" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="691.9134,-1513.5 891.9134,-1513.5 "/>
<text text-anchor="middle" x="791.9134" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="691.9134,-1490.5 891.9134,-1490.5 "/>
<text text-anchor="middle" x="791.9134" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="891.9134,-1467.5 891.9134,-1628.5 "/>
<text text-anchor="middle" x="902.4134" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;genomic_info -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M825.2923,-1467.3421C842.4469,-1446.8067 861.585,-1423.8968 881.1008,-1400.5349"/>
<polygon fill="#000000" stroke="#000000" points="884.0064,-1402.516 887.7313,-1392.5975 878.6342,-1398.0282 884.0064,-1402.516"/>
<text text-anchor="middle" x="904.4134" y="-1437.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_genomic_info</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M602.5723,-1540.264C422.0617,-1527.642 140.4928,-1495.4671 74.9134,-1416 -35.9778,-1281.6254 -11.9633,-1175.0159 74.9134,-1024 92.7316,-993.027 120.9186,-968.6462 151.4546,-949.7244"/>
<polygon fill="#000000" stroke="#000000" points="153.3433,-952.673 160.123,-944.5313 149.7459,-946.6681 153.3433,-952.673"/>
<text text-anchor="middle" x="125.4134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M602.7509,-1508.0329C543.6074,-1487.4201 478.3593,-1457.6333 427.9134,-1416 370.8681,-1368.9201 331.0343,-1289.1083 312.9261,-1247.3369"/>
<polygon fill="#000000" stroke="#000000" points="316.1187,-1245.9004 308.9922,-1238.0606 309.6743,-1248.6334 316.1187,-1245.9004"/>
<text text-anchor="middle" x="510.9134" y="-1437.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- file&#45;&gt;genomic_info -->
<g id="edge6" class="edge">
<title>file&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M1083.5156,-972.6845C1081.3284,-983.8808 1079.0846,-995.2312 1076.9134,-1006 1074.8309,-1016.329 1072.6711,-1026.9337 1070.4751,-1037.6328"/>
<polygon fill="#000000" stroke="#000000" points="1067.0362,-1036.9797 1068.4494,-1047.4799 1073.8926,-1038.3902 1067.0362,-1036.9797"/>
<text text-anchor="middle" x="1147.4134" y="-994.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_genomic_info</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1203.7676,-943.8775C1233.9264,-964.3953 1263.169,-991.0643 1279.9134,-1024 1358.8697,-1179.3039 1394.0641,-1284.3831 1279.9134,-1416 1227.4064,-1476.5411 999.4937,-1443.3845 922.9134,-1467 922.8134,-1467.0309 922.7133,-1467.0618 922.6132,-1467.0927"/>
<polygon fill="#000000" stroke="#000000" points="921.7028,-1463.7085 913.2696,-1470.1218 923.8615,-1470.3673 921.7028,-1463.7085"/>
<text text-anchor="middle" x="1399.4134" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
</g>
</svg>
</div>
