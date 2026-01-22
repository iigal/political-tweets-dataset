# Critical Data Update Report

## 1. Data Integrity & Deduplication
During the quality assurance audit, we identified several files containing duplicate data from other political figures. To ensure the integrity of the analysis, the following files have been **removed** from the merge pipeline:

| Removed File | Reason | Duplicate Of |
| :--- | :--- | :--- |
| `TWEET_SherBDeuba_100.csv` | Duplicate Entry | `TWEET_udayasjbrana_100.csv` |
| `TWEET_RajendraLingden_89.csv` (RPP) | Duplicate Entry | `TWEET_NCPurnaKhadka_100.csv` |
| `TWEET_RamhariKhatiwa_100.csv` | Duplicate Entry | `TWEET_NPSaudnc_100.csv` |

---

## 2. Manual Data Patches
### Follower Counts
For several key political figures whose source files lacked metadata, **Follower Counts** were manually verified and injected into the dataset to ensure accuracy.

| Username | Manual Entry | Original Status |
| :--- | :--- | :--- |
| `kpsharmaoli` | **856,000** | Missing |
| `bishwaprakash77` | **347,000** | Missing |
| `GokulPBaskota` | **146,000** | Missing |
| `amanlalmodi` | **95** | Missing |
| `khanabdul_24` | **60** | Missing |

### Missing Metrics (View Count)
Unlike follower counts, historical **View Counts** could not be manually recovered for older tweets or missing files.
* **Action:** Missing `view_count` values have been filled with `0`.
* **Recommendation:** Recommended to prioritize **Likes, Retweets, and Replies** as the primary performance metrics, as these are consistent across 100% of the dataset. `View_count` should be used with caution and filtered for non-zero values.


---

## 3. Extended Features & Individual Cleaning Reports
For granular details on specific files or access to the full feature set (up to 40+ columns per tweet), please refer to the `cleaned_dataset/` directory.

> **Important:** Inside every party's folder within `cleaned_dataset/`, you will find a **`#CLEANING_REPORT.md`**. 
> This file contains the specific cleaning logs, transformations, and issue tracking for every individual file in that folder. Please check those reports for a better understanding of the data provenance.