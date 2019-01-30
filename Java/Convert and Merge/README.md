# Convert and Merge Documents
The Java sample provided in this section uses the *[Muhimbi PDF Converter Services](http://www.muhimbi.com/Products/PDF-Converter-Services/summary.aspx)* to convert (if needed) and merge multiple files and HTML into a single PDF. Additional sample code to convert, merge, watermark, secure and OCR files [can be found here](../).

Any questions? [Drop us a line](http://www.muhimbi.com/contact.aspx), we love to help.


<br/>


## Prerequisites
For an overview of the prerequisites for the various platforms, including software to install as well as how to download this sample code, see the [overview page for all Java sample code](../).

<br/>

### Compiling and Running the Sample Code
Although compiled binaries are supplied with the sample code, once you decide to use this code in your own applications you may want to change the namespace of the proxy classes. Points 1 and 2 are optional and only needed if you wish to generate proxy classes yourself.

If the *Muhimbi PDF Converter Services* is installed on the same machine that is running this sample code, it can be executed straight away by running the `run.sh` (for Linux) or the `run.bat` script file.

:bangbang:Dont forget to make the various .sh files executable using `chmod +x *.sh`:bangbang:

1. Edit the `GenerateJavaWSProxies.sh` (for Linux) or the `GenerateJavaWSProxies.bat` (for Windows) script and change `localhost` to the name or ip-address of the server running the Muhimbi Conversion Service.
2. Execute the `GenerateJavaWSProxies.sh` (for Linux) or the `GenerateJavaWSProxies.bat` (for Windows) script to generate proxy classes for the web service.
3. Modify the `src/com/muhimbi/app/WsClient.java` source file so the `DOCUMENTCONVERTERSERVICE_WSDL_LOCATION` constant points to the WSDL of the *Muhimbi PDF Converter Services*
4. Execute the `compile.sh` (for Linux) or the `compile.bat` (for Windows) script
5. Execute the `run.sh` (for Linux) or the `run.bat` (for Windows) script

<br/>

Any questions? [Drop us a line](http://www.muhimbi.com/contact.aspx), we love to help.