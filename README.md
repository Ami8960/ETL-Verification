Overview:

This guide provides a step-by-step approach to execute Operational Qualification(OQ) documents post ETL execution to validate data is migrated from Argus Safety database(source)
to Beigene Safety Data Mart(target) database as per the approved specifications.

Steps include:

1. Execute OQ1 (Table Count Verification). Follow steps mentioned in OQ1 to validate the count of each row in source and target database are equal for all the
   tables post ETL execution.

3. Execute OQ2 (Field Count Verification). Follow steps mentioned in OQ2 to validate the number of distinct values and its count is same for all the columns/fields in source
   and target database post ETL execution.

5. Execute OQ3 (Calculated Field Verification). Follow steps mentioned in OQ3 to execute minus queries and validate the source minus target and target minus source is zero i.e.,
   the values for fields which are not directly mapped post ETL Execution.
