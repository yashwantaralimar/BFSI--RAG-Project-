# BFSI RAG Project — Test Cases Document

**Project:** Bank Policy Q&A Chatbot
**Test Type:** Functional Testing — RAG Retrieval Accuracy
**Total Test Cases:** 5
**Date:** July 2026

---

## Test Environment

| Item | Detail |
|---|---|
| Platform | TCS GenAI Lab — Jupyter Notebook |
| Python Version | 3.9.12 |
| Notebook | bfsi_rag_project.ipynb |
| Document Used | bfsi_policy.txt |

---

## TC-01: Home Loan Eligibility Query

| Field | Detail |
|---|---|
| **Test Case ID** | TC-01 |
| **Test Case Name** | Home Loan Eligibility Check |
| **Objective** | Verify RAG retrieves correct home loan policy |
| **Input Question** | "What is the eligibility criteria for a home loan?" |
| **Expected Output** | Age 21-65, salary Rs.25,000/month, max Rs.1 Crore, tenure 5-30 years |
| **Step** | Run Step 7 Cell 1 |
| **Status** | [ ] Pass  [ ] Fail |
| **Screenshot** | Attach SS of cell output |

---

## TC-02: Credit Card Requirements Query

| Field | Detail |
|---|---|
| **Test Case ID** | TC-02 |
| **Test Case Name** | Credit Card Minimum Score Check |
| **Objective** | Verify RAG retrieves correct credit card requirements |
| **Input Question** | "What is the minimum credit score needed for a credit card?" |
| **Expected Output** | Minimum credit score 700, minimum age 18, annual income Rs.2,40,000 |
| **Step** | Run Step 7 Cell 2 |
| **Status** | [ ] Pass  [ ] Fail |
| **Screenshot** | Attach SS of cell output |

---

## TC-03: KYC Document Query

| Field | Detail |
|---|---|
| **Test Case ID** | TC-03 |
| **Test Case Name** | KYC Documents Required |
| **Objective** | Verify RAG retrieves correct KYC guidelines |
| **Input Question** | "What documents are needed for KYC verification?" |
| **Expected Output** | PAN Card, Aadhaar Card, Address Proof mentioned |
| **Step** | Run Step 7 Cell 3 |
| **Status** | [ ] Pass  [ ] Fail |
| **Screenshot** | Attach SS of cell output |

---

## TC-04: Fixed Deposit Senior Citizen Rate Query

| Field | Detail |
|---|---|
| **Test Case ID** | TC-04 |
| **Test Case Name** | FD Interest Rate for Senior Citizens |
| **Objective** | Verify RAG retrieves FD rates correctly |
| **Input Question** | "What is the interest rate for fixed deposits for senior citizens?" |
| **Expected Output** | 5.5% to 7.5% general + additional 0.5% for senior citizens |
| **Step** | Run Step 7 Cell 4 |
| **Status** | [ ] Pass  [ ] Fail |
| **Screenshot** | Attach SS of cell output |

---

## TC-05: Personal Loan Maximum Amount Query

| Field | Detail |
|---|---|
| **Test Case ID** | TC-05 |
| **Test Case Name** | Personal Loan Maximum Amount |
| **Objective** | Verify RAG retrieves personal loan limits correctly |
| **Input Question** | "What is the maximum personal loan amount I can get?" |
| **Expected Output** | Rs. 25,00,000 maximum, tenure 12-60 months |
| **Step** | Run Step 7 Cell 5 |
| **Status** | [ ] Pass  [ ] Fail |
| **Screenshot** | Attach SS of cell output |

---

## Test Summary Table

| TC ID | Question Topic | Expected | Actual | Status |
|---|---|---|---|---|
| TC-01 | Home Loan | Eligibility details | [Fill after running] | [ ]Pass [ ]Fail |
| TC-02 | Credit Card | Score 700 | [Fill after running] | [ ]Pass [ ]Fail |
| TC-03 | KYC | PAN, Aadhaar | [Fill after running] | [ ]Pass [ ]Fail |
| TC-04 | Fixed Deposit | 0.5% extra senior | [Fill after running] | [ ]Pass [ ]Fail |
| TC-05 | Personal Loan | Rs.25 Lakhs max | [Fill after running] | [ ]Pass [ ]Fail |

**Total:** 5 | **Pass:** ___ | **Fail:** ___ | **Pass %:** ___%

---

*Test document for BFSI RAG Project | TCS GenAI Lab | July 2026*
