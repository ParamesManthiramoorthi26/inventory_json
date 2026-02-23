# Applied AI and ML Essential Assignment (inventory json)

---

## **Student Details**

**Name:** Parameswari Manthiramoorthi  
**ID No:** IITP_AIMLTN_2602771  
**Course:** Applied AI and ML Essential  
**Submission Date:** 23-02-2026  

---

## **Assignment Overview**

This assignment demonstrates how to **work with files and JSON in Python** to manage a bookstore inventory. The tasks include:

- Reading an existing inventory from a JSON file.  
- Adding new books to the inventory.  
- Saving the updated inventory back to the JSON file.  
- Displaying the inventory in a **clean, table-like format**.  

---

## **Code Explanation**

- **JSON** is used to **store and manage structured data**, such as a list of books in the inventory.  
- **`with open()`** blocks handle **file operations safely**, ensuring the file is automatically closed after reading or writing.  
- **`json.load()`** converts JSON data into **Python objects**, while **`json.dump()`** writes Python objects back to a JSON file with proper formatting.  
- **Lists** allow you to **append new items**, making the inventory **dynamic and easy to update**.  
- **F-strings with alignment** are used to display **book details clearly and neatly**, forming a readable table-like output.  
- Using **indentation** in **`json.dump()`** improves **file readability**, making it easier to view and edit the inventory manually if needed.  
- Overall, the program demonstrates **safe file handling**, **dynamic data management**, and **clean output formatting** in **Python**.  

**Conclusion:** This program effectively demonstrates **reading, updating, and managing JSON data** in Python while ensuring **clean, readable, and well-formatted output**.

---

## **Assignment Git Workflow**

This workflow explains how to manage your **local Git repository** for the assignment.

---

### Step 1 — Initialize Local Repository

```bash
# Create a project folder
mkdir inventory_json
cd inventory_json

# Initialize a Git repository
git init# Add all files (Colab notebook and PDF) to staging

# Add Assignment Files
git add .

# Check status of files staged for commit
git status

# Commit Files Locally
# Commit staged files with a clear message
git commit -m "Added Colab notebook for assignment and PDF of question"

# Connect Local Repo to GitHub (Optional)
# Add the remote repository URL (replace with your repo URL)
git remote add origin https://github.com/ParamesManthiramoorthi26/inventory_json.git

# Rename default branch to main
git branch -M main

# Push local commits to GitHub
git push -u origin main Step 6 — Push Future Updates to GitHub

# Push any new commits to GitHub
git push



