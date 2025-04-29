# dp-700-lab-05

# Microsoft Fabric Lab – Create and Use Dataflows (Gen2)

## Overview
This lab demonstrates how to create and use **Dataflows (Gen2)** in Microsoft Fabric to ingest, transform, and load data into a Lakehouse environment. It also shows how to orchestrate the data ingestion process using a pipeline.

## Steps Completed

1. **Workspace Creation**
   - Created a new workspace with Microsoft Fabric trial enabled.

2. **Lakehouse Creation**
   - Built a new Lakehouse to store ingested data.

3. **Dataflow (Gen2) Setup**
   - Ingested data from a CSV file using Power Query Online.
   - Performed data transformation:
     - Added a custom column `MonthNo` using `Date.Month([OrderDate])`.
   - Verified data types and transformation steps.

4. **Data Destination Configuration**
   - Connected the Dataflow output to the previously created Lakehouse.
   - Saved the table as `orders`.

5. **Pipeline Integration**
   - Created a Data Pipeline.
   - Added a Dataflow activity and linked it to the `Dataflow 1`.
   - Successfully ran the pipeline and ingested data into the Lakehouse.

6. **Validation**
   - Verified that the `orders` table was created and loaded with the expected data.

## Notes
- Power Query Online was used for transformations.
- Authentication was set to Anonymous for the public CSV file.
- This lab is designed for learning and not intended for production-level scenarios.

## Resources Used
- Microsoft Fabric Trial
- Dataset: https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/orders.csv
## Screenshots
![Screenshot 2025-04-29 at 19 34 31](https://github.com/user-attachments/assets/1904a253-d160-416b-a432-de13788c5261)
![Screenshot 2025-04-29 at 19 51 57](https://github.com/user-attachments/assets/23f0e65d-a3e2-4c6f-961a-be414d73aa8a)
![Screenshot 2025-04-29 at 19 33 56](https://github.com/user-attachments/assets/223f974e-8bb4-4167-be75-eae4afe30ac0)
![Screenshot 2025-04-29 at 19 33 28](https://github.com/user-attachments/assets/55b2a1bd-cded-4ef9-9f50-1fc1a624ce06)
![Screenshot 2025-04-29 at 19 31 29](https://github.com/user-attachments/assets/b72be156-786e-457d-8f5b-8d8b08f2e8e7)
![Screenshot 2025-04-29 at 19 30 48](https://github.com/user-attachments/assets/261990ef-c259-4eef-844a-fc3d1401e070)
![Screenshot 2025-04-29 at 19 29 28](https://github.com/user-attachments/assets/5b59de58-44c4-47c1-bbee-791493586a1c)
![Screenshot 2025-04-29 at 19 29 21](https://github.com/user-attachments/assets/fa70a121-e904-4d03-9cd4-aea3bf8f0bb9)
![Screenshot 2025-04-29 at 19 51 20](https://github.com/user-attachments/assets/6c5514c1-2b42-4398-b6f6-66c051cc5d34)
![Screenshot 2025-04-29 at 19 49 37](https://github.com/user-attachments/assets/c30162a1-c8c1-406c-a213-bf5bda297028)
![Screenshot 2025-04-29 at 19 41 30](https://github.com/user-attachments/assets/d0885ed7-1777-4d8c-83a4-459edcadc980)
![Screenshot 2025-04-29 at 19 41 02](https://github.com/user-attachments/assets/84fd356a-cc9b-4185-9577-ecc678978600)
![Screenshot 2025-04-29 at 19 38 25](https://github.com/user-attachments/assets/f24a8ebb-791f-475a-a1ac-865b7d3f091c)
