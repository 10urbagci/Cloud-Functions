# Cloud Functions
<img src = "img/project_arc.png">

<p>Cloud Storage is set to trigger with Cloud Functions.</p>

<img src = "img/resim1.png">
<p>Cloud Functions is triggered when a CSV file is uploaded to Bucket. Then it writes the metadata of the data and the data in the CSV file to BigQuery tables. Separate tables were created for metadata and CSV.</p>