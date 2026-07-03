# BFSI RAG Project — Complete Execution Guide
## Step-by-Step: From Download to Submission

---

# PHASE 1: DOWNLOAD FILES FROM CLAUDE CHAT

## Step 1.1 — Download the Notebook
```
In this Claude chat window:
      ↓
Find the file: bfsi_rag_project.ipynb
      ↓
Click on it to download
      ↓
It saves to: C:\Users\YourName\Downloads\bfsi_rag_project.ipynb
```

## Step 1.2 — Download All Documents
Download these files too (all available in Claude chat):
- ✅ bfsi_rag_project.ipynb  (Main notebook)
- ✅ Project_Document.md     (Project report)
- ✅ Test_Cases.md           (Test case document)
- ✅ Execution_Guide.md      (This file)

---

# PHASE 2: UPLOAD TO TCS LAB

## Step 2.1 — Login to TCS GenAI Lab
```
Open your browser
      ↓
Go to TCS GenAI Lab URL
      ↓
Login with your credentials
      ↓
You will see Jupyter interface
(same place where you open Question.ipynb)
```

## Step 2.2 — Upload the Notebook
```
In Jupyter file browser (left side panel)
      ↓
Look at the TOP of the file browser
      ↓
Click the UPLOAD button (⬆ arrow icon)
      OR
Simply DRAG the .ipynb file from
your Downloads folder into Jupyter
      ↓
File appears in the file list
```

## Step 2.3 — Open the Notebook
```
Double-click: bfsi_rag_project.ipynb
      ↓
Notebook opens in a new tab
      ↓
You will see 8 steps/cells
```

---

# PHASE 3: EXECUTE THE NOTEBOOK

## ⚠️ IMPORTANT RULE
```
Always wait for each cell to finish
before running the next one.
A cell is running when you see: [*]
A cell is done when you see:    [1] or [2] etc.
```

## Step 3.1 — Run Cell 1 (Install Libraries)
```
Click on Cell 1 (Install libraries)
      ↓
Press Shift + Enter
      ↓
WAIT — this takes 30-60 seconds
      ↓
You will see: ✅ All libraries installed successfully!
      ↓
📸 SCREENSHOT 1: Take screenshot now
   (Show the cell + output with ✅ message)
```

## Step 3.2 — Run Cell 2 (Import Libraries)
```
Press Shift + Enter on Cell 2
      ↓
Very fast — 2-3 seconds
      ↓
You will see: ✅ All imports successful!
      ↓
📸 SCREENSHOT 2: Take screenshot now
```

## Step 3.3 — Run Cell 3 (Create Document)
```
Press Shift + Enter on Cell 3
      ↓
Instant — less than 1 second
      ↓
You will see:
✅ Sample BFSI document created: bfsi_policy.txt
📄 Document size: XXXX characters
📋 Topics covered: Home Loan, Personal Loan...
      ↓
📸 SCREENSHOT 3: Take screenshot now
```

## Step 3.4 — Run Cell 4 (Load & Split)
```
Press Shift + Enter on Cell 4
      ↓
Fast — 2-3 seconds
      ↓
You will see:
✅ Document loaded successfully!
📦 Total chunks created: XX
📌 Sample chunk (first one):
--------------------------------------------------
[Text of first chunk appears here]
      ↓
📸 SCREENSHOT 4: Take screenshot now
```

## Step 3.5 — Run Cell 5 (Create Vector Store)
```
Press Shift + Enter on Cell 5
      ↓
⚠️ THIS IS THE SLOWEST STEP
WAIT 2-5 minutes on first run
(downloads embedding model ~90MB)
      ↓
You will see:
⏳ Loading embedding model...
✅ Embedding model loaded!
⏳ Creating FAISS vector store...
✅ FAISS vector store created and saved!
🗃️  Index saved to: bfsi_faiss_index/
📊 Total vectors stored: XX
      ↓
📸 SCREENSHOT 5: Take screenshot now
   (Most important screenshot!)
```

## Step 3.6 — Run Cell 6 (RAG Function)
```
Press Shift + Enter on Cell 6
      ↓
Instant
      ↓
You will see:
✅ RAG Q&A function created successfully!
💡 Ready to answer BFSI questions!
      ↓
📸 SCREENSHOT 6: Take screenshot now
```

