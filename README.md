# New vs Refurbished Apple Product: Data Harvesting Final Project

## Pre-requisites

This work consists of three different parts in technique and development: On the one hand, to obtain the data of the new Apple products, we have manually scrapped the web that we refer in the body of the work. Secondly, for the refurbished part, the web scraping has been done using the Rselenium package, which automates the whole process. To verify the replicability of the project, please follow the instructions below:

1. Install Java 8 Update 441: The scrapping with RSelenium was done with this version. This does not mean that another version is not valid to perform the activity, but, to avoid bugs, we leave attached in this repository the installation of the specific version for both Mac and Windows operating systems:
    - Java 8.441 for Mac: https://mac.filehorse.com/download-java-runtime/download/
    - Java 8.441 for Windows: https://www.filehorse.com/download-java-runtime-64/download/#google_vignette
   
2. Install Firefox Version 135.0.1.: As with Java, it should not be necessary to have the same version of Firefox. To avoid problems, version installer is attached in turn: https://ftp.mozilla.org/pub/firefox/releases/135.0.1/.
3. Change the user_agent to your own one. If you type "My user agent" in Google you would find your own one to replace. 

These three steps have been replicated on other computers and have made the code work. In the extreme case, after the execution of the scrapping part with RSelenium, we have left an updated read.xml with the last Selenium scrapping done before the delivery of this project.

IMPORTANT: The final product comparison section is made in two Shiny Apps. The html format does not allow the export of these apps, so, in order to view these apps, please run Rmd file.

Enjoy the project!! 
