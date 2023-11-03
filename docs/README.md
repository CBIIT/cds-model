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
<svg width="1232pt" height="2385pt"
 viewBox="0.00 0.00 1231.50 2385.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 2381)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-2381 1227.5,-2381 1227.5,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M12,-2135C12,-2135 277,-2135 277,-2135 283,-2135 289,-2141 289,-2147 289,-2147 289,-2238 289,-2238 289,-2244 283,-2250 277,-2250 277,-2250 12,-2250 12,-2250 6,-2250 0,-2244 0,-2238 0,-2238 0,-2147 0,-2147 0,-2141 6,-2135 12,-2135"/>
<text text-anchor="middle" x="44.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="89,-2135 89,-2250 "/>
<text text-anchor="middle" x="99.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="110,-2135 110,-2250 "/>
<text text-anchor="middle" x="189" y="-2234.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="110,-2227 268,-2227 "/>
<text text-anchor="middle" x="189" y="-2211.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="110,-2204 268,-2204 "/>
<text text-anchor="middle" x="189" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="110,-2181 268,-2181 "/>
<text text-anchor="middle" x="189" y="-2165.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="110,-2158 268,-2158 "/>
<text text-anchor="middle" x="189" y="-2142.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="268,-2135 268,-2250 "/>
<text text-anchor="middle" x="278.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M387.5,-213.5C387.5,-213.5 703.5,-213.5 703.5,-213.5 709.5,-213.5 715.5,-219.5 715.5,-225.5 715.5,-225.5 715.5,-1029.5 715.5,-1029.5 715.5,-1035.5 709.5,-1041.5 703.5,-1041.5 703.5,-1041.5 387.5,-1041.5 387.5,-1041.5 381.5,-1041.5 375.5,-1035.5 375.5,-1029.5 375.5,-1029.5 375.5,-225.5 375.5,-225.5 375.5,-219.5 381.5,-213.5 387.5,-213.5"/>
<text text-anchor="middle" x="403.5" y="-623.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="431.5,-213.5 431.5,-1041.5 "/>
<text text-anchor="middle" x="442" y="-623.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="452.5,-213.5 452.5,-1041.5 "/>
<text text-anchor="middle" x="573.5" y="-1026.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="452.5,-1018.5 694.5,-1018.5 "/>
<text text-anchor="middle" x="573.5" y="-1003.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="452.5,-995.5 694.5,-995.5 "/>
<text text-anchor="middle" x="573.5" y="-980.3" font-family="Times,serif" font-size="14.00" fill="#000000">authz</text>
<polyline fill="none" stroke="#000000" points="452.5,-972.5 694.5,-972.5 "/>
<text text-anchor="middle" x="573.5" y="-957.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_accession</text>
<polyline fill="none" stroke="#000000" points="452.5,-949.5 694.5,-949.5 "/>
<text text-anchor="middle" x="573.5" y="-934.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_primary_bucket</text>
<polyline fill="none" stroke="#000000" points="452.5,-926.5 694.5,-926.5 "/>
<text text-anchor="middle" x="573.5" y="-911.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="452.5,-903.5 694.5,-903.5 "/>
<text text-anchor="middle" x="573.5" y="-888.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_secondary_bucket</text>
<polyline fill="none" stroke="#000000" points="452.5,-880.5 694.5,-880.5 "/>
<text text-anchor="middle" x="573.5" y="-865.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_tertiary_bucket</text>
<polyline fill="none" stroke="#000000" points="452.5,-857.5 694.5,-857.5 "/>
<text text-anchor="middle" x="573.5" y="-842.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="452.5,-834.5 694.5,-834.5 "/>
<text text-anchor="middle" x="573.5" y="-819.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="452.5,-811.5 694.5,-811.5 "/>
<text text-anchor="middle" x="573.5" y="-796.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_system</text>
<polyline fill="none" stroke="#000000" points="452.5,-788.5 694.5,-788.5 "/>
<text text-anchor="middle" x="573.5" y="-773.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_email</text>
<polyline fill="none" stroke="#000000" points="452.5,-765.5 694.5,-765.5 "/>
<text text-anchor="middle" x="573.5" y="-750.3" font-family="Times,serif" font-size="14.00" fill="#000000">co_investigator_name</text>
<polyline fill="none" stroke="#000000" points="452.5,-742.5 694.5,-742.5 "/>
<text text-anchor="middle" x="573.5" y="-727.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="452.5,-719.5 694.5,-719.5 "/>
<text text-anchor="middle" x="573.5" y="-704.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="452.5,-696.5 694.5,-696.5 "/>
<text text-anchor="middle" x="573.5" y="-681.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="452.5,-673.5 694.5,-673.5 "/>
<text text-anchor="middle" x="573.5" y="-658.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="452.5,-650.5 694.5,-650.5 "/>
<text text-anchor="middle" x="573.5" y="-635.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="452.5,-627.5 694.5,-627.5 "/>
<text text-anchor="middle" x="573.5" y="-612.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="452.5,-604.5 694.5,-604.5 "/>
<text text-anchor="middle" x="573.5" y="-589.3" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="452.5,-581.5 694.5,-581.5 "/>
<text text-anchor="middle" x="573.5" y="-566.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="452.5,-558.5 694.5,-558.5 "/>
<text text-anchor="middle" x="573.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="452.5,-535.5 694.5,-535.5 "/>
<text text-anchor="middle" x="573.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="452.5,-512.5 694.5,-512.5 "/>
<text text-anchor="middle" x="573.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="452.5,-489.5 694.5,-489.5 "/>
<text text-anchor="middle" x="573.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="452.5,-466.5 694.5,-466.5 "/>
<text text-anchor="middle" x="573.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_email</text>
<polyline fill="none" stroke="#000000" points="452.5,-443.5 694.5,-443.5 "/>
<text text-anchor="middle" x="573.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_investigator_name</text>
<polyline fill="none" stroke="#000000" points="452.5,-420.5 694.5,-420.5 "/>
<text text-anchor="middle" x="573.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_description</text>
<polyline fill="none" stroke="#000000" points="452.5,-397.5 694.5,-397.5 "/>
<text text-anchor="middle" x="573.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="452.5,-374.5 694.5,-374.5 "/>
<text text-anchor="middle" x="573.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_access</text>
<polyline fill="none" stroke="#000000" points="452.5,-351.5 694.5,-351.5 "/>
<text text-anchor="middle" x="573.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="452.5,-328.5 694.5,-328.5 "/>
<text text-anchor="middle" x="573.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="452.5,-305.5 694.5,-305.5 "/>
<text text-anchor="middle" x="573.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="452.5,-282.5 694.5,-282.5 "/>
<text text-anchor="middle" x="573.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="452.5,-259.5 694.5,-259.5 "/>
<text text-anchor="middle" x="573.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="452.5,-236.5 694.5,-236.5 "/>
<text text-anchor="middle" x="573.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_version</text>
<polyline fill="none" stroke="#000000" points="694.5,-213.5 694.5,-1041.5 "/>
<text text-anchor="middle" x="705" y="-623.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node8" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M391.5,-.5C391.5,-.5 699.5,-.5 699.5,-.5 705.5,-.5 711.5,-6.5 711.5,-12.5 711.5,-12.5 711.5,-149.5 711.5,-149.5 711.5,-155.5 705.5,-161.5 699.5,-161.5 699.5,-161.5 391.5,-161.5 391.5,-161.5 385.5,-161.5 379.5,-155.5 379.5,-149.5 379.5,-149.5 379.5,-12.5 379.5,-12.5 379.5,-6.5 385.5,-.5 391.5,-.5"/>
<text text-anchor="middle" x="418.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="457.5,-.5 457.5,-161.5 "/>
<text text-anchor="middle" x="468" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="478.5,-.5 478.5,-161.5 "/>
<text text-anchor="middle" x="584.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="478.5,-138.5 690.5,-138.5 "/>
<text text-anchor="middle" x="584.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="478.5,-115.5 690.5,-115.5 "/>
<text text-anchor="middle" x="584.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="478.5,-92.5 690.5,-92.5 "/>
<text text-anchor="middle" x="584.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="478.5,-69.5 690.5,-69.5 "/>
<text text-anchor="middle" x="584.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="478.5,-46.5 690.5,-46.5 "/>
<text text-anchor="middle" x="584.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="478.5,-23.5 690.5,-23.5 "/>
<text text-anchor="middle" x="584.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="690.5,-.5 690.5,-161.5 "/>
<text text-anchor="middle" x="701" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge5" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M545.5,-213.2924C545.5,-198.6089 545.5,-184.6733 545.5,-171.7422"/>
<polygon fill="#000000" stroke="#000000" points="549.0001,-171.592 545.5,-161.592 542.0001,-171.5921 549.0001,-171.592"/>
<text text-anchor="middle" x="587" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_program</text>
</g>
<!-- genomic_info -->
<g id="node3" class="node">
<title>genomic_info</title>
<path fill="none" stroke="#000000" d="M319,-2008.5C319,-2008.5 772,-2008.5 772,-2008.5 778,-2008.5 784,-2014.5 784,-2020.5 784,-2020.5 784,-2364.5 784,-2364.5 784,-2370.5 778,-2376.5 772,-2376.5 772,-2376.5 319,-2376.5 319,-2376.5 313,-2376.5 307,-2370.5 307,-2364.5 307,-2364.5 307,-2020.5 307,-2020.5 307,-2014.5 313,-2008.5 319,-2008.5"/>
<text text-anchor="middle" x="363" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info</text>
<polyline fill="none" stroke="#000000" points="419,-2008.5 419,-2376.5 "/>
<text text-anchor="middle" x="429.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="440,-2008.5 440,-2376.5 "/>
<text text-anchor="middle" x="601.5" y="-2361.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="440,-2353.5 763,-2353.5 "/>
<text text-anchor="middle" x="601.5" y="-2338.3" font-family="Times,serif" font-size="14.00" fill="#000000">bases</text>
<polyline fill="none" stroke="#000000" points="440,-2330.5 763,-2330.5 "/>
<text text-anchor="middle" x="601.5" y="-2315.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="440,-2307.5 763,-2307.5 "/>
<text text-anchor="middle" x="601.5" y="-2292.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="440,-2284.5 763,-2284.5 "/>
<text text-anchor="middle" x="601.5" y="-2269.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="440,-2261.5 763,-2261.5 "/>
<text text-anchor="middle" x="601.5" y="-2246.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_info_id</text>
<polyline fill="none" stroke="#000000" points="440,-2238.5 763,-2238.5 "/>
<text text-anchor="middle" x="601.5" y="-2223.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="440,-2215.5 763,-2215.5 "/>
<text text-anchor="middle" x="601.5" y="-2200.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="440,-2192.5 763,-2192.5 "/>
<text text-anchor="middle" x="601.5" y="-2177.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="440,-2169.5 763,-2169.5 "/>
<text text-anchor="middle" x="601.5" y="-2154.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="440,-2146.5 763,-2146.5 "/>
<text text-anchor="middle" x="601.5" y="-2131.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="440,-2123.5 763,-2123.5 "/>
<text text-anchor="middle" x="601.5" y="-2108.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="440,-2100.5 763,-2100.5 "/>
<text text-anchor="middle" x="601.5" y="-2085.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="440,-2077.5 763,-2077.5 "/>
<text text-anchor="middle" x="601.5" y="-2062.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="440,-2054.5 763,-2054.5 "/>
<text text-anchor="middle" x="601.5" y="-2039.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="440,-2031.5 763,-2031.5 "/>
<text text-anchor="middle" x="601.5" y="-2016.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="763,-2008.5 763,-2376.5 "/>
<text text-anchor="middle" x="773.5" y="-2188.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node6" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M355.5,-1749.5C355.5,-1749.5 735.5,-1749.5 735.5,-1749.5 741.5,-1749.5 747.5,-1755.5 747.5,-1761.5 747.5,-1761.5 747.5,-1944.5 747.5,-1944.5 747.5,-1950.5 741.5,-1956.5 735.5,-1956.5 735.5,-1956.5 355.5,-1956.5 355.5,-1956.5 349.5,-1956.5 343.5,-1950.5 343.5,-1944.5 343.5,-1944.5 343.5,-1761.5 343.5,-1761.5 343.5,-1755.5 349.5,-1749.5 355.5,-1749.5"/>
<text text-anchor="middle" x="363" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="382.5,-1749.5 382.5,-1956.5 "/>
<text text-anchor="middle" x="393" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="403.5,-1749.5 403.5,-1956.5 "/>
<text text-anchor="middle" x="565" y="-1941.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtypes</text>
<polyline fill="none" stroke="#000000" points="403.5,-1933.5 726.5,-1933.5 "/>
<text text-anchor="middle" x="565" y="-1918.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="403.5,-1910.5 726.5,-1910.5 "/>
<text text-anchor="middle" x="565" y="-1895.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_id</text>
<polyline fill="none" stroke="#000000" points="403.5,-1887.5 726.5,-1887.5 "/>
<text text-anchor="middle" x="565" y="-1872.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="403.5,-1864.5 726.5,-1864.5 "/>
<text text-anchor="middle" x="565" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="403.5,-1841.5 726.5,-1841.5 "/>
<text text-anchor="middle" x="565" y="-1826.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="403.5,-1818.5 726.5,-1818.5 "/>
<text text-anchor="middle" x="565" y="-1803.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="403.5,-1795.5 726.5,-1795.5 "/>
<text text-anchor="middle" x="565" y="-1780.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="403.5,-1772.5 726.5,-1772.5 "/>
<text text-anchor="middle" x="565" y="-1757.3" font-family="Times,serif" font-size="14.00" fill="#000000">submission_version</text>
<polyline fill="none" stroke="#000000" points="726.5,-1749.5 726.5,-1956.5 "/>
<text text-anchor="middle" x="737" y="-1849.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_info&#45;&gt;file -->
<g id="edge2" class="edge">
<title>genomic_info&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M545.5,-2008.3433C545.5,-1994.3068 545.5,-1980.4026 545.5,-1967.0183"/>
<polygon fill="#000000" stroke="#000000" points="549.0001,-1966.891 545.5,-1956.891 542.0001,-1966.8911 549.0001,-1966.891"/>
<text text-anchor="middle" x="567.5" y="-1978.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M573.5,-1093.5C573.5,-1093.5 851.5,-1093.5 851.5,-1093.5 857.5,-1093.5 863.5,-1099.5 863.5,-1105.5 863.5,-1105.5 863.5,-1219.5 863.5,-1219.5 863.5,-1225.5 857.5,-1231.5 851.5,-1231.5 851.5,-1231.5 573.5,-1231.5 573.5,-1231.5 567.5,-1231.5 561.5,-1225.5 561.5,-1219.5 561.5,-1219.5 561.5,-1105.5 561.5,-1105.5 561.5,-1099.5 567.5,-1093.5 573.5,-1093.5"/>
<text text-anchor="middle" x="609.5" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="657.5,-1093.5 657.5,-1231.5 "/>
<text text-anchor="middle" x="668" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="678.5,-1093.5 678.5,-1231.5 "/>
<text text-anchor="middle" x="760.5" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbGaP_subject_id</text>
<polyline fill="none" stroke="#000000" points="678.5,-1208.5 842.5,-1208.5 "/>
<text text-anchor="middle" x="760.5" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="678.5,-1185.5 842.5,-1185.5 "/>
<text text-anchor="middle" x="760.5" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="678.5,-1162.5 842.5,-1162.5 "/>
<text text-anchor="middle" x="760.5" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="678.5,-1139.5 842.5,-1139.5 "/>
<text text-anchor="middle" x="760.5" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="678.5,-1116.5 842.5,-1116.5 "/>
<text text-anchor="middle" x="760.5" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_participant_id</text>
<polyline fill="none" stroke="#000000" points="842.5,-1093.5 842.5,-1231.5 "/>
<text text-anchor="middle" x="853" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M690.9243,-1093.3802C686.9265,-1080.5728 682.4963,-1066.3804 677.7417,-1051.1487"/>
<polygon fill="#000000" stroke="#000000" points="681.0612,-1050.0363 674.7404,-1041.5335 674.3791,-1052.1222 681.0612,-1050.0363"/>
<text text-anchor="middle" x="715" y="-1063.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M569.5,-1410C569.5,-1410 855.5,-1410 855.5,-1410 861.5,-1410 867.5,-1416 867.5,-1422 867.5,-1422 867.5,-1559 867.5,-1559 867.5,-1565 861.5,-1571 855.5,-1571 855.5,-1571 569.5,-1571 569.5,-1571 563.5,-1571 557.5,-1565 557.5,-1559 557.5,-1559 557.5,-1422 557.5,-1422 557.5,-1416 563.5,-1410 569.5,-1410"/>
<text text-anchor="middle" x="591.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="625.5,-1410 625.5,-1571 "/>
<text text-anchor="middle" x="636" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="646.5,-1410 646.5,-1571 "/>
<text text-anchor="middle" x="746.5" y="-1555.8" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="646.5,-1548 846.5,-1548 "/>
<text text-anchor="middle" x="746.5" y="-1532.8" font-family="Times,serif" font-size="14.00" fill="#000000">derived_from_specimen</text>
<polyline fill="none" stroke="#000000" points="646.5,-1525 846.5,-1525 "/>
<text text-anchor="middle" x="746.5" y="-1509.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="646.5,-1502 846.5,-1502 "/>
<text text-anchor="middle" x="746.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="646.5,-1479 846.5,-1479 "/>
<text text-anchor="middle" x="746.5" y="-1463.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="646.5,-1456 846.5,-1456 "/>
<text text-anchor="middle" x="746.5" y="-1440.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="646.5,-1433 846.5,-1433 "/>
<text text-anchor="middle" x="746.5" y="-1417.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="846.5,-1410 846.5,-1571 "/>
<text text-anchor="middle" x="857" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M712.5,-1409.8421C712.5,-1358.7344 712.5,-1292.9196 712.5,-1242.0303"/>
<polygon fill="#000000" stroke="#000000" points="716.0001,-1241.7346 712.5,-1231.7347 709.0001,-1241.7347 716.0001,-1241.7346"/>
<text text-anchor="middle" x="763" y="-1253.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M545.5,-1749.3071C545.5,-1596.2974 545.5,-1301.2385 545.5,-1052.1217"/>
<polygon fill="#000000" stroke="#000000" points="549.0001,-1051.7893 545.5,-1041.7893 542.0001,-1051.7894 549.0001,-1051.7893"/>
<text text-anchor="middle" x="576" y="-1253.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M593.3555,-1749.122C617.8995,-1695.8454 647.5018,-1631.5889 671.0593,-1580.4537"/>
<polygon fill="#000000" stroke="#000000" points="674.3797,-1581.6109 675.385,-1571.0639 668.0219,-1578.6819 674.3797,-1581.6109"/>
<text text-anchor="middle" x="650" y="-1719.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M897.5,-1283.5C897.5,-1283.5 1211.5,-1283.5 1211.5,-1283.5 1217.5,-1283.5 1223.5,-1289.5 1223.5,-1295.5 1223.5,-1295.5 1223.5,-1685.5 1223.5,-1685.5 1223.5,-1691.5 1217.5,-1697.5 1211.5,-1697.5 1211.5,-1697.5 897.5,-1697.5 897.5,-1697.5 891.5,-1697.5 885.5,-1691.5 885.5,-1685.5 885.5,-1685.5 885.5,-1295.5 885.5,-1295.5 885.5,-1289.5 891.5,-1283.5 897.5,-1283.5"/>
<text text-anchor="middle" x="927.5" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="969.5,-1283.5 969.5,-1697.5 "/>
<text text-anchor="middle" x="980" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="990.5,-1283.5 990.5,-1697.5 "/>
<text text-anchor="middle" x="1096.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="990.5,-1674.5 1202.5,-1674.5 "/>
<text text-anchor="middle" x="1096.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="990.5,-1651.5 1202.5,-1651.5 "/>
<text text-anchor="middle" x="1096.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="990.5,-1628.5 1202.5,-1628.5 "/>
<text text-anchor="middle" x="1096.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="990.5,-1605.5 1202.5,-1605.5 "/>
<text text-anchor="middle" x="1096.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="990.5,-1582.5 1202.5,-1582.5 "/>
<text text-anchor="middle" x="1096.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_type</text>
<polyline fill="none" stroke="#000000" points="990.5,-1559.5 1202.5,-1559.5 "/>
<text text-anchor="middle" x="1096.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="990.5,-1536.5 1202.5,-1536.5 "/>
<text text-anchor="middle" x="1096.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="990.5,-1513.5 1202.5,-1513.5 "/>
<text text-anchor="middle" x="1096.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">morphology</text>
<polyline fill="none" stroke="#000000" points="990.5,-1490.5 1202.5,-1490.5 "/>
<text text-anchor="middle" x="1096.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="990.5,-1467.5 1202.5,-1467.5 "/>
<text text-anchor="middle" x="1096.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="990.5,-1444.5 1202.5,-1444.5 "/>
<text text-anchor="middle" x="1096.5" y="-1429.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="990.5,-1421.5 1202.5,-1421.5 "/>
<text text-anchor="middle" x="1096.5" y="-1406.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="990.5,-1398.5 1202.5,-1398.5 "/>
<text text-anchor="middle" x="1096.5" y="-1383.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="990.5,-1375.5 1202.5,-1375.5 "/>
<text text-anchor="middle" x="1096.5" y="-1360.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="990.5,-1352.5 1202.5,-1352.5 "/>
<text text-anchor="middle" x="1096.5" y="-1337.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="990.5,-1329.5 1202.5,-1329.5 "/>
<text text-anchor="middle" x="1096.5" y="-1314.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="990.5,-1306.5 1202.5,-1306.5 "/>
<text text-anchor="middle" x="1096.5" y="-1291.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="1202.5,-1283.5 1202.5,-1697.5 "/>
<text text-anchor="middle" x="1213" y="-1486.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M885.3706,-1291.3634C882.4161,-1288.5331 879.4581,-1285.7432 876.5,-1283 859.7256,-1267.4442 840.945,-1252.0486 822.2462,-1237.7274"/>
<polygon fill="#000000" stroke="#000000" points="824.3263,-1234.9122 814.2435,-1231.6582 820.0964,-1240.4897 824.3263,-1234.9122"/>
<text text-anchor="middle" x="906" y="-1253.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
