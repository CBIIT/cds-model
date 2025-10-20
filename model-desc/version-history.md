### 10.0.1 (Released 10/20/2025)
- Updated the composite key rule for the prop: "**_study\_participant\_id_**".

### 10.0.0 (Released 9/5/2025)
- Updated the prop: "**_race_**"'s type to list.
- Updated the prop: "**_ethnicity_**"'s type to list.
- Added the node: "**_investigator_**".
- Added the prop: "**_tumor\_classification_**" to the node : "**_sample_**".
- Added the prop: "**_study\_id_**" to the node : "**_study_**" to replace the prop: "**_phs\_accession_**" as the key property. 

### 9.0.0 (Released 7/17/2025)
- Reassigned the prop: "**_performed\_imaging\_study\_typeCode_**" to the node: "**_NonDICOMradiologyAllModalities_**".
- Added the node: "**_consent\_group_**".

### 8.0.3 (Released 7/8/2025)
- Updated the prop: "**_implantation\_type_**"'s type to list.
- Updated the prop: "**_sample\_anatomic\_site_**"'s type to list.

### 8.0.2 (Released 6/26/2025)
- Updated the README.md.
- Updated the prop: "**_embedding\_medium_**"'s CDE code and the Enum values.

### 8.0.1 (Released 6/2/2025)
- Added the relationship between the node: "**_diagnosis_**" and the node: "**_sample_**".
- Updated the category of the node: "**_program_**" to "administrative".
- Updated the category of the node: "**_participant_**" to "case".
- Updated the category of the node:"**_sample_**" to "biospecimen".
- Updated the category of the node:"**_diagnosis_**" to "clinical".
- Updated the category of the node:"**_pdx_**" to "biospecimen".

### 8.0.0 (Released 5/20/2025)
- Added the node: "**_pdx_**".

### 7.0.0 (Released 5/8/2025)
- Added "**_nodeReq: true_**" to all nodes except the the node: "**_treatment_**" and the nodes: "**_version_**".
- Updated the prop: "**_program\_short\_description_**" from the node: "**_program_**" to be required.
- Updated the prop: "**_program\_full\_description_**" from the node: "**_program_**" to be required.
- Updated the prop: "**_program\_external\_url_**" from the node: "**_program_**" to be required.
- Updated the prop: "**_program\_short\_name_**" from the node: "**_program_**" to be required.
- Updated the prop: "**_institution_**" from the node: "**_program_**" to be required.
- Updated the prop: "**_study\_acronym_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_study\_description_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_short\_description_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_study\_external\_url_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_role\_or\_affiliation_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_first\_name_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_last\_name_**" from the node: "**_study_**" to be required.
- Updated the prop: "**_reference\_genome\_assembly_**" from the node: "**_genomic\_info_**" to be required.
- Updated the prop: "**_library\_strategy_**" from the node: "**_genomic\_info_**" to be required.
- Updated the prop: "**_library\_layout_**" from the node: "**_genomic\_info_**" to be required.
- Updated the prop: "**_library\_selection_**" from the node: "**_genomic\_info_**" to be required.
- Updated the prop: "**_platform_**" from the node: "**_genomic\_info_**" to be required.
- Updated the prop: "**_instrument\_model_**" from the node: "**_genomic\_info_**" to be required.
- Updated the prop: "**_number\_of\_participants_**" from the node: "**_study_**" to be not required.
- Updated the prop: "**_number\_of\_samples_**" from the node: "**_study_**" to be not required.
- Updated the prop: "**_study\_access_**" from the node: "**_study_**" to be not required.
- Removed the prop: "**_program\_sort\_order_**" from the node: "**_program_**"
- Removed the prop: "**_index\_date_**" from the node: "**_study_**"
- Removed the prop: "**_cds\_requestor_**" from the node: "**_study_**"
- Removed the prop: "**_clinical\_trial\_system_**" from the node: "**_study_**"
- Removed the prop: "**_clinical\_trial\_identifier_**" from the node: "**_study_**"
- Removed the prop: "**_clinical\_trial\_arm_**" from the node: "**_study_**"
- Removed the prop: "**_data\_types_**" from the node: "**_study_**"
- Removed the prop: "**_file\_types_**" from the node: "**_study_**"
- Removed the prop: "**_cds\_primary\_bucket_**" from the node: "**_study_**"
- Removed the prop: "**_cds\_secondary\_bucket_**" from the node: "**_study_**"
- Removed the prop: "**_cds\_tertiary\_bucket_**" from the node: "**_study_**"
- Removed the prop: "**_clinical\_trial\_repository_**" from the node: "**_study_**"

