<Entry>

<Developer_Name>

</Developer_Name>

<Developer_email>

</Developer_email>

<!- This would be your CCR, VCR, Routine, Config Change request number ->
<Change_Request_Number> 
</Change_Request_Number>

<!- Story associated with the changes ->
<Story_Number>
</Story_Number>

<!- RTC link/url ->
<RTC_Link>
</RTC_Link>

<!- Defect number through which you deliver this defect ->
<Defect_Number>
</Defect_Number>


<!- The type of Database change i.e one of these: CATALOG, LOG, CONFIG, ROUTINE, PACKAGE, OTHER 
    IF YOU CHOOSE OTHER, PLEASE ALSO SEND AN EMAIL TO THE "DB2-Deployment-ISL"  DISTRIBUTION LIST AS
    THIS VALUE IS INTENDED TO CAPTURE NEW/UNKNOWN TYPES OF CHANGES ONLY. ->

<DB_Change_Type>
</DB_Change_Type>


<!- If CATALOG change type, please fill in this section. If not CATALOG type, you can delete this section. ->
<Catalog_change>

        <!- Catalog table/view schema ->
        <Catalog_Schema>
        </Catalog_Schema>

        <!- Catalog table/view name ->
        <Catalog_Name>
        </Catalog_Name>

        <!- What is the change type? Use one of the abbreviations for the corresponding actions
              DROP - Catalog table/view is being dropped
              ADD/DEL/UPDATE - New column being added, column being deleted, Column being updated respectively
              COMMENTS - Comments being updated for the table/view/column
	      PD - Packed Descriptor is changed
	      NEWINX - New index/indices being added ->
	<Catalog_Change_Type>
	</Catalog_Change_Type>

        <!- Column name. For each column, pls. include a new <Column_Name> entry ->
        <Column_Name>
        </Column_Name>

	<!- Index related information. For each Index changed/added, pls. include a new <Index_Name> entry ->
        <Index_Name>
	</Index_Name>

	<!-If you have changed the packed descriptor, pls mention the column name->
	<Packed_Desc_Column_Name>
	</Packed_Desc_Column_Name>

</Catalog_change>

<!- Include any internal details like design document links, technical details of the implementation, etc
    Useful for internal reference for developers and QA ->
<Internal_Description>
</Internal_Description>

</Entry>
