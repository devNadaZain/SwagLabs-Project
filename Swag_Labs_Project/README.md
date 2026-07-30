#  Swag Labs Project

## 🧾 Description
Comprehensive **manual testing** project for the [Swag Labs](https://www.saucedemo.com/) e-commerce platform, covering **225 test cases** that validate core functionalities including authentication, product browsing, product details, cart management, and the checkout process.

---

## 🎯 Project Scope

### 📋 Manual Testing
- User Stories & Test Plan
- Test Cases Creation & Execution
- Bug Reports & Test Summary

---

## 🧰 Tools & Technologies

| Category | Tools |
|----------|-------|
| **Test Documentation** | Google Sheets / Microsoft Excel |
| **Browser** | Google Chrome |

---

## ⚙️ Prerequisites
- Google Chrome browser
- Internet connection
- A spreadsheet viewer (Google Sheets or Microsoft Excel) to open the test case workbook

---

## 📥 Getting Started

Open the test case documentation, then execute the cases against [https://www.saucedemo.com/](https://www.saucedemo.com/) and record the results.

---

## 📁 Test Documentation

| File | Description |
|------|-------------|
| `SwagLabs TestCases.xlsx` | Source workbook containing all test cases and the summary report |
| [`SwagLabs TestCases.md`](../SwagLabs%20TestCases.md) | Markdown version of the full test case suite |

---

## 👥 Users Under Test

| Username | Purpose |
|----------|---------|
| `standard_user` | Baseline user for normal flows |
| `locked_out_user` | Verifies access is blocked for locked accounts |
| `problem_user` | Surfaces UI and data defects |
| `performance_glitch_user` | Verifies behaviour under delayed responses |
| `error_user` | Surfaces functional errors |
| `visual_user` | Surfaces visual/layout defects |

> Test cases were created for the `standard_user` only, while execution was carried out across all users. This is why the bug count exceeds the number of failed test cases.

---

## 🧪 Test Coverage

| User Story | No. of Test Cases | Passed | Failed | No. of Bugs |
| --- | --- | --- | --- | --- |
| Login | 57 | 55 | 1 | 3 |
| Home | 52 | 51 | 1 | 35 |
| Product Detail Page | 15 | 15 | 0 | 43 |
| Cart Page | 17 | 16 | 1 | 13 |
| Checkout | 40 | 32 | 8 | 12 |
| Sidebar | 6 | 5 | 1 | 1 |
| About | 15 | 15 | 0 | 2 |
| System | 11 | 10 | 1 | 1 |
| End to End | 12 | 12 | 0 | 0 |

### Testing Activities
- **User Stories:** Feature requirements and acceptance criteria
- **Test Plan:** Testing strategy and scope
- **Test Cases:** Detailed test scenarios with expected results
- **Execution:** Systematic test runs and result documentation
- **Bug Reports:** Defect identification and tracking
- **Summary:** Quality metrics and recommendations

---

## 📊 Test Summary

| Metric | Value |
| --- | --- |
| Total Test Cases | 225 |
| Total Passed | 211 |
| Total Failed | 13 |
| Total Bugs | 110 |
| Pass Rate | 93.78% |
| Fail Rate | 5.78% |

---

> 🧠 *Demonstrates a complete manual testing approach, from user stories and test case design through execution, defect reporting, and quality metrics.*
