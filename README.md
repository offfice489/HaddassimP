## Corona management system for the HMO
This system manages a database that contains all the details of the insured, including details about the corona virus,
Such as the number of vaccinations received, the vaccination company, the date of receiving a positive answer if applicable and the date
recovery from the virus.

For the purpose of writing the code I used the visual studio 2022 software
computer Windows 10

### Screenshots
This is the form through which you can execute the queries to get the information from the database.
![theForm](https://github.com/offfice489/HaddassimP/assets/129285639/61d77939-2880-4a64-b3dd-2910dfb91165)
On the top left is the title: search by ID. In the textbox you can enter the ID of the insured and we can see all his personal details. fish':
![searchID](https://github.com/offfice489/HaddassimP/assets/129285639/7c99564f-1e16-4c35-bd8a-6a231c6b84f4)
![outputPatientDetails](https://github.com/offfice489/HaddassimP/assets/129285639/b23123cd-0ffd-4fe7-a5a5-a48245b2e5ca)
Select vaccination's details about specific ID:
This query retrieves information about all the insured's corona vaccinations. For each vaccine, the date of vaccination and the manufacturer of the vaccine will appear.
![vaccinationDetailsToID](https://github.com/offfice489/HaddassimP/assets/129285639/00a36d2a-a592-4d0e-96af-79153a9597ee)
![outputPatientDetails](https://github.com/offfice489/HaddassimP/assets/129285639/0fb046a6-92ed-44f6-bb13-584709d21c34)
Select all patients that did specific vaccination:
This query receives a vaccination number (1-4), and retrieves the details of the insured persons who had the same vaccination number:
![numVaccinate](https://github.com/offfice489/HaddassimP/assets/129285639/26cf4911-5f32-48e9-ba9d-6a68e6c4599b)
![outputVaccinateTable](https://github.com/offfice489/HaddassimP/assets/129285639/e2388d48-7a62-4fd1-b0f5-032d02190945)
Add patient:
In this query, the user can enter insured information (he must fill in all the text fields below), and by clicking on add - a new insured will be added to the data of the insured in the health fund.
![addPatientButton](https://github.com/offfice489/HaddassimP/assets/129285639/c90b67be-13d8-4e3b-8f4a-2f3a1eb488db)
the patient details table in sql:
![addPatientToSql](https://github.com/offfice489/HaddassimP/assets/129285639/4c1431ea-9b3c-438e-ade0-66ff10072cfe)
