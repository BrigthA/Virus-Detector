# Virus-Detector

Readme
=======

The VirusTotal API lets you upload and scan files or URLs, 
access finished scan reports without the need of using the website interface.
We can use this API/Application to detect Malware, Trojan, Worm, Blacklisted IP, Malicious Domain..etc  

While many of the endpoints and features provided by the VirusTotal API are freely accessible to all registered users, some of them are restricted to our premium customers only. 

Those endpoints and features constitute the VirusTotal Private API and they will be appropriately identified in this section. If you are interested in using our Private API please contact (https://www.virustotal.com)

In this module V2 is implemented

Many clients want to secure their environment without any flaws/loopholes..etc. So we can use this sample module to detect the virus(Example: Binded with Image+Trojan or Pdf+Malware)    

1) First of all we need to register for API key from Virustotal (Public API key / Premium API key) Link: https://www.virustotal.com/gui/join-us

2) After registration you can use this public API key to get authorization from the Virustotal. 

3) Update the api key constant value under the Constant folder

3) You can use this microflow(ACT_FileScan) to get hash value for the Document/file you have uploaded.

4) You can use this microflow(SUB_FileScannedReport) to get a Document scanned report.   

5) You can use this microflow (ACT_URLScan) to get a Blaclisted/Suspected URL report.
Note
====
You can use this Microflow in Event handler(BCO) to Perform inspection.

Example
=======

1) Use this FileUploading_NewEdit page in the navigation. 

2) Upload the file or add the url to inspect.


If you want to view the result manually, go ahead and use this link( https://www.virustotal.com/gui/home/upload)?
