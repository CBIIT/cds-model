### The Graph-Based Data Model

The GC data model is graph-based, where nodes correspond functionally to tables in a traditional relational database. Each node contains properties that represent columns or fields in the respective table, with relationships stored at the level of individual records. This flexible data model is developed to accommodate genomic and imaging cancer data submitted to GC, enabling the exploration of biological questions in basic cancer research. Nodes are designed to capture specific information relevant to each study and data type, recognizing variations between submissions.

### Node Categories

All nodes are categorized into several groups, each representing a family of interconnected nodes that collectively define higher-level entities within the data model. For example, the **Participant** category encompasses a small set of nodes that comprehensively describe GC study participants/subjects. The **Study** category includes nodes that collectively define various aspects of studies. Meanwhile, the **Sequencing** category contains nodes where genomic experimental observations related to various cancer conditions can be represented

### Assignment: Core nodes versus Extended nodes

GC is data type agnostic, and within its data model, there are nodes that are consistently or frequently populated with data, irrespective of the study type. These nodes, positioned at the core of the data model, are classified as 'Core' nodes. Surrounding the core is the extended data model, which includes numerous nodes that currently have lower data density. This division aims to guide users, especially data submitters, towards focusing on the nodes and properties crucial for defining any study, regardless of its specific nature.

### Class: Required nodes versus Optional nodes

Within the core data model and its extended counterpart, certain nodes are more crucial and therefore more densely populated. These nodes include fields designated as 'Required,' distinguishing them from less populated nodes with 'Optional' fields. Core nodes are essential components that form the backbone of any study, containing numerous required properties. It's important to note that each node contains both required and optional fields. Optional fields may contain valuable accessory data relevant to some studies but not necessarily all.

<!-- PAGE BREAK -->

### Facet-Based Filtering

The facet-based filtering options available in the left-hand sidebar of the Data Model Navigator allow users to filter nodes based on several criteria: Category, Assignment, and Class designations; properties marked as Required, or Optional; and properties displayed in the application’s user interface (UI). Using these filtering criteria, users can efficiently segment the data model into smaller sets of nodes and identify nodes of specific interest. It's important to note that these filters apply to both the Graph View and the Table View, and selected filters remain active when switching between these viewing modes.

### Graph View

In Graph View mode, the Data Model Navigator offers users an interactive, graphical representation of the data model. Users can apply filters, as described previously, to pinpoint nodes and their associated properties that are most relevant or interesting. Selecting a node activates a Properties Dialogue box, which displays the node’s Assignment and Class designations and quantifies the number of properties categorized as Required, and Optional. 

### Table View

In Table View mode, the Data Model Navigator displays detailed tabular views of each node, which fully-define the properties within them, inclusive of the applicable controlled vocabularies of acceptable terms for enumerated properties. The tabular views also clearly identify which properties are Required versus those that are Preferred or Optional; the acceptable data type for each property; which properties are displayed within the application’s UI; and the labels via which such properties are displayed. Note that many properties displayed within the UI are renamed with labels which are more intuitive than the property names themselves, and that some properties are displayed via more than one label. As described below, comprehensive documentation of the data model’s nodes and property requirements can be downloaded in PDF format via the Table View, alongside node-specific data loading templates into which data submitters can insert the relevant data values and thereby create loading-ready data files.

### Required, Preferred and Optional Properties

Each property is assigned one of three requirement levels - Required, or Optional.

- **Required** properties are largely self-explanatory, i.e. data destined for a node which contains required properties must include values for all such properties, and values must be compliant with the acceptable values for properties which are both required and enumerated. Controlled vocabularies for such properties typically include terms such as “Not Applicable”, “Not Reported” and “Unknown” to accommodate situations where data values aren’t relevant or weren’t collected, either by design or otherwise. Notably, for nodes into which a data submitter is not propagating any data values, required fields are no longer relevant, and can be ignored.
- **Optional** properties are precisely that and null values are allowed.

