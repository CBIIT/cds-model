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
<svg width="1409pt" height="1827pt"
 viewBox="0.00 0.00 1408.64 1827.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1823)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1823 1404.6447,-1823 1404.6447,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M479.6447,-1657.5C479.6447,-1657.5 765.6447,-1657.5 765.6447,-1657.5 771.6447,-1657.5 777.6447,-1663.5 777.6447,-1669.5 777.6447,-1669.5 777.6447,-1806.5 777.6447,-1806.5 777.6447,-1812.5 771.6447,-1818.5 765.6447,-1818.5 765.6447,-1818.5 479.6447,-1818.5 479.6447,-1818.5 473.6447,-1818.5 467.6447,-1812.5 467.6447,-1806.5 467.6447,-1806.5 467.6447,-1669.5 467.6447,-1669.5 467.6447,-1663.5 473.6447,-1657.5 479.6447,-1657.5"/>
<text text-anchor="middle" x="501.6447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="535.6447,-1657.5 535.6447,-1818.5 "/>
<text text-anchor="middle" x="546.1447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="556.6447,-1657.5 556.6447,-1818.5 "/>
<text text-anchor="middle" x="656.6447" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="556.6447,-1795.5 756.6447,-1795.5 "/>
<text text-anchor="middle" x="656.6447" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="556.6447,-1772.5 756.6447,-1772.5 "/>
<text text-anchor="middle" x="656.6447" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="556.6447,-1749.5 756.6447,-1749.5 "/>
<text text-anchor="middle" x="656.6447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="556.6447,-1726.5 756.6447,-1726.5 "/>
<text text-anchor="middle" x="656.6447" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="556.6447,-1703.5 756.6447,-1703.5 "/>
<text text-anchor="middle" x="656.6447" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="556.6447,-1680.5 756.6447,-1680.5 "/>
<text text-anchor="middle" x="656.6447" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="756.6447,-1657.5 756.6447,-1818.5 "/>
<text text-anchor="middle" x="767.1447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M798.1447,-1024.5C798.1447,-1024.5 1057.1447,-1024.5 1057.1447,-1024.5 1063.1447,-1024.5 1069.1447,-1030.5 1069.1447,-1036.5 1069.1447,-1036.5 1069.1447,-1127.5 1069.1447,-1127.5 1069.1447,-1133.5 1063.1447,-1139.5 1057.1447,-1139.5 1057.1447,-1139.5 798.1447,-1139.5 798.1447,-1139.5 792.1447,-1139.5 786.1447,-1133.5 786.1447,-1127.5 786.1447,-1127.5 786.1447,-1036.5 786.1447,-1036.5 786.1447,-1030.5 792.1447,-1024.5 798.1447,-1024.5"/>
<text text-anchor="middle" x="834.1447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="882.1447,-1024.5 882.1447,-1139.5 "/>
<text text-anchor="middle" x="892.6447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="903.1447,-1024.5 903.1447,-1139.5 "/>
<text text-anchor="middle" x="975.6447" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="903.1447,-1116.5 1048.1447,-1116.5 "/>
<text text-anchor="middle" x="975.6447" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="903.1447,-1093.5 1048.1447,-1093.5 "/>
<text text-anchor="middle" x="975.6447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="903.1447,-1070.5 1048.1447,-1070.5 "/>
<text text-anchor="middle" x="975.6447" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="903.1447,-1047.5 1048.1447,-1047.5 "/>
<text text-anchor="middle" x="975.6447" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1048.1447,-1024.5 1048.1447,-1139.5 "/>
<text text-anchor="middle" x="1058.6447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M670.2472,-1657.3684C672.7142,-1651.276 674.8921,-1645.1167 676.6447,-1639 702.7038,-1548.052 652.1571,-1294.6324 701.6447,-1214 719.8702,-1184.3044 747.4542,-1160.5554 777.1552,-1141.8548"/>
<polygon fill="#000000" stroke="#000000" points="779.2862,-1144.655 786.0057,-1136.4636 775.6446,-1138.6768 779.2862,-1144.655"/>
<text text-anchor="middle" x="752.1447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genomic_info -->
<g id="node7" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M190.1447,-1237.5C190.1447,-1237.5 643.1447,-1237.5 643.1447,-1237.5 649.1447,-1237.5 655.1447,-1243.5 655.1447,-1249.5 655.1447,-1249.5 655.1447,-1570.5 655.1447,-1570.5 655.1447,-1576.5 649.1447,-1582.5 643.1447,-1582.5 643.1447,-1582.5 190.1447,-1582.5 190.1447,-1582.5 184.1447,-1582.5 178.1447,-1576.5 178.1447,-1570.5 178.1447,-1570.5 178.1447,-1249.5 178.1447,-1249.5 178.1447,-1243.5 184.1447,-1237.5 190.1447,-1237.5"/>
<text text-anchor="middle" x="234.1447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="290.1447,-1237.5 290.1447,-1582.5 "/>
<text text-anchor="middle" x="300.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="311.1447,-1237.5 311.1447,-1582.5 "/>
<text text-anchor="middle" x="472.6447" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1559.5 634.1447,-1559.5 "/>
<text text-anchor="middle" x="472.6447" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1536.5 634.1447,-1536.5 "/>
<text text-anchor="middle" x="472.6447" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1513.5 634.1447,-1513.5 "/>
<text text-anchor="middle" x="472.6447" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1490.5 634.1447,-1490.5 "/>
<text text-anchor="middle" x="472.6447" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1467.5 634.1447,-1467.5 "/>
<text text-anchor="middle" x="472.6447" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1444.5 634.1447,-1444.5 "/>
<text text-anchor="middle" x="472.6447" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1421.5 634.1447,-1421.5 "/>
<text text-anchor="middle" x="472.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1398.5 634.1447,-1398.5 "/>
<text text-anchor="middle" x="472.6447" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1375.5 634.1447,-1375.5 "/>
<text text-anchor="middle" x="472.6447" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1352.5 634.1447,-1352.5 "/>
<text text-anchor="middle" x="472.6447" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1329.5 634.1447,-1329.5 "/>
<text text-anchor="middle" x="472.6447" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1306.5 634.1447,-1306.5 "/>
<text text-anchor="middle" x="472.6447" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1283.5 634.1447,-1283.5 "/>
<text text-anchor="middle" x="472.6447" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="311.1447,-1260.5 634.1447,-1260.5 "/>
<text text-anchor="middle" x="472.6447" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="634.1447,-1237.5 634.1447,-1582.5 "/>
<text text-anchor="middle" x="644.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;genomic_info -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M571.9876,-1657.3421C559.2025,-1636.9852 544.952,-1614.2951 530.4121,-1591.1442"/>
<polygon fill="#000000" stroke="#000000" points="533.3269,-1589.2044 525.0444,-1582.5975 527.3991,-1592.9274 533.3269,-1589.2044"/>
<text text-anchor="middle" x="614.1447" y="-1627.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_genomic_info</text>
</g>
<!-- specimen -->
<g id="node9" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M823.1447,-1392C823.1447,-1392 1032.1447,-1392 1032.1447,-1392 1038.1447,-1392 1044.1447,-1398 1044.1447,-1404 1044.1447,-1404 1044.1447,-1416 1044.1447,-1416 1044.1447,-1422 1038.1447,-1428 1032.1447,-1428 1032.1447,-1428 823.1447,-1428 823.1447,-1428 817.1447,-1428 811.1447,-1422 811.1447,-1416 811.1447,-1416 811.1447,-1404 811.1447,-1404 811.1447,-1398 817.1447,-1392 823.1447,-1392"/>
<text text-anchor="middle" x="853.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="896.1447,-1392 896.1447,-1428 "/>
<text text-anchor="middle" x="906.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="917.1447,-1392 917.1447,-1428 "/>
<text text-anchor="middle" x="970.1447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="1023.1447,-1392 1023.1447,-1428 "/>
<text text-anchor="middle" x="1033.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M740.4686,-1657.1687C760.2114,-1641.2809 779.7462,-1623.9409 796.6447,-1606 847.305,-1552.215 891.66,-1476.8187 913.4099,-1437.0376"/>
<polygon fill="#000000" stroke="#000000" points="916.5184,-1438.6472 918.1966,-1428.1862 910.361,-1435.3174 916.5184,-1438.6472"/>
<text text-anchor="middle" x="819.6447" y="-1627.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M729.1447,-190.5C729.1447,-190.5 1126.1447,-190.5 1126.1447,-190.5 1132.1447,-190.5 1138.1447,-196.5 1138.1447,-202.5 1138.1447,-202.5 1138.1447,-937.5 1138.1447,-937.5 1138.1447,-943.5 1132.1447,-949.5 1126.1447,-949.5 1126.1447,-949.5 729.1447,-949.5 729.1447,-949.5 723.1447,-949.5 717.1447,-943.5 717.1447,-937.5 717.1447,-937.5 717.1447,-202.5 717.1447,-202.5 717.1447,-196.5 723.1447,-190.5 729.1447,-190.5"/>
<text text-anchor="middle" x="745.1447" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="773.1447,-190.5 773.1447,-949.5 "/>
<text text-anchor="middle" x="783.6447" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="794.1447,-190.5 794.1447,-949.5 "/>
<text text-anchor="middle" x="955.6447" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="794.1447,-926.5 1117.1447,-926.5 "/>
<text text-anchor="middle" x="955.6447" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="794.1447,-903.5 1117.1447,-903.5 "/>
<text text-anchor="middle" x="955.6447" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="794.1447,-880.5 1117.1447,-880.5 "/>
<text text-anchor="middle" x="955.6447" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="794.1447,-857.5 1117.1447,-857.5 "/>
<text text-anchor="middle" x="955.6447" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="794.1447,-834.5 1117.1447,-834.5 "/>
<text text-anchor="middle" x="955.6447" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="794.1447,-811.5 1117.1447,-811.5 "/>
<text text-anchor="middle" x="955.6447" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="794.1447,-788.5 1117.1447,-788.5 "/>
<text text-anchor="middle" x="955.6447" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="794.1447,-765.5 1117.1447,-765.5 "/>
<text text-anchor="middle" x="955.6447" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="794.1447,-742.5 1117.1447,-742.5 "/>
<text text-anchor="middle" x="955.6447" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="794.1447,-719.5 1117.1447,-719.5 "/>
<text text-anchor="middle" x="955.6447" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="794.1447,-696.5 1117.1447,-696.5 "/>
<text text-anchor="middle" x="955.6447" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="794.1447,-673.5 1117.1447,-673.5 "/>
<text text-anchor="middle" x="955.6447" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="794.1447,-650.5 1117.1447,-650.5 "/>
<text text-anchor="middle" x="955.6447" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="794.1447,-627.5 1117.1447,-627.5 "/>
<text text-anchor="middle" x="955.6447" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="794.1447,-604.5 1117.1447,-604.5 "/>
<text text-anchor="middle" x="955.6447" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="794.1447,-581.5 1117.1447,-581.5 "/>
<text text-anchor="middle" x="955.6447" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="794.1447,-558.5 1117.1447,-558.5 "/>
<text text-anchor="middle" x="955.6447" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="794.1447,-535.5 1117.1447,-535.5 "/>
<text text-anchor="middle" x="955.6447" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="794.1447,-512.5 1117.1447,-512.5 "/>
<text text-anchor="middle" x="955.6447" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="794.1447,-489.5 1117.1447,-489.5 "/>
<text text-anchor="middle" x="955.6447" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="794.1447,-466.5 1117.1447,-466.5 "/>
<text text-anchor="middle" x="955.6447" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="794.1447,-443.5 1117.1447,-443.5 "/>
<text text-anchor="middle" x="955.6447" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="794.1447,-420.5 1117.1447,-420.5 "/>
<text text-anchor="middle" x="955.6447" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="794.1447,-397.5 1117.1447,-397.5 "/>
<text text-anchor="middle" x="955.6447" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="794.1447,-374.5 1117.1447,-374.5 "/>
<text text-anchor="middle" x="955.6447" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="794.1447,-351.5 1117.1447,-351.5 "/>
<text text-anchor="middle" x="955.6447" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="794.1447,-328.5 1117.1447,-328.5 "/>
<text text-anchor="middle" x="955.6447" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="794.1447,-305.5 1117.1447,-305.5 "/>
<text text-anchor="middle" x="955.6447" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="794.1447,-282.5 1117.1447,-282.5 "/>
<text text-anchor="middle" x="955.6447" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="794.1447,-259.5 1117.1447,-259.5 "/>
<text text-anchor="middle" x="955.6447" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="794.1447,-236.5 1117.1447,-236.5 "/>
<text text-anchor="middle" x="955.6447" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="794.1447,-213.5 1117.1447,-213.5 "/>
<text text-anchor="middle" x="955.6447" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1117.1447,-190.5 1117.1447,-949.5 "/>
<text text-anchor="middle" x="1127.6447" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M927.6447,-1024.2624C927.6447,-1005.8164 927.6447,-983.8319 927.6447,-959.6339"/>
<polygon fill="#000000" stroke="#000000" points="931.1448,-959.5094 927.6447,-949.5094 924.1448,-959.5094 931.1448,-959.5094"/>
<text text-anchor="middle" x="958.1447" y="-971.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- program -->
<g id="node3" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M773.6447,-.5C773.6447,-.5 1081.6447,-.5 1081.6447,-.5 1087.6447,-.5 1093.6447,-6.5 1093.6447,-12.5 1093.6447,-12.5 1093.6447,-126.5 1093.6447,-126.5 1093.6447,-132.5 1087.6447,-138.5 1081.6447,-138.5 1081.6447,-138.5 773.6447,-138.5 773.6447,-138.5 767.6447,-138.5 761.6447,-132.5 761.6447,-126.5 761.6447,-126.5 761.6447,-12.5 761.6447,-12.5 761.6447,-6.5 767.6447,-.5 773.6447,-.5"/>
<text text-anchor="middle" x="800.6447" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="839.6447,-.5 839.6447,-138.5 "/>
<text text-anchor="middle" x="850.1447" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="860.6447,-.5 860.6447,-138.5 "/>
<text text-anchor="middle" x="966.6447" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="860.6447,-115.5 1072.6447,-115.5 "/>
<text text-anchor="middle" x="966.6447" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="860.6447,-92.5 1072.6447,-92.5 "/>
<text text-anchor="middle" x="966.6447" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="860.6447,-69.5 1072.6447,-69.5 "/>
<text text-anchor="middle" x="966.6447" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="860.6447,-46.5 1072.6447,-46.5 "/>
<text text-anchor="middle" x="966.6447" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="860.6447,-23.5 1072.6447,-23.5 "/>
<text text-anchor="middle" x="966.6447" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1072.6447,-.5 1072.6447,-138.5 "/>
<text text-anchor="middle" x="1083.1447" y="-65.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node4" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M257.1447,-1001.5C257.1447,-1001.5 442.1447,-1001.5 442.1447,-1001.5 448.1447,-1001.5 454.1447,-1007.5 454.1447,-1013.5 454.1447,-1013.5 454.1447,-1150.5 454.1447,-1150.5 454.1447,-1156.5 448.1447,-1162.5 442.1447,-1162.5 442.1447,-1162.5 257.1447,-1162.5 257.1447,-1162.5 251.1447,-1162.5 245.1447,-1156.5 245.1447,-1150.5 245.1447,-1150.5 245.1447,-1013.5 245.1447,-1013.5 245.1447,-1007.5 251.1447,-1001.5 257.1447,-1001.5"/>
<text text-anchor="middle" x="264.6447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="284.1447,-1001.5 284.1447,-1162.5 "/>
<text text-anchor="middle" x="294.6447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="305.1447,-1001.5 305.1447,-1162.5 "/>
<text text-anchor="middle" x="369.1447" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="305.1447,-1139.5 433.1447,-1139.5 "/>
<text text-anchor="middle" x="369.1447" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="305.1447,-1116.5 433.1447,-1116.5 "/>
<text text-anchor="middle" x="369.1447" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="305.1447,-1093.5 433.1447,-1093.5 "/>
<text text-anchor="middle" x="369.1447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="305.1447,-1070.5 433.1447,-1070.5 "/>
<text text-anchor="middle" x="369.1447" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="305.1447,-1047.5 433.1447,-1047.5 "/>
<text text-anchor="middle" x="369.1447" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="305.1447,-1024.5 433.1447,-1024.5 "/>
<text text-anchor="middle" x="369.1447" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="433.1447,-1001.5 433.1447,-1162.5 "/>
<text text-anchor="middle" x="443.6447" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M244.8165,-1103.4716C184.1403,-1121.8577 112.652,-1155.0939 75.6447,-1214 -17.0365,-1361.5248 -32.1351,-1469.1173 75.6447,-1606 122.6015,-1665.6361 314.1022,-1701.5098 457.3645,-1720.4955"/>
<polygon fill="#000000" stroke="#000000" points="457.2239,-1724.0068 467.5934,-1721.8333 458.1318,-1717.0659 457.2239,-1724.0068"/>
<text text-anchor="middle" x="122.1447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- file&#45;&gt;genomic_info -->
<g id="edge5" class="edge">
<title>file&#45;&gt;genomic_info</title>
<path fill="none" stroke="#000000" d="M388.8332,-1162.5108C391.035,-1168.6835 393.0114,-1174.8898 394.6447,-1181 398.6002,-1195.7973 401.8643,-1211.3002 404.5553,-1226.9653"/>
<polygon fill="#000000" stroke="#000000" points="401.1737,-1227.9735 406.2425,-1237.2771 408.0818,-1226.8431 401.1737,-1227.9735"/>
<text text-anchor="middle" x="467.1447" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_genomic_info</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1074.6447,-1214.5C1074.6447,-1214.5 1388.6447,-1214.5 1388.6447,-1214.5 1394.6447,-1214.5 1400.6447,-1220.5 1400.6447,-1226.5 1400.6447,-1226.5 1400.6447,-1593.5 1400.6447,-1593.5 1400.6447,-1599.5 1394.6447,-1605.5 1388.6447,-1605.5 1388.6447,-1605.5 1074.6447,-1605.5 1074.6447,-1605.5 1068.6447,-1605.5 1062.6447,-1599.5 1062.6447,-1593.5 1062.6447,-1593.5 1062.6447,-1226.5 1062.6447,-1226.5 1062.6447,-1220.5 1068.6447,-1214.5 1074.6447,-1214.5"/>
<text text-anchor="middle" x="1104.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1146.6447,-1214.5 1146.6447,-1605.5 "/>
<text text-anchor="middle" x="1157.1447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1214.5 1167.6447,-1605.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1582.5 1379.6447,-1582.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1559.5 1379.6447,-1559.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1536.5 1379.6447,-1536.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1513.5 1379.6447,-1513.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1490.5 1379.6447,-1490.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1467.5 1379.6447,-1467.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1444.5 1379.6447,-1444.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1421.5 1379.6447,-1421.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1398.5 1379.6447,-1398.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1375.5 1379.6447,-1375.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1352.5 1379.6447,-1352.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1329.5 1379.6447,-1329.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1306.5 1379.6447,-1306.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1283.5 1379.6447,-1283.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1260.5 1379.6447,-1260.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1167.6447,-1237.5 1379.6447,-1237.5 "/>
<text text-anchor="middle" x="1273.6447" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1379.6447,-1214.5 1379.6447,-1605.5 "/>
<text text-anchor="middle" x="1390.1447" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1063.8502,-1214.2344C1053.4051,-1202.8853 1042.9505,-1191.7327 1032.6447,-1181 1021.7232,-1169.6261 1009.8254,-1157.861 998.0914,-1146.5845"/>
<polygon fill="#000000" stroke="#000000" points="1000.4651,-1144.0116 990.8167,-1139.6342 995.6294,-1149.0729 1000.4651,-1144.0116"/>
<text text-anchor="middle" x="1094.1447" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node6" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M808.1447,-1680.5C808.1447,-1680.5 1073.1447,-1680.5 1073.1447,-1680.5 1079.1447,-1680.5 1085.1447,-1686.5 1085.1447,-1692.5 1085.1447,-1692.5 1085.1447,-1783.5 1085.1447,-1783.5 1085.1447,-1789.5 1079.1447,-1795.5 1073.1447,-1795.5 1073.1447,-1795.5 808.1447,-1795.5 808.1447,-1795.5 802.1447,-1795.5 796.1447,-1789.5 796.1447,-1783.5 796.1447,-1783.5 796.1447,-1692.5 796.1447,-1692.5 796.1447,-1686.5 802.1447,-1680.5 808.1447,-1680.5"/>
<text text-anchor="middle" x="840.6447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="885.1447,-1680.5 885.1447,-1795.5 "/>
<text text-anchor="middle" x="895.6447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="906.1447,-1680.5 906.1447,-1795.5 "/>
<text text-anchor="middle" x="985.1447" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="906.1447,-1772.5 1064.1447,-1772.5 "/>
<text text-anchor="middle" x="985.1447" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="906.1447,-1749.5 1064.1447,-1749.5 "/>
<text text-anchor="middle" x="985.1447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="906.1447,-1726.5 1064.1447,-1726.5 "/>
<text text-anchor="middle" x="985.1447" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="906.1447,-1703.5 1064.1447,-1703.5 "/>
<text text-anchor="middle" x="985.1447" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1064.1447,-1680.5 1064.1447,-1795.5 "/>
<text text-anchor="middle" x="1074.6447" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge1" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M358.7426,-1237.2653C355.5208,-1223.4137 352.7465,-1209.5429 350.6447,-1196 349.4709,-1188.4364 348.6289,-1180.5566 348.0453,-1172.6285"/>
<polygon fill="#000000" stroke="#000000" points="351.5351,-1172.3517 347.4387,-1162.5808 344.5478,-1172.7736 351.5351,-1172.3517"/>
<text text-anchor="middle" x="372.6447" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge8" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M927.6447,-190.338C927.6447,-175.5265 927.6447,-161.5495 927.6447,-148.7219"/>
<polygon fill="#000000" stroke="#000000" points="931.1448,-148.6868 927.6447,-138.6868 924.1448,-148.6869 931.1448,-148.6868"/>
<text text-anchor="middle" x="969.1447" y="-160.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- specimen&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>specimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M927.6447,-1391.8981C927.6447,-1346.5915 927.6447,-1226.45 927.6447,-1149.7595"/>
<polygon fill="#000000" stroke="#000000" points="931.1448,-1149.7032 927.6447,-1139.7032 924.1448,-1149.7032 931.1448,-1149.7032"/>
<text text-anchor="middle" x="978.1447" y="-1184.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
