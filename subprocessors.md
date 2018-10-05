## Scan website for subprocessors
### Ideas
* there is always a date on the page, when the page was updated. We probably can track this!
* Create a user interactive tool to retrieve data from webpage  
  * user click on the portion which contains the date, then the portion is recorded, and can be checked later

### Problems
* how to retrieve the link to the page about subprocessors 
  *Probably, we can start with inputing the subprocessors*
  
### Questions
* What is a business scenario where this is needed?
  * for a specific company, we want to keep track of the subprocessors?
  * if so, we could input the page link manually
* subprocessors are always company name?
  * if so, we can have a company name training data set to do the extraction

### Todo
* find some definitions about what is subprocessors
* find out a way to retrieve only text from webpage without htmt and style
  * user click on the portion which contains subprocessors' name, the name will be displayed in our app
* look into how people do the location and name tag, it is similar here, we want to do subprocessors tag
