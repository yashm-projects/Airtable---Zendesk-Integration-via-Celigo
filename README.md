# Airtable-Zendesk-Integration-via-Celigo

**Note** -
Using Zendesk, Airtable & Celigo trial accounts.
All data being used is dummy data & for my learning purposes.
This project is still in progress, as I will be tweaking the mapping and integrating more platforms

Building out Airtable-Zendesk integration via Celigo.

WHAT?
Import records from the Airtable "Tasks" table and export them in Zendesk as tickets.

**Celigo steps**
<img width="959" height="337" alt="image" src="https://github.com/user-attachments/assets/6eda98fd-f73f-45e0-a654-8ef931f8ddfa" />

**Airtable (source), using the Tasks table to export only those records that have {Send as Zendesk Ticket} ✅**
<img width="917" height="266" alt="image" src="https://github.com/user-attachments/assets/1500d0b3-6e62-4e1f-acae-4d7bd9f48579" />

**Sample tickets imported in Zendesk based on the applied query parameter**
<img width="958" height="290" alt="image" src="https://github.com/user-attachments/assets/e5edb9ba-fed3-4e10-963c-85f51e1b5f08" />

**Mapping in Celigo**

<img width="941" height="379" alt="image" src="https://github.com/user-attachments/assets/bac4cfa8-82bc-4cea-bd75-29702ee304ed" />


**The project is in progress. Next up...**
Build a callback step from Zendesk to Airtable to indicate that the ticket was imported successfully, and then trigger a Slack alert from Airtable to the relevant channels/teams.
Use a pre-defined schedule to check new tickets and ultimately use a Webhook to run a flow in real time.
