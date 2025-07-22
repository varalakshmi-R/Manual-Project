# Manual-Project
# STUCOR Application - Manual Testing Project

## 📱 Project Overview

This repository documents the manual testing process for the **STUCOR Application**, a student-centric app used for exam results, college circulars, and academic updates. The aim of this project is to validate the core functionality, usability, and reliability of the application through a systematic manual testing approach.

---

## 🧪 Test Scenarios

Below are some key test scenarios covered in this project:

| Scenario ID | Module                | Scenario Description                                  |
|-------------|-----------------------|--------------------------------------------------------|
| TS001       | Login Module          | Verify login with valid credentials                    |
| TS002       | Login Module          | Verify login with invalid credentials                  |
| TS003       | Circulars             | Verify if latest circulars are fetched and displayed   |
| TS004       | Results Module        | Verify correct display of semester results             |
| TS005       | Internet Dependency   | Check app behavior when there is no internet connection|
| TS006       | UI Compatibility      | Validate UI responsiveness on small screen devices     |

---

## ✅ Test Cases

Test cases are written in a structured format including Header, Body, and Footer:

### Example Test Case

**Test Case ID:** TC_STUCOR_002  
**Test Case Title:** Login with Invalid Credentials  

#### **Header Section**
- **Module:** Login  
- **Pre-Condition:** App is installed and launched  
- **Test Priority:** High  
- **Tester Name:** Varalakshmi Ramamoorthy  
- **Test Type:** Negative Testing  

#### **Body Section**
- **Test Steps:**
  1. Open the STUCOR App
  2. Enter invalid username/email
  3. Enter incorrect password
  4. Tap on "Login" button
- **Expected Result:** App should show an error message like "Invalid username or password"
- **Actual Result:** App displays appropriate error message  
- **Status:** ✅ Pass / ❌ Fail  

#### **Footer Section**
- **Test Environment:** Android 11, Redmi Note 10  
- **Date Executed:** 20-July-2025  
- **Bug Linked:** No  

---

## 🐞 Defect Report Summary

| Bug ID          | Description                                | Severity | Status  | Screenshot Reference |
|------------------|--------------------------------------------|----------|---------|-----------------------|
| BUG-STUCOR-001   | App crashes when switching tabs without net | Critical | Open    | `defects/bug001.png`  |
| BUG-STUCOR-002   | App crashes on tapping circulars with no data | High     | Fixed   | `defects/bug002.png`  |
| BUG-STUCOR-003   | UI broken on 4-inch screen size             | Medium   | Open    | `defects/bug003.png`  |
| BUG-STUCOR-004   | Incorrect error message for wrong password  | Low      | Closed  | `defects/bug004.png`  |

---

## 📂 Folder Structure

stucor-manual-testing/
├── test-scenarios/
│ └── stucor_test_scenarios.xlsx
├── test-cases/
│ └── login_module_test_cases.xlsx
├── defect-reports/
│ └── stucor_defects.xlsx
│ └── bug_screenshots/
│ ├── bug001.png
│ ├── bug002.png
│ └── ...
├── README.md

---

## 📌 Conclusion

This manual testing project ensured the STUCOR application's core functionalities work as expected, even in negative and edge cases. Further improvements can be made by incorporating automation testing for regression and frequent releases.

---

## 🧑‍💻 Tested By
**Varalakshmi Ramamoorthy**  
Manual & Automation Testing Engineer  
