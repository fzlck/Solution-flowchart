1. INSTANCE (GCP SQL)
Create new INSTANCE w/ Postgres

2. DATABASE (GCP SQL)
Prerequisite: INSTANCE
Create (postgresql) DATABASE under INSTANCE

3. BUCKET (GCP Cloud Storage)
Create storage bucket

4. DUMPFILE (LOCAL)
https://github.com/fzlck/Solution-flowchart/blob/master/postgres%20dumpfile%20for%20google%20cloud%20sql

5. DUMPFILE TO BUCKET (GCP Cloud Storage)
Prerequisites: BUCKET, DUMPFILE
Upload DUMPFILE to Cloud Storage BUCKET

6. Enable Cloud SQL Admin API (GCP)
https://console.developers.google.com/apis/api/sqladmin.googleapis.com/overview?project=sonic-airfoil-445613-m4

7. DUMPFILE - DATABASE (GCP SQL: Overview)
Import dumpfile from bucket (source) to database in the instance (destination)

<img width="1146" alt="Screenshot 2024-12-25 at 5 48 37 PM" src="https://github.com/user-attachments/assets/f07ceb6b-5670-4d2c-bdb7-4d99c81f0026" />

---

Open cloud shell
gcloud sql connect instancepostgresql --user=postgres --quiet

8. Connect to desired db
\c chopin-db

10. Test some queries

<img width="761" alt="Screenshot 2024-12-25 at 6 57 35 PM" src="https://github.com/user-attachments/assets/c5590636-a567-496d-9de3-747851965fad" />



