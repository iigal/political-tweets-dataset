# File name: TWEET_Bhanubhakta99_2.csv

**File Name:** `TWEET_Bhanubhakta99_2.csv`

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 1 missing
*   **url_mentions:** 1 missing
*   **website:** 2 missing
*   **websites:** 2 missing
*   **followed_by:** 2 missing
*   **following:** 2 missing
*   **profile_banner_url:** 2 missing

---

## 2. Actions Taken

### A. Filling Missing Mentions
*   **What I did:** Replaced the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the code runs smoothly without hitting "null" errors during execution.

### B. Removing Empty/Unnecessary Columns
*   **What I did:** Completely removed the following columns: **profile_banner_url**, **following**, **followed_by**, **website**, and **websites**.
*   **Why:** These columns were empty and did not contain any useful information for the analysis.

---

## 3. Final Result
The dataset is now clean. All empty columns have been removed, and missing text fields have been filled.

**Status:** Ready for Analysis.


```



```

# 2 File name: ``TWEET_Krishnacpnus_46.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 1 missing
*   **url_mentions:** 1 missing
*   **website:** 2 missing
*   **websites:** 2 missing
*   **followed_by:** 2 missing
*   **following:** 2 missing
*   **profile_banner_url:** 2 missing

---

## 2. Actions Taken

### A. Filling Missing Mentions
*   **What I did:** Replaced missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To prevent errors during execution and keep the data consistent.

### B. Removing Empty Columns
*   **What I did:** Deleted the following columns: **profile_banner_url**, **following**, **followed_by**, **website**, and **websites**.
*   **Why:** These columns were empty and did not provide any useful information.

### C. Dropping Location Data
*   **What I did:** Removed the **location** column.
*   **Why:** Even though it wasn't empty, this information was not needed for the current analysis.

---

## 3. Final Result
The dataset is now optimized. Unnecessary columns have been removed, and missing text fields are properly handled.

**Status:** Ready for Analysis.

```



```

# Data Cleaning Report: TWEET_ncp_madhavnepal_100.csv

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 49 missing
*   **url_mentions:** 78 missing
*   **followed_by:** 100 missing
*   **following:** 100 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To prevent "null" errors during execution and keep the data consistent.

### B. Removing Empty Columns
*   **What I did:** Deleted the **followed_by** and **following** columns.
*   **Why:** These columns were 100% empty, so they were not useful for the analysis.

---

## 3. Final Result
The dataset is now clean and optimized. All empty columns have been removed and text fields are properly handled.

**Status:** Ready for Analysis.