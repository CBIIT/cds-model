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
<svg width="1231pt" height="2184pt"
 viewBox="0.00 0.00 1230.50 2184.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 2180)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-2180 1226.5,-2180 1226.5,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M12,-2060.5C12,-2060.5 277,-2060.5 277,-2060.5 283,-2060.5 289,-2066.5 289,-2072.5 289,-2072.5 289,-2163.5 289,-2163.5 289,-2169.5 283,-2175.5 277,-2175.5 277,-2175.5 12,-2175.5 12,-2175.5 6,-2175.5 0,-2169.5 0,-2163.5 0,-2163.5 0,-2072.5 0,-2072.5 0,-2066.5 6,-2060.5 12,-2060.5"/>
<text text-anchor="middle" x="44.5" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="89,-2060.5 89,-2175.5 "/>
<text text-anchor="middle" x="99.5" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="110,-2060.5 110,-2175.5 "/>
<text text-anchor="middle" x="189" y="-2160.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="110,-2152.5 268,-2152.5 "/>
<text text-anchor="middle" x="189" y="-2137.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="110,-2129.5 268,-2129.5 "/>
<text text-anchor="middle" x="189" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="110,-2106.5 268,-2106.5 "/>
<text text-anchor="middle" x="189" y="-2091.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="110,-2083.5 268,-2083.5 "/>
<text text-anchor="middle" x="189" y="-2068.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="268,-2060.5 268,-2175.5 "/>
<text text-anchor="middle" x="278.5" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation -->
<g id="node2" class="node">
<title>methylation</title>
<path fill="none" stroke="#000000" d="M319,-2095C319,-2095 610,-2095 610,-2095 616,-2095 622,-2101 622,-2107 622,-2107 622,-2129 622,-2129 622,-2135 616,-2141 610,-2141 610,-2141 319,-2141 319,-2141 313,-2141 307,-2135 307,-2129 307,-2129 307,-2107 307,-2107 307,-2101 313,-2095 319,-2095"/>
<text text-anchor="middle" x="358" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation</text>
<polyline fill="none" stroke="#000000" points="409,-2095 409,-2141 "/>
<text text-anchor="middle" x="419.5" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="430,-2095 430,-2141 "/>
<text text-anchor="middle" x="515.5" y="-2125.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="430,-2118 601,-2118 "/>
<text text-anchor="middle" x="515.5" y="-2102.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="601,-2095 601,-2141 "/>
<text text-anchor="middle" x="611.5" y="-2114.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node10" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M305,-1847.5C305,-1847.5 490,-1847.5 490,-1847.5 496,-1847.5 502,-1853.5 502,-1859.5 502,-1859.5 502,-1996.5 502,-1996.5 502,-2002.5 496,-2008.5 490,-2008.5 490,-2008.5 305,-2008.5 305,-2008.5 299,-2008.5 293,-2002.5 293,-1996.5 293,-1996.5 293,-1859.5 293,-1859.5 293,-1853.5 299,-1847.5 305,-1847.5"/>
<text text-anchor="middle" x="312.5" y="-1924.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="332,-1847.5 332,-2008.5 "/>
<text text-anchor="middle" x="342.5" y="-1924.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="353,-1847.5 353,-2008.5 "/>
<text text-anchor="middle" x="417" y="-1993.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="353,-1985.5 481,-1985.5 "/>
<text text-anchor="middle" x="417" y="-1970.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="353,-1962.5 481,-1962.5 "/>
<text text-anchor="middle" x="417" y="-1947.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="353,-1939.5 481,-1939.5 "/>
<text text-anchor="middle" x="417" y="-1924.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="353,-1916.5 481,-1916.5 "/>
<text text-anchor="middle" x="417" y="-1901.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="353,-1893.5 481,-1893.5 "/>
<text text-anchor="middle" x="417" y="-1878.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="353,-1870.5 481,-1870.5 "/>
<text text-anchor="middle" x="417" y="-1855.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="481,-1847.5 481,-2008.5 "/>
<text text-anchor="middle" x="491.5" y="-1924.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation&#45;&gt;file -->
<g id="edge7" class="edge">
<title>methylation&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M434.3113,-2094.7464C419.2645,-2081.1994 402.5884,-2062.7208 394.5,-2042 391.5826,-2034.5262 389.6639,-2026.562 388.501,-2018.4499"/>
<polygon fill="#000000" stroke="#000000" points="391.9812,-2018.0773 387.4409,-2008.5047 385.0206,-2018.8193 391.9812,-2018.0773"/>
<text text-anchor="middle" x="416.5" y="-2030.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- specimen -->
<g id="node3" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M508,-1369C508,-1369 717,-1369 717,-1369 723,-1369 729,-1375 729,-1381 729,-1381 729,-1393 729,-1393 729,-1399 723,-1405 717,-1405 717,-1405 508,-1405 508,-1405 502,-1405 496,-1399 496,-1393 496,-1393 496,-1381 496,-1381 496,-1375 502,-1369 508,-1369"/>
<text text-anchor="middle" x="538.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="581,-1369 581,-1405 "/>
<text text-anchor="middle" x="591.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="602,-1369 602,-1405 "/>
<text text-anchor="middle" x="655" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="708,-1369 708,-1405 "/>
<text text-anchor="middle" x="718.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M636,-1024.5C636,-1024.5 895,-1024.5 895,-1024.5 901,-1024.5 907,-1030.5 907,-1036.5 907,-1036.5 907,-1127.5 907,-1127.5 907,-1133.5 901,-1139.5 895,-1139.5 895,-1139.5 636,-1139.5 636,-1139.5 630,-1139.5 624,-1133.5 624,-1127.5 624,-1127.5 624,-1036.5 624,-1036.5 624,-1030.5 630,-1024.5 636,-1024.5"/>
<text text-anchor="middle" x="672" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="720,-1024.5 720,-1139.5 "/>
<text text-anchor="middle" x="730.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="741,-1024.5 741,-1139.5 "/>
<text text-anchor="middle" x="813.5" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="741,-1116.5 886,-1116.5 "/>
<text text-anchor="middle" x="813.5" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="741,-1093.5 886,-1093.5 "/>
<text text-anchor="middle" x="813.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="741,-1070.5 886,-1070.5 "/>
<text text-anchor="middle" x="813.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="741,-1047.5 886,-1047.5 "/>
<text text-anchor="middle" x="813.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="886,-1024.5 886,-1139.5 "/>
<text text-anchor="middle" x="896.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- specimen&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>specimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M610.8815,-1368.9346C608.1185,-1327.8598 606.514,-1225.7813 650.5,-1158 652.8816,-1154.3301 655.5094,-1150.7968 658.3363,-1147.3992"/>
<polygon fill="#000000" stroke="#000000" points="661.1679,-1149.4857 665.2711,-1139.7177 655.972,-1144.7949 661.1679,-1149.4857"/>
<text text-anchor="middle" x="701" y="-1161.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M567,-190.5C567,-190.5 964,-190.5 964,-190.5 970,-190.5 976,-196.5 976,-202.5 976,-202.5 976,-960.5 976,-960.5 976,-966.5 970,-972.5 964,-972.5 964,-972.5 567,-972.5 567,-972.5 561,-972.5 555,-966.5 555,-960.5 555,-960.5 555,-202.5 555,-202.5 555,-196.5 561,-190.5 567,-190.5"/>
<text text-anchor="middle" x="583" y="-577.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="611,-190.5 611,-972.5 "/>
<text text-anchor="middle" x="621.5" y="-577.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="632,-190.5 632,-972.5 "/>
<text text-anchor="middle" x="793.5" y="-957.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="632,-949.5 955,-949.5 "/>
<text text-anchor="middle" x="793.5" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="632,-926.5 955,-926.5 "/>
<text text-anchor="middle" x="793.5" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="632,-903.5 955,-903.5 "/>
<text text-anchor="middle" x="793.5" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="632,-880.5 955,-880.5 "/>
<text text-anchor="middle" x="793.5" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="632,-857.5 955,-857.5 "/>
<text text-anchor="middle" x="793.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="632,-834.5 955,-834.5 "/>
<text text-anchor="middle" x="793.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="632,-811.5 955,-811.5 "/>
<text text-anchor="middle" x="793.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="632,-788.5 955,-788.5 "/>
<text text-anchor="middle" x="793.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="632,-765.5 955,-765.5 "/>
<text text-anchor="middle" x="793.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="632,-742.5 955,-742.5 "/>
<text text-anchor="middle" x="793.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="632,-719.5 955,-719.5 "/>
<text text-anchor="middle" x="793.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="632,-696.5 955,-696.5 "/>
<text text-anchor="middle" x="793.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="632,-673.5 955,-673.5 "/>
<text text-anchor="middle" x="793.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="632,-650.5 955,-650.5 "/>
<text text-anchor="middle" x="793.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="632,-627.5 955,-627.5 "/>
<text text-anchor="middle" x="793.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="632,-604.5 955,-604.5 "/>
<text text-anchor="middle" x="793.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="632,-581.5 955,-581.5 "/>
<text text-anchor="middle" x="793.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="632,-558.5 955,-558.5 "/>
<text text-anchor="middle" x="793.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="632,-535.5 955,-535.5 "/>
<text text-anchor="middle" x="793.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="632,-512.5 955,-512.5 "/>
<text text-anchor="middle" x="793.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="632,-489.5 955,-489.5 "/>
<text text-anchor="middle" x="793.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="632,-466.5 955,-466.5 "/>
<text text-anchor="middle" x="793.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="632,-443.5 955,-443.5 "/>
<text text-anchor="middle" x="793.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="632,-420.5 955,-420.5 "/>
<text text-anchor="middle" x="793.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="632,-397.5 955,-397.5 "/>
<text text-anchor="middle" x="793.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="632,-374.5 955,-374.5 "/>
<text text-anchor="middle" x="793.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="632,-351.5 955,-351.5 "/>
<text text-anchor="middle" x="793.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="632,-328.5 955,-328.5 "/>
<text text-anchor="middle" x="793.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="632,-305.5 955,-305.5 "/>
<text text-anchor="middle" x="793.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="632,-282.5 955,-282.5 "/>
<text text-anchor="middle" x="793.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="632,-259.5 955,-259.5 "/>
<text text-anchor="middle" x="793.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="632,-236.5 955,-236.5 "/>
<text text-anchor="middle" x="793.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="632,-213.5 955,-213.5 "/>
<text text-anchor="middle" x="793.5" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="955,-190.5 955,-972.5 "/>
<text text-anchor="middle" x="965.5" y="-577.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node8" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M611.5,-.5C611.5,-.5 919.5,-.5 919.5,-.5 925.5,-.5 931.5,-6.5 931.5,-12.5 931.5,-12.5 931.5,-126.5 931.5,-126.5 931.5,-132.5 925.5,-138.5 919.5,-138.5 919.5,-138.5 611.5,-138.5 611.5,-138.5 605.5,-138.5 599.5,-132.5 599.5,-126.5 599.5,-126.5 599.5,-12.5 599.5,-12.5 599.5,-6.5 605.5,-.5 611.5,-.5"/>
<text text-anchor="middle" x="638.5" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="677.5,-.5 677.5,-138.5 "/>
<text text-anchor="middle" x="688" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="698.5,-.5 698.5,-138.5 "/>
<text text-anchor="middle" x="804.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="698.5,-115.5 910.5,-115.5 "/>
<text text-anchor="middle" x="804.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="698.5,-92.5 910.5,-92.5 "/>
<text text-anchor="middle" x="804.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="698.5,-69.5 910.5,-69.5 "/>
<text text-anchor="middle" x="804.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="698.5,-46.5 910.5,-46.5 "/>
<text text-anchor="middle" x="804.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="698.5,-23.5 910.5,-23.5 "/>
<text text-anchor="middle" x="804.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="910.5,-.5 910.5,-138.5 "/>
<text text-anchor="middle" x="921" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge2" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M765.5,-190.1885C765.5,-175.355 765.5,-161.3721 765.5,-148.5489"/>
<polygon fill="#000000" stroke="#000000" points="769.0001,-148.5194 765.5,-138.5194 762.0001,-148.5195 769.0001,-148.5194"/>
<text text-anchor="middle" x="807" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- genomic_info -->
<g id="node5" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M13,-1214.5C13,-1214.5 466,-1214.5 466,-1214.5 472,-1214.5 478,-1220.5 478,-1226.5 478,-1226.5 478,-1547.5 478,-1547.5 478,-1553.5 472,-1559.5 466,-1559.5 466,-1559.5 13,-1559.5 13,-1559.5 7,-1559.5 1,-1553.5 1,-1547.5 1,-1547.5 1,-1226.5 1,-1226.5 1,-1220.5 7,-1214.5 13,-1214.5"/>
<text text-anchor="middle" x="57" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="113,-1214.5 113,-1559.5 "/>
<text text-anchor="middle" x="123.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="134,-1214.5 134,-1559.5 "/>
<text text-anchor="middle" x="295.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="134,-1536.5 457,-1536.5 "/>
<text text-anchor="middle" x="295.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="134,-1513.5 457,-1513.5 "/>
<text text-anchor="middle" x="295.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="134,-1490.5 457,-1490.5 "/>
<text text-anchor="middle" x="295.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="134,-1467.5 457,-1467.5 "/>
<text text-anchor="middle" x="295.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="134,-1444.5 457,-1444.5 "/>
<text text-anchor="middle" x="295.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="134,-1421.5 457,-1421.5 "/>
<text text-anchor="middle" x="295.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="134,-1398.5 457,-1398.5 "/>
<text text-anchor="middle" x="295.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="134,-1375.5 457,-1375.5 "/>
<text text-anchor="middle" x="295.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="134,-1352.5 457,-1352.5 "/>
<text text-anchor="middle" x="295.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="134,-1329.5 457,-1329.5 "/>
<text text-anchor="middle" x="295.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="134,-1306.5 457,-1306.5 "/>
<text text-anchor="middle" x="295.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="134,-1283.5 457,-1283.5 "/>
<text text-anchor="middle" x="295.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="134,-1260.5 457,-1260.5 "/>
<text text-anchor="middle" x="295.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="134,-1237.5 457,-1237.5 "/>
<text text-anchor="middle" x="295.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="457,-1214.5 457,-1559.5 "/>
<text text-anchor="middle" x="467.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge6" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M344.5742,-1559.5307C355.9644,-1583.873 366.0897,-1609.1008 373.5,-1634 393.2124,-1700.2354 398.8117,-1778.3327 399.6993,-1837.3826"/>
<polygon fill="#000000" stroke="#000000" points="396.1999,-1837.4721 399.8078,-1847.4337 403.1995,-1837.3964 396.1999,-1837.4721"/>
<text text-anchor="middle" x="420.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M765.5,-1024.0973C765.5,-1011.7491 765.5,-997.8274 765.5,-982.7358"/>
<polygon fill="#000000" stroke="#000000" points="769.0001,-982.6542 765.5,-972.6543 762.0001,-982.6543 769.0001,-982.6542"/>
<text text-anchor="middle" x="796" y="-994.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M469.5,-1634.5C469.5,-1634.5 755.5,-1634.5 755.5,-1634.5 761.5,-1634.5 767.5,-1640.5 767.5,-1646.5 767.5,-1646.5 767.5,-1783.5 767.5,-1783.5 767.5,-1789.5 761.5,-1795.5 755.5,-1795.5 755.5,-1795.5 469.5,-1795.5 469.5,-1795.5 463.5,-1795.5 457.5,-1789.5 457.5,-1783.5 457.5,-1783.5 457.5,-1646.5 457.5,-1646.5 457.5,-1640.5 463.5,-1634.5 469.5,-1634.5"/>
<text text-anchor="middle" x="491.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="525.5,-1634.5 525.5,-1795.5 "/>
<text text-anchor="middle" x="536" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="546.5,-1634.5 546.5,-1795.5 "/>
<text text-anchor="middle" x="646.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="546.5,-1772.5 746.5,-1772.5 "/>
<text text-anchor="middle" x="646.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="546.5,-1749.5 746.5,-1749.5 "/>
<text text-anchor="middle" x="646.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="546.5,-1726.5 746.5,-1726.5 "/>
<text text-anchor="middle" x="646.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="546.5,-1703.5 746.5,-1703.5 "/>
<text text-anchor="middle" x="646.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="546.5,-1680.5 746.5,-1680.5 "/>
<text text-anchor="middle" x="646.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="546.5,-1657.5 746.5,-1657.5 "/>
<text text-anchor="middle" x="646.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="746.5,-1634.5 746.5,-1795.5 "/>
<text text-anchor="middle" x="757" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;methylation -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M622.383,-1795.5919C626.944,-1865.709 623.4901,-1967.4866 578.5,-2042 566.3978,-2062.0438 546.748,-2077.9099 527.1441,-2089.8476"/>
<polygon fill="#000000" stroke="#000000" points="525.3555,-2086.8389 518.4686,-2094.89 528.8732,-2092.8909 525.3555,-2086.8389"/>
<text text-anchor="middle" x="677" y="-1924.3" font-family="Times,serif" font-size="14.00" fill="#000000">in_methylation</text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M612.5,-1634.3421C612.5,-1563.248 612.5,-1463.6949 612.5,-1415.4473"/>
<polygon fill="#000000" stroke="#000000" points="616.0001,-1415.1441 612.5,-1405.1442 609.0001,-1415.1442 616.0001,-1415.1441"/>
<text text-anchor="middle" x="657.5" y="-1604.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- sample&#45;&gt;genomic_info -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M513.1021,-1634.3723C505.7548,-1628.1995 498.4884,-1622.0271 491.5,-1616 473.0242,-1600.0656 453.9558,-1583.3171 434.9663,-1566.4312"/>
<polygon fill="#000000" stroke="#000000" points="437.2053,-1563.7384 427.4098,-1559.701 432.5496,-1568.9657 437.2053,-1563.7384"/>
<text text-anchor="middle" x="550" y="-1604.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_genomic_info</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M705.8602,-1634.2872C718.9286,-1618.6185 730.5809,-1601.3208 738.5,-1583 771.3263,-1507.0567 770.3025,-1267.9544 767.59,-1149.6522"/>
<polygon fill="#000000" stroke="#000000" points="771.0883,-1149.5362 767.3493,-1139.6231 764.0903,-1149.7042 771.0883,-1149.5362"/>
<text text-anchor="middle" x="819" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M896.5,-1191.5C896.5,-1191.5 1210.5,-1191.5 1210.5,-1191.5 1216.5,-1191.5 1222.5,-1197.5 1222.5,-1203.5 1222.5,-1203.5 1222.5,-1570.5 1222.5,-1570.5 1222.5,-1576.5 1216.5,-1582.5 1210.5,-1582.5 1210.5,-1582.5 896.5,-1582.5 896.5,-1582.5 890.5,-1582.5 884.5,-1576.5 884.5,-1570.5 884.5,-1570.5 884.5,-1203.5 884.5,-1203.5 884.5,-1197.5 890.5,-1191.5 896.5,-1191.5"/>
<text text-anchor="middle" x="926.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="968.5,-1191.5 968.5,-1582.5 "/>
<text text-anchor="middle" x="979" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="989.5,-1191.5 989.5,-1582.5 "/>
<text text-anchor="middle" x="1095.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="989.5,-1559.5 1201.5,-1559.5 "/>
<text text-anchor="middle" x="1095.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="989.5,-1536.5 1201.5,-1536.5 "/>
<text text-anchor="middle" x="1095.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="989.5,-1513.5 1201.5,-1513.5 "/>
<text text-anchor="middle" x="1095.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="989.5,-1490.5 1201.5,-1490.5 "/>
<text text-anchor="middle" x="1095.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="989.5,-1467.5 1201.5,-1467.5 "/>
<text text-anchor="middle" x="1095.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="989.5,-1444.5 1201.5,-1444.5 "/>
<text text-anchor="middle" x="1095.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="989.5,-1421.5 1201.5,-1421.5 "/>
<text text-anchor="middle" x="1095.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="989.5,-1398.5 1201.5,-1398.5 "/>
<text text-anchor="middle" x="1095.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="989.5,-1375.5 1201.5,-1375.5 "/>
<text text-anchor="middle" x="1095.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="989.5,-1352.5 1201.5,-1352.5 "/>
<text text-anchor="middle" x="1095.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="989.5,-1329.5 1201.5,-1329.5 "/>
<text text-anchor="middle" x="1095.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="989.5,-1306.5 1201.5,-1306.5 "/>
<text text-anchor="middle" x="1095.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="989.5,-1283.5 1201.5,-1283.5 "/>
<text text-anchor="middle" x="1095.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="989.5,-1260.5 1201.5,-1260.5 "/>
<text text-anchor="middle" x="1095.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="989.5,-1237.5 1201.5,-1237.5 "/>
<text text-anchor="middle" x="1095.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="989.5,-1214.5 1201.5,-1214.5 "/>
<text text-anchor="middle" x="1095.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1201.5,-1191.5 1201.5,-1582.5 "/>
<text text-anchor="middle" x="1212" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M884.3508,-1205.6319C879.6889,-1200.6984 875.065,-1195.8135 870.5,-1191 856.9505,-1176.713 842.3364,-1161.4504 828.4419,-1147.0075"/>
<polygon fill="#000000" stroke="#000000" points="830.7083,-1144.3151 821.251,-1139.539 825.6657,-1149.1703 830.7083,-1144.3151"/>
<text text-anchor="middle" x="901" y="-1161.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;methylation -->
<g id="edge4" class="edge">
<title>file&#45;&gt;methylation</title>
<path fill="none" stroke="#000000" d="M435.6106,-2008.5336C438.0784,-2014.7282 440.4083,-2020.9312 442.5,-2027 448.9475,-2045.7064 454.2379,-2067.1994 458.0136,-2084.5988"/>
<polygon fill="#000000" stroke="#000000" points="454.6843,-2085.7752 460.1656,-2094.8419 461.5347,-2084.3359 454.6843,-2085.7752"/>
<text text-anchor="middle" x="511" y="-2030.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_methylation</text>
</g>
<!-- file&#45;&gt;genomic_info -->
<g id="edge1" class="edge">
<title>file&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M292.6286,-1864.7324C269.997,-1845.6783 249.1013,-1822.6268 236.5,-1796 203.7537,-1726.8068 199.1191,-1643.3599 204.7269,-1569.9343"/>
<polygon fill="#000000" stroke="#000000" points="208.2419,-1569.8987 205.5843,-1559.6427 201.2661,-1569.3175 208.2419,-1569.8987"/>
<text text-anchor="middle" x="305" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_genomic_info</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M470.793,-1847.4588C481.6092,-1836.0782 492.7361,-1824.6388 503.5,-1814 507.2116,-1810.3315 511.0244,-1806.6186 514.8987,-1802.8916"/>
<polygon fill="#000000" stroke="#000000" points="517.5991,-1805.1524 522.4144,-1795.715 512.7649,-1800.0897 517.5991,-1805.1524"/>
<text text-anchor="middle" x="550" y="-1817.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
</g>
</svg>
</div>