## Step 3.7 — Run Test Cases (Cells 7a to 7e)
```
Run each test cell one by one:

CELL 7a — Home Loan Question
Press Shift+Enter
Wait 3-5 seconds
See retrieved policy sections appear
📸 SCREENSHOT 7: Take screenshot

CELL 7b — Credit Card Question
Press Shift+Enter
Wait 3-5 seconds
📸 SCREENSHOT 8: Take screenshot

CELL 7c — KYC Question
Press Shift+Enter
Wait 3-5 seconds
📸 SCREENSHOT 9: Take screenshot

CELL 7d — Fixed Deposit Question
Press Shift+Enter
Wait 3-5 seconds
📸 SCREENSHOT 10: Take screenshot

CELL 7e — Personal Loan Question
Press Shift+Enter
Wait 3-5 seconds
📸 SCREENSHOT 11: Take screenshot
```

## Step 3.8 — Run Summary Report (Cell 8)
```
Press Shift + Enter on Cell 8
      ↓
Instant
      ↓
You will see a full table:
✅ All 5 test cases PASSED
100% Pass Rate
      ↓
📸 SCREENSHOT 12: Take screenshot
   (This is your PROOF OF EXECUTION)
```

---

# PHASE 4: SAVE THE NOTEBOOK WITH OUTPUTS

```
After all cells have run:
      ↓
Press Ctrl + S   (Save)
      ↓
The notebook saves WITH all outputs visible
      ↓
This .ipynb file is your execution proof
```

---

# PHASE 5: EXPORT AS HTML (For Submission)

```
In Jupyter menu bar at the top:
      ↓
Click: File
      ↓
Click: Save and Export Notebook As
      ↓
Click: HTML
      ↓
File downloads as: bfsi_rag_project.html
      ↓
This HTML file has ALL your code
+ ALL outputs in one clean document
      ↓
Perfect for submission!
```

---

# PHASE 6: HOW TO TAKE SCREENSHOTS

## Windows
```
Press: Windows key + Shift + S
      ↓
Drag to select the area you want
      ↓
Screenshot saves to clipboard
      ↓
Paste in Word/Paint to save as image
```

## Alternative
```
Press: Print Screen (PrtSc) key
      ↓
Open Paint → Ctrl+V → Save
```

## What to Include in Each Screenshot
```
✅ Show the cell NUMBER on the left (like [1], [2])
✅ Show the CODE in the cell
✅ Show the OUTPUT below the cell
✅ Make sure ✅ messages are visible
✅ Make sure no error messages are visible
```

---

# PHASE 7: COMPLETE SUBMISSION CHECKLIST

Fill this checklist before submitting:

```
EXECUTION SCREENSHOTS:
[ ] SS1  — Libraries installed (✅ message visible)
[ ] SS2  — Imports successful (✅ message visible)
[ ] SS3  — BFSI document created (file size visible)
[ ] SS4  — Document chunks created (count visible)
[ ] SS5  — FAISS vector store created ⭐ MOST IMPORTANT
[ ] SS6  — RAG function ready
[ ] SS7  — TC-01 Home Loan output
[ ] SS8  — TC-02 Credit Card output
[ ] SS9  — TC-03 KYC output
[ ] SS10 — TC-04 Fixed Deposit output
[ ] SS11 — TC-05 Personal Loan output
[ ] SS12 — Summary report (100% Pass Rate visible) ⭐

DOCUMENTS:
[ ] bfsi_rag_project.ipynb  (with all outputs saved)
[ ] bfsi_rag_project.html   (exported from Jupyter)
[ ] Project_Document.md     (project report)
[ ] Test_Cases.md           (test results filled in)
[ ] All 12 screenshots

TOTAL FILES TO SUBMIT: 5 files + 12 screenshots
```

---

# COMMON ERRORS AND FIXES

| Error | Fix |
|---|---|
| ModuleNotFoundError | Re-run Cell 1 (install cell) |
| Cell stuck at [*] | Wait longer — model downloading |
| Kernel died | Click Restart + Run All |
| Import error | Restart kernel, run from Cell 1 |
| No output visible | Scroll down below the cell |

---

# TIMELINE ESTIMATE

```
Phase 1 — Download files      :  2 minutes
Phase 2 — Upload to lab       :  2 minutes
Phase 3 — Run all cells       :  10-15 minutes
          (Cell 5 takes longest — model download)
Phase 4 — Save notebook       :  1 minute
Phase 5 — Export HTML         :  1 minute
Phase 6 — Take screenshots    :  5 minutes
Phase 7 — Organize submission :  5 minutes

TOTAL ESTIMATED TIME: 25-30 minutes
```

---

*Execution Guide for BFSI RAG Project | TCS GenAI Lab | July 2026*
