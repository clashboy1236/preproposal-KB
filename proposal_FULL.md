# Proposal 
 
## What will (likely) be the title of your project? 
 
Philadelphia Vaccine Forecaster 
 
## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.") 
 
A website that analyzes an individual's Immunization Record and recommends vaccinations that need to be renewed based on vaccine guidelines for adults and ages 18+. Essentially, this would be a vaccine forecaster that would allow the patient to see which vaccines she needs to renew and plan her care accordingly.  
 
## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed? 
 
Our project will be a website that forecasts vaccinations for adults based in Philadelphia. In this website, the patient will be able to upload her official Immunization Record from the Philadelphia Department of Public Health. Once the patient uploads the Immunization Record, which comes in the form of a PDF, the website will read the record, checking for which vaccines were previously received and on what dates. If the program notices that some essential vaccines are missing from the record entirely, it will recommend that those vaccines be received by the patient. Otherwise, the program will compare the dates of the vaccines last received by the patient to the current guidelines regarding vaccine timing for adults and will print a report for the patient containing information about all the vaccines that need to be renewed. For example, if the patient last received a flu vaccine on November 12, 2021, and the recommendation for the flu vaccine is one dose annually, the report will state “Based on your record, it is recommended that you renew your flu vaccine. This vaccine should be received once yearly.” If the patient is up to date on a particular vaccine, such as a Tdap vaccine, the report will state, “you are up to date on your Tdap vaccine. This vaccine should be renewed every 10 years.” If the patient is missing a dose of a key vaccine, for example she only has 1 of 2 recommended doses of the Varicella vaccine, the report will read “You have received 1 of the 2 doses necessary for the Varicella vaccine. Please discuss your options with a provider.” The website will also contain a page with more information about each vaccine, as well as useful links and resources.  
 
## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course? 
 
N/A. 
 
## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below. 
Katerina Orlovskiy, tug64171@temple.edu, Xinwen (Ellen) Zhang 
Keith Bunn, tup81883@temple.edu, Zhengkang Fan   
Meira Galapo, tup71978@temple.edu, Bin Li 
 
  
## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.
 
### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?
-    Uploading the file and converting it to csv
-    Reading the file and forecasting the needed vaccinations for the patient

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

-  Uploading the file and converting it to csv
-    Reading the file and forecasting the needed vaccinations for the patient
-    Printing out a report for the patient with all the needed information, perhaps as a file

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

-  Uploading the file and converting it to csv
-    Reading the file and forecasting the needed vaccinations for the patient
-    Printing out a report for the patient with all the needed information, perhaps as a file
-   Decorating the website to look visually appealing
-  Recommending nearby pharmacies where patients can be vaccinated 


## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

First, we plan on learning how to convert a pdf file to a csv file. This can only be accomplished if the patient is able to upload their file to the computer, so we additionally must research how to do this. Then, we plan on watching youtube videos and using prior knowledge to construct our own website in python. Once we have our website, we plan on dividing it into three pages; the first- a welcome page, the second- a forecasting page, and the third- an information page. The welcome page will contain information regarding uploading the file. For this, we will try to create an upload button that will assist the patients in doing this. In addition, this page will include information about the website, say that we are not HIPAA compliant, and that we will not save any confidential data. Our second page will return a new separate file that will provide the patients with forecasting information. The third page will give a brief overview of each vaccine and will provide data regarding the overall benefits of getting the shot for both the individual and the society as a whole. It will also provide useful links to the health department website and the CDC website.
