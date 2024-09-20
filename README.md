## Applying Filters to SQL Queries

## Objective
The project involved leveraging SQL to investigate system security incidents, particularly login attempts and employee activity. This hands-on work focused on retrieving critical information from logs to enhance system security and detect suspicious activities. The investigation targeted after-hours login attempts, login activities on specific dates, and activities from specific regions or departments.

### Skills Learned
- Proficiency in applying filters in SQL to retrieve and analyze large data sets related to security events.
- Experience in analyzing login attempts to detect suspicious behavior.
- Improved knowledge in creating efficient SQL queries to address specific security incidents.
- Ability to derive insights from log-in attempts based on time, location, and departmental data.

### Tools Used
- SQL for querying and filtering data from system logs.
- Network log tables (e.g., log_in_attempts and employees) for in-depth analysis.

## Steps
![5-Applying Filters to SQL Queries-1](https://github.com/user-attachments/assets/7c3d2128-ba76-49a7-becf-9c795991b3d6)

Ref 1: Failed Login Attempts after Business Hours - 

To investigate potential security incidents outside of business hours, I queried the log_in_attempts table to retrieve all failed login attempts after 18:00. This allowed for targeted analysis of after-hours activity, highlighting any unauthorized access attempts.

![5-Applying Filters to SQL Queries-2](https://github.com/user-attachments/assets/dbcb0d50-c7ae-4261-9db0-97698b20a886)

Ref 2: Suspicious Login Activity on Specific Dates - 

For a more focused investigation, I created a query to retrieve all login attempts that occurred on specific dates, such as May 9, 2022, and the previous day, to detect any correlations in suspicious activity.

![5-Applying Filters to SQL Queries-3](https://github.com/user-attachments/assets/2f19425c-05a5-4f73-be37-e9793329cffc)

Ref 3: Login Attempts outside of Mexico - 

To further enhance the investigation, I generated a query to retrieve all login attempts originating from outside Mexico, allowing the identification of any geographically suspicious activity.

![5-Applying Filters to SQL Queries-4](https://github.com/user-attachments/assets/8ca6872e-246e-4b0a-a5f3-100cf00f7b92)

Ref 4: Departmental Employee Log-ins - 

I also focused on specific departments such as Marketing and Finance, filtering out login attempts based on employees from these areas. This helped isolate the activity of certain departments to ensure their systems were secure.
