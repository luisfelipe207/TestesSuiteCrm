# Test Case 05: Deletion of a Contact

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Deletion of a Contact**

## 3. Description
This test validates whether a contact can be successfully deleted from the system using the available UI options in the Contacts module.

## 4. Objective
To confirm that deleting a contact removes the record effectively from the system without leaving residual data.

## 5. What is Being Tested
The deletion functionality in the Contacts module of SuiteCRM.

## 6. Prerequisites
- Valid Admin user credentials:
  - Username: `admin`
  - Password: `admin123`
- At least one contact already exists (e.g., `TestUser Edited`)
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Log in as Admin at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Navigate to the **Contacts** module
3. Click on **View Contacts** to list existing records
4. Locate and click on the contact (e.g., `TestUser Edited`)
5. In the contact’s detail view, click **Actions** and select **Delete**
6. Confirm the deletion by clicking **Proceed** in the confirmation prompt
7. Verify that the contact no longer appears in the contact list

## 8. Expected Result
The selected contact should be completely removed from the system and no longer appear in the Contacts list.

## 9. Actual Result
The contact was successfully deleted. The system redirected back to the contact list, and the deleted contact was no longer present.

## 10. Result Analysis
✅ **Test Passed** — The deletion operation worked correctly, and the contact was effectively removed from the database and UI.

## 11. Error Description (if applicable)
N/A — The operation executed as expected without any issues.

## 12. Evidence
- ✅ Screenshot: `contact_deletion_confirmation.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
