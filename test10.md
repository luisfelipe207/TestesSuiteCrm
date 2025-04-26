# Test Case 07: Data Import

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Data Import**

## 3. Description
This test verifies whether the SuiteCRM system correctly imports records from a CSV file, validating fields and allowing the addition or updating of entries.

## 4. Objective
To ensure that the data import functionality works as intended, correctly processing CSV files and handling field validation appropriately.

## 5. What is Being Tested
The data import tool within the Contacts module of SuiteCRM.

## 6. Prerequisites
- Valid Admin user credentials:
  - Username: `admin`
  - Password: `admin123`
- A properly formatted CSV file prepared for import
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Log in as Admin at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Navigate to the **Contacts** module
3. Select the option **Import Contacts** from the menu
4. Upload the CSV file prepared for the test
5. Set the source of the file if necessary
6. Validate the field mappings to ensure correct alignment
7. Proceed with the import process
8. Verify that the new records are correctly inserted or updated within the system

Path used:
- **Contacts** → **Import Contacts**

## 8. Expected Result
The system should successfully import the records from the CSV file, with all fields correctly mapped and records either added or updated as configured.

## 9. Actual Result
The records were imported correctly, and the system provided a complete and helpful validation step before finalizing the import. However, a visual UI bug was observed where, after some steps, the page did not return the user to the top, causing minor confusion and time loss.

## 10. Result Analysis
🟡 **Test Partially Passed** — Although the data import itself was successful, a minor UI bug slightly affects the user experience during the import process.

## 11. Error Description (if applicable)
- **UI Bug**: After certain import steps, the system does not automatically scroll the user back to the top of the page.
- **Impact**: Causes confusion and minor delays for users unfamiliar with the interface.

## 12. Evidence
- ✅ Screenshot: `data_import_success.png` (attach in GitHub repo)
- ⚠️ Screenshot: `ui_scroll_issue_import.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