<!-- PAGE BREAK -->

### Key Properties

Many nodes contain a single property visually identified as a Key Property by a **blue key icon** displayed next to the name of the appropriate property. In addition to several nodes that require one in support of data updates, all nodes which act as parents of child nodes will likewise have a single property within them identified as a Key Property. During data loading, **_child records_** are associated with their correct **_parents_** by virtue of data loading files which contain the appropriate values for the property identified as their parents’ Key Property. For example, files via which sample records are loaded will contain a column into which values of "Participant ID" must be inserted, such that samples can be associated with the appropriate participant from which they were derived, with “Participant ID” being designated as the Key Property within the **Participant** node. Key Properties are therefore functionally equivalent to foreign keys in traditional relational databases.

### PDF Documentation

Detailed documentation of the data model’s nodes and property requirements can be downloaded as PDF exports, either in the form of a comprehensive data dictionary inclusive of all nodes, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a node-by-node basis. Used alongside the corresponding data loading templates described below, these node-specific PDF exports function as user guides for data preparation and submission. See the associated [Data Submission Guidelines](/#/submit)

### Data Loading Templates

In support of data submission, data loading templates can be downloaded, either in the form of a zip file containing copies of all available templates, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a node-by-node basis. Templates include columns into which the data values required to associate child records with their parents can be inserted. Notably, each template will include a **mapping column** for each potential parent, but although \*all child records must be mapped to **at least one parent\***, submitters are not required to provide a mapping value for each and every potential parent, _only the_ **_most appropriate parent(s)_**. Guided by the corresponding node-specific PDF exports described above, data submitters can insert the relevant data values into these data loading templates, and thereby create loading-ready data files that can be handed off to the GC Data Team.

### Controlled Vocabularies

In the interests of data quality and consistency, the GC data model makes extensive use of enumerated properties and controlled vocabularies of acceptable terms. All such controlled vocabularies can be viewed via Table View mode, and value sets are included in full in the appropriate PDF exports. Furthermore, in support of data submitters pre-validating their templated data, all controlled vocabularies can be exported in machine readable JSON and TSV formats, either in the form of a zip file containing copies of controlled vocabularies for all enumerated properties, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a property-by-property basis. As more studies are added to the GC, many of these controlled vocabularies will continue to evolve, and will be updated by the GC Data Team during study on-boarding, in order to accommodate additional terms not yet encountered.

### Key Properties for Each Node

The key property is the ID property for each different node. Each unique node will have one unique key property value as its ID.

- **_program\_acronym_** is the key property for the node **_program_**. It is the name of the program under which related studies will be grouped, expressed in the form of the acronym by which it will identified within the UI. This property is used as the key via which study records can be associated with the appropriate program during data loading, and to identify the correct records during data updates.
- **_phs\_accession_** is the key property for the node **_study_**. It is the PHS accession number (a.k.a dbGaP accession).
- **_study\_participant\_id_** is the key property of the node **_participant_**. The property **_study\_participant\_id_** is a compound property, combining the property **_participant\_id_**, string character "_" in the middle as the connector, and the parent property **_study.phs\_accession_**.
- **_study\_diagnosis\_id_** is the key property for the node **_diagnosis_**. The property **_study\_diagnosis\_id_** is a compound property, combining the property **_diagnosis\_id_**, string character "_" in the middle as the connector, and the parent property **_participant.study\_participant\_id_**.
- **_sample\_id_** is the key property of the node **_sample_**. It is the sample identifier as submitted by requestor.
- **_treatment\_id_** is the key property of the node **_treatment_**. The property **_treatment\_id_** is a compound property, combining the parent property **_participant.study\_participant\_id_**, string character "\_" in the middle as the connector, and the property **_therapeutic\_agents_**.
- **_file\_id_** is the key property of the node **_file_**. It is the file identifier.
- **_genomic\_info\_id_** is the key property of the node **_genomic\_info_**. It is the genomic info identifier. If the value is missing, but the **_library\_id_** values are given, will replace the **_genomic\_info\_id_** value with the combination of the parent node id value **_file\_id_** and **_library\_id_**; if the **_library\_id_** is also missing, will replace the value with the parent id value **_file\_id_**.
- **_study\_link\_id_** is the key property of the node **_image_**. It should consist of a string and a number.
- **_MultiplexMicroscopy\_id_** is the key property of the node **_MultiplexMicroscopy_**. It is the MultiplexMicroscopy identifier.
- **_NonDICOMCTimages\_id_** is the key property of the node **_NonDICOMCTimages_**. It is the NonDICOMCTimages identifier.
- **_NonDICOMpathologyImages\_id_** is the key property of the node **_NonDICOMpathologyImages_**. It is the NonDICOMpathologyImages identifier.
- **_NonDICOMPETimages\_id_** is the key property for the node **_NonDICOMPETimages_**. It is the NonDICOMPETimages identifier.
- **_NonDICOMradiologyAllModalities\_id_** is the key property of the node **_NonDICOMradiologyAllModalities_**. It is the NonDICOMradiologyAllModalities identifier.
- **_NonDICOMMRimages\_id_** is the key property for the node **_NonDICOMMRimages_**. It is the NonDICOMMRimages identifier.
- **_proteomic\_info\_id_** is the key property for the node **_proteomic_**. It is the proteomic info identifier.
- **_data\_version\_id_** is the key property of the node **_version_**. It is the static data version ID that is used primarily to assist in data loading. This ID will be used as a reference to update the existing data_version node instead of creating a new one with each version change.
- **_pdx\_id_** is the key property for the node **_pdx_**. It is the unique sequence of characters used to identify the human-derived tumor sample that is transplanted into an immunodeficient mouse.

### Submission Rules:

If it is a recurring study being submitted meaning that data for that PHS accession exists in the General Commons (GC) no need to submit data under the program node.

**_Genomics_** - All required fields in program if new study, all required fields in Genomic Info, all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Genomic Info node.
 
**_Imaging_** - For a new study, all required fields in the Program must be completed, then complete all required fields in the IMAGE section, File node, Diagnosis section.
Depending on the IMAGE Types please follow the criteria below:
If using Multiplex Microscopy, provide the relevant metadata in the MultiplexMicroscopy section.
For Non-DICOM CT, provide all required metadata from the NonDicomCTImages node.
For Non-DICOM MRI, provide all required metadata from the NonDicomMRimages node.
For Non-DICOM Pathology, provide metadata in the NonDicomPathologyImages section.
For Non-DICOM PET, provide all required metadata from the NonDicomPETImages node.
For Non-DICOM Radiology, provide all required metadata from the NonDicomRadiologyAllModalities node.

**_Proteomics_** - All required fields in program if new study, all required fields in Genomic Info (if applicable for a proteogenomic study), all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Proteomic Info node.

**_Sequence Data_** - All required fields in program if new study, all required fields in Genomic Info, all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Genomic Info node.

**_Pathology Imaging_** - follow imaging data criteria for Non-DICOM Pathology images.

**_Radiology Imaging_** - follow imaging data criteria for Radiology images.
 
**_Transcriptome Profiling_** - All required fields in program if new study, all required fields in Genomic Info, all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Genomic Info node.
 
**_Gene Expression Analysis_** - All required fields in program if new study, all required fields in Genomic Info, all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Genomic Info node.

**_Mass Spectrometry_** - All required fields in program if new study, all required fields in Genomic Info (if applicable for proteogenomic data), all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Proteomic Info node.

**_Methylation Analysis_** - All required fields in program if new study, all required fields in Genomic Info, all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Genomic Info node.

**_Genomic Structural Variation_** - All required fields in program if new study, all required fields in Genomic Info, all required fields in Sample Node, All required fields in File node, all required fields in Diagnosis, all required fields in Genomic Info node.