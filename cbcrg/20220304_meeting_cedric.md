# Meeting with Cedric

## Topics

### 1. BovReg

#### 1.1 Pending deliverables/milestones

##### 1.1.1 MS29- Cloud deployment

**Month 30** - Working in the document, quite general don't know if the will ask for more details but I will try.

[Gdocs](https://docs.google.com/document/d/1CzkuienmghrHaeIu2pcZ5lH6SAFurMng/edit?usp=sharing&ouid=113761000134872093168&rtpof=true&sd=true)

##### 1.1.2 MS25 - Survey workflows

**Month 31** - Did not start working in the document. I will also create a very simple report and then if they want us to do more stuff we do it. Like establishing actions, which I guess they will...

##### 1.1.3 MS28 - Survey evolutionary annotation

**Month 31** - **URGENT** we need still to create the survey. Maybe we can brainstorm in a gdocs about the questions? 

* From the DoW:

*Milestone title*: Establishment of current needs and possible gaps for bioinformatic analysis of integrated data, including evolutionary information."

*Means of verification*: M28 Catalogue of needs and possible gaps for bioinformatic analysis of integrated data, including evolutionary information verified through Survey.

#### 1.2 Other stuff

##### 1.2.1 eMail to euroFAANG pipeline group

Email sent by Peter

*Our analyses are likely complimentary, all of the projects are now using nf-core pipelines and we really should try to ensure as much standardisation here as possible.*
*In regards to EMBL-EBI pipelines. For BovReg for example, these Ensembl analyses are seen as “complimentary” to the project so will be performed, but all of the scientific working groups and research outputs are largely planning to utilise analysis outputs from the nf-core pipelines.*

*I feel that for the comparative working group it could well be Ensembl outputs that are used, but could also be nf-core. The main issue with Ensembl is timing, with the large delays to data production, for all of the projects we have missed the planned processing periods for each of their data. Ensembl requires all data to be public in ENA before it can be processed and also needs to schedule the analysis for an appropriate Ensembl release. It therefore may well be that analysis by nf-core would be more timely, but obviously you then need to find someone to run the combined analyses, or ensure that each projects analyses are already standardised. This is also where establishing the EuroFAANG pipelines working group (that Cedric was to launch) to focus these efforts would be very useful. As would the standardised output log file from nf-core pipelines that we could then make a mandatory part of FAANG.*


#### 1.2.2 Contribution to Peter workshop

**DATE**: 07/04/2022-14:00 to 18:00

Once Jose is ready with a firmer plan, let me know and I will doodle poll for a time for us to chat in February or March so that we can discuss the course and also the nf-core to FAANG connections in general to see if further improvements can be made.

**TODOs** Sent a doodle for set the meeting on March.

Try to have a meeting before with Phil and maybe Harshil to see what are the trends now in nf-core and what they plan in the future

#### 1.2.3 nf-core pipelines for Gabriel

#### 1.2.3.1 chipseq

He asked me if the pipelines will be ready for half March, I have been working in the chipseq and in principle we have to release next week.

#### 1.2.3.2 atacseq

It should be more straight forward but I don't see very feasible to be able to have it until the end of march with luck, two options:

[ ] Make our own bovreg release, we may have undetected bugs.

[ ] Make the release in nf-core and tell the partners that we may need a little bit more of time.

##### 1.2.5 Limoges

**DATE**: 07/04/2022-14:00 to 18:00

atac-seq nf-core pipeline should be ready but we have to develop what we want to show during the workshop in coordination with Gabriel.

### 2. VEIS

#### 2.1 GRAL ASSEMBLY NOTES

They probably will want us to make a nextflow course during 2022.

#### 2.2 Bencmarking project

Start the benchmarking project. Could Igor start exploring the simulator ?

### 3. nf-core/proteinfold

What should be my role?

### 4. tcoffee

#### 4.1 Fix CircleCI

In the long range it will be preferably to go for github actions, but I will try to implement a simple fix in the mean time.

#### 4.2 Bioconda Bot

This will need a little bit of rethinking on how the releasing process works.

Development branch and release in master. It is more tedious but in the long range it will pay off.

#### 4.Tcoffee bug

It works with the test dataset in the server.
The dataset send by the user does not work. We should see if it is:

1- A problem of the tcoffee version in the server

2- A bug both in the current version of tcoffee and the version of the server

3- A problem of the dataset, too big or memory intensive...
