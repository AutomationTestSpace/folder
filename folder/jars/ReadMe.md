Diana Test Jars
This document describes how to set up and utilize the project specific jars. 
Set up
* Copy the project specific jars from cnrfiler, /auto/cnr-filer1/test/dianajars and paste the cnrdhcp.jar, dianaclient_0.0.1, dianaserver_0.0.1 under the jars folder.
* Download the cnr product tar file, extract and copy the cnrsdk.jar
* Create a folder with the version number as suffix followed by 'x' under jars folder.
	Ex: For 9.0 release, create a folder named 'cnr90x' and place the cnrsdk.jar
* Go to pom.xml and update the folder name in <cnrfolder> tag
* Ex: For 9.0 release, update as <cnrfolder>cnr90x</cnrfolder>
