# Webafrica - RPA Assessment
## 1) Prerequisites:
### Power Automate Desktop Version 
- (Skep this steps if you already have Power Automate) Download power automate desktop using the instructions [here](https://learn.microsoft.com/en-us/power-automate/desktop-flows/install#install-power-automate-using-the-msi-installer).
- (Skep this steps if you already have UI Path Community Edition) Run the installer, and be sure to enable “Install the Power Automate for deskop to build desktop flows” checkbox.
- Sign in with your work or personal microsoft account. *Once logged in: you may get an error regarding the organization. Search in windows for Power Automate again and then try and launch*.

### SqlServer Express
- The test will require to you to setup a database, and store data there in.
- (If you have Sql Server Express installed skip this step) Download and install the Free [Sql Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads).
- (If you have Sql Server Express installed skip this step) Download and install [Sql Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?redirectedfrom=MSDN&view=sql-server-ver16).
- Within Sql Server Management Studio, connect to your running Sql Server Express instance, and create a database using the database.sql file part of this repository.

## 2) What are we looking for:
- Shows ability to perform Scraping, Downloading, Editing, and Database interaction using RPA tools.

## 3) Submitting Results
- Once you've completed your project, copy the power automate workflow to a text file. See instructions [here](https://www.linkedin.com/pulse/how-copypaste-power-automate-desktop-flows-another-computer-sharif/).
- Export the database, by going to Sql Server Management Studio and follow the steps [here](https://docs.telerik.com/devtools/aspnet-ajax/knowledge-base/common-import-and-export-sql-database-to-sql-script-via-sql-management-studio).
- Submit the test by either: 1) Emailing the results. 2) Uploading it to a shared folder (Google Drive, DropBox etc) and sharing it with the Webafrica co-ordinator.
- Include in your submission, the version of Power Automate used (can typically be found at the bottom of the PA window)

## 4) Start The Test

Using Power Automate:

- Browse to https://www.webafrica.co.za/voip, and find the link next to the text "View the full list of international call rates". Download the Excel file behind that link. (The file will give you a list of all Voip call rates.).
- Open the downloaded file, read the data, and store all the "Afghanistan" rates in the table **VoipPrices** (this table you will need to create on your local instance of SQL Server)
- Open in the browse the Google Forms RPA test form using the link [here](https://docs.google.com/forms/d/e/1FAIpQLSfT6HYGjRadUwY7OpyCe9QFqhkG0tDdOyIFn9pbVrfo3yMKLg/viewform).
- Store your name in the "Applicants Name" question in the form.
- Scrape the site and store description of "What Is Webafrica Voice?", storing it in the "What Is Webafrica Voice?" answer in the Google Form.
- Scrape the site, open the drop down and store description of "Do I have to use a Webafrica Voice phone?", storing it in the "Do I have to use a Webafrica Voice phone?" answer in the Google Form.
- Click Submit on the Google Form

Complete
