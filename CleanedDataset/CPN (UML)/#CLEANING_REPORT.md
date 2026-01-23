# Data Cleaning Report: ``bpaudel1959.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. What the data showed
The initial analysis showed missing values in the following columns:

*   **Video Thumbnail:** 67 missing
*   **Image:** 27 missing
*   **Retweet:** 2 missing
*   **Reply:** 1 missing

---

## 2. Actions Taken

### A. Adding Missing Identity Columns
*   **What I did:** I created and filled four new columns: **username** (bpaudel1959), **name** (Bishnu Paudel), **first_name** (Bishnu), and **last_name** (Paudel).
*   **Why:** The original file was missing information about the user. Adding these ensures we know exactly whose data is being analyzed.

### B. Removing Media Columns
*   **What I did:** Dropped the **Video Thumbnail** and **Image** columns.
*   **Why:** These columns had a high number of missing values and were not needed for the current analysis.

### B. Replaced missing value to 0 in Retweets and Reply

---

## 3. Final Result
The dataset now includes proper user identification, and the unnecessary columns have been removed.

**Status:** Ready for Analysis.

```



```

# Data Cleaning Report: ``GokulPBaskota.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. What the data showed
The initial analysis showed missing values in the following columns:

*   **Video Thumbnail:** 260 missing
*   **Image:** 235 missing
*   **Like:** 37 missing
*   **Retweet:** 141 missing
*   **Reply:** 63 missing

---

## 2. Actions Taken

### A. Adding User Identity
*   **What I did:** Added new columns for **username**, **name**, **first_name**, and **last_name** using "Gokul Baskota".
*   **Why:** These details were missing from the file. Adding them helps identify the owner of the tweets during analysis.

### B. Filling Engagement Metrics
*   **What I did:** Filled all missing values in the **Like**, **Retweet**, and **Reply** columns with **0**.
*   **Why:** It is logically assumed that if these values are missing, it means the post received no engagement (zero likes, retweets, or replies).

### C. Removing Media Columns
*   **What I did:** Dropped the **Video Thumbnail** and **Image** columns.
*   **Why:** These columns were mostly empty and were not required for the analysis.

---

## 3. Final Result
The dataset is now complete with proper user information and cleaned engagement stats.

**Status:** Ready for Analysis.

```



```

# Data Cleaning Report: ``kpsharmaoli.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. What the data showed
The initial analysis identified the following missing values:

*   **full_text:** 2 missing
*   **Video Thumbnail:** 65 missing
*   **Image:** 42 missing

---

## 2. Actions Taken

### A. Adding Identity Information
*   **What I did:** Created the **username**, **name**, **first_name**, and **last_name** columns for "K P Sharma Oli".
*   **Why:** To ensure the dataset clearly identifies who the posts belong to.

### B. Cleaning Content
*   **What I did:** Removed the rows where **full_text** was missing.
*   **Why:** Posts without text content do not provide any information for analysis, so they were deleted to keep the data quality high.

### C. Removing Media Columns
*   **What I did:** Dropped the **Video Thumbnail** and **Image** columns.
*   **Why:** These columns had many missing values and were not needed for this report.

---

## 3. Final Result
The dataset now only contains valid text posts and full user identification.

**Status:** Ready for Analysis.

```



```
# Data Cleaning Report: ``TWEET_Bidyabhattarai_100.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 36 missing
*   **url_mentions:** 38 missing
*   **followed_by:** 39 missing
*   **following:** 39 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To prevent errors during data processing and ensure the code can handle these rows smoothly.

### B. Removing Unnecessary Columns
*   **What I did:** Dropped the **followed_by** and **following** columns.
*   **Why:** These columns had a significant amount of missing data and were not required for the analysis.

---

## 3. Final Result
The dataset has been cleaned, missing text fields are handled, and redundant columns have been removed.

**Status:** Ready for Analysis.

```



```
# Data Cleaning Report: ``TWEET_GokarnaRajBista_100.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 94 missing
*   **url_mentions:** 91 missing
*   **website:** 95 missing
*   **websites:** 95 missing
*   **followed_by:** 95 missing
*   **following:** 95 missing
*   **profile_banner_url:** 95 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** This prevents the system from showing "null" or crashing during execution while keeping the data format consistent.

### B. Removing Empty/Unnecessary Columns
*   **What I did:** Deleted the following columns: **followed_by**, **following**, **website**, **websites**, and **profile_banner_url**.
*   **Why:** These columns were almost entirely empty (95% missing data), making them useless for the analysis.

---

## 3. Final Result
The dataset is now cleaned and the bulk of the empty information has been removed to focus on the actual tweet data.

**Status:** Ready for Analysis.
```



```
# Data Cleaning Report: ``TWEET_MaMaheshBasnet_100.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 63 missing
*   **url_mentions:** 52 missing
*   **followed_by:** 65 missing
*   **following:** 65 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Replaced missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To ensure the data is consistent and to prevent any "null" errors during processing.

### B. Removing Empty Columns
*   **What I did:** Dropped the **followed_by** and **following** columns.
*   **Why:** These columns had a high number of missing values and were not necessary for the analysis.

---

## 3. Final Result
The dataset is now cleaned and optimized for further analysis.

**Status:** Ready for Analysis.

```



```
# Data Cleaning Report: ``TWEET_yogesbhattarai_100.csv``

This report summarizes the missing data found and the steps taken to fix it.

## 1. Missing Values Found
The following columns contained missing data:

*   **user_mentions:** 61 missing
*   **url_mentions:** 51 missing
*   **followed_by:** 66 missing
*   **following:** 66 missing

---

## 2. Actions Taken

### A. Handling Missing Mentions
*   **What I did:** Filled the missing values in **user_mentions** and **url_mentions** with an empty string ("").
*   **Why:** To avoid errors during execution and ensure the dataset remains consistent for text processing.

### B. Removing Empty Columns
*   **What I did:** Deleted the **followed_by** and **following** columns.
*   **Why:** These columns contained a lot of missing values and were not needed for the analysis.

---

## 3. Final Result
The dataset is now cleaned and redundant columns have been removed.

**Status:** Ready for Analysis.