# Email-Process-Analysis
This was an ongoing effort to create a Business Continuity plan for an organization regarding their automations. The actual automation names have been hidden for anonymity purposes. 

This project was split into two major components:

1. Retrieve the automation data from the local database. Existing security controls within the organization prevented me from retrieving data directly from the Jupyter notebook, therefore, this required reading the data from an SQL query I created to downloading it and subsequently loading the data in the Jupyter Notebook.

2. Data cleaning, amalgamation, and manipulation.

   The result is an Excel file that the operations team can leverage to run automations and tasks relative to the previous schedule manually. The inventory of all automations is huge, and thus, additional filtering features, such as marking automations by priority levels, should be incorporated to ensure that needed outputs from automations are met promptly.

   This was a unique project, as it required substantial data manipulation post-retrieving the data from the database. The most difficult component of this project was contextualizing run times by date, which went through multiple iterations.\, e.g. Mon 2am-9pm, Thursday (3am-6am). This proved difficult when I was using conditional formatting in Excel to simulate a schedule, so I opted to split automations into unique rows by run day. E.g. there is a field that shows that the automation runs Mon-Fri 9am-6pm, but there is a unique row for each day of the week e.g. Friday.


   



