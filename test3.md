# Test Case 03: Creation of New Contact

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Creation of New Contact**

## 3. Description
This test verifies whether the Contacts module allows the creation of a new record using minimal required data.

## 4. Objective
To ensure that a new contact can be successfully created using only the “First Name” field while leaving other fields blank.

## 5. What is Being Tested
The contact creation functionality in the Contacts module of SuiteCRM.

## 6. Prerequisites
- Valid Admin user credentials:
  - Username: `admin`
  - Password: `admin123`
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Log in as Admin at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. From the dashboard, navigate to the **Contacts** module
3. Click on **Create Contact**
4. In the creation form, fill in only the **First Name** field with: `TestUser`
5. Leave all other fields empty
6. Click **Save**
7. Confirm that the contact is created and listed in the Contacts module

Alternative access:
- Navigate directly to:  
  [https://crm.alunostds.dev.br/index.php?module=Contacts&action=EditView](https://crm.alunostds.dev.br/index.php?module=Contacts&action=EditView)

## 8. Expected Result
The system should accept the minimal input, create a new contact with the provided name, and redirect to the detail view of the newly created contact.

## 9. Actual Result
The system successfully created a new contact using only the name `TestUser`. The contact detail view was displayed after saving.

## 10. Result Analysis
✅ **Test Passed** — The system allowed creation of a contact with only a name and functioned as expected without errors or warnings.

## 11. Error Description (if applicable)
N/A — No errors or issues occurred during this test.

## 12. Evidence
- ✅ Screenshot: `contact_creation_testuser.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
