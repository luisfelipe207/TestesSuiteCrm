# Test Case 04: Editing an Existing Contact

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Editing an Existing Contact**

## 3. Description
This test checks whether the SuiteCRM system allows users to edit a contact that has already been created and whether changes are saved and reflected correctly.

## 4. Objective
To verify that the contact editing functionality works as intended and that all modifications persist after being saved.

## 5. What is Being Tested
The contact editing functionality in the Contacts module of SuiteCRM.

## 6. Prerequisites
- Valid Admin user credentials:
  - Username: `admin`
  - Password: `admin123`
- At least one contact already exists (e.g., `TestUser`)
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Log in as Admin at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Navigate to the **Contacts** module
3. Locate and open an existing contact (e.g., `TestUser`)
4. Click the **Edit** button
5. Modify the contact's **First Name** to `TestUser Edited`
6. Leave other fields as-is (optional)
7. Click **Save**
8. Confirm that the changes are displayed correctly in the contact detail view

URL used for navigation/editing:
[https://crm.alunostds.dev.br/index.php?module=Contacts&action=EditView](https://crm.alunostds.dev.br/index.php?module=Contacts&action=EditView)

## 8. Expected Result
The system should save the changes made to the contact and display the updated information in the contact detail view.

## 9. Actual Result
The system successfully updated the contact. The edited name (`TestUser Edited`) was saved and reflected in the contact view without errors.

## 10. Result Analysis
✅ **Test Passed** — The contact editing functionality worked as expected. Changes were saved and properly displayed.

## 11. Error Description (if applicable)
N/A — No issues were found during this test.

## 12. Evidence
- ✅ Screenshot: `contact_edit_testuser_edited.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
