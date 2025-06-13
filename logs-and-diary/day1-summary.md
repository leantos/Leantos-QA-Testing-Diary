# 📅 Day 1 — June 13, 2025

---

## ✅ What I Did Today

- Started my **QA Testing Diary** to track my transition from full-stack developer to QA-focused roles.
- Watched ~1.5 hours of [Simplilearn’s Manual Testing Full Course](https://www.youtube.com/watch?v=zp5Jh2FIpF0).
- Learned about:
  - SDLC and STLC
  - Functional vs Non-functional testing
  - Types of testing (Smoke, Regression, Unit, Integration)
- Used **DevTools** to inspect the login form on my Yaalnits POS app:
  - Tested responsive layout
  - Verified form validation and button behavior
- Used **Postman** to:
  - Send valid and invalid login requests
  - Observe behavior with missing/expired tokens

---

## 🧠 What I Learned

- QA isn't just clicking buttons — it’s structured, lifecycle-based work (STLC).
- Much of what I already do as a developer overlaps with QA, especially in debugging and validation.
- Writing down test cases helps surface edge cases I might’ve skipped mentally.

---

## ✍️ First Manual Test Cases Written (Yaalnits POS Login)

| Test Case ID | Scenario | Steps | Expected Result |
|--------------|----------|-------|-----------------|
| TC001 | Valid login | Enter valid email & password → Click login | Redirect to dashboard |
| TC002 | Invalid login | Enter valid email & wrong password → Submit | Show error message |
| TC003 | Empty fields | Submit without inputs | Show required field error |

*Full file in:* `manual-tests/yaalnits-login-test-cases.md`

---

## 🔧 Tools Used

- **Chrome DevTools** (Inspect → Mobile view → Form testing)
- **Postman** (API calls to login and product endpoints)

---

## 🚩 Next Goals (Day 2)

- Write formal **bug report** for a missing error message on invalid input
- Learn **severity vs priority** in bug classification
- Explore how to log bugs (JIRA-style format)
- Expand test cases for the product list and cart features

---

## 💬 Notes

- This repo will serve as a QA resume enhancer and a learning record
- I’ll update this log with completed goals or missed items if needed

