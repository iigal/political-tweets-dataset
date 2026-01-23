# Data Cleaning Report: ``TWEET_yogeshbhattarai_100.csv``

This report summarizes the identity correction and cleaning steps performed on the dataset (76 rows).

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 62 missing
*   **url_mentions:** 68 missing
*   **followed_by:** 76 missing (100% empty)
*   **following:** 76 missing (100% empty)

---

## 2. Actions Taken

### A. Correcting Identity and Filename
*   **What I did:** Recognized that the file `TWEET_manishjhanepal_100.csv` actually contained data for **Yogesh Bhattarai**. I corrected the file name and updated the identity fields accordingly.
*   **Why:** To ensure the data is attributed to the correct person and to fix a naming mistake in the source.

### B. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To prevent "null" errors during execution and keep the text formatting consistent.

### C. Removing Empty Columns
*   **What I did:** Deleted the **followed_by** and **following** columns.
*   **Why:** These columns were 100% empty across all 76 rows, so they were removed to clean up the dataset.

---

## 3. Final Result
The dataset now has the correct identity information and is cleaned of entirely empty columns.

**Status:** Ready for Analysis.

```



```
# Data Cleaning Report: ``TWEET_ashimshahnepal_100.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 70 missing
*   **url_mentions:** 74 missing
*   **location:** 77 missing
*   **website:** 77 missing
*   **websites:** 77 missing
*   **followed_by:** 77 missing
*   **following:** 77 missing
*   **profile_banner_url:** 77 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" errors during processing or code execution.

### B. Removing Empty/Unnecessary Columns
*   **What I did:** Deleted the following columns: **location**, **website**, **websites**, **followed_by**, **following**, and **profile_banner_url**.
*   **Why:** These columns were almost entirely empty (77 out of 100 rows missing) and did not provide useful information for the analysis.

---

## 3. Final Result
The dataset is now optimized. Unnecessary empty columns have been removed, and the remaining text fields are properly handled.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_dolprasadaryal_100.csv``

This report summarizes the missing data found and the identity corrections made to the dataset.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 82 missing
*   **url_mentions:** 82 missing
*   **location:** 83 missing
*   **followed_by:** 83 missing
*   **following:** 83 missing

---

## 2. Actions Taken

### A. Standardizing Names
*   **What I did:** Changed the **name** from "DP Aryal" to "Dol Prasad Aryal" and updated the **first_name** from "DP" to "Dol Prasad".
*   **Why:** To use the full official name instead of initials for better clarity and professional formatting.

### B. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To prevent "null" errors during execution and keep the text data consistent.

### C. Removing Empty Columns
*   **What I did:** Deleted the **location**, **followed_by**, and **following** columns.
*   **Why:** These columns were almost entirely empty and did not provide any useful information for the analysis.

---

## 3. Final Result
The dataset now features the corrected full name and is cleaned of unnecessary empty columns.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_hamrorabi_100.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 95 missing
*   **url_mentions:** 98 missing
*   **website:** 98 missing
*   **websites:** 98 missing
*   **followed_by:** 98 missing
*   **following:** 98 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" errors during processing.

### B. Removing Empty Columns
*   **What I did:** Deleted the following columns: **website**, **websites**, **followed_by**, and **following**.
*   **Why:** These columns were  entirely empty (100%), making them unnecessary for the analysis.

---

## 3. Final Result
The dataset is now optimized. Unnecessary empty columns have been removed, and the remaining text fields are properly handled.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_Himalayabiraj_100.csv``

This report summarizes the missing data found and the steps taken to fix it for the 92 rows in this dataset.

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 84 missing
*   **url_mentions:** 85 missing
*   **followed_by:** 92 missing (100% empty)
*   **following:** 92 missing (100% empty)

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" errors during execution or processing.

### B. Removing Empty Columns
*   **What I did:** Deleted the **followed_by** and **following** columns.
*   **Why:** Since the dataset has 92 rows and these columns were missing all 92 values, they were completely empty and useless for analysis.

---

## 3. Final Result
The dataset is now optimized. All entirely empty columns have been removed, and the remaining missing text fields have been handled.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_MPnishadangi_89.csv``

This report summarizes the missing data found and the steps taken to fix it for the 82 rows in this dataset.

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 79 missing
*   **url_mentions:** 78 missing
*   **location:** 82 missing (100% empty)
*   **website:** 82 missing (100% empty)
*   **websites:** 82 missing (100% empty)
*   **followed_by:** 82 missing (100% empty)
*   **following:** 82 missing (100% empty)

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent "null" or "NaN" errors during processing.

### B. Removing Empty Columns
*   **What I did:** Deleted the following columns: **location**, **website**, **websites**, **followed_by**, and **following**.
*   **Why:** These columns were 100% empty across all 82 rows, providing no information and cluttering the dataset.

---

## 3. Final Result
The dataset is now optimized. All entirely empty metadata columns have been removed, and the remaining text fields are properly handled.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_sobita465_100.csv``

This report summarizes the missing data found and the steps taken to fix it for the 35 rows in this dataset.

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 33 missing
*   **url_mentions:** 31 missing
*   **location:** 35 missing (100% empty)
*   **website:** 35 missing (100% empty)
*   **websites:** 35 missing (100% empty)
*   **followed_by:** 35 missing (100% empty)
*   **following:** 35 missing (100% empty)

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" errors during processing or code execution.

### B. Removing Empty Columns
*   **What I did:** Deleted the following columns: **location**, **website**, **websites**, **followed_by**, and **following**.
*   **Why:** These columns were 100% empty across all 35 rows. Removing them cleans up the dataset by getting rid of columns that provide no information.

---

## 3. Final Result
The dataset is now optimized. All entirely empty metadata columns have been removed, and the remaining missing text fields are properly handled.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: TWEET_SwarnimWagle_100.csv

This report summarizes the missing data found and the steps taken to fix it for the 8 rows in this dataset.

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 3 missing
*   **url_mentions:** 7 missing
*   **followed_by:** 8 missing (100% empty)
*   **following:** 8 missing (100% empty)

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" errors during processing.

### B. Removing Empty Columns
*   **What I did:** Deleted the **followed_by** and **following** columns.
*   **Why:** These columns were 100% empty across all 8 rows. Removing them cleans up the dataset by removing data points that provide no information.

---

## 3. Final Result
The dataset is now optimized. All entirely empty columns have been removed, and the remaining missing text fields are properly handled.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_ToshimaKarkiDr_100.csv``

This report summarizes the missing data found and the steps taken to fix it for the 89 rows in this dataset.

## 1. Missing Values Found
The initial analysis identified the following missing data:

*   **user_mentions:** 87 missing
*   **url_mentions:** 82 missing
*   **website:** 89 missing (100% empty)
*   **websites:** 89 missing (100% empty)
*   **followed_by:** 89 missing (100% empty)
*   **following:** 89 missing (100% empty)

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" or "NaN" errors during data processing or analysis.

### B. Removing Empty Columns
*   **What I did:** Deleted the following columns: **website**, **websites**, **followed_by**, and **following**.
*   **Why:** These columns were 100% empty across all 89 rows. Removing them cleans up the dataset by eliminating columns that provide no useful information.

---

## 3. Final Result
The dataset is now optimized. All entirely empty metadata columns have been removed, and the remaining text fields are properly handled.

**Status:** Ready for Analysis.