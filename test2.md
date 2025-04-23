# Test Case 02: Login with Invalid User

## 1. Introduction and Description
This activity aims to provide a realistic software testing experience within the SuiteCRM environment, combining code analysis with hands-on testing. The focus is on producing detailed and well-organized test reports that simulate the daily tasks of a software tester. The tested software is SuiteCRM, accessed at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br).

## 2. Test Title
**Login with Invalid User**

## 3. Description
This test verifies the system's response when incorrect login credentials are provided by the user.

## 4. Objective
To evaluate the system’s behavior when invalid credentials are entered, confirming that an appropriate error message is displayed and that access is denied.

## 5. What is Being Tested
The login validation and error-handling mechanism in the authentication flow of SuiteCRM.

## 6. Prerequisites
- Access to the SuiteCRM instance at [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
- Supported browser (Chrome, Firefox, or Edge)
- Internet connection

## 7. Test Procedure
1. Open a supported browser and navigate to [https://crm.alunostds.dev.br](https://crm.alunostds.dev.br)
2. Enter an **invalid username**, e.g., `invalidUser`
3. Enter an **invalid password**, e.g., `wrongPass123`
4. Click the **Login** button

## 8. Expected Result
The system should:
- Deny access to the application
- Remain on the login page
- Display an appropriate error message indicating that the user is unauthorized or that the credentials are invalid

## 9. Actual Result
The system correctly:
- Prevented login
- Returned to the login page
- Displayed an error message on the screen:  
  **"Invalid Credentials. Please try again."**  
  (Error message confirmed in HTML output)

## 10. Result Analysis
✅ **Test Passed** — The actual result matches the expected behavior. The system blocked access and displayed the appropriate error message for invalid login attempts.

## 11. Error Description (if applicable)
N/A — No system errors occurred. The behavior was correct and expected.

## 12. Evidence
- ✅ Screenshot: `invalid_login_error_message.png` (attach in GitHub repo)
- 🌐 Browser: Google Chrome 123.0.6312.86 (64-bit)
- 💻 OS: Windows 11 Pro – Version 23H2
- 🖥️ Screen Resolution: 1920x1080

---

*Test conducted by: [Seu Nome]*  
*Date: April 22, 2025*  
