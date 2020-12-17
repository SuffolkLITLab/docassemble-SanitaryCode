# docassemble.SanitaryCode

A docassemble extension.

## Author

Michael Cronin, mcronin@su.suffolk.edu

## Disclaimer

This is intended for demonstration only. It produces an example document and is for demonstration only. It should not be implemented into existing interviews without refinement detailed below.

## Project Biography

This project was created for the Document Assembly Line Project on behalf of the Massachusetts Court System and the Suffolk Legal Innovation and Technology department. The Document Assembly Line Project was created to address the issue left behind by the absence of access to court assitance offices for people who wish to represent themselves Pro Se in court and cannot seek help from court assistance programs in person because of issues related to the COVID-19 pandemic. This project creates user friendly, mobile friendly, online court forms that can be downloaded or sent directly to courts. Using guided interviews, the project collects peoples information, helps them determine what it is they need to complete a court form and guide them on the next steps. 

# Problem

The project specifically addresses court proceedings that the underrepresented legal community are most likely to be involved in. The idea is to close the access to justice gap experineced by people with low income and guide them through some of the more fairly simple processes. One of the more common legal issues experienced in the housing sector is the inability of a tenant to get repairs made in their rental property by their landlord. Every residence is subject to a set of standards known as the Sanitary Code. The state sanitary code varies from state to state but across Massachusetts every city and town needs to ensure that landlords are staying up to code with the houses and aprtmetns that they are renting out. These codes are very strict since they are formed by public health concerns, therefore a court is able to order a landlord to make repairs if they see fit. 

In order to get repairs made a tenant needs to "petition the court to enforce the state sanitary code". This is a court proceeding that the tenant starts to ask a court to make the landlord to make the repairs to the tenants residence. The product I created collects all the information necessary for the tenant to begin this proceeding and succeed in the proceeding. This will be done with a series of screens that will either explain what it is that the tenant needs to do in order to complete the interview or screens that will collect the information for the petition. 

The idea is to make this process as simple as possible for users, as if they were filling it out with the assistance of a licensed attorney alonside them. 

# Users

This product will be used by tenants in situations where they have a landlord that has incessantly ignored requests to make repairs to the rental property. This can be utilized by users in both apartments and larger homes. 

# Research 

