HOSPITAL MANAGEMENT SYSTEM.


Hospital management system project is just a console application without graphics, designed for Alka Hospital, situated in Lalitpur, Nepal.
This project mainly uses file handling to perform basic operations like how to add, edit, search and delete record using file.


REQUIREMENTS:

1. Add a new patient record : In this feature, user can add a new patient record choosing between O.P.D. service and Emergency service. In O.P.D. service (shown in output screen below), name, address, age, sex, disease description and specialist room number to be referred are available. Thus given information is stored in file. The information to be given are same in Emergency service.

2. Search or edit patient record : All the information corresponding to the respective patient are displayed. These include the ones provided while adding a new patient record. If wrong information about record number or patient full name is provided, the program displays a message saying that no records were available.

    Also, user can view the list of expenditures of the particular patient whose record is sought. In the program, the financial information include total charge, total deposited and total money to return.
    
3. List record of patients : 

* Records of patients in alphabetical order
* Records of Emergency patients
* Records of O.P.D. patients
* Records of patients in a particular date

4. Delete patient records : This features allows user to delete added record of any patient. For this the patient number to be removed is to be provided. Upon ‘Enter’, user can view the patient record and the financial records of the patient. To delete the record, press ‘Enter’ and the respective patient record will be deleted from the file.



https://www.code-inspector.com/project/25036/score/svg
https://www.code-inspector.com/project/25036/status/svg


# MATRIX CALCULATOR
### 
## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

| Feature Id | Feature |
| -----------|---------|
|F_01| Options to select matrix operation|
|F_02| Operations on two matrices such as addition, subtraction and multiplication are included|
|F_03| Single matrix operations such as determinant, transpose and inverse of a matrix |
|F_04| Separate function for each operation |
|F_05| A structure has been implemented for storing the matrices|
|F_06| Dynamic memory allocation and deallocation has been implemented for the matrices|
|F_07|  There is no upper limit for the size of the matrix|

## Challenges Faced and How Was It Overcome

| No. | Challenge | Solution
|-----|-----------|--------
|1. | Dynamic memory allocation of 2D arrays created segmentation faults| running the code in GDB helped find the line where the program crashes
|2. | Program crashes | Writing clean code with allocating and deallocating memory at all functions as per requirement|
|3. | Logical errors faced while designing matrix operations| Referred some articles to revise matrix basics and operations on 2D arrays
|4. | Unit testing on dynamic 2D array outputs| Created enumerated variables to be returned by those functions if the specified operation executes successfully
