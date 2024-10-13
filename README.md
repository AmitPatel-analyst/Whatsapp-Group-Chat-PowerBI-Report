# Whatsapp-Group-Chat-PowerBI-Report
Cleaning and analysing WhatsApp group chat data as well as report design in PowerBI

## Data Gathering & Transformation
To get the WhatsApp chat data, I simply exported the chat from the WhatsApp group by navigating to the ellipsis at the top right corner of the group chat and selecting "Export Chat". That exported the chat as a text file. However with this method, one is limited to only 40,000 messages (without media). The exported chats needed to be transformed for ease of analysis and it was done using Power Query.   

## Report Requirement   
The initial purpose of creating the report was to see the overall trend of conversations on the group and identify what period of time the most conversations took place. However, during the report design I was also interested in creating a report that lets the individual members of the group see their level of activity on the group over time. In summary, the report requirement was to provide an overall trend of group activity and let each group member see their activity.    

## Data Modeling
For the Data Model the key tables that needed to be created were:

|Table Name | Description |
|-----------|-------------|
|Chats|This would contain the messages, when they were sent, what time and by who
|Dates|A standard date table
|TimeTable|A time table to facilitate analysis across time; hourly, by minute, AM/PM)
|Person|A table containing a unique list of the group members  

After all the tables are created, the needed relationships are created and it looks like this:    

## Report Design  
The design layout was designed in PowerPoint to have an idea of what I wanted the final output to be in PowerBI.   

## Live Report
you can explore the interactive version of the report to see the full functionality and User Experience. [WhatsApp Analytics](https://app.powerbi.com/view?r=eyJrIjoiMWM4Zjc5NWEtZDg4YS00YmUxLTlmYjgtYTA1Y2NhMDNiOTMxIiwidCI6IjA3ZjAxN2QwLWJiNzEtNDliYS1iMTMxLTJkZDkyZWQ3MWE3MiJ9)

Thanks to Great PowerBI Report Creator @BolajiBI
