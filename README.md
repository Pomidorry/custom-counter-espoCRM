# Custom Counter EspoCRM

## Features
- Create custom counters for tracking various metrics within your CRM.
- User-friendly interface for easy management of counter settings.
- Real-time updates and reporting capabilities.
- API integration

## Installation
- Download the extension package from the repository.
- Access your EspoCRM instance and navigate to the Admin panel.
- Click on "Extensions" and select "Install."
- Upload the downloaded package and follow the on-screen instructions to complete the installation.

## Configuration
- To activate counter recording you need to go to "Scheduled Jobs" -> "Create New Job" -> find "CounterJob" and set Scheduling with crontab notation for the job to work on a scheduled time. <br></br>
![image](https://github.com/user-attachments/assets/8e4e29e3-41e5-4108-8f52-563f4013e5c8)
- Set integration you HMAC API User credentials if you want to post data to your detination url <br></br>
![image](https://github.com/user-attachments/assets/cbd80ded-1f09-4e2b-bbeb-acb1c866532e) <br></br>
(I entered localhost so both save data directly and post to my crm simulteniously)
![image](https://github.com/user-attachments/assets/29dc9079-84d9-4e15-b5d7-4f3d32f63b5f)

> [!NOTE]
> This extension is developed specifically for Linux systems and may not be fully supported on other operating systems.
