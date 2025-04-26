# Test Case 08: Data Export

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Data Export**

## 3. Description
This test verifies that the SuiteCRM system correctly exports contact records and that the resulting file includes complete and accurate information.

## 4. Objective
To ensure that the data export functionality works properly, generating a file with all the intended data fields without corruption or loss.

## 5. What is Being Tested
The data export tool within the Contacts module of SuiteCRM.

## 6. Prerequisites
- Valid Admin user credentials:
  - Username: `admin`
  - Password: `admin123`
- Existing contact records to be exported
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Log in as Admin at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Navigate to the **Contacts** module
3. Select the contacts you wish to export
4. Click on the **Actions** menu and choose **Export**
5. Download the generated file
6. Open the exported file to verify that all intended fields and records are present

Path used:
- **Contacts** → **Select Records** → **Actions** → **Export**

## 8. Expected Result
The system should successfully generate a file containing the selected contacts, with all fields populated as recorded in the CRM system.

## 9. Actual Result
The data export was successfully completed. The exported file contained all the expected fields and records without any data loss or corruption.

## 10. Result Analysis
✅ **Test Passed** — The export functionality worked as expected, generating a complete and accurate file of contacts.

## 11. Error Description (if applicable)
N/A — The operation executed as expected without any issues.

## 12. Evidence
- ✅ Screenshot: `data_export_success.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
