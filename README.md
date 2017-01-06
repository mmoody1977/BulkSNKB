# BulkSNKB
Usage Information:

C:\ >BulkKBUpload.exe /?
Bulk uploads all .docx Word documents in a targeted folder, as an HTML based KB Article, to the kb_submission table on a Service Now instance.

BulkKBUpload folderpath [/U:username] [/P:password] [/I:instance]

folderpath    The complete path to the folder containing the documents to convert and upload.
/U:username   The Service Now username that has permissions to create kb_submission records.
/P:password   The password for the supplied username.
/I:instance   The Service Now instance hostname. Example: myinstance.service-now.com

Example usage: BulkKBUpload "C:\Docs" /U:mmoody /P:p@ssw0rd! /I:moodydev.service-now.com
