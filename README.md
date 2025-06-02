# Task 1: Data Cleaning and Preprocessing

**Dataset Used:** Investigate_No_Show_Medical_dataset.csv (provided)

**Summary of Changes:**
- Checked for missing values: No missing values found in the dataset.
- Removed 5 duplicate rows. Dataset reduced from 623 to 618 rows.
- Standardized `gender` column to lowercase (e.g., 'F' to 'f', 'M' to 'm').
- Standardized `no_show` column to lowercase (e.g., 'No' to 'no', 'Yes' to 'yes').
- Converted `scheduledday` and `appointmentday` to 'DD-MM-YY HH:MM:SS' format (e.g., '2016-04-29T18:38:08Z' to '29-04-16 18:38:08').
- Renamed columns to lowercase with underscores (e.g., 'PatientId' to 'patientid', 'No-show' to 'no_show').
- Ensured correct data types: `patientid`, `gender`, and `no_show` as strings; `scheduledday` and `appointmentday` as datetime; `appointmentid`, `age`, `hipertension`, `diabetes`, `alcoholism`, `handcap`, and `sms_received` as integers.
- Checked for invalid ages: No invalid ages found (no ages less than 0).

**Files Included:**
- `Investigate_No_Show_Medical_dataset.csv`: Original dataset
- `cleaned_no_show_medical_dataset.csv`: Cleaned dataset
- `Task1cleaned_no_show_medical_database.ipynb`: Python script used for cleaning
- `README.md`: This summary file
