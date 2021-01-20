# 2020-Work-History


 > **Sadly due to complicated legal requirement's I am not allowed to share the source code from [2016](https://github.com/Lwachira/2016-Internship), [2018](https://github.com/Lwachira/2018-Work-History), [2019](https://github.com/Lwachira/2019-Work-History) with you. If you wish to pursue this further, we should chat, I can explain all the interesting things I built over the last 3 years**.

## What is this?

The work here is a representation of the work I did in 2020. This was different from previous both what was going on with the world in 2020 as well as my personal growth that same year. If 2019 was the year I learnt and grew more so than ever, 2020 was the year those new hard worn skills became more refined and polished. 

I have 7 applications currently running and being used in the company. Two of those are user-facing programs in the form of a jQuery Application as well as an asp blazor application. 


### Table of Contents
- [ElasticSearch Python Extractor](#elasticsearch-python-extractor)
- [EmailLogger](#emaillogger)
- [QueueMetricsExtraction](#queuemetricsextraction)
- [SiebelCRMAutoAssign](#siebelcrmautoassign)
- [SiebelCRMServiceRequestExtract](#siebelcrmservicerequestextract)
- [LeadGenerator](#leadgenerator)
- [lexisebook](#lexisebook)
- [Failed Projects](#failed-projects)
    - [ActiveCampaignLogger](#activecampaignlogger)
    - [CRMSyncService](#crmsyncservice)
    

# ElasticSearch Python Extractor

This one was fun. Previously an outsourced company built a similar service, their version was a C-sharp application that needed to update once a month, it often broke and was very expensive for the business to own. In come's Lincoln, who happens to have some python experience and a solid way to build this? The new version uses only a handful of imports and some beautiful python magic.

# EmailLogger
Very similar to [SiebelCRM365](https://github.com/Lwachira/2019-Work-History), the difference is no CRM system to interface with, just read emails then copy to database tables then move to a done email folder.

# QueueMetricsExtraction
An API extraction service, calling a very old piece of software called Queue Metrics. These old software’s are the business favorites, costs very little and automating these processes saves tons.

# SiebelCRMAutoAssign
This was a big win for manager and myself. So much skepticism before we started, essentially we need a way to Service Request Tickets to be assigned to reports, previously managers had to do the allocation work themselves, the way to calculate the cost saving would be (Managers pay per hour * hours spent) * number of days = total spend per month. We roughly got to R40k per month.

# SiebelCRMServiceRequestExtract
Another Extract service. Saved the company R10k per month.

# LeadGenerator
This was a new system to solve a 3-year-old problem the company had. Essentially marketing wanted to know the ISBN responsible for sales within the company.

# lexisebook
A site that enabled internal members to generate ebook links for sales done on the Lexis Nexis Ebook Store.

# Failed Projects

# ActiveCampaignLogger

An API extraction service, calling active campaign. I built it to work in both directions, reads from Active Campaign and pushes the data elsewhere as well as writes to Active Campaign. 

# CRMSyncService
We had an issue where our CRM was running out of space, so we built an achiever service that fetches files larger or older than a supplied amount and moves them to on prem storage instead of cloud, then we provide a link to access those files.
