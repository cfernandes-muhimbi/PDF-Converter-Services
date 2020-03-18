## Muhimbi Converter Service PowerShell Module
	
The PowerShell samples do not use PowerShell's built in web services facilities (New-WebServiceProxy), as that makes things very difficult when dealing with complex web services such as the one exposed by the Muhimbi PDF Converter.
	
Instead the sample uses the pre-generated proxy DLLs that ship alongside our software. They can be found in the folder where the Conversion Service has been deployed to (See the Muhimbi Document Converter/Open Installation Folder shortcut in the Windows start menu). 
	
**Note:** The following sample shows the minimum steps required to process a document and provides a starting point for custom development. To keep the samples short and concise it makes various assumptions and short cuts. 

* For the 'ConvertTo-PDF.ps1' example, we do not explicitly set ConversionSettings.Format. As a result the file is converted to the default PDF format. It is possible to convert files to other file formats as well by setting this property to a value of the OutputFormat enumeration. For details [see this blog post](https://blog.muhimbi.com/2012/02/convert-document-types-using-pdf.html).
* The output file name is always the same as the source file.
* The URL to the server running the conversion service is hard-coded to 'localhost'. If the MDCS is located on a different machine then substitute localhost with the server’s name, etc.
