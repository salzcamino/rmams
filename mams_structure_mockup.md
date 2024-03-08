S4 object MAMS:
- FOM: list of S4 objects of type FOM
    - S4 object FOM:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("FOM")
        - data_type: character
            - getter/setter
        - representation: character
            - getter/setter
        - representation_description: character
            - getter/setter
        - obs_unit: character
            - getter/setter
        - processing: character
            - getter/setter
        - processing_description: character
            - getter/setter
        - analyte: character
            - getter/setter
        - analyte_description: character
            - getter/setter
        - modality: character
            - getter/setter
        - obs_subset: character
            - getter/setter
        - obs_subset_description: character
            - getter/setter
        - feature_subset: character
            - getter/setter
        - feature_subset_description: character
            - getter/setter
        - record_id: character
            - getter
        - parent_id: character
            - getter/setter
        - parent_relationship: character
            - getter/setter
        - parent_relationship_description: character
            - getter/setter
    - more of S4 objects FOM as above
- OID: list of S4 objects of type OID
    - S4 object OID:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("OID")
        - oid_header: character
            - getter/setter
        - oid_header_delim: character
            - getter/setter
    - more of S4 objects OID as above
- FID: list of S4 objects of type FID
    - S4 object FID:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("FID")
        - fid_header: character
            - getter/setter
        - fid_header_delim: character
            - getter/setter
    - more of S4 objects FID as above
- OBS: list of S4 objects of type OBS
    - S4 object OBS:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("OBS")
        - record_id: character or list
            - getter
    - more of S4 objects OBS as above
- FEA: list of S4 objects of type FEA
    - S4 object FEA:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("FEA")
        - feature_name: character
            - getter/setter
        - reference_database: character
            - getter/setter
        - reference_organism: character
            - getter/setter
        - record_id: character
            - getter
    - more of S4 objects FEA as above
- ONG: list of S4 objects of type ONG
    - S4 object ONG:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("ONG")
        - edge_metric: character
            - getter/setter
        - metric_type: character
            - getter/setter
    - more of S4 objects ONG as above
- FNG: list of S4 objects of type FNG
    - S4 object FNG:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("FNG")
        - edge_metric: character
            - getter/setter
        - metric_type: character
            - getter/setter
    - more of S4 objects FNG as above
- REC: list of S4 objects of type REC
    - S4 object REC:
        - constructor function
        - id: character
            - getter/setter
        - dataset_id: character
            - getter/setter
        - class: character ("REC")
        - record_id: character
            - getter
        - record_package_name: character
            - getter/setter
        - record_package_version: character
            - getter/setter
        - record_function_name: character
            - getter/setter
        - record_function_parameters: character or list
            - getter/setter
        - record_workflow_link: character
            - getter/setter
        - record_runtime_start: character
            - getter/setter
        - record_runtime_end: character
            - getter/setter
        - record_runtime_duration: character
            - getter/setter
    - more of S4 objects REC as above
- General information if needed