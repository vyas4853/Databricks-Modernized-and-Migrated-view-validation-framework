This Framework is designed while validating modernized and migrated view of SAP in databricks. I have used Pyspark and databricks SQL in this Framework.

Validation done using Framework.

Row count,
Column Count,
Column name,
Column schema/datatype,
Minus query,
Reverse Minus query,
Execution time of modernized and migrated views.


You have to pass parameters from another notebook to this farmework notebook.

Parameters should be passed from another notebook.

%run ./Validation_framework
$view_name="AN_SM_INVEN_TARGET" 
$org_view_name="v_SM_INVEN_TARGET" 
$mod_view_name="v_SM_INVEN_TARGET" 
$org_view_database="sm_original"
$mod_view_database="curated_sm"
