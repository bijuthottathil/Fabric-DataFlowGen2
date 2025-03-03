# Create and use Dataflows (Gen2) in Microsoft Fabric

Create new workspace in Microsoft Fabric

![image](https://github.com/user-attachments/assets/9a20f44f-ed94-4db5-aeac-1e9e8402a47b)

Next Step is to create new Lakehouse from Data Engineering Section
![image](https://github.com/user-attachments/assets/5741b684-455d-4b8d-b84a-fdb852a43e94)

![image](https://github.com/user-attachments/assets/8db0e490-f2ae-4172-853e-d2f24fede953)

Create a Dataflow (Gen2) to ingest data  . Get Data--> New DataFlow Gen2-->

![image](https://github.com/user-attachments/assets/513dacb8-3af9-4362-a7fb-f0c3257722ff)

Select Import from a Text/CSV file and choose below csv file,
![image](https://github.com/user-attachments/assets/5472781e-25c0-4bc9-9592-ea0463b1559b)


![image](https://github.com/user-attachments/assets/fcc202ea-39fe-40dd-beba-ac07c437cec9)

![image](https://github.com/user-attachments/assets/8c8520d8-a623-4b69-922f-92940eb22f91)


![image](https://github.com/user-attachments/assets/f9e9e63f-78be-4d61-a797-3c3cc1cb87d0)

![image](https://github.com/user-attachments/assets/3c3df762-82dc-4260-8289-acd8782d74b1)
Adding a custom column

![image](https://github.com/user-attachments/assets/01e2a485-37b0-406d-bc40-58e68748495b)

Next we need to set destination ![image](https://github.com/user-attachments/assets/a2062204-716c-47a3-9fbe-7288546fa495)

I have opted Lake house

![image](https://github.com/user-attachments/assets/f631c503-3ef8-4280-b574-d223c93f3c1b)

![image](https://github.com/user-attachments/assets/28fc70cb-d5ea-425e-b1f8-08d2e91a788d)


![image](https://github.com/user-attachments/assets/4c614b0f-00c1-4020-93eb-bbc62eaa8557)

Now we will publish this table to Lake house

![image](https://github.com/user-attachments/assets/aa297221-4983-44d4-8f57-1b32e7a6d810)


Add a dataflow to a pipeline
You can include a dataflow as an activity in a pipeline. Pipelines are used to orchestrate data ingestion and processing activities

![image](https://github.com/user-attachments/assets/7469174f-e74c-4bbd-b2f0-7fa40dc4c1d8)

![image](https://github.com/user-attachments/assets/c6b2dbc3-aad4-4be6-b3d5-864cd2600b45)

Save and Run pipe line

![image](https://github.com/user-attachments/assets/296aeae3-e1f1-44ae-937a-56e084be78f4)

![image](https://github.com/user-attachments/assets/171aa81c-f351-4ad9-9aff-9ab500c63c56)


You can see delta table is created in lake house

![image](https://github.com/user-attachments/assets/783d7802-7415-4cf6-bb3c-ce4a58847071)

To view the content, we can open a notebook and browse data


![image](https://github.com/user-attachments/assets/de9246b1-4501-4513-b4e5-eee8364c99d3)

FInally I am creating a symatec model for Power BI here

![image](https://github.com/user-attachments/assets/5499d62b-c138-4369-999d-db57c7ea20fd)


Power BI report is generated from the model

![image](https://github.com/user-attachments/assets/e3aaa139-2981-438a-9ec0-019a2b61af67)


