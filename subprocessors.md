## Scan website for subprocessors
### Subprocessors 
* Processors: “Processor means a natural or legal person, public authority, agency or other body which processes personal data on behalf of the controller.”
* Sub-Processors: “Often processors will work with other processors (sub-processors)…Maybe your marketing agency works with partners for specific tasks whereby these partners also process personal data and thus become processors.”

### Data Processor Obligation
* GDPR Article 28 – The data processor can’t bring in another processor without a clear permission from (and thus notification duty towards) the controller.
* GDPR Article 28/29/32-36/42/43 – the contract between data controller and data processor
* GDPR Article 30 – data processors, record keeping and secure processing
* GDPR Article 5 – data processors and controllers: common duties, shared liability 

### Problems to be solved
* How to automatically retrieve a list of sub-processors for a certain company
* How to automatically get updates if sub-processors are added, deleted, or changed

### Proposed Solutions
Step 1 - input the link to the page with sub-processor info, such as https://www.atlassian.com/legal/sub-processors 
Step 2 - select the format type 
Step 3 - Crawl the webpage, and search for the list of sub-processors (Beautiful Soup)
Step 4 - Record sub-processors, and the location of the sub-processor lists on the webpage
Step 5 - 


### Ideas
* there is always a date on the page, when the page was updated. We probably can track this!
* Create a user interactive tool to retrieve data from webpage  
  * user click on the portion which contains the date, then the portion is recorded, and can be checked later


### Problems to solve
* how to retrieve the link to the page about subprocessors 
  *Probably, we can start with inputing the subprocessors*
* find out a way to retrieve only text from webpage without htmt and style
  * user click on the portion which contains subprocessors' name, the name will be displayed in our app
  
### Questions to ask
* What is a business scenario where this is needed?
  * for a specific company, we want to keep track of the subprocessors?
  * if so, we could input the page link manually
* subprocessors are always company name?
  * if so, we can have a company name training data set to do the extraction
* subprocessors === vendors in our APP
  https://blog.whistic.com/gdpr-assessing-and-managing-processors-and-sub-processors-in-whistic-f20117f9ab3

### Todo
* look into how people do the location and name tag, it is similar here, we want to do subprocessors tag



Reference
* https://www.i-scoop.eu/gdpr/data-processor-gdpr/ 
