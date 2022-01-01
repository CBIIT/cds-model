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
<svg width="1187pt" height="1327pt"
 viewBox="0.00 0.00 1186.50 1327.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1323)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1323 1182.5,-1323 1182.5,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-449.5C12,-449.5 326,-449.5 326,-449.5 332,-449.5 338,-455.5 338,-461.5 338,-461.5 338,-667.5 338,-667.5 338,-673.5 332,-679.5 326,-679.5 326,-679.5 12,-679.5 12,-679.5 6,-679.5 0,-673.5 0,-667.5 0,-667.5 0,-461.5 0,-461.5 0,-455.5 6,-449.5 12,-449.5"/>
<text text-anchor="middle" x="42" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-449.5 84,-679.5 "/>
<text text-anchor="middle" x="94.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-449.5 105,-679.5 "/>
<text text-anchor="middle" x="211" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-656.5 317,-656.5 "/>
<text text-anchor="middle" x="211" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_status</text>
<polyline fill="none" stroke="#000000" points="105,-633.5 317,-633.5 "/>
<text text-anchor="middle" x="211" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="105,-610.5 317,-610.5 "/>
<text text-anchor="middle" x="211" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">incidence_type</text>
<polyline fill="none" stroke="#000000" points="105,-587.5 317,-587.5 "/>
<text text-anchor="middle" x="211" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="105,-564.5 317,-564.5 "/>
<text text-anchor="middle" x="211" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-541.5 317,-541.5 "/>
<text text-anchor="middle" x="211" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="105,-518.5 317,-518.5 "/>
<text text-anchor="middle" x="211" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-495.5 317,-495.5 "/>
<text text-anchor="middle" x="211" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="105,-472.5 317,-472.5 "/>
<text text-anchor="middle" x="211" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage</text>
<polyline fill="none" stroke="#000000" points="317,-449.5 317,-679.5 "/>
<text text-anchor="middle" x="327.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_subject -->
<g id="node4" class="node">
<title>study_subject</title>
<path fill="none" stroke="#000000" d="M619,-236.5C619,-236.5 853,-236.5 853,-236.5 859,-236.5 865,-242.5 865,-248.5 865,-248.5 865,-339.5 865,-339.5 865,-345.5 859,-351.5 853,-351.5 853,-351.5 619,-351.5 619,-351.5 613,-351.5 607,-345.5 607,-339.5 607,-339.5 607,-248.5 607,-248.5 607,-242.5 613,-236.5 619,-236.5"/>
<text text-anchor="middle" x="665" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_subject</text>
<polyline fill="none" stroke="#000000" points="723,-236.5 723,-351.5 "/>
<text text-anchor="middle" x="733.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="744,-236.5 744,-351.5 "/>
<text text-anchor="middle" x="794" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="744,-328.5 844,-328.5 "/>
<text text-anchor="middle" x="794" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="744,-305.5 844,-305.5 "/>
<text text-anchor="middle" x="794" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="744,-282.5 844,-282.5 "/>
<text text-anchor="middle" x="794" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">subject_id</text>
<polyline fill="none" stroke="#000000" points="744,-259.5 844,-259.5 "/>
<text text-anchor="middle" x="794" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="844,-236.5 844,-351.5 "/>
<text text-anchor="middle" x="854.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;study_subject -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M307.329,-449.4081C320.0527,-440.9457 333.0396,-432.9991 346,-426 425.0141,-383.3292 520.3973,-350.7504 597.0561,-328.6345"/>
<polygon fill="#000000" stroke="#000000" points="598.133,-331.9669 606.7867,-325.8542 596.2099,-325.2362 598.133,-331.9669"/>
<text text-anchor="middle" x="467.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M771.5,-.5C771.5,-.5 996.5,-.5 996.5,-.5 1002.5,-.5 1008.5,-6.5 1008.5,-12.5 1008.5,-12.5 1008.5,-149.5 1008.5,-149.5 1008.5,-155.5 1002.5,-161.5 996.5,-161.5 996.5,-161.5 771.5,-161.5 771.5,-161.5 765.5,-161.5 759.5,-155.5 759.5,-149.5 759.5,-149.5 759.5,-12.5 759.5,-12.5 759.5,-6.5 765.5,-.5 771.5,-.5"/>
<text text-anchor="middle" x="787.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="815.5,-.5 815.5,-161.5 "/>
<text text-anchor="middle" x="826" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="836.5,-.5 836.5,-161.5 "/>
<text text-anchor="middle" x="912" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">bioproject_id</text>
<polyline fill="none" stroke="#000000" points="836.5,-138.5 987.5,-138.5 "/>
<text text-anchor="middle" x="912" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">index_date</text>
<polyline fill="none" stroke="#000000" points="836.5,-115.5 987.5,-115.5 "/>
<text text-anchor="middle" x="912" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="836.5,-92.5 987.5,-92.5 "/>
<text text-anchor="middle" x="912" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="836.5,-69.5 987.5,-69.5 "/>
<text text-anchor="middle" x="912" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="836.5,-46.5 987.5,-46.5 "/>
<text text-anchor="middle" x="912" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_external_url</text>
<polyline fill="none" stroke="#000000" points="836.5,-23.5 987.5,-23.5 "/>
<text text-anchor="middle" x="912" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_title</text>
<polyline fill="none" stroke="#000000" points="987.5,-.5 987.5,-161.5 "/>
<text text-anchor="middle" x="998" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node3" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M377.5,-944.5C377.5,-944.5 598.5,-944.5 598.5,-944.5 604.5,-944.5 610.5,-950.5 610.5,-956.5 610.5,-956.5 610.5,-1139.5 610.5,-1139.5 610.5,-1145.5 604.5,-1151.5 598.5,-1151.5 598.5,-1151.5 377.5,-1151.5 377.5,-1151.5 371.5,-1151.5 365.5,-1145.5 365.5,-1139.5 365.5,-1139.5 365.5,-956.5 365.5,-956.5 365.5,-950.5 371.5,-944.5 377.5,-944.5"/>
<text text-anchor="middle" x="385" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="404.5,-944.5 404.5,-1151.5 "/>
<text text-anchor="middle" x="415" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="425.5,-944.5 425.5,-1151.5 "/>
<text text-anchor="middle" x="507.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">drs_url</text>
<polyline fill="none" stroke="#000000" points="425.5,-1128.5 589.5,-1128.5 "/>
<text text-anchor="middle" x="507.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="425.5,-1105.5 589.5,-1105.5 "/>
<text text-anchor="middle" x="507.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="425.5,-1082.5 589.5,-1082.5 "/>
<text text-anchor="middle" x="507.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="425.5,-1059.5 589.5,-1059.5 "/>
<text text-anchor="middle" x="507.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="425.5,-1036.5 589.5,-1036.5 "/>
<text text-anchor="middle" x="507.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">internal_url</text>
<polyline fill="none" stroke="#000000" points="425.5,-1013.5 589.5,-1013.5 "/>
<text text-anchor="middle" x="507.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="425.5,-990.5 589.5,-990.5 "/>
<text text-anchor="middle" x="507.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">sra_run_accession</text>
<polyline fill="none" stroke="#000000" points="425.5,-967.5 589.5,-967.5 "/>
<text text-anchor="middle" x="507.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">sra_study_accession</text>
<polyline fill="none" stroke="#000000" points="589.5,-944.5 589.5,-1151.5 "/>
<text text-anchor="middle" x="600" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- submission -->
<g id="node5" class="node">
<title>submission</title>
<path fill="none" stroke="#000000" d="M367.5,-426.5C367.5,-426.5 688.5,-426.5 688.5,-426.5 694.5,-426.5 700.5,-432.5 700.5,-438.5 700.5,-438.5 700.5,-690.5 700.5,-690.5 700.5,-696.5 694.5,-702.5 688.5,-702.5 688.5,-702.5 367.5,-702.5 367.5,-702.5 361.5,-702.5 355.5,-696.5 355.5,-690.5 355.5,-690.5 355.5,-438.5 355.5,-438.5 355.5,-432.5 361.5,-426.5 367.5,-426.5"/>
<text text-anchor="middle" x="404" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">submission</text>
<polyline fill="none" stroke="#000000" points="452.5,-426.5 452.5,-702.5 "/>
<text text-anchor="middle" x="463" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="473.5,-426.5 473.5,-702.5 "/>
<text text-anchor="middle" x="576.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="473.5,-679.5 679.5,-679.5 "/>
<text text-anchor="middle" x="576.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="473.5,-656.5 679.5,-656.5 "/>
<text text-anchor="middle" x="576.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">image_series_id</text>
<polyline fill="none" stroke="#000000" points="473.5,-633.5 679.5,-633.5 "/>
<text text-anchor="middle" x="576.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="473.5,-610.5 679.5,-610.5 "/>
<text text-anchor="middle" x="576.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="473.5,-587.5 679.5,-587.5 "/>
<text text-anchor="middle" x="576.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="473.5,-564.5 679.5,-564.5 "/>
<text text-anchor="middle" x="576.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="473.5,-541.5 679.5,-541.5 "/>
<text text-anchor="middle" x="576.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="473.5,-518.5 679.5,-518.5 "/>
<text text-anchor="middle" x="576.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="473.5,-495.5 679.5,-495.5 "/>
<text text-anchor="middle" x="576.5" y="-480.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="473.5,-472.5 679.5,-472.5 "/>
<text text-anchor="middle" x="576.5" y="-457.3" font-family="Times,serif" font-size="14.00" fill="#000000">software_packages</text>
<polyline fill="none" stroke="#000000" points="473.5,-449.5 679.5,-449.5 "/>
<text text-anchor="middle" x="576.5" y="-434.3" font-family="Times,serif" font-size="14.00" fill="#000000">sra_experiment_accession</text>
<polyline fill="none" stroke="#000000" points="679.5,-426.5 679.5,-702.5 "/>
<text text-anchor="middle" x="690" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;submission -->
<g id="edge1" class="edge">
<title>file&#45;&gt;submission</title>
<path fill="none" stroke="#000000" d="M482.6652,-944.2195C481.972,-927.1121 481.3738,-909.5621 481,-893 479.6061,-831.2379 473.5089,-815.3219 481,-754 482.6454,-740.5304 484.9256,-726.6395 487.6018,-712.7883"/>
<polygon fill="#000000" stroke="#000000" points="491.087,-713.2084 489.617,-702.7161 484.2231,-711.835 491.087,-713.2084"/>
<text text-anchor="middle" x="542" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_submission</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M624.5,-754.5C624.5,-754.5 885.5,-754.5 885.5,-754.5 891.5,-754.5 897.5,-760.5 897.5,-766.5 897.5,-766.5 897.5,-880.5 897.5,-880.5 897.5,-886.5 891.5,-892.5 885.5,-892.5 885.5,-892.5 624.5,-892.5 624.5,-892.5 618.5,-892.5 612.5,-886.5 612.5,-880.5 612.5,-880.5 612.5,-766.5 612.5,-766.5 612.5,-760.5 618.5,-754.5 624.5,-754.5"/>
<text text-anchor="middle" x="646.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="680.5,-754.5 680.5,-892.5 "/>
<text text-anchor="middle" x="691" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="701.5,-754.5 701.5,-892.5 "/>
<text text-anchor="middle" x="789" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">biosample_accession</text>
<polyline fill="none" stroke="#000000" points="701.5,-869.5 876.5,-869.5 "/>
<text text-anchor="middle" x="789" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_collection</text>
<polyline fill="none" stroke="#000000" points="701.5,-846.5 876.5,-846.5 "/>
<text text-anchor="middle" x="789" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="701.5,-823.5 876.5,-823.5 "/>
<text text-anchor="middle" x="789" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="701.5,-800.5 876.5,-800.5 "/>
<text text-anchor="middle" x="789" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="701.5,-777.5 876.5,-777.5 "/>
<text text-anchor="middle" x="789" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="876.5,-754.5 876.5,-892.5 "/>
<text text-anchor="middle" x="887" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M610.5597,-944.9488C628.8676,-929.5551 647.4518,-913.9291 664.9225,-899.2393"/>
<polygon fill="#000000" stroke="#000000" points="667.4647,-901.6746 672.8662,-892.56 662.9598,-896.3168 667.4647,-901.6746"/>
<text text-anchor="middle" x="692.5" y="-914.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_sample</text>
</g>
<!-- study_subject&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_subject&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M776.0509,-236.3591C790.1701,-216.039 806.3944,-192.6892 821.9025,-170.3701"/>
<polygon fill="#000000" stroke="#000000" points="824.9733,-172.0843 827.8052,-161.875 819.2247,-168.09 824.9733,-172.0843"/>
<text text-anchor="middle" x="845.5" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- sample&#45;&gt;study_subject -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M748.5407,-754.4111C747.1697,-737.6015 745.8741,-719.6658 745,-703 738.7036,-582.949 736.7989,-442.8522 736.231,-361.6977"/>
<polygon fill="#000000" stroke="#000000" points="739.7305,-361.5913 736.1652,-351.6144 732.7306,-361.6371 739.7305,-361.5913"/>
<text text-anchor="middle" x="805.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
<!-- sample&#45;&gt;submission -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;submission</title>
<path fill="none" stroke="#000000" d="M639.0488,-754.3009C632.2874,-748.4806 625.864,-742.3702 620,-736 612.8167,-728.1967 606.0117,-719.7284 599.6004,-710.8756"/>
<polygon fill="#000000" stroke="#000000" points="602.4334,-708.8196 593.8234,-702.6455 596.7039,-712.8412 602.4334,-708.8196"/>
<text text-anchor="middle" x="671" y="-724.8" font-family="Times,serif" font-size="14.00" fill="#000000">in_submission</text>
</g>
<!-- specimen -->
<g id="node10" class="node">
<title>specimen</title>
<path fill="none" stroke="#000000" d="M887.5,-546.5C887.5,-546.5 1096.5,-546.5 1096.5,-546.5 1102.5,-546.5 1108.5,-552.5 1108.5,-558.5 1108.5,-558.5 1108.5,-570.5 1108.5,-570.5 1108.5,-576.5 1102.5,-582.5 1096.5,-582.5 1096.5,-582.5 887.5,-582.5 887.5,-582.5 881.5,-582.5 875.5,-576.5 875.5,-570.5 875.5,-570.5 875.5,-558.5 875.5,-558.5 875.5,-552.5 881.5,-546.5 887.5,-546.5"/>
<text text-anchor="middle" x="918" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="960.5,-546.5 960.5,-582.5 "/>
<text text-anchor="middle" x="971" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="981.5,-546.5 981.5,-582.5 "/>
<text text-anchor="middle" x="1034.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen_id</text>
<polyline fill="none" stroke="#000000" points="1087.5,-546.5 1087.5,-582.5 "/>
<text text-anchor="middle" x="1098" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;specimen -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;specimen</title>
<path fill="none" stroke="#000000" d="M818.2003,-754.433C867.7435,-700.2908 933.9108,-627.9814 968.5694,-590.1056"/>
<polygon fill="#000000" stroke="#000000" points="971.3009,-592.3051 975.4696,-582.5649 966.1366,-587.5796 971.3009,-592.3051"/>
<text text-anchor="middle" x="891" y="-724.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_specimen</text>
</g>
<!-- therapeutic_procedure -->
<g id="node7" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M729.5,-1226.5C729.5,-1226.5 1086.5,-1226.5 1086.5,-1226.5 1092.5,-1226.5 1098.5,-1232.5 1098.5,-1238.5 1098.5,-1238.5 1098.5,-1283.5 1098.5,-1283.5 1098.5,-1289.5 1092.5,-1295.5 1086.5,-1295.5 1086.5,-1295.5 729.5,-1295.5 729.5,-1295.5 723.5,-1295.5 717.5,-1289.5 717.5,-1283.5 717.5,-1283.5 717.5,-1238.5 717.5,-1238.5 717.5,-1232.5 723.5,-1226.5 729.5,-1226.5"/>
<text text-anchor="middle" x="808" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="898.5,-1226.5 898.5,-1295.5 "/>
<text text-anchor="middle" x="909" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="919.5,-1226.5 919.5,-1295.5 "/>
<text text-anchor="middle" x="998.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="919.5,-1272.5 1077.5,-1272.5 "/>
<text text-anchor="middle" x="998.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="919.5,-1249.5 1077.5,-1249.5 "/>
<text text-anchor="middle" x="998.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1077.5,-1226.5 1077.5,-1295.5 "/>
<text text-anchor="middle" x="1088" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_details -->
<g id="node8" class="node">
<title>genomic_details</title>
<path fill="none" stroke="#000000" d="M288,-1203.5C288,-1203.5 688,-1203.5 688,-1203.5 694,-1203.5 700,-1209.5 700,-1215.5 700,-1215.5 700,-1306.5 700,-1306.5 700,-1312.5 694,-1318.5 688,-1318.5 688,-1318.5 288,-1318.5 288,-1318.5 282,-1318.5 276,-1312.5 276,-1306.5 276,-1306.5 276,-1215.5 276,-1215.5 276,-1209.5 282,-1203.5 288,-1203.5"/>
<text text-anchor="middle" x="342.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_details</text>
<polyline fill="none" stroke="#000000" points="409,-1203.5 409,-1318.5 "/>
<text text-anchor="middle" x="419.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="430,-1203.5 430,-1318.5 "/>
<text text-anchor="middle" x="554.5" y="-1303.3" font-family="Times,serif" font-size="14.00" fill="#000000">average_read_length</text>
<polyline fill="none" stroke="#000000" points="430,-1295.5 679,-1295.5 "/>
<text text-anchor="middle" x="554.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="430,-1272.5 679,-1272.5 "/>
<text text-anchor="middle" x="554.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference_or_accession</text>
<polyline fill="none" stroke="#000000" points="430,-1249.5 679,-1249.5 "/>
<text text-anchor="middle" x="554.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="430,-1226.5 679,-1226.5 "/>
<text text-anchor="middle" x="554.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="679,-1203.5 679,-1318.5 "/>
<text text-anchor="middle" x="689.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_details&#45;&gt;file -->
<g id="edge10" class="edge">
<title>genomic_details&#45;&gt;file</title>
<path fill="none" stroke="#000000" d="M488,-1203.3591C488,-1190.3456 488,-1176.0895 488,-1161.6573"/>
<polygon fill="#000000" stroke="#000000" points="491.5001,-1161.6507 488,-1151.6508 484.5001,-1161.6508 491.5001,-1161.6507"/>
<text text-anchor="middle" x="510" y="-1173.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_file</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M895.5,-213.5C895.5,-213.5 1166.5,-213.5 1166.5,-213.5 1172.5,-213.5 1178.5,-219.5 1178.5,-225.5 1178.5,-225.5 1178.5,-362.5 1178.5,-362.5 1178.5,-368.5 1172.5,-374.5 1166.5,-374.5 1166.5,-374.5 895.5,-374.5 895.5,-374.5 889.5,-374.5 883.5,-368.5 883.5,-362.5 883.5,-362.5 883.5,-225.5 883.5,-225.5 883.5,-219.5 889.5,-213.5 895.5,-213.5"/>
<text text-anchor="middle" x="937.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="991.5,-213.5 991.5,-374.5 "/>
<text text-anchor="middle" x="1002" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1012.5,-213.5 1012.5,-374.5 "/>
<text text-anchor="middle" x="1085" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_requestor</text>
<polyline fill="none" stroke="#000000" points="1012.5,-351.5 1157.5,-351.5 "/>
<text text-anchor="middle" x="1085" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_access_level</text>
<polyline fill="none" stroke="#000000" points="1012.5,-328.5 1157.5,-328.5 "/>
<text text-anchor="middle" x="1085" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="1012.5,-305.5 1157.5,-305.5 "/>
<text text-anchor="middle" x="1085" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types</text>
<polyline fill="none" stroke="#000000" points="1012.5,-282.5 1157.5,-282.5 "/>
<text text-anchor="middle" x="1085" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="1012.5,-259.5 1157.5,-259.5 "/>
<text text-anchor="middle" x="1085" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">species</text>
<polyline fill="none" stroke="#000000" points="1012.5,-236.5 1157.5,-236.5 "/>
<text text-anchor="middle" x="1085" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_type</text>
<polyline fill="none" stroke="#000000" points="1157.5,-213.5 1157.5,-374.5 "/>
<text text-anchor="middle" x="1168" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M975.4256,-213.4738C965.6386,-199.2927 955.4,-184.4571 945.4631,-170.0588"/>
<polygon fill="#000000" stroke="#000000" points="948.2137,-167.8823 939.653,-161.64 942.4525,-171.8583 948.2137,-167.8823"/>
<text text-anchor="middle" x="992.5" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- specimen&#45;&gt;study_subject -->
<g id="edge3" class="edge">
<title>specimen&#45;&gt;study_subject</title>
<path fill="none" stroke="#000000" d="M974.6274,-546.1259C949.5441,-519.5981 901.7228,-469.0288 861,-426 840.4291,-404.2643 817.948,-380.5209 797.7939,-359.2391"/>
<polygon fill="#000000" stroke="#000000" points="800.1866,-356.6755 790.7692,-351.8214 795.1041,-361.4889 800.1866,-356.6755"/>
<text text-anchor="middle" x="901.5" y="-396.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_subject</text>
</g>
</g>
</svg>
</div>
