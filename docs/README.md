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
<svg width="1622pt" height="2661pt"
 viewBox="0.00 0.00 1622.00 2661.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 2657)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-2657 1618,-2657 1618,4 -4,4"/>
<!-- image -->
<g id="node1" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M12,-2054.5C12,-2054.5 644,-2054.5 644,-2054.5 650,-2054.5 656,-2060.5 656,-2066.5 656,-2066.5 656,-2640.5 656,-2640.5 656,-2646.5 650,-2652.5 644,-2652.5 644,-2652.5 12,-2652.5 12,-2652.5 6,-2652.5 0,-2646.5 0,-2640.5 0,-2640.5 0,-2066.5 0,-2066.5 0,-2060.5 6,-2054.5 12,-2054.5"/>
<text text-anchor="middle" x="30" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
<polyline fill="none" stroke="#000000" points="60,-2054.5 60,-2652.5 "/>
<text text-anchor="middle" x="70.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="81,-2054.5 81,-2652.5 "/>
<text text-anchor="middle" x="358" y="-2637.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiPhantomTypeCode</text>
<polyline fill="none" stroke="#000000" points="81,-2629.5 635,-2629.5 "/>
<text text-anchor="middle" x="358" y="-2614.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_ctdiVol</text>
<polyline fill="none" stroke="#000000" points="81,-2606.5 635,-2606.5 "/>
<text text-anchor="middle" x="358" y="-2591.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_exposureModulationType_Code</text>
<polyline fill="none" stroke="#000000" points="81,-2583.5 635,-2583.5 "/>
<text text-anchor="middle" x="358" y="-2568.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_gantryDetectorTilt</text>
<polyline fill="none" stroke="#000000" points="81,-2560.5 635,-2560.5 "/>
<text text-anchor="middle" x="358" y="-2545.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_kVp</text>
<polyline fill="none" stroke="#000000" points="81,-2537.5 635,-2537.5 "/>
<text text-anchor="middle" x="358" y="-2522.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_singleCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="81,-2514.5 635,-2514.5 "/>
<text text-anchor="middle" x="358" y="-2499.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_spiralPitchFactor</text>
<polyline fill="none" stroke="#000000" points="81,-2491.5 635,-2491.5 "/>
<text text-anchor="middle" x="358" y="-2476.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTAquisitionProtocolElement_totalCollimationWidth</text>
<polyline fill="none" stroke="#000000" points="81,-2468.5 635,-2468.5 "/>
<text text-anchor="middle" x="358" y="-2453.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernel</text>
<polyline fill="none" stroke="#000000" points="81,-2445.5 635,-2445.5 "/>
<text text-anchor="middle" x="358" y="-2430.3" font-family="Times,serif" font-size="14.00" fill="#000000">CTImageReconstructionProtocolElement_convolutionKernelGroupCode</text>
<polyline fill="none" stroke="#000000" points="81,-2422.5 635,-2422.5 "/>
<text text-anchor="middle" x="358" y="-2407.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_acquisitionContrastCode</text>
<polyline fill="none" stroke="#000000" points="81,-2399.5 635,-2399.5 "/>
<text text-anchor="middle" x="358" y="-2384.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_arterialSpinLabelingContrastCode</text>
<polyline fill="none" stroke="#000000" points="81,-2376.5 635,-2376.5 "/>
<text text-anchor="middle" x="358" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionBValue</text>
<polyline fill="none" stroke="#000000" points="81,-2353.5 635,-2353.5 "/>
<text text-anchor="middle" x="358" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_diffusionDirectionalityCode</text>
<polyline fill="none" stroke="#000000" points="81,-2330.5 635,-2330.5 "/>
<text text-anchor="middle" x="358" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPlanarPulseSequenceIndicator</text>
<polyline fill="none" stroke="#000000" points="81,-2307.5 635,-2307.5 "/>
<text text-anchor="middle" x="358" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_echoPulseSequenceCategoryCode</text>
<polyline fill="none" stroke="#000000" points="81,-2284.5 635,-2284.5 "/>
<text text-anchor="middle" x="358" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_inversionRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="81,-2261.5 635,-2261.5 "/>
<text text-anchor="middle" x="358" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_magneticFieldStrength</text>
<polyline fill="none" stroke="#000000" points="81,-2238.5 635,-2238.5 "/>
<text text-anchor="middle" x="358" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_multipleSpinEchoIndicator</text>
<polyline fill="none" stroke="#000000" points="81,-2215.5 635,-2215.5 "/>
<text text-anchor="middle" x="358" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_phaseContrastIndicator</text>
<polyline fill="none" stroke="#000000" points="81,-2192.5 635,-2192.5 "/>
<text text-anchor="middle" x="358" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_pulseSequenceName</text>
<polyline fill="none" stroke="#000000" points="81,-2169.5 635,-2169.5 "/>
<text text-anchor="middle" x="358" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_resonantNucleusCode</text>
<polyline fill="none" stroke="#000000" points="81,-2146.5 635,-2146.5 "/>
<text text-anchor="middle" x="358" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_saturationRecoveryIndicator</text>
<polyline fill="none" stroke="#000000" points="81,-2123.5 635,-2123.5 "/>
<text text-anchor="middle" x="358" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_spectrallySelectedSuppressionCode</text>
<polyline fill="none" stroke="#000000" points="81,-2100.5 635,-2100.5 "/>
<text text-anchor="middle" x="358" y="-2085.3" font-family="Times,serif" font-size="14.00" fill="#000000">MRImageAcquisitionProtocolElement_steadyStatePulseSequenceCode</text>
<polyline fill="none" stroke="#000000" points="81,-2077.5 635,-2077.5 "/>
<text text-anchor="middle" x="358" y="-2062.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 81 properties</text>
<polyline fill="none" stroke="#000000" points="635,-2054.5 635,-2652.5 "/>
<text text-anchor="middle" x="645.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node2" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M430,-1703.5C430,-1703.5 810,-1703.5 810,-1703.5 816,-1703.5 822,-1709.5 822,-1715.5 822,-1715.5 822,-1990.5 822,-1990.5 822,-1996.5 816,-2002.5 810,-2002.5 810,-2002.5 430,-2002.5 430,-2002.5 424,-2002.5 418,-1996.5 418,-1990.5 418,-1990.5 418,-1715.5 418,-1715.5 418,-1709.5 424,-1703.5 430,-1703.5"/>
<text text-anchor="middle" x="437.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="457,-1703.5 457,-2002.5 "/>
<text text-anchor="middle" x="467.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="478,-1703.5 478,-2002.5 "/>
<text text-anchor="middle" x="639.5" y="-1987.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="478,-1979.5 801,-1979.5 "/>
<text text-anchor="middle" x="639.5" y="-1964.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="478,-1956.5 801,-1956.5 "/>
<text text-anchor="middle" x="639.5" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="478,-1933.5 801,-1933.5 "/>
<text text-anchor="middle" x="639.5" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="478,-1910.5 801,-1910.5 "/>
<text text-anchor="middle" x="639.5" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="478,-1887.5 801,-1887.5 "/>
<text text-anchor="middle" x="639.5" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="478,-1864.5 801,-1864.5 "/>
<text text-anchor="middle" x="639.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="478,-1841.5 801,-1841.5 "/>
<text text-anchor="middle" x="639.5" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="478,-1818.5 801,-1818.5 "/>
<text text-anchor="middle" x="639.5" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="478,-1795.5 801,-1795.5 "/>
<text text-anchor="middle" x="639.5" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="478,-1772.5 801,-1772.5 "/>
<text text-anchor="middle" x="639.5" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="478,-1749.5 801,-1749.5 "/>
<text text-anchor="middle" x="639.5" y="-1734.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="478,-1726.5 801,-1726.5 "/>
<text text-anchor="middle" x="639.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="801,-1703.5 801,-2002.5 "/>
<text text-anchor="middle" x="811.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- image&#45;&gt;file -->
<g id="edge7" class="edge">
<title>image&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M502.4946,-2054.409C511.0681,-2039.7138 519.5052,-2025.2523 527.6813,-2011.2381"/>
<polygon fill="#000000" stroke="#000000" points="530.7211,-2012.9732 532.7373,-2002.5719 524.6748,-2009.4457 530.7211,-2012.9732"/>
<text text-anchor="middle" x="540" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- file&#45;&gt;file -->
<g id="edge5" class="edge">
<title>file&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M822.1809,-1874.8677C833.3527,-1869.55 840,-1862.2607 840,-1853 840,-1846.4885 836.7137,-1840.9518 830.8789,-1836.3897"/>
<polygon fill="#000000" stroke="#000000" points="832.5495,-1833.3098 822.1809,-1831.1323 828.9285,-1839.3005 832.5495,-1833.3098"/>
<text text-anchor="middle" x="897.5" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">associated_with</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M477,-1283.5C477,-1283.5 763,-1283.5 763,-1283.5 769,-1283.5 775,-1289.5 775,-1295.5 775,-1295.5 775,-1501.5 775,-1501.5 775,-1507.5 769,-1513.5 763,-1513.5 763,-1513.5 477,-1513.5 477,-1513.5 471,-1513.5 465,-1507.5 465,-1501.5 465,-1501.5 465,-1295.5 465,-1295.5 465,-1289.5 471,-1283.5 477,-1283.5"/>
<text text-anchor="middle" x="499" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="533,-1283.5 533,-1513.5 "/>
<text text-anchor="middle" x="543.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="554,-1283.5 554,-1513.5 "/>
<text text-anchor="middle" x="654" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="554,-1490.5 754,-1490.5 "/>
<text text-anchor="middle" x="654" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="554,-1467.5 754,-1467.5 "/>
<text text-anchor="middle" x="654" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="554,-1444.5 754,-1444.5 "/>
<text text-anchor="middle" x="654" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="554,-1421.5 754,-1421.5 "/>
<text text-anchor="middle" x="654" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="554,-1398.5 754,-1398.5 "/>
<text text-anchor="middle" x="654" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="554,-1375.5 754,-1375.5 "/>
<text text-anchor="middle" x="654" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="554,-1352.5 754,-1352.5 "/>
<text text-anchor="middle" x="654" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="554,-1329.5 754,-1329.5 "/>
<text text-anchor="middle" x="654" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="554,-1306.5 754,-1306.5 "/>
<text text-anchor="middle" x="654" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type_category</text>
<polyline fill="none" stroke="#000000" points="754,-1283.5 754,-1513.5 "/>
<text text-anchor="middle" x="764.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M620,-1703.2352C620,-1645.1622 620,-1579.4201 620,-1523.9028"/>
<polygon fill="#000000" stroke="#000000" points="623.5001,-1523.6596 620,-1513.6597 616.5001,-1523.6597 623.5001,-1523.6596"/>
<text text-anchor="middle" x="666.5" y="-1673.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M799,-909.5C799,-909.5 1077,-909.5 1077,-909.5 1083,-909.5 1089,-915.5 1089,-921.5 1089,-921.5 1089,-1081.5 1089,-1081.5 1089,-1087.5 1083,-1093.5 1077,-1093.5 1077,-1093.5 799,-1093.5 799,-1093.5 793,-1093.5 787,-1087.5 787,-1081.5 787,-1081.5 787,-921.5 787,-921.5 787,-915.5 793,-909.5 799,-909.5"/>
<text text-anchor="middle" x="835" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="883,-909.5 883,-1093.5 "/>
<text text-anchor="middle" x="893.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="904,-909.5 904,-1093.5 "/>
<text text-anchor="middle" x="986" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="904,-1070.5 1068,-1070.5 "/>
<text text-anchor="middle" x="986" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="904,-1047.5 1068,-1047.5 "/>
<text text-anchor="middle" x="986" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="904,-1024.5 1068,-1024.5 "/>
<text text-anchor="middle" x="986" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="904,-1001.5 1068,-1001.5 "/>
<text text-anchor="middle" x="986" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="904,-978.5 1068,-978.5 "/>
<text text-anchor="middle" x="986" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="904,-955.5 1068,-955.5 "/>
<text text-anchor="middle" x="986" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="904,-932.5 1068,-932.5 "/>
<text text-anchor="middle" x="986" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="1068,-909.5 1068,-1093.5 "/>
<text text-anchor="middle" x="1078.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M417.9812,-1733.6164C392.5866,-1709.8679 370.2178,-1682.6426 355,-1652 254.7736,-1450.1838 216.0045,-1322.3566 355,-1145 406.5912,-1079.1702 622.5944,-1039.4837 776.6093,-1019.0321"/>
<polygon fill="#000000" stroke="#000000" points="777.2025,-1022.4844 786.662,-1017.7128 776.2915,-1015.5439 777.2025,-1022.4844"/>
<text text-anchor="middle" x="405.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1075,-259.5C1075,-259.5 1391,-259.5 1391,-259.5 1397,-259.5 1403,-265.5 1403,-271.5 1403,-271.5 1403,-845.5 1403,-845.5 1403,-851.5 1397,-857.5 1391,-857.5 1391,-857.5 1075,-857.5 1075,-857.5 1069,-857.5 1063,-851.5 1063,-845.5 1063,-845.5 1063,-271.5 1063,-271.5 1063,-265.5 1069,-259.5 1075,-259.5"/>
<text text-anchor="middle" x="1091" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1119,-259.5 1119,-857.5 "/>
<text text-anchor="middle" x="1129.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1140,-259.5 1140,-857.5 "/>
<text text-anchor="middle" x="1261" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="1140,-834.5 1382,-834.5 "/>
<text text-anchor="middle" x="1261" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="1140,-811.5 1382,-811.5 "/>
<text text-anchor="middle" x="1261" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="1140,-788.5 1382,-788.5 "/>
<text text-anchor="middle" x="1261" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="1140,-765.5 1382,-765.5 "/>
<text text-anchor="middle" x="1261" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="1140,-742.5 1382,-742.5 "/>
<text text-anchor="middle" x="1261" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="1140,-719.5 1382,-719.5 "/>
<text text-anchor="middle" x="1261" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="1140,-696.5 1382,-696.5 "/>
<text text-anchor="middle" x="1261" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="1140,-673.5 1382,-673.5 "/>
<text text-anchor="middle" x="1261" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="1140,-650.5 1382,-650.5 "/>
<text text-anchor="middle" x="1261" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="1140,-627.5 1382,-627.5 "/>
<text text-anchor="middle" x="1261" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="1140,-604.5 1382,-604.5 "/>
<text text-anchor="middle" x="1261" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="1140,-581.5 1382,-581.5 "/>
<text text-anchor="middle" x="1261" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="1140,-558.5 1382,-558.5 "/>
<text text-anchor="middle" x="1261" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="1140,-535.5 1382,-535.5 "/>
<text text-anchor="middle" x="1261" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1140,-512.5 1382,-512.5 "/>
<text text-anchor="middle" x="1261" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="1140,-489.5 1382,-489.5 "/>
<text text-anchor="middle" x="1261" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1140,-466.5 1382,-466.5 "/>
<text text-anchor="middle" x="1261" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">email</text>
<polyline fill="none" stroke="#000000" points="1140,-443.5 1382,-443.5 "/>
<text text-anchor="middle" x="1261" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="1140,-420.5 1382,-420.5 "/>
<text text-anchor="middle" x="1261" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="1140,-397.5 1382,-397.5 "/>
<text text-anchor="middle" x="1261" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_name</text>
<polyline fill="none" stroke="#000000" points="1140,-374.5 1382,-374.5 "/>
<text text-anchor="middle" x="1261" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1140,-351.5 1382,-351.5 "/>
<text text-anchor="middle" x="1261" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="1140,-328.5 1382,-328.5 "/>
<text text-anchor="middle" x="1261" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="1140,-305.5 1382,-305.5 "/>
<text text-anchor="middle" x="1261" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="1140,-282.5 1382,-282.5 "/>
<text text-anchor="middle" x="1261" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 20 properties</text>
<polyline fill="none" stroke="#000000" points="1382,-259.5 1382,-857.5 "/>
<text text-anchor="middle" x="1392.5" y="-554.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M822.0717,-1836.0247C1057.1149,-1811.6003 1423.7964,-1757.3934 1508,-1652 1700.814,-1410.6645 1551.4366,-1051.3681 1408.4646,-811.2313"/>
<polygon fill="#000000" stroke="#000000" points="1411.3073,-809.1657 1403.1677,-802.3836 1405.3013,-812.7614 1411.3073,-809.1657"/>
<text text-anchor="middle" x="1583.5" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- program -->
<g id="node3" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1079,-.5C1079,-.5 1387,-.5 1387,-.5 1393,-.5 1399,-6.5 1399,-12.5 1399,-12.5 1399,-195.5 1399,-195.5 1399,-201.5 1393,-207.5 1387,-207.5 1387,-207.5 1079,-207.5 1079,-207.5 1073,-207.5 1067,-201.5 1067,-195.5 1067,-195.5 1067,-12.5 1067,-12.5 1067,-6.5 1073,-.5 1079,-.5"/>
<text text-anchor="middle" x="1106" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1145,-.5 1145,-207.5 "/>
<text text-anchor="middle" x="1155.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1166,-.5 1166,-207.5 "/>
<text text-anchor="middle" x="1272" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1166,-184.5 1378,-184.5 "/>
<text text-anchor="middle" x="1272" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="1166,-161.5 1378,-161.5 "/>
<text text-anchor="middle" x="1272" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="1166,-138.5 1378,-138.5 "/>
<text text-anchor="middle" x="1272" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="1166,-115.5 1378,-115.5 "/>
<text text-anchor="middle" x="1272" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="1166,-92.5 1378,-92.5 "/>
<text text-anchor="middle" x="1272" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1166,-69.5 1378,-69.5 "/>
<text text-anchor="middle" x="1272" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="1166,-46.5 1378,-46.5 "/>
<text text-anchor="middle" x="1272" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_name</text>
<polyline fill="none" stroke="#000000" points="1166,-23.5 1378,-23.5 "/>
<text text-anchor="middle" x="1272" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1378,-.5 1378,-207.5 "/>
<text text-anchor="middle" x="1388.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info -->
<g id="node4" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M686.5,-2112C686.5,-2112 1139.5,-2112 1139.5,-2112 1145.5,-2112 1151.5,-2118 1151.5,-2124 1151.5,-2124 1151.5,-2583 1151.5,-2583 1151.5,-2589 1145.5,-2595 1139.5,-2595 1139.5,-2595 686.5,-2595 686.5,-2595 680.5,-2595 674.5,-2589 674.5,-2583 674.5,-2583 674.5,-2124 674.5,-2124 674.5,-2118 680.5,-2112 686.5,-2112"/>
<text text-anchor="middle" x="730.5" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="786.5,-2112 786.5,-2595 "/>
<text text-anchor="middle" x="797" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="807.5,-2112 807.5,-2595 "/>
<text text-anchor="middle" x="969" y="-2579.8" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="807.5,-2572 1130.5,-2572 "/>
<text text-anchor="middle" x="969" y="-2556.8" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="807.5,-2549 1130.5,-2549 "/>
<text text-anchor="middle" x="969" y="-2533.8" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="807.5,-2526 1130.5,-2526 "/>
<text text-anchor="middle" x="969" y="-2510.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="807.5,-2503 1130.5,-2503 "/>
<text text-anchor="middle" x="969" y="-2487.8" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="807.5,-2480 1130.5,-2480 "/>
<text text-anchor="middle" x="969" y="-2464.8" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="807.5,-2457 1130.5,-2457 "/>
<text text-anchor="middle" x="969" y="-2441.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="807.5,-2434 1130.5,-2434 "/>
<text text-anchor="middle" x="969" y="-2418.8" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="807.5,-2411 1130.5,-2411 "/>
<text text-anchor="middle" x="969" y="-2395.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="807.5,-2388 1130.5,-2388 "/>
<text text-anchor="middle" x="969" y="-2372.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="807.5,-2365 1130.5,-2365 "/>
<text text-anchor="middle" x="969" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="807.5,-2342 1130.5,-2342 "/>
<text text-anchor="middle" x="969" y="-2326.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="807.5,-2319 1130.5,-2319 "/>
<text text-anchor="middle" x="969" y="-2303.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_material</text>
<polyline fill="none" stroke="#000000" points="807.5,-2296 1130.5,-2296 "/>
<text text-anchor="middle" x="969" y="-2280.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_source_molecule</text>
<polyline fill="none" stroke="#000000" points="807.5,-2273 1130.5,-2273 "/>
<text text-anchor="middle" x="969" y="-2257.8" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="807.5,-2250 1130.5,-2250 "/>
<text text-anchor="middle" x="969" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="807.5,-2227 1130.5,-2227 "/>
<text text-anchor="middle" x="969" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="807.5,-2204 1130.5,-2204 "/>
<text text-anchor="middle" x="969" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="807.5,-2181 1130.5,-2181 "/>
<text text-anchor="middle" x="969" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="807.5,-2158 1130.5,-2158 "/>
<text text-anchor="middle" x="969" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="807.5,-2135 1130.5,-2135 "/>
<text text-anchor="middle" x="969" y="-2119.8" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="1130.5,-2112 1130.5,-2595 "/>
<text text-anchor="middle" x="1141" y="-2349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge6" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M771.435,-2111.6799C751.5224,-2077.6654 731.4881,-2043.443 712.8059,-2011.5302"/>
<polygon fill="#000000" stroke="#000000" points="715.6462,-2009.4542 707.5736,-2002.5924 709.6053,-2012.9907 715.6462,-2009.4542"/>
<text text-anchor="middle" x="746" y="-2024.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M686.749,-1283.3458C714.8282,-1238.4693 749.2599,-1187.6729 785,-1145 797.4451,-1130.1408 811.3286,-1115.2576 825.5145,-1101.0027"/>
<polygon fill="#000000" stroke="#000000" points="828.3284,-1103.1406 832.9543,-1093.609 823.3941,-1098.1755 828.3284,-1103.1406"/>
<text text-anchor="middle" x="862.5" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M999.3033,-909.4411C1016.7368,-883.2614 1036.6452,-853.365 1057.3208,-822.3165"/>
<polygon fill="#000000" stroke="#000000" points="1060.2513,-824.2304 1062.8808,-813.9671 1054.4249,-820.3505 1060.2513,-824.2304"/>
<text text-anchor="middle" x="1047.5" y="-879.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M805.5,-1318C805.5,-1318 1070.5,-1318 1070.5,-1318 1076.5,-1318 1082.5,-1324 1082.5,-1330 1082.5,-1330 1082.5,-1467 1082.5,-1467 1082.5,-1473 1076.5,-1479 1070.5,-1479 1070.5,-1479 805.5,-1479 805.5,-1479 799.5,-1479 793.5,-1473 793.5,-1467 793.5,-1467 793.5,-1330 793.5,-1330 793.5,-1324 799.5,-1318 805.5,-1318"/>
<text text-anchor="middle" x="838" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="882.5,-1318 882.5,-1479 "/>
<text text-anchor="middle" x="893" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="903.5,-1318 903.5,-1479 "/>
<text text-anchor="middle" x="982.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="903.5,-1456 1061.5,-1456 "/>
<text text-anchor="middle" x="982.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="903.5,-1433 1061.5,-1433 "/>
<text text-anchor="middle" x="982.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="903.5,-1410 1061.5,-1410 "/>
<text text-anchor="middle" x="982.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="903.5,-1387 1061.5,-1387 "/>
<text text-anchor="middle" x="982.5" y="-1371.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="903.5,-1364 1061.5,-1364 "/>
<text text-anchor="middle" x="982.5" y="-1348.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="903.5,-1341 1061.5,-1341 "/>
<text text-anchor="middle" x="982.5" y="-1325.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1061.5,-1318 1061.5,-1479 "/>
<text text-anchor="middle" x="1072" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M938,-1317.6826C938,-1255.9009 938,-1170.315 938,-1103.7663"/>
<polygon fill="#000000" stroke="#000000" points="941.5001,-1103.6738 938,-1093.6738 934.5001,-1103.6738 941.5001,-1103.6738"/>
<text text-anchor="middle" x="988.5" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge9" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1233,-259.4595C1233,-244.999 1233,-230.9707 1233,-217.6442"/>
<polygon fill="#000000" stroke="#000000" points="1236.5001,-217.5945 1233,-207.5945 1229.5001,-217.5946 1236.5001,-217.5945"/>
<text text-anchor="middle" x="1274.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1113,-1145.5C1113,-1145.5 1487,-1145.5 1487,-1145.5 1493,-1145.5 1499,-1151.5 1499,-1157.5 1499,-1157.5 1499,-1639.5 1499,-1639.5 1499,-1645.5 1493,-1651.5 1487,-1651.5 1487,-1651.5 1113,-1651.5 1113,-1651.5 1107,-1651.5 1101,-1645.5 1101,-1639.5 1101,-1639.5 1101,-1157.5 1101,-1157.5 1101,-1151.5 1107,-1145.5 1113,-1145.5"/>
<text text-anchor="middle" x="1143" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1185,-1145.5 1185,-1651.5 "/>
<text text-anchor="middle" x="1195.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1206,-1145.5 1206,-1651.5 "/>
<text text-anchor="middle" x="1342" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1206,-1628.5 1478,-1628.5 "/>
<text text-anchor="middle" x="1342" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">crdc_id</text>
<polyline fill="none" stroke="#000000" points="1206,-1605.5 1478,-1605.5 "/>
<text text-anchor="middle" x="1342" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1206,-1582.5 1478,-1582.5 "/>
<text text-anchor="middle" x="1342" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1206,-1559.5 1478,-1559.5 "/>
<text text-anchor="middle" x="1342" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="1206,-1536.5 1478,-1536.5 "/>
<text text-anchor="middle" x="1342" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1206,-1513.5 1478,-1513.5 "/>
<text text-anchor="middle" x="1342" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1206,-1490.5 1478,-1490.5 "/>
<text text-anchor="middle" x="1342" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="1206,-1467.5 1478,-1467.5 "/>
<text text-anchor="middle" x="1342" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="1206,-1444.5 1478,-1444.5 "/>
<text text-anchor="middle" x="1342" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1206,-1421.5 1478,-1421.5 "/>
<text text-anchor="middle" x="1342" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="1206,-1398.5 1478,-1398.5 "/>
<text text-anchor="middle" x="1342" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1206,-1375.5 1478,-1375.5 "/>
<text text-anchor="middle" x="1342" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1206,-1352.5 1478,-1352.5 "/>
<text text-anchor="middle" x="1342" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1206,-1329.5 1478,-1329.5 "/>
<text text-anchor="middle" x="1342" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1206,-1306.5 1478,-1306.5 "/>
<text text-anchor="middle" x="1342" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1206,-1283.5 1478,-1283.5 "/>
<text text-anchor="middle" x="1342" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1206,-1260.5 1478,-1260.5 "/>
<text text-anchor="middle" x="1342" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1206,-1237.5 1478,-1237.5 "/>
<text text-anchor="middle" x="1342" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1206,-1214.5 1478,-1214.5 "/>
<text text-anchor="middle" x="1342" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1206,-1191.5 1478,-1191.5 "/>
<text text-anchor="middle" x="1342" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1206,-1168.5 1478,-1168.5 "/>
<text text-anchor="middle" x="1342" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1478,-1145.5 1478,-1651.5 "/>
<text text-anchor="middle" x="1488.5" y="-1394.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1100.9772,-1155.7353C1097.6442,-1152.1168 1094.3171,-1148.5361 1091,-1145 1077.1895,-1130.2776 1062.1866,-1115.2032 1047.1551,-1100.6193"/>
<polygon fill="#000000" stroke="#000000" points="1049.4058,-1097.9273 1039.7789,-1093.503 1044.5456,-1102.965 1049.4058,-1097.9273"/>
<text text-anchor="middle" x="1121.5" y="-1115.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
