# Data Cleaning Report: ``drckraut.csv``

This report summarizes the structural repairs and cleaning steps performed on the dataset.

## 1. Missing Values Found
The initial analysis identified the following missing values:

*   **Content:** 58 missing
*   **Video Thumbnail:** 225 missing
*   **Image:** 81 missing
*   **Retweet:** 2 missing
*   **Reply:** 31 missing

---

## 2. Actions Taken

### A. Structural Repair (Fixing Broken Rows)
*   **What I did:** Used a Python script to fix broken rows caused by extra quotes and multiline text.
*   **Why:** The original file was corrupted because commas inside tweets were being mistaken for new columns. I reassembled the rows to restore the correct data structure.

### B. Adding User Identity
*   **What I did:** Added new columns for **username** (drckraut), **name** (Chandra Kant Raut), **first_name** (Chandra Kant), and **last_name** (Raut).
*   **Why:** These identity details were missing. Adding them ensures the dataset is properly labeled for analysis.

### C. Cleaning Content and Media
*   **What I did:** Deleted rows with empty **Content** and dropped the **Video Thumbnail** and **Image** columns.
*   **Why:** Posts without text are not useful for analysis, and the media columns contained mostly missing data.

### D. Filling Engagement Stats
*   **What I did:** Filled missing values in **Retweet** and **Reply** with **0**.
*   **Why:** Missing values in these columns signify that no retweets or replies occurred.

---

## 3. Final Result
The file structure is now fully repaired, the user identity is added, and all missing values have been handled.

**Status:** Ready for Analysis.

```



```
# Data Cleaning Report: ``khanabdul_24.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. What the data showed
The initial analysis identified the following missing values:

*   **Post Type:** 12 missing
*   **Content:** 11 missing
*   **Video Thumbnail:** 106 missing
*   **Image:** 37 missing
*   **Like:** 52 missing
*   **Retweet:** 114 missing
*   **Reply:** 114 missing

---

## 2. Actions Taken

### A. Adding User Identity
*   **What I did:** Created columns for **username** (khanabdul_24), **name** (Abdul Khan), **first_name** (Abdul), and **last_name** (Khan).
*   **Why:** To properly label the dataset with the user's information for the analysis.

### B. Cleaning Content
*   **What I did:** Removed all rows where the **Content** column was missing.
*   **Why:** Rows without text are not useful for analysis, so they were deleted to keep the data quality high.

### C. Filling Engagement Stats
*   **What I did:** Filled missing values in the **Like**, **Retweet**, and **Reply** columns with **0**.
*   **Why:** It is assumed that missing data in these categories means the posts received zero likes, retweets, or replies.

### D. Removing Unnecessary Columns
*   **What I did:** Dropped the **Video Thumbnail**, **Image**, and **Post Type** columns.
*   **Why:** These columns were either mostly empty or not required for the current analysis.

---

## 3. Final Result
The dataset now has full user identification, zero missing engagement values, and only contains rows with valid content.

**Status:** Ready for Analysis.