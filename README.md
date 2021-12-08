# ServiceNow-Attachments-Download-with-Powershell
Download ServiceNow Attachments using powershell (Internally uses Aggregate API , Attachment API &amp; Table API )
# ServiceNow_Attachment_Download_Powershell
Download ServiceNow Attachments using powershell (Internally uses Aggregate API , Attachment API &amp; Table API )

## Pre execution steps - Update below variables with relevant details
* ***$userName*** with User id of servicenow user record
* ***$password*** with User password 
* ***$logFilePath*** with a log file path , all the execution log will be stored in it
* ***$instanceUrl*** with ServiceNow Instance to connect 
* ***$baseFolderPath*** with initial folder where we need to create subfolder , by default that folder should exist
* ***$tables*** with list of table names for attachments need to be retrieved
* ***$relativeTablePath*** with table and its relevant subdirectory names, script will automatically create if folder doesnt exist

## Known issues
* Exception handling is not yet implemented 
* In some instances , huge files download might be incomplete, In such cases retrigger script
