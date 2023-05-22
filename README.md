# Webafrica - RPA Assessment
## 1) Prerequisites:
- UI Path / UI Path Studio Community Edition 
-- (Skep this steps if you already have UI Path Community Edition) Register for a UI Path community edition profile, [try it for free](https://www.uipath.com/product) button
-- (Skep this steps if you already have UI Path Community Edition) Once Registering yourself as a home/personal company, you should gain access to the UI Path Automation Studio
-- Download the [UIPath Installer](https://download.uipath.com/UiPathStudioCommunity.msi). *Once logged in: you can also find this download link the right on the home screen of the Automation Cloud platform*
-- Create a Project using UiPath Studio (**not UiPath StudioX**)
-- Once UiPath Studio is opened, go the Home > Help and copy the UiPath version used on the right side. **You need to supply the UiPath studio version when submitting your assessment**

- SqlServer Express
-- The test will require to you to setup a database, and store data there in.
-- (If you have Sql Server Express installed skip the below steps)
-- Download and install the Free [Sql Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads).
-- Download and install [Sql Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?redirectedfrom=MSDN&view=sql-server-ver16)
-- Within Sql Server Management Studio, connect to your running Sql Server instance, and create a database using the database.sql file part of this repository

## 2) What are we looking for:
- Shows ability to perform Scraping, Downloading, Editing, and Database interaction using RPA tools

## 3) Submitting Results
- Once you've completed your project, Zip the entire folder where the .xaml and project.json file exists.
- Export the database, by going to Sql Server Management Studio and follow the steps [here](https://docs.telerik.com/devtools/aspnet-ajax/knowledge-base/common-import-and-export-sql-database-to-sql-script-via-sql-management-studio)
- Submit the test by either: 1) Emailing the results. 2) Uploading it to a shared folder (Google Drive, DropBox etc) and sharing it with the Webafrica co-ordinator.

## 4) Start The Test

Using UiPath:

- Browse to https://www.webafrica.co.za/voip, and find the link next to the text "View the full list of international call rates". Download the Excel file behind that link. (The file will give you a list of all Voip call rates.)
- Open the downloaded file, read the data, and store all the "Afghanistan" rates in the table **VoipPrices**
- Open in the browse the Google Forms RPA test form using the link here
- Store your name in the "Applicants Name" question in the form.
- Scrape the site and store description of "What Is Webafrica Voice?", storing it in the "What Is Webafrica Voice?" answer.
- Scrape the site, open the drop down and store description of "Do I have to use a Webafrica Voice phone?", storing it in the "Do I have to use a Webafrica Voice phone?" answer.
