Database Management and Database Design
# Hospital-Data-Management-System
 The hospital data management system is a case study of a mid-sized hospital prototype.  

Database is a data repository of different records collected from an Information System (Source). Database systems must follow proper structure, planning, designing, and implementation methodology to produce a reliable and effective system.The database systems project work is a prototype database system for Hospital Information/Data Management System. Implementing an advanced database will require a modification of the project strategies and procedures.

## Project Statement:<br />

The key agenda of any project to identify the problem and provide a solution using structured project work.

Manual record management system operations are both operationally and financially costly when it comes to managing client records: <br />
•	The manual record management system cannot give us a proper understanding of the healthcare service consumer base. <br />
•	Data and information are not adequately protected. <br />
•	There is a possibility that the patient data and information may be exposed for unauthorized modifications. <br />
•	Maintaining a manual record-keeping system might be too onerous. <br />
•	Data access is insufficiently controlled. <br />

## Implementation Objectives: <br />
•	We must guarantee that patient data is acquired correctly, processed effectively, securely kept, and retrievable by authorized users for operational purposes. <br />
•	The database will make client records available in real-time so that services may be provided to them.<br />
•	Structure of the database is simple and easy to filter the data.<br />
•	System administrator will be given privileges to handle the accounts and permissions for the view. <br />
•	Patient’s data is stored in different levels and can be accessed by the “Patient_ID”. <br />
•	The doctor will be able to access patient’s medical records but not personal information.<br />

## Proposed Solution:<br />
To overcome the above problems, a model can be used. The issues are resolved as follows. <br />
•	To avoid cluttering we have divided the patient data into tables interlinked using the primary and foreign keys for integrity and uniqueness of data. <br />
•	Using the database design, the doctor can access the records of patients such as Patient Vital Signs, Patient Lab tests, Patient Medication and Patient Medical History without disclosing the patient personal information. This guarantees data security. <br />
•	All the patient billings records can be shown in one table that is ‘Patient_Invoice’ entity rather than creating separate tables for different entities. <br />
•	The database contains staff entity that includes the records of the other staff in the hospital excluding doctors for instance nurse, reception, department with respective ‘Staff_Id’ as primary and ‘Department_Id’ as foreign key. <br />