Currently, the only product that is avaiable is a downloadable PDF that allows the tenant to fill out this information by hand and provides insturctions on the next step. This product is useful but it lacks a lot of information specifically on which each section does what and why some of the information is necessary, or why the questions are being asked. This document was created by Mass Legal Help and is the basis for the final product that the document will serve. You can find the original version of the document [here](https://www.masslegalhelp.org/housing/lt1-form-14-tenant-petition.pdf)

This document asks for simple information about the tenant and landlord including name and address, this information will be easy to collect using the AssemblyLine Basic Questions. The main purpose of this petition is to ask the court to force the landlord to make repairs, therefore any user completeing this form will automatically be asking the court to do this and to issue the user an order of notice for the tenant to give to the landlord. The repairs that are being made must be cited by an official inspection report, therefore one must be done as a requirement before filing this peition, the interview will make sure that the user has an inspection done prior to the filing of the form. This is vital because a court is more likely to recognize evidence of the problems if there is an inspection report and also the inspection report is the document that will outline the issues the tenant is pointing out and will be referred to as Exhibit A. This is vitally important.

Other than that the user can also ask the court to make fair market value determinations, appoint a reciever, and issue a restraining order or injunciton against the landlord. These additional processes are question that will be added to the project explaining what they do, and what they are asking for from the user and how the user will be able to accomplish this end goal

The outcome from these questions will be entered into the final documentation and assembled for the user to use in the end. 

# Ideation and Prototyping

The idea behind the product that i want to create is something which makes the process of completing this form easier, will provide more context for each question asked and will allow the tenant to produce a document that is easy to use, organized and effective. Throughout the brief history of the Document Assembly line we have crafted many online guided interviews which solve similar solutions for similar documents. The idea was to use the background of what we know is effective in those interviews and craft it to this specific petition. This is simple for things like collecting addresses and names but for the questions involving the substantive law there needed to be more specific context and background. 

In order to complete this there needed to be background from multiple sources including my own research, practiced professionals on the project, a subject matter expert and input from outside users. Starting with the document provided I began breaking down what each individual blank space was asking for and the best way to collect it. Again with simple things like names and addresses this was straightforward but in refecrence to more complex issues like the questions asking about inspections that needed to be completed prior to the filing of the petition, this needed more research.

Fortunately, I had found more resources that were also produced by Mass Legal Help. These resources included a 30 page in-depth explanation of the entire process of asking for repairs in their apartment called "Getting Repairs Made" (found [here](https://www.masslegalhelp.org/housing/lt1-chapter-8-getting-repairs-made.pdf)) using this resource I was able to better understand what the form was referring to and include the information in plain language terms in the interview. 

Information from more senior professionals on the project (Caroline and Maeve) were also used to make adjustments which included mostly plain language edits, edits asking for more context and some minor legal process suggestions from Caroline. Efforts were made to reach out to SME Gordon Shaw but he was unable to correspond, Caroline stood in as the SME for the purposes of completing this project. 

# User Testing and Refinement 

User testing was created in a Google Docs form using potential real world scenario testing. Various scenarios were created and a chart was made for testers to record their answers in a chart. The testing scenarios didnt need to be too complex, the answers were mostly yes and no for checkbox purposes, the feedback that was necessary was whether or not the questions being asked for the yes/no questions were 1. understandable in plain language terms 2. able to convey what this yes/no question was going to do or not do and 3. whether the instructions on the cover page of the final document made sense and if the documentation reflected the answers of the tester. 

Testing was done by 2 volunteers who provided feed back similar to what was asked above. Below are examples of the issues found and correlating solutions

  Tester1 1: 
1. id: intro page says "IMPORTANT" at bottom but nothing else, possibly just a mistake as the next page is titled important requirement 
2. on id: filing requirements page "Is the appointment before 24 hours of when you plan to file this petition?" unclear in wording? maybe plain english, like, "is the appointment more than 24 hours before you plan to file this petition?" 

  Solution: 
1. The word "Important" was deleted from id: intro page.
2. Language edits made to this quesiton to make it sound less confusing. 

  Tester 2:
1. I was never asked to describe the conditions for paragraph 6 on the document.
2. in paragraph 4 of the document it shows up as per "Montly" which was my selection, but per month would make more sense 
3. In (id: explaining the petition) this page is confusing, I would say something that tells them what they have already done, rather than what  is automatically asked for if that makes sense. It would be nice to be able to say yes or no if you want to ask for any other remedies and if they say no skip past. 


  Solutions: 
1. In section 6 of the pdf it used to say "the conditions decribed above" which was wrong. The pdf was edited to say "the conditions described in "exhibit A"" which is the document that will outline the isses found in the inspection by a code enforcement agency.
2. In the rent section the language was changed to fit better to the language on the pdf document so instead of saying  monthly or daily it now says per day or per month.
3. This was a page made in consultation with Caroline during her suggested edits. We bleive it is important to tell them what they are already getting from the interview and allow them to ask for further edits. 

A link to the testing scenarios google sheet can be found [Here](https://docs.google.com/spreadsheets/d/1It5dTveXSbWouF2F1Fo68ixqr6wgcQQczGgQy8JLpT0/edit?usp=sharing)

In addition to the recorded user testing there are updates from former pushes by both Maeve and Caroline. 

# What this Product Improves

I belive this product provides any user with more context for which they would need to understand the process they are attempting to begin, as well as more information about the individual solutions. 

For Example, in section 8(b) the document from Mass Legal help asks them if they wish to file an injunction or restraining order. The average user will not know the difference between these two terms, nor what those will specifically ask for. This would be acceptable at an in-person court assistance office, but since the pandemic began, they will not have the interactions with a legal professional necessary to get this information. Therefore, the abiillty to explain what an injunction is, where to go to ask for an official inspection report, what information the court will want, this is all very valuable information that a person will not get from a fillable pdf. The addition of context alone makes this interview more valuable than the Mass Legal help version already.

This also allows the basic information to be entered in an appealing manner, users dont have to worry about fitting everything into a single space, sloppy hand-writing or whether or not they need to fill out a specific section. Lastly, the ability to print multiple identical documents is valuable for court proceedings so that everything is synomynous. 

The reach of this form is great too, any application that can be filled out on a computer or mobile phone easily will not only allow more tenants to begin this proceedings they are legally entitled to, but the ease and accessibility will encourage them to do so. 

# Future improvements

This court form needs further plain language and subject matter expert input in order for it to be as easy and usable as possible. There are certain things that I am not entirely confident that i explained in the best sense and will need an SME to improve upon. 

This court form also needs accessiblilty for more than one tenant to be added to the plaintiffs party at once, but this is not an MVP issue.

Other than that I believe that this is ready to go and is usable to a basic MVP level. The proceeding is not too complex so long as it is accompanied by the relevant inepction report that details the damage that the tenant is complaining about. 

## Video demonstration

View a demonstration of this project [Here](https://youtu.be/GH01BMXqV-Q)
