### The Graph-Based Data Model

The CDS data model is graph-based, where nodes correspond functionally to tables in a traditional relational database. Each node contains properties that represent columns or fields in the respective table, with relationships stored at the level of individual records. This flexible data model is developed to accommodate genomic and imaging cancer data submitted to CDS, enabling the exploration of biological questions in basic cancer research. Nodes are designed to capture specific information relevant to each study and data type, recognizing variations between submissions.

### Node Categories

All nodes are categorized into several groups, each representing a family of interconnected nodes that collectively define higher-level entities within the data model. For example, the **Participant** category encompasses a small set of nodes that comprehensively describe CDS study participants/subjects. The **Study** category includes nodes that collectively define various aspects of studies. Meanwhile, the **Sequencing** category contains nodes where genomic experimental observations related to various cancer conditions can be represented

### Assignment: Core nodes versus Extended nodes

CDS is data type agnostic, and within its data model, there are nodes that are consistently or frequently populated with data, irrespective of the study type. These nodes, positioned at the core of the data model, are classified as 'Core' nodes. Surrounding the core is the extended data model, which includes numerous nodes that currently have lower data density. This division aims to guide users, especially data submitters, towards focusing on the nodes and properties crucial for defining any study, regardless of its specific nature.

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

In support of data submission, data loading templates can be downloaded, either in the form of a zip file containing copies of all available templates, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a node-by-node basis. Templates include columns into which the data values required to associate child records with their parents can be inserted. Notably, each template will include a **mapping column** for each potential parent, but although \*all child records must be mapped to **at least one parent\***, submitters are not required to provide a mapping value for each and every potential parent, _only the_ **_most appropriate parent(s)_**. Guided by the corresponding node-specific PDF exports described above, data submitters can insert the relevant data values into these data loading templates, and thereby create loading-ready data files that can be handed off to the CDS Data Team.

### Controlled Vocabularies

In the interests of data quality and consistency, the CDS data model makes extensive use of enumerated properties and controlled vocabularies of acceptable terms. All such controlled vocabularies can be viewed via Table View mode, and value sets are included in full in the appropriate PDF exports. Furthermore, in support of data submitters pre-validating their templated data, all controlled vocabularies can be exported in machine readable JSON and TSV formats, either in the form of a zip file containing copies of controlled vocabularies for all enumerated properties, invoked via the upper-level “Available Downloads” option, or from within the Table View, and invoked on a property-by-property basis. As more studies are added to the CDS, many of these controlled vocabularies will continue to evolve, and will be updated by the CDS Data Team during study on-boarding, in order to accommodate additional terms not yet encountered.
