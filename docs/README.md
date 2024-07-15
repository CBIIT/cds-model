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
<svg width="1632pt" height="4938pt"
 viewBox="0.00 0.00 1631.50 4938.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 4934)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-4934 1627.5,-4934 1627.5,4 -4,4"/>
<!-- genomic_info -->
<g id="node1" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M12,-3469C12,-3469 465,-3469 465,-3469 471,-3469 477,-3475 477,-3481 477,-3481 477,-3940 477,-3940 477,-3946 471,-3952 465,-3952 465,-3952 12,-3952 12,-3952 6,-3952 0,-3946 0,-3940 0,-3940 0,-3481 0,-3481 0,-3475 6,-3469 12,-3469"/>
<text text-anchor="middle" x="56" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="112,-3469 112,-3952 "/>
<text text-anchor="middle" x="122.5" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="133,-3469 133,-3952 "/>
<text text-anchor="middle" x="294.5" y="-3936.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="133,-3929 456,-3929 "/>
<text text-anchor="middle" x="294.5" y="-3913.8" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="133,-3906 456,-3906 "/>
<text text-anchor="middle" x="294.5" y="-3890.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="133,-3883 456,-3883 "/>
<text text-anchor="middle" x="294.5" y="-3867.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="133,-3860 456,-3860 "/>
<text text-anchor="middle" x="294.5" y="-3844.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="133,-3837 456,-3837 "/>
<text text-anchor="middle" x="294.5" y="-3821.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="133,-3814 456,-3814 "/>
<text text-anchor="middle" x="294.5" y="-3798.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="133,-3791 456,-3791 "/>
<text text-anchor="middle" x="294.5" y="-3775.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="133,-3768 456,-3768 "/>
<text text-anchor="middle" x="294.5" y="-3752.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="133,-3745 456,-3745 "/>
<text text-anchor="middle" x="294.5" y="-3729.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="133,-3722 456,-3722 "/>
<text text-anchor="middle" x="294.5" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="133,-3699 456,-3699 "/>
<text text-anchor="middle" x="294.5" y="-3683.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="133,-3676 456,-3676 "/>
<text text-anchor="middle" x="294.5" y="-3660.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="133,-3653 456,-3653 "/>
<text text-anchor="middle" x="294.5" y="-3637.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="133,-3630 456,-3630 "/>
<text text-anchor="middle" x="294.5" y="-3614.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="133,-3607 456,-3607 "/>
<text text-anchor="middle" x="294.5" y="-3591.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="133,-3584 456,-3584 "/>
<text text-anchor="middle" x="294.5" y="-3568.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="133,-3561 456,-3561 "/>
<text text-anchor="middle" x="294.5" y="-3545.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="133,-3538 456,-3538 "/>
<text text-anchor="middle" x="294.5" y="-3522.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="133,-3515 456,-3515 "/>
<text text-anchor="middle" x="294.5" y="-3499.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="133,-3492 456,-3492 "/>
<text text-anchor="middle" x="294.5" y="-3476.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="456,-3469 456,-3952 "/>
<text text-anchor="middle" x="466.5" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node2" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M340.5,-2140.5C340.5,-2140.5 720.5,-2140.5 720.5,-2140.5 726.5,-2140.5 732.5,-2146.5 732.5,-2152.5 732.5,-2152.5 732.5,-2427.5 732.5,-2427.5 732.5,-2433.5 726.5,-2439.5 720.5,-2439.5 720.5,-2439.5 340.5,-2439.5 340.5,-2439.5 334.5,-2439.5 328.5,-2433.5 328.5,-2427.5 328.5,-2427.5 328.5,-2152.5 328.5,-2152.5 328.5,-2146.5 334.5,-2140.5 340.5,-2140.5"/>
<text text-anchor="middle" x="348" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="367.5,-2140.5 367.5,-2439.5 "/>
<text text-anchor="middle" x="378" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="388.5,-2140.5 388.5,-2439.5 "/>
<text text-anchor="middle" x="550" y="-2424.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="388.5,-2416.5 711.5,-2416.5 "/>
<text text-anchor="middle" x="550" y="-2401.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="388.5,-2393.5 711.5,-2393.5 "/>
<text text-anchor="middle" x="550" y="-2378.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="388.5,-2370.5 711.5,-2370.5 "/>
<text text-anchor="middle" x="550" y="-2355.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="388.5,-2347.5 711.5,-2347.5 "/>
<text text-anchor="middle" x="550" y="-2332.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="388.5,-2324.5 711.5,-2324.5 "/>
<text text-anchor="middle" x="550" y="-2309.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="388.5,-2301.5 711.5,-2301.5 "/>
<text text-anchor="middle" x="550" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="388.5,-2278.5 711.5,-2278.5 "/>
<text text-anchor="middle" x="550" y="-2263.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="388.5,-2255.5 711.5,-2255.5 "/>
<text text-anchor="middle" x="550" y="-2240.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="388.5,-2232.5 711.5,-2232.5 "/>
<text text-anchor="middle" x="550" y="-2217.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="388.5,-2209.5 711.5,-2209.5 "/>
<text text-anchor="middle" x="550" y="-2194.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="388.5,-2186.5 711.5,-2186.5 "/>
<text text-anchor="middle" x="550" y="-2171.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="388.5,-2163.5 711.5,-2163.5 "/>
<text text-anchor="middle" x="550" y="-2148.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="711.5,-2140.5 711.5,-2439.5 "/>
<text text-anchor="middle" x="722" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge1" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M286.5557,-3468.774C335.7609,-3222.569 414.9533,-2829.8887 486.5,-2491 489.3205,-2477.6405 492.2796,-2463.7896 495.2731,-2449.8917"/>
<polygon fill="#000000" stroke="#000000" points="498.7691,-2450.2833 497.4574,-2439.77 491.9266,-2448.8066 498.7691,-2450.2833"/>
<text text-anchor="middle" x="516.5" y="-2461.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge11" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M732.6809,-2311.8677C743.8527,-2306.55 750.5,-2299.2607 750.5,-2290 750.5,-2283.4885 747.2137,-2277.9518 741.3789,-2273.3897"/>
<polygon fill="#000000" stroke="#000000" points="743.0495,-2270.3098 732.6809,-2268.1323 739.4285,-2276.3005 743.0495,-2270.3098"/>
<text text-anchor="middle" x="808" y="-2286.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M709.5,-1346.5C709.5,-1346.5 987.5,-1346.5 987.5,-1346.5 993.5,-1346.5 999.5,-1352.5 999.5,-1358.5 999.5,-1358.5 999.5,-1518.5 999.5,-1518.5 999.5,-1524.5 993.5,-1530.5 987.5,-1530.5 987.5,-1530.5 709.5,-1530.5 709.5,-1530.5 703.5,-1530.5 697.5,-1524.5 697.5,-1518.5 697.5,-1518.5 697.5,-1358.5 697.5,-1358.5 697.5,-1352.5 703.5,-1346.5 709.5,-1346.5"/>
<text text-anchor="middle" x="745.5" y="-1434.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="793.5,-1346.5 793.5,-1530.5 "/>
<text text-anchor="middle" x="804" y="-1434.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="814.5,-1346.5 814.5,-1530.5 "/>
<text text-anchor="middle" x="896.5" y="-1515.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="814.5,-1507.5 978.5,-1507.5 "/>
<text text-anchor="middle" x="896.5" y="-1492.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="814.5,-1484.5 978.5,-1484.5 "/>
<text text-anchor="middle" x="896.5" y="-1469.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="814.5,-1461.5 978.5,-1461.5 "/>
<text text-anchor="middle" x="896.5" y="-1446.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="814.5,-1438.5 978.5,-1438.5 "/>
<text text-anchor="middle" x="896.5" y="-1423.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="814.5,-1415.5 978.5,-1415.5 "/>
<text text-anchor="middle" x="896.5" y="-1400.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="814.5,-1392.5 978.5,-1392.5 "/>
<text text-anchor="middle" x="896.5" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="814.5,-1369.5 978.5,-1369.5 "/>
<text text-anchor="middle" x="896.5" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="978.5,-1346.5 978.5,-1530.5 "/>
<text text-anchor="middle" x="989" y="-1434.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M732.5717,-2273.0247C967.6149,-2248.6003 1334.2964,-2194.3934 1418.5,-2089 1559.1515,-1912.9538 1557.0263,-1759.7233 1418.5,-1582 1368.5585,-1517.9271 1160.2568,-1478.0461 1009.8939,-1457.0491"/>
<polygon fill="#000000" stroke="#000000" points="1010.0083,-1453.5318 999.6236,-1455.6316 1009.0511,-1460.466 1010.0083,-1453.5318"/>
<text text-anchor="middle" x="1573" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M205.5,-259.5C205.5,-259.5 521.5,-259.5 521.5,-259.5 527.5,-259.5 533.5,-265.5 533.5,-271.5 533.5,-271.5 533.5,-1282.5 533.5,-1282.5 533.5,-1288.5 527.5,-1294.5 521.5,-1294.5 521.5,-1294.5 205.5,-1294.5 205.5,-1294.5 199.5,-1294.5 193.5,-1288.5 193.5,-1282.5 193.5,-1282.5 193.5,-271.5 193.5,-271.5 193.5,-265.5 199.5,-259.5 205.5,-259.5"/>
<text text-anchor="middle" x="221.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="249.5,-259.5 249.5,-1294.5 "/>
<text text-anchor="middle" x="260" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="270.5,-259.5 270.5,-1294.5 "/>
<text text-anchor="middle" x="391.5" y="-1279.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="270.5,-1271.5 512.5,-1271.5 "/>
<text text-anchor="middle" x="391.5" y="-1256.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="270.5,-1248.5 512.5,-1248.5 "/>
<text text-anchor="middle" x="391.5" y="-1233.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="270.5,-1225.5 512.5,-1225.5 "/>
<text text-anchor="middle" x="391.5" y="-1210.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="270.5,-1202.5 512.5,-1202.5 "/>
<text text-anchor="middle" x="391.5" y="-1187.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="270.5,-1179.5 512.5,-1179.5 "/>
<text text-anchor="middle" x="391.5" y="-1164.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="270.5,-1156.5 512.5,-1156.5 "/>
<text text-anchor="middle" x="391.5" y="-1141.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="270.5,-1133.5 512.5,-1133.5 "/>
<text text-anchor="middle" x="391.5" y="-1118.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="270.5,-1110.5 512.5,-1110.5 "/>
<text text-anchor="middle" x="391.5" y="-1095.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="270.5,-1087.5 512.5,-1087.5 "/>
<text text-anchor="middle" x="391.5" y="-1072.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="270.5,-1064.5 512.5,-1064.5 "/>
<text text-anchor="middle" x="391.5" y="-1049.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="270.5,-1041.5 512.5,-1041.5 "/>
<text text-anchor="middle" x="391.5" y="-1026.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="270.5,-1018.5 512.5,-1018.5 "/>
<text text-anchor="middle" x="391.5" y="-1003.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="270.5,-995.5 512.5,-995.5 "/>
<text text-anchor="middle" x="391.5" y="-980.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-972.5 512.5,-972.5 "/>
<text text-anchor="middle" x="391.5" y="-957.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="270.5,-949.5 512.5,-949.5 "/>
<text text-anchor="middle" x="391.5" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="270.5,-926.5 512.5,-926.5 "/>
<text text-anchor="middle" x="391.5" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="270.5,-903.5 512.5,-903.5 "/>
<text text-anchor="middle" x="391.5" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="270.5,-880.5 512.5,-880.5 "/>
<text text-anchor="middle" x="391.5" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="270.5,-857.5 512.5,-857.5 "/>
<text text-anchor="middle" x="391.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="270.5,-834.5 512.5,-834.5 "/>
<text text-anchor="middle" x="391.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-811.5 512.5,-811.5 "/>
<text text-anchor="middle" x="391.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="270.5,-788.5 512.5,-788.5 "/>
<text text-anchor="middle" x="391.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-765.5 512.5,-765.5 "/>
<text text-anchor="middle" x="391.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="270.5,-742.5 512.5,-742.5 "/>
<text text-anchor="middle" x="391.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="270.5,-719.5 512.5,-719.5 "/>
<text text-anchor="middle" x="391.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-696.5 512.5,-696.5 "/>
<text text-anchor="middle" x="391.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">middle_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-673.5 512.5,-673.5 "/>
<text text-anchor="middle" x="391.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="270.5,-650.5 512.5,-650.5 "/>
<text text-anchor="middle" x="391.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="270.5,-627.5 512.5,-627.5 "/>
<text text-anchor="middle" x="391.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="270.5,-604.5 512.5,-604.5 "/>
<text text-anchor="middle" x="391.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="270.5,-581.5 512.5,-581.5 "/>
<text text-anchor="middle" x="391.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="270.5,-558.5 512.5,-558.5 "/>
<text text-anchor="middle" x="391.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-535.5 512.5,-535.5 "/>
<text text-anchor="middle" x="391.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">role_or_affiliation</text>
<polyline fill="none" stroke="#000000" points="270.5,-512.5 512.5,-512.5 "/>
<text text-anchor="middle" x="391.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="270.5,-489.5 512.5,-489.5 "/>
<text text-anchor="middle" x="391.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="270.5,-466.5 512.5,-466.5 "/>
<text text-anchor="middle" x="391.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_access</text>
<polyline fill="none" stroke="#000000" points="270.5,-443.5 512.5,-443.5 "/>
<text text-anchor="middle" x="391.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="270.5,-420.5 512.5,-420.5 "/>
<text text-anchor="middle" x="391.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="270.5,-397.5 512.5,-397.5 "/>
<text text-anchor="middle" x="391.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="270.5,-374.5 512.5,-374.5 "/>
<text text-anchor="middle" x="391.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="270.5,-351.5 512.5,-351.5 "/>
<text text-anchor="middle" x="391.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="270.5,-328.5 512.5,-328.5 "/>
<text text-anchor="middle" x="391.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_version</text>
<polyline fill="none" stroke="#000000" points="270.5,-305.5 512.5,-305.5 "/>
<text text-anchor="middle" x="391.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">suffix</text>
<polyline fill="none" stroke="#000000" points="270.5,-282.5 512.5,-282.5 "/>
<text text-anchor="middle" x="391.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">title</text>
<polyline fill="none" stroke="#000000" points="512.5,-259.5 512.5,-1294.5 "/>
<text text-anchor="middle" x="523" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M391.4633,-2140.4991C381.4566,-2123.9825 372.8296,-2106.7058 366.5,-2089 277.9213,-1841.219 268.6765,-1549.8925 285.2026,-1304.7794"/>
<polygon fill="#000000" stroke="#000000" points="288.7073,-1304.8308 285.9045,-1294.6135 281.7239,-1304.3486 288.7073,-1304.8308"/>
<text text-anchor="middle" x="310" y="-1552.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M387.5,-1720.5C387.5,-1720.5 673.5,-1720.5 673.5,-1720.5 679.5,-1720.5 685.5,-1726.5 685.5,-1732.5 685.5,-1732.5 685.5,-1938.5 685.5,-1938.5 685.5,-1944.5 679.5,-1950.5 673.5,-1950.5 673.5,-1950.5 387.5,-1950.5 387.5,-1950.5 381.5,-1950.5 375.5,-1944.5 375.5,-1938.5 375.5,-1938.5 375.5,-1732.5 375.5,-1732.5 375.5,-1726.5 381.5,-1720.5 387.5,-1720.5"/>
<text text-anchor="middle" x="409.5" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="443.5,-1720.5 443.5,-1950.5 "/>
<text text-anchor="middle" x="454" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="464.5,-1720.5 464.5,-1950.5 "/>
<text text-anchor="middle" x="564.5" y="-1935.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="464.5,-1927.5 664.5,-1927.5 "/>
<text text-anchor="middle" x="564.5" y="-1912.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="464.5,-1904.5 664.5,-1904.5 "/>
<text text-anchor="middle" x="564.5" y="-1889.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="464.5,-1881.5 664.5,-1881.5 "/>
<text text-anchor="middle" x="564.5" y="-1866.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="464.5,-1858.5 664.5,-1858.5 "/>
<text text-anchor="middle" x="564.5" y="-1843.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="464.5,-1835.5 664.5,-1835.5 "/>
<text text-anchor="middle" x="564.5" y="-1820.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="464.5,-1812.5 664.5,-1812.5 "/>
<text text-anchor="middle" x="564.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="464.5,-1789.5 664.5,-1789.5 "/>
<text text-anchor="middle" x="564.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="464.5,-1766.5 664.5,-1766.5 "/>
<text text-anchor="middle" x="564.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="464.5,-1743.5 664.5,-1743.5 "/>
<text text-anchor="middle" x="564.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="664.5,-1720.5 664.5,-1950.5 "/>
<text text-anchor="middle" x="675" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M530.5,-2140.2352C530.5,-2082.1622 530.5,-2016.4201 530.5,-1960.9028"/>
<polygon fill="#000000" stroke="#000000" points="534.0001,-1960.6596 530.5,-1950.6597 527.0001,-1960.6597 534.0001,-1960.6596"/>
<text text-anchor="middle" x="577" y="-2110.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- program -->
<g id="node3" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M209.5,-.5C209.5,-.5 517.5,-.5 517.5,-.5 523.5,-.5 529.5,-6.5 529.5,-12.5 529.5,-12.5 529.5,-195.5 529.5,-195.5 529.5,-201.5 523.5,-207.5 517.5,-207.5 517.5,-207.5 209.5,-207.5 209.5,-207.5 203.5,-207.5 197.5,-201.5 197.5,-195.5 197.5,-195.5 197.5,-12.5 197.5,-12.5 197.5,-6.5 203.5,-.5 209.5,-.5"/>
<text text-anchor="middle" x="236.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="275.5,-.5 275.5,-207.5 "/>
<text text-anchor="middle" x="286" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="296.5,-.5 296.5,-207.5 "/>
<text text-anchor="middle" x="402.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="296.5,-184.5 508.5,-184.5 "/>
<text text-anchor="middle" x="402.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="296.5,-161.5 508.5,-161.5 "/>
<text text-anchor="middle" x="402.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="296.5,-138.5 508.5,-138.5 "/>
<text text-anchor="middle" x="402.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="296.5,-115.5 508.5,-115.5 "/>
<text text-anchor="middle" x="402.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="296.5,-92.5 508.5,-92.5 "/>
<text text-anchor="middle" x="402.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="296.5,-69.5 508.5,-69.5 "/>
<text text-anchor="middle" x="402.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="296.5,-46.5 508.5,-46.5 "/>
<text text-anchor="middle" x="402.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="296.5,-23.5 508.5,-23.5 "/>
<text text-anchor="middle" x="402.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="508.5,-.5 508.5,-207.5 "/>
<text text-anchor="middle" x="519" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M780.8077,-1346.1732C718.4828,-1261.1673 623.2795,-1131.3178 539.5358,-1017.0983"/>
<polygon fill="#000000" stroke="#000000" points="542.2622,-1014.8975 533.5267,-1008.9024 536.6169,-1019.0365 542.2622,-1014.8975"/>
<text text-anchor="middle" x="797" y="-1316.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M716,-1755C716,-1755 981,-1755 981,-1755 987,-1755 993,-1761 993,-1767 993,-1767 993,-1904 993,-1904 993,-1910 987,-1916 981,-1916 981,-1916 716,-1916 716,-1916 710,-1916 704,-1910 704,-1904 704,-1904 704,-1767 704,-1767 704,-1761 710,-1755 716,-1755"/>
<text text-anchor="middle" x="748.5" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="793,-1755 793,-1916 "/>
<text text-anchor="middle" x="803.5" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="814,-1755 814,-1916 "/>
<text text-anchor="middle" x="893" y="-1900.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="814,-1893 972,-1893 "/>
<text text-anchor="middle" x="893" y="-1877.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="814,-1870 972,-1870 "/>
<text text-anchor="middle" x="893" y="-1854.8" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="814,-1847 972,-1847 "/>
<text text-anchor="middle" x="893" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="814,-1824 972,-1824 "/>
<text text-anchor="middle" x="893" y="-1808.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="814,-1801 972,-1801 "/>
<text text-anchor="middle" x="893" y="-1785.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="814,-1778 972,-1778 "/>
<text text-anchor="middle" x="893" y="-1762.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="972,-1755 972,-1916 "/>
<text text-anchor="middle" x="982.5" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M848.5,-1754.6826C848.5,-1692.9009 848.5,-1607.315 848.5,-1540.7663"/>
<polygon fill="#000000" stroke="#000000" points="852.0001,-1540.6738 848.5,-1530.6738 845.0001,-1540.6738 852.0001,-1540.6738"/>
<text text-anchor="middle" x="899" y="-1552.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge3" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M363.5,-259.2448C363.5,-244.8306 363.5,-231.0489 363.5,-218.0672"/>
<polygon fill="#000000" stroke="#000000" points="367.0001,-217.8308 363.5,-207.8308 360.0001,-217.8308 367.0001,-217.8308"/>
<text text-anchor="middle" x="405" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M597.249,-1720.3458C625.3282,-1675.4693 659.7599,-1624.6729 695.5,-1582 707.9451,-1567.1408 721.8286,-1552.2576 736.0145,-1538.0027"/>
<polygon fill="#000000" stroke="#000000" points="738.8284,-1540.1406 743.4543,-1530.609 733.8941,-1535.1755 738.8284,-1540.1406"/>
<text text-anchor="middle" x="773" y="-1552.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1023.5,-1582.5C1023.5,-1582.5 1397.5,-1582.5 1397.5,-1582.5 1403.5,-1582.5 1409.5,-1588.5 1409.5,-1594.5 1409.5,-1594.5 1409.5,-2076.5 1409.5,-2076.5 1409.5,-2082.5 1403.5,-2088.5 1397.5,-2088.5 1397.5,-2088.5 1023.5,-2088.5 1023.5,-2088.5 1017.5,-2088.5 1011.5,-2082.5 1011.5,-2076.5 1011.5,-2076.5 1011.5,-1594.5 1011.5,-1594.5 1011.5,-1588.5 1017.5,-1582.5 1023.5,-1582.5"/>
<text text-anchor="middle" x="1053.5" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1095.5,-1582.5 1095.5,-2088.5 "/>
<text text-anchor="middle" x="1106" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1116.5,-1582.5 1116.5,-2088.5 "/>
<text text-anchor="middle" x="1252.5" y="-2073.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1116.5,-2065.5 1388.5,-2065.5 "/>
<text text-anchor="middle" x="1252.5" y="-2050.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1116.5,-2042.5 1388.5,-2042.5 "/>
<text text-anchor="middle" x="1252.5" y="-2027.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1116.5,-2019.5 1388.5,-2019.5 "/>
<text text-anchor="middle" x="1252.5" y="-2004.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1996.5 1388.5,-1996.5 "/>
<text text-anchor="middle" x="1252.5" y="-1981.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1973.5 1388.5,-1973.5 "/>
<text text-anchor="middle" x="1252.5" y="-1958.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1950.5 1388.5,-1950.5 "/>
<text text-anchor="middle" x="1252.5" y="-1935.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1927.5 1388.5,-1927.5 "/>
<text text-anchor="middle" x="1252.5" y="-1912.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1904.5 1388.5,-1904.5 "/>
<text text-anchor="middle" x="1252.5" y="-1889.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1881.5 1388.5,-1881.5 "/>
<text text-anchor="middle" x="1252.5" y="-1866.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1858.5 1388.5,-1858.5 "/>
<text text-anchor="middle" x="1252.5" y="-1843.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1835.5 1388.5,-1835.5 "/>
<text text-anchor="middle" x="1252.5" y="-1820.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1812.5 1388.5,-1812.5 "/>
<text text-anchor="middle" x="1252.5" y="-1797.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1789.5 1388.5,-1789.5 "/>
<text text-anchor="middle" x="1252.5" y="-1774.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1766.5 1388.5,-1766.5 "/>
<text text-anchor="middle" x="1252.5" y="-1751.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1743.5 1388.5,-1743.5 "/>
<text text-anchor="middle" x="1252.5" y="-1728.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1720.5 1388.5,-1720.5 "/>
<text text-anchor="middle" x="1252.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1697.5 1388.5,-1697.5 "/>
<text text-anchor="middle" x="1252.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1674.5 1388.5,-1674.5 "/>
<text text-anchor="middle" x="1252.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1651.5 1388.5,-1651.5 "/>
<text text-anchor="middle" x="1252.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1628.5 1388.5,-1628.5 "/>
<text text-anchor="middle" x="1252.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1116.5,-1605.5 1388.5,-1605.5 "/>
<text text-anchor="middle" x="1252.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1388.5,-1582.5 1388.5,-2088.5 "/>
<text text-anchor="middle" x="1399" y="-1831.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1011.4772,-1592.7353C1008.1442,-1589.1168 1004.8171,-1585.5361 1001.5,-1582 987.6895,-1567.2776 972.6866,-1552.2032 957.6551,-1537.6193"/>
<polygon fill="#000000" stroke="#000000" points="959.9058,-1534.9273 950.2789,-1530.503 955.0456,-1539.965 959.9058,-1534.9273"/>
<text text-anchor="middle" x="1032" y="-1552.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- image -->
<g id="node9" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M507.5,-2491.5C507.5,-2491.5 1139.5,-2491.5 1139.5,-2491.5 1145.5,-2491.5 1151.5,-2497.5 1151.5,-2503.5 1151.5,-2503.5 1151.5,-4917.5 1151.5,-4917.5 1151.5,-4923.5 1145.5,-4929.5 1139.5,-4929.5 1139.5,-4929.5 507.5,-4929.5 507.5,-4929.5 501.5,-4929.5 495.5,-4923.5 495.5,-4917.5 495.5,-4917.5 495.5,-2503.5 495.5,-2503.5 495.5,-2497.5 501.5,-2491.5 507.5,-2491.5"/>
<text text-anchor="middle" x="525.5" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="555.5,-2491.5 555.5,-4929.5 "/>
<text text-anchor="middle" x="566" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="576.5,-2491.5 576.5,-4929.5 "/>
<text text-anchor="middle" x="853.5" y="-4914.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4906.5 1130.5,-4906.5 "/>
<text text-anchor="middle" x="853.5" y="-4891.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="576.5,-4883.5 1130.5,-4883.5 "/>
<text text-anchor="middle" x="853.5" y="-4868.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="576.5,-4860.5 1130.5,-4860.5 "/>
<text text-anchor="middle" x="853.5" y="-4845.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="576.5,-4837.5 1130.5,-4837.5 "/>
<text text-anchor="middle" x="853.5" y="-4822.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="576.5,-4814.5 1130.5,-4814.5 "/>
<text text-anchor="middle" x="853.5" y="-4799.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-4791.5 1130.5,-4791.5 "/>
<text text-anchor="middle" x="853.5" y="-4776.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="576.5,-4768.5 1130.5,-4768.5 "/>
<text text-anchor="middle" x="853.5" y="-4753.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-4745.5 1130.5,-4745.5 "/>
<text text-anchor="middle" x="853.5" y="-4730.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="576.5,-4722.5 1130.5,-4722.5 "/>
<text text-anchor="middle" x="853.5" y="-4707.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4699.5 1130.5,-4699.5 "/>
<text text-anchor="middle" x="853.5" y="-4684.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4676.5 1130.5,-4676.5 "/>
<text text-anchor="middle" x="853.5" y="-4661.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4653.5 1130.5,-4653.5 "/>
<text text-anchor="middle" x="853.5" y="-4638.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="576.5,-4630.5 1130.5,-4630.5 "/>
<text text-anchor="middle" x="853.5" y="-4615.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4607.5 1130.5,-4607.5 "/>
<text text-anchor="middle" x="853.5" y="-4592.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-4584.5 1130.5,-4584.5 "/>
<text text-anchor="middle" x="853.5" y="-4569.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4561.5 1130.5,-4561.5 "/>
<text text-anchor="middle" x="853.5" y="-4546.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-4538.5 1130.5,-4538.5 "/>
<text text-anchor="middle" x="853.5" y="-4523.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="576.5,-4515.5 1130.5,-4515.5 "/>
<text text-anchor="middle" x="853.5" y="-4500.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-4492.5 1130.5,-4492.5 "/>
<text text-anchor="middle" x="853.5" y="-4477.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-4469.5 1130.5,-4469.5 "/>
<text text-anchor="middle" x="853.5" y="-4454.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="576.5,-4446.5 1130.5,-4446.5 "/>
<text text-anchor="middle" x="853.5" y="-4431.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4423.5 1130.5,-4423.5 "/>
<text text-anchor="middle" x="853.5" y="-4408.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-4400.5 1130.5,-4400.5 "/>
<text text-anchor="middle" x="853.5" y="-4385.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4377.5 1130.5,-4377.5 "/>
<text text-anchor="middle" x="853.5" y="-4362.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4354.5 1130.5,-4354.5 "/>
<text text-anchor="middle" x="853.5" y="-4339.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_timeOfFlightContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-4331.5 1130.5,-4331.5 "/>
<text text-anchor="middle" x="853.5" y="-4316.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageReconstructionProtocolElement_complexImageComponentCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4308.5 1130.5,-4308.5 "/>
<text text-anchor="middle" x="853.5" y="-4293.3" font-family="Times,serif" font-size="14.00" fill="#000000">PETImagingAcquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="576.5,-4285.5 1130.5,-4285.5 "/>
<text text-anchor="middle" x="853.5" y="-4270.3" font-family="Times,serif" font-size="14.00" fill="#000000">Radiopharmaceutical_radionuclideCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-4262.5 1130.5,-4262.5 "/>
<text text-anchor="middle" x="853.5" y="-4247.3" font-family="Times,serif" font-size="14.00" fill="#000000">acquisition_method_type</text>
<polyline fill="none" stroke="#000000" points="576.5,-4239.5 1130.5,-4239.5 "/>
<text text-anchor="middle" x="853.5" y="-4224.3" font-family="Times,serif" font-size="14.00" fill="#000000">antibody_name</text>
<polyline fill="none" stroke="#000000" points="576.5,-4216.5 1130.5,-4216.5 "/>
<text text-anchor="middle" x="853.5" y="-4201.3" font-family="Times,serif" font-size="14.00" fill="#000000">catalog_number</text>
<polyline fill="none" stroke="#000000" points="576.5,-4193.5 1130.5,-4193.5 "/>
<text text-anchor="middle" x="853.5" y="-4178.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_id</text>
<polyline fill="none" stroke="#000000" points="576.5,-4170.5 1130.5,-4170.5 "/>
<text text-anchor="middle" x="853.5" y="-4155.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="576.5,-4147.5 1130.5,-4147.5 "/>
<text text-anchor="middle" x="853.5" y="-4132.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_metadata_filename</text>
<polyline fill="none" stroke="#000000" points="576.5,-4124.5 1130.5,-4124.5 "/>
<text text-anchor="middle" x="853.5" y="-4109.3" font-family="Times,serif" font-size="14.00" fill="#000000">channel_name</text>
<polyline fill="none" stroke="#000000" points="576.5,-4101.5 1130.5,-4101.5 "/>
<text text-anchor="middle" x="853.5" y="-4086.3" font-family="Times,serif" font-size="14.00" fill="#000000">citation_or_DOI</text>
<polyline fill="none" stroke="#000000" points="576.5,-4078.5 1130.5,-4078.5 "/>
<text text-anchor="middle" x="853.5" y="-4063.3" font-family="Times,serif" font-size="14.00" fill="#000000">clone</text>
<polyline fill="none" stroke="#000000" points="576.5,-4055.5 1130.5,-4055.5 "/>
<text text-anchor="middle" x="853.5" y="-4040.3" font-family="Times,serif" font-size="14.00" fill="#000000">concentration</text>
<polyline fill="none" stroke="#000000" points="576.5,-4032.5 1130.5,-4032.5 "/>
<text text-anchor="middle" x="853.5" y="-4017.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="576.5,-4009.5 1130.5,-4009.5 "/>
<text text-anchor="middle" x="853.5" y="-3994.3" font-family="Times,serif" font-size="14.00" fill="#000000">cycle_number</text>
<polyline fill="none" stroke="#000000" points="576.5,-3986.5 1130.5,-3986.5 "/>
<text text-anchor="middle" x="853.5" y="-3971.3" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_description</text>
<polyline fill="none" stroke="#000000" points="576.5,-3963.5 1130.5,-3963.5 "/>
<text text-anchor="middle" x="853.5" y="-3948.3" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_method_type</text>
<polyline fill="none" stroke="#000000" points="576.5,-3940.5 1130.5,-3940.5 "/>
<text text-anchor="middle" x="853.5" y="-3925.3" font-family="Times,serif" font-size="14.00" fill="#000000">de_identification_software</text>
<polyline fill="none" stroke="#000000" points="576.5,-3917.5 1130.5,-3917.5 "/>
<text text-anchor="middle" x="853.5" y="-3902.3" font-family="Times,serif" font-size="14.00" fill="#000000">dilution</text>
<polyline fill="none" stroke="#000000" points="576.5,-3894.5 1130.5,-3894.5 "/>
<text text-anchor="middle" x="853.5" y="-3879.3" font-family="Times,serif" font-size="14.00" fill="#000000">embedding_medium</text>
<polyline fill="none" stroke="#000000" points="576.5,-3871.5 1130.5,-3871.5 "/>
<text text-anchor="middle" x="853.5" y="-3856.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_bandwidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-3848.5 1130.5,-3848.5 "/>
<text text-anchor="middle" x="853.5" y="-3833.3" font-family="Times,serif" font-size="14.00" fill="#000000">emission_wavelength</text>
<polyline fill="none" stroke="#000000" points="576.5,-3825.5 1130.5,-3825.5 "/>
<text text-anchor="middle" x="853.5" y="-3810.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_bandwidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-3802.5 1130.5,-3802.5 "/>
<text text-anchor="middle" x="853.5" y="-3787.3" font-family="Times,serif" font-size="14.00" fill="#000000">excitation_wavelength</text>
<polyline fill="none" stroke="#000000" points="576.5,-3779.5 1130.5,-3779.5 "/>
<text text-anchor="middle" x="853.5" y="-3764.3" font-family="Times,serif" font-size="14.00" fill="#000000">fluorophore</text>
<polyline fill="none" stroke="#000000" points="576.5,-3756.5 1130.5,-3756.5 "/>
<text text-anchor="middle" x="853.5" y="-3741.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="576.5,-3733.5 1130.5,-3733.5 "/>
<text text-anchor="middle" x="853.5" y="-3718.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_assay_type</text>
<polyline fill="none" stroke="#000000" points="576.5,-3710.5 1130.5,-3710.5 "/>
<text text-anchor="middle" x="853.5" y="-3695.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_manufacturer</text>
<polyline fill="none" stroke="#000000" points="576.5,-3687.5 1130.5,-3687.5 "/>
<text text-anchor="middle" x="853.5" y="-3672.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_equipment_model</text>
<polyline fill="none" stroke="#000000" points="576.5,-3664.5 1130.5,-3664.5 "/>
<text text-anchor="middle" x="853.5" y="-3649.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_protocol</text>
<polyline fill="none" stroke="#000000" points="576.5,-3641.5 1130.5,-3641.5 "/>
<text text-anchor="middle" x="853.5" y="-3626.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_sofware</text>
<polyline fill="none" stroke="#000000" points="576.5,-3618.5 1130.5,-3618.5 "/>
<text text-anchor="middle" x="853.5" y="-3603.3" font-family="Times,serif" font-size="14.00" fill="#000000">immersion</text>
<polyline fill="none" stroke="#000000" points="576.5,-3595.5 1130.5,-3595.5 "/>
<text text-anchor="middle" x="853.5" y="-3580.3" font-family="Times,serif" font-size="14.00" fill="#000000">lens_numerical_aperture</text>
<polyline fill="none" stroke="#000000" points="576.5,-3572.5 1130.5,-3572.5 "/>
<text text-anchor="middle" x="853.5" y="-3557.3" font-family="Times,serif" font-size="14.00" fill="#000000">license</text>
<polyline fill="none" stroke="#000000" points="576.5,-3549.5 1130.5,-3549.5 "/>
<text text-anchor="middle" x="853.5" y="-3534.3" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_offset</text>
<polyline fill="none" stroke="#000000" points="576.5,-3526.5 1130.5,-3526.5 "/>
<text text-anchor="middle" x="853.5" y="-3511.3" font-family="Times,serif" font-size="14.00" fill="#000000">longitudinal_temporal_event_type</text>
<polyline fill="none" stroke="#000000" points="576.5,-3503.5 1130.5,-3503.5 "/>
<text text-anchor="middle" x="853.5" y="-3488.3" font-family="Times,serif" font-size="14.00" fill="#000000">lot</text>
<polyline fill="none" stroke="#000000" points="576.5,-3480.5 1130.5,-3480.5 "/>
<text text-anchor="middle" x="853.5" y="-3465.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_abbreviation</text>
<polyline fill="none" stroke="#000000" points="576.5,-3457.5 1130.5,-3457.5 "/>
<text text-anchor="middle" x="853.5" y="-3442.3" font-family="Times,serif" font-size="14.00" fill="#000000">metal_isotope_element_mass</text>
<polyline fill="none" stroke="#000000" points="576.5,-3434.5 1130.5,-3434.5 "/>
<text text-anchor="middle" x="853.5" y="-3419.3" font-family="Times,serif" font-size="14.00" fill="#000000">nominal_magnification</text>
<polyline fill="none" stroke="#000000" points="576.5,-3411.5 1130.5,-3411.5 "/>
<text text-anchor="middle" x="853.5" y="-3396.3" font-family="Times,serif" font-size="14.00" fill="#000000">objective</text>
<polyline fill="none" stroke="#000000" points="576.5,-3388.5 1130.5,-3388.5 "/>
<text text-anchor="middle" x="853.5" y="-3373.3" font-family="Times,serif" font-size="14.00" fill="#000000">oligo_barcode_lower_strand</text>
<polyline fill="none" stroke="#000000" points="576.5,-3365.5 1130.5,-3365.5 "/>
<text text-anchor="middle" x="853.5" y="-3350.3" font-family="Times,serif" font-size="14.00" fill="#000000">oligo_barcode_upper_strand</text>
<polyline fill="none" stroke="#000000" points="576.5,-3342.5 1130.5,-3342.5 "/>
<text text-anchor="middle" x="853.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">organ_or_tissue</text>
<polyline fill="none" stroke="#000000" points="576.5,-3319.5 1130.5,-3319.5 "/>
<text text-anchor="middle" x="853.5" y="-3304.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_acquisitionTypeCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3296.5 1130.5,-3296.5 "/>
<text text-anchor="middle" x="853.5" y="-3281.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_admittingDiagnosisCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3273.5 1130.5,-3273.5 "/>
<text text-anchor="middle" x="853.5" y="-3258.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_algorithmCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3250.5 1130.5,-3250.5 "/>
<text text-anchor="middle" x="853.5" y="-3235.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_bodyPositionCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3227.5 1130.5,-3227.5 "/>
<text text-anchor="middle" x="853.5" y="-3212.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_cardiacSynchronizationTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3204.5 1130.5,-3204.5 "/>
<text text-anchor="middle" x="853.5" y="-3189.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_dataCollectionDiameter</text>
<polyline fill="none" stroke="#000000" points="576.5,-3181.5 1130.5,-3181.5 "/>
<text text-anchor="middle" x="853.5" y="-3166.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_description</text>
<polyline fill="none" stroke="#000000" points="576.5,-3158.5 1130.5,-3158.5 "/>
<text text-anchor="middle" x="853.5" y="-3143.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_lossyImageCompressionIndicator</text>
<polyline fill="none" stroke="#000000" points="576.5,-3135.5 1130.5,-3135.5 "/>
<text text-anchor="middle" x="853.5" y="-3120.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_nonAcquisitionModalitiesInStudyCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3112.5 1130.5,-3112.5 "/>
<text text-anchor="middle" x="853.5" y="-3097.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_primaryAnatomicSiteCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-3089.5 1130.5,-3089.5 "/>
<text text-anchor="middle" x="853.5" y="-3074.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionDiameter</text>
<polyline fill="none" stroke="#000000" points="576.5,-3066.5 1130.5,-3066.5 "/>
<text text-anchor="middle" x="853.5" y="-3051.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewHeight</text>
<polyline fill="none" stroke="#000000" points="576.5,-3043.5 1130.5,-3043.5 "/>
<text text-anchor="middle" x="853.5" y="-3028.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionFieldOfViewWidth</text>
<polyline fill="none" stroke="#000000" points="576.5,-3020.5 1130.5,-3020.5 "/>
<text text-anchor="middle" x="853.5" y="-3005.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_reconstructionInterval</text>
<polyline fill="none" stroke="#000000" points="576.5,-2997.5 1130.5,-2997.5 "/>
<text text-anchor="middle" x="853.5" y="-2982.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_respiratoryMotionTechniqueCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2974.5 1130.5,-2974.5 "/>
<text text-anchor="middle" x="853.5" y="-2959.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_sliceThickness</text>
<polyline fill="none" stroke="#000000" points="576.5,-2951.5 1130.5,-2951.5 "/>
<text text-anchor="middle" x="853.5" y="-2936.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_summary</text>
<polyline fill="none" stroke="#000000" points="576.5,-2928.5 1130.5,-2928.5 "/>
<text text-anchor="middle" x="853.5" y="-2913.3" font-family="Times,serif" font-size="14.00" fill="#000000">performed_imaging_study_typeCode</text>
<polyline fill="none" stroke="#000000" points="576.5,-2905.5 1130.5,-2905.5 "/>
<text text-anchor="middle" x="853.5" y="-2890.3" font-family="Times,serif" font-size="14.00" fill="#000000">physical_size_x</text>
<polyline fill="none" stroke="#000000" points="576.5,-2882.5 1130.5,-2882.5 "/>
<text text-anchor="middle" x="853.5" y="-2867.3" font-family="Times,serif" font-size="14.00" fill="#000000">physical_size_y</text>
<polyline fill="none" stroke="#000000" points="576.5,-2859.5 1130.5,-2859.5 "/>
<text text-anchor="middle" x="853.5" y="-2844.3" font-family="Times,serif" font-size="14.00" fill="#000000">physical_size_z</text>
<polyline fill="none" stroke="#000000" points="576.5,-2836.5 1130.5,-2836.5 "/>
<text text-anchor="middle" x="853.5" y="-2821.3" font-family="Times,serif" font-size="14.00" fill="#000000">pyramid</text>
<polyline fill="none" stroke="#000000" points="576.5,-2813.5 1130.5,-2813.5 "/>
<text text-anchor="middle" x="853.5" y="-2798.3" font-family="Times,serif" font-size="14.00" fill="#000000">rrid_identifier</text>
<polyline fill="none" stroke="#000000" points="576.5,-2790.5 1130.5,-2790.5 "/>
<text text-anchor="middle" x="853.5" y="-2775.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_c</text>
<polyline fill="none" stroke="#000000" points="576.5,-2767.5 1130.5,-2767.5 "/>
<text text-anchor="middle" x="853.5" y="-2752.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_t</text>
<polyline fill="none" stroke="#000000" points="576.5,-2744.5 1130.5,-2744.5 "/>
<text text-anchor="middle" x="853.5" y="-2729.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_x</text>
<polyline fill="none" stroke="#000000" points="576.5,-2721.5 1130.5,-2721.5 "/>
<text text-anchor="middle" x="853.5" y="-2706.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_y</text>
<polyline fill="none" stroke="#000000" points="576.5,-2698.5 1130.5,-2698.5 "/>
<text text-anchor="middle" x="853.5" y="-2683.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_z</text>
<polyline fill="none" stroke="#000000" points="576.5,-2675.5 1130.5,-2675.5 "/>
<text text-anchor="middle" x="853.5" y="-2660.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="576.5,-2652.5 1130.5,-2652.5 "/>
<text text-anchor="middle" x="853.5" y="-2637.3" font-family="Times,serif" font-size="14.00" fill="#000000">staining_method</text>
<polyline fill="none" stroke="#000000" points="576.5,-2629.5 1130.5,-2629.5 "/>
<text text-anchor="middle" x="853.5" y="-2614.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_link_id</text>
<polyline fill="none" stroke="#000000" points="576.5,-2606.5 1130.5,-2606.5 "/>
<text text-anchor="middle" x="853.5" y="-2591.3" font-family="Times,serif" font-size="14.00" fill="#000000">sub_cycle_number</text>
<polyline fill="none" stroke="#000000" points="576.5,-2583.5 1130.5,-2583.5 "/>
<text text-anchor="middle" x="853.5" y="-2568.3" font-family="Times,serif" font-size="14.00" fill="#000000">target_name</text>
<polyline fill="none" stroke="#000000" points="576.5,-2560.5 1130.5,-2560.5 "/>
<text text-anchor="middle" x="853.5" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_fixative</text>
<polyline fill="none" stroke="#000000" points="576.5,-2537.5 1130.5,-2537.5 "/>
<text text-anchor="middle" x="853.5" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_type</text>
<polyline fill="none" stroke="#000000" points="576.5,-2514.5 1130.5,-2514.5 "/>
<text text-anchor="middle" x="853.5" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">working_distance</text>
<polyline fill="none" stroke="#000000" points="1130.5,-2491.5 1130.5,-4929.5 "/>
<text text-anchor="middle" x="1141" y="-3706.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge2" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M572.0133,-2491.2618C569.027,-2476.7839 566.1634,-2462.9004 563.4355,-2449.6751"/>
<polygon fill="#000000" stroke="#000000" points="566.8241,-2448.7777 561.3761,-2439.691 559.9684,-2450.1919 566.8241,-2448.7777"/>
<text text-anchor="middle" x="589.5" y="-2461.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
</g>
</svg>
</div>
