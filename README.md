# 📊 Task 1 - Google Cloud Storage Bucket Setup

## Objective
Create and configure cloud storage using Google Cloud Storage (GCS).

## Deliverables
- GCS bucket with uploaded files
- Configured access permissions

## Tools Used
- Google Cloud Storage
- Git & GitHub
  
## Steps Followed
1. Created GCS bucket
2. Uploaded sample files
3. Set public access for uploaded files
4. Verified access via public URL

## Screenshots
- Bucket Creation (codetech-task1) ![Screenshot (75)](https://github.com/user-attachments/assets/dca090b1-5ca4-4e6b-9ffc-b61663c8acf4)
- Files upload (CLOUD COMPUTING.pdf & IMDB Dataset.csv) ![Screenshot (77)](https://github.com/user-attachments/assets/3cf939d8-c82f-4df7-b2f4-3ffee63b34e8)
- Access permissions ![Screenshot (78)](https://github.com/user-attachments/assets/6b0b4b14-12c2-407c-9c2d-137329fab6e9)

## Public URL
- [GCS Bucket](https://console.cloud.google.com/storage/browser/codetech-task1)


---

# 📊 Task 2 – Cloud Monitoring and Alerts

## Objective
To set up monitoring and alerts for a cloud-based application/resource using **Google Cloud Monitoring**.

## Deliverables
- Uptime Check for a public file hosted on Google Cloud Storage (GCS)
- Alert Policy configured to trigger on Uptime Check failure
- Email notification set up and tested
- Dashboard created to visualize uptime data

## Tools Used
- Google Cloud Monitoring
- Google Cloud Console
- Google Cloud Storage (from Task 1)
- Gmail for receiving alerts
- GitHub for version control and documentation

## Steps Performed
1. Enabled Monitoring API
2. Created Uptime Check
3. Set Up Alert Policy
4. Dashboard Creation
5. Tested Alert

## Screenshots
- Uptime Check Setup
![Screenshot (81)](https://github.com/user-attachments/assets/60fad245-9f2d-4e8f-961e-61a19401ab0c)
![Screenshot (80)](https://github.com/user-attachments/assets/a48c915f-88b4-45c7-b33e-db6f06d0f74d)

- Alert Policy Config
![Screenshot (85)](https://github.com/user-attachments/assets/a06ea31b-95de-4521-beb6-700764d9e5e8)

- Dashboard Setup
![Screenshot (83)](https://github.com/user-attachments/assets/4d5343b6-cd1b-45a2-996d-16db842c400e)

## Alert Testing
- Temporarily deleted ```CLOUD COMPUTING.pdf``` from ```codetech-task1``` bucket.
- Alert Notification Mail
![Screenshot (88)](https://github.com/user-attachments/assets/214423cf-1eb6-4b16-8d91-46a4a28af601)
- Alerting Incident
![Screenshot (87)](https://github.com/user-attachments/assets/c4341738-b252-4f5a-b303-9c6758c0b7a9)
- Dashboard after alert triggered
![Screenshot (91)](https://github.com/user-attachments/assets/ae14d21c-e22e-408e-9517-3c1a48a2c7e8)


## Conclusion
- The monitored GCS file```CLOUD COMPUTING.pdf```is publicly accessible in incognito mode.
![image](https://github.com/user-attachments/assets/19027f09-0688-4314-8181-ea09d949e663)


## Public URL's
- [Uptime Details](https://console.cloud.google.com/monitoring/uptime/task1check-4qxJRkBjr9I;startTime=2025-05-28T06:06:36.000Z;endTime=2025-05-28T07:04:38.000Z?inv=1&invt=AbylIA&project=bucket-create)
- [Alerting Policy](https://console.cloud.google.com/monitoring/alerting/policies/7492110310646992765?inv=1&invt=AbylIA&project=bucket-create)
- [Dashboard](https://console.cloud.google.com/monitoring/dashboards/builder/295c3c44-1465-4c9a-92ec-bd37dd829f6c;startTime=2025-05-28T06:06:36.000Z;endTime=2025-05-28T07:04:38.000Z?inv=1&invt=AbylIA&project=bucket-create&pageState=(%22eventTypes%22:(%22selected%22:%5B%22CLOUD_ALERTING_ALERT%22%5D)))
