# Test Case 06: Record Search

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Record Search**

## 3. Description
This test evaluates the search functionality within the SuiteCRM system by using different search criteria such as name, email, and phone number.

## 4. Objective
To ensure that the search engine accurately retrieves records based on various input criteria and displays precise results.

## 5. What is Being Tested
The search mechanism for contacts and records within SuiteCRM.

## 6. Prerequisites
- Valid Admin user credentials:
  - Username: `admin`
  - Password: `admin123`
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection
- Existing records with data in fields like name, email, and phone number

## 7. Test Procedure
1. Log in as Admin at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Navigate to the **Contacts** module
3. Use the search bar at the top of the page
4. Perform a search using:
   - A contact’s **First Name**
   - A contact’s **Email Address**
   - A contact’s **Phone Number**
5. Verify if the corresponding records are accurately retrieved and displayed.

## 8. Expected Result
The system should accurately return the correct records matching the search criteria used.

## 9. Actual Result
The system successfully retrieved the correct contacts when searching by name, email, and phone number. The search results were objective and precise.

## 10. Result Analysis
✅ **Test Passed** — The search functionality worked effectively across different fields without errors.

## 11. Error Description (if applicable)
N/A — No issues were encountered during the execution of this test.

## 12. Evidence
- ✅ Screenshot: `record_search_name_email_phone.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