### 6.0.5 (Released 4/29/2025)
- Updated the description for the prop: "**_study\_participant\_id_**".
- Updated the description for the prop: "**_study\_diagnosis\_id_**".

### 6.0.4 (Released 4/8/2025)
- Rebranded the CDS model to the GC model.

### 6.0.3 (Released 3/21/2025)
- Updated the pattern of the prop: "**_phs\_accession_**".
- Updated the CDE version of some of the properties to the latest CDE version.
- Updated the CDE information for the prop: "**_sex_**".

### 6.0.2 (Released 2/18/2025)
- Updated the version-history.md.
- Updated the relationship between the node: "**_proteomic_**" and the node: "**_file_**" to be many-to-one.

### 6.0.1 (Released 2/13/2025)
- Renaming the prop: "**_gender_**" to "**_sex_**".

### 6.0.0 (Released 2/1/2025)
- Added the prop: "**_is\_supplementary\_file_**" to the node: "**_file_**".
- Added the prop: "**_release\_datetime_**" to the node: "**_file_**".
- Removed the prop: "**_library\_source_**" from the node: "**_genomic\_info_**".
- Updated the description for the prop: "**_file\_id_**".
- Updated the prop: "**__study\_data\_types__**"'s type to list.

### 5.0.4 (Released 12/20/2024)
- Updated the example mock data file "**_cds-file-examples.zip_**".

### 5.0.3 (Released 12/13/2024)
- Added the prop: "**_proteomic\_info\_id_**" to the node: "**_proteomic_**".
- Added the prop: "**_manufacturer\_model\_name_**" to the node: "**_proteomic_**".

### 5.0.2 (Released 11/27/2024)
- Updated the description for the prop: "**_treatment\_id_**".
- Updated the description for the prop: "**_image\_id_**".

### 5.0.1 (Released 11/22/2024)
- Updated the CDE information for the prop: "**_progression\_or\_recurrence_**".

### 5.0.0 (Released 11/18/2024)
- Added the node: "**_MultiplexMicroscopy_**".
- Added the node: "**_NonDICOMCTimages_**".
- Added the node: "**_NonDICOMMRimages_**".
- Added the node: "**_NonDICOMpathologyImages_**".
- Added the node: "**_NonDICOMPETimages_**".
- Added the node: "**_NonDICOMradiologyAllModalities_**".
- Added the node: "**_proteomic_**".
- Added the node: "**_data\_version_**".
- Removed the prop: "**_treatment\_outcome_**" from the node: "**_treatment_**".
- Updated the model description file "**_README.md_**".

### 4.0.4 (Released 10/11/2024)
- Updated the CDS model to enable template generation for the node: "**_treatment_**".

### 4.0.3 (Released 10/11/2024)
- Added the example mock data file "**_cds-file-examples.zip_**" to the CDS model repo.
- Added the file ""**_navigator-icon.png_**"" to the CDS model repo.
- Added the model description file "**_README.md_**" to the CDS model repo.
- Updated the description for the node" "**_sample_**".

### 4.0.1 (Released 7/15/2024)
- Added and updated the CDE information to each node and property in the CDS model.
- Added the CRDC Submission Portal related property "**_Tags_**" to every nodes in the CDS model.
- Added the CRDC Submission Portal related property "**_Key_**" to the ID prop of each node in the CDS model.
- Updated the prop: "**__acl__**"'s type to list.
- Updated the prop: "**_data\_types_**"'s type to list.
- Updated the prop: "**_file\_types_**"'s type to list.
- Updated the prop: "**_file\_types\_and\_format_**"'s type to list.
- Updated the prop: "**_experimental\_strategy\_and\_data\_subtypes_**"'s type to list.
