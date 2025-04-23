Test Case 01: Valid Login with Correct Credentials

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Valid Login with Correct Credentials**

## 3. Description
This test verifies that the SuiteCRM login process works correctly when valid credentials are provided.

## 4. Objective
To confirm that the system authenticates a user with valid credentials and redirects to the dashboard properly.

## 5. What is Being Tested
The login functionality and authentication flow of the SuiteCRM system.

## 6. Prerequisites
- A valid user account exists in the system:
  - Username: `admin`
  - Password: `admin123`
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Open a supported browser and navigate to [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Enter the username: `admin`
3. Enter the password: `admin123`
4. Click the **Login** button

## 8. Expected Result
The system should authenticate the user successfully and redirect to the SuiteCRM dashboard without errors.

## 9. Actual Result
The user was authenticated successfully and redirected to the SuiteCRM dashboard as expected.

## 10. Result Analysis
✅ **Test Passed** — The actual result matches the expected behavior. The login functionality is working correctly with valid credentials.

## 11. Error Description (if applicable)
N/A — No errors were encountered during this test.

## 12. Evidence
- ✅ Screenshot: `login_success_dashboard.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
