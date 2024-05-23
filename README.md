# Anypoint Platform Reporting
Mule 4 Project for generating report on Anypoint platform account.

This project will provide a way to export anypoint platform data in reporting format for runtime manager, api manager, anypoint queues and other platform components data.

#Problem Statement
At this moment we do not have export functionality available on Anypoint platform which can export data in csv format. csv format exported data can be used for no of project management use case, e.g. to identify current usage, licence limit n identify how much headroom present so project allocation can be managed.

#Solution
Scheduler Based mulesoft project development which can be deployed on cloudhub as well as you can run locally as well.

#pre-requisite
1. Create connected app on anypoint platform which has almost full access on all business groups and environments. Add connected app client Id and secret on properties file.
2. setup drive location where you need csv file to exported.(make sure drive location is accessible by cloudhub app or local machine)





Contribution : Please use standard component and standard coding style while contributing.
