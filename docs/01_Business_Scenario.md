# 📌 Business Scenario

A rapidly growing retail company receives daily business data from multiple departments, including **Sales**, **Products**, **Customers**, **Employees**, and **Inventory**. Each department uploads CSV or Excel files to designated Google Drive folders for further processing and reporting.

As the volume of data increases, the company's existing manual process becomes inefficient. Data engineers must manually download files, validate the data, identify new files, remove duplicates, load the data into reporting systems, and maintain processing logs. This approach is time-consuming, error-prone, and difficult to scale.

## Challenges

The company faces several operational challenges:

* Duplicate files are processed multiple times.
* Entire datasets are reprocessed instead of only newly arrived data.
* Poor-quality data affects business reports and dashboards.
* There is no centralized audit trail to track processed files and execution history.
* Onboarding new datasets requires code changes, increasing maintenance effort.
* The growing number of daily files makes the current process unsustainable.

## Proposed Solution

To address these challenges, the company plans to build a **Metadata-Driven Incremental Data Ingestion Framework** using **Databricks**, **PySpark**, and **Delta Lake**.

The solution will:

* Automatically discover new files from Google Drive.
* Process only incremental data.
* Validate data quality before ingestion.
* Maintain audit and metadata tables.
* Organize data using the **Bronze–Silver–Gold (Medallion) Architecture**.
* Archive successfully processed files.

## Expected Outcome

This framework provides a scalable, reusable, and enterprise-ready data engineering solution that delivers reliable, analytics-ready data while minimizing manual intervention and improving operational efficiency.
