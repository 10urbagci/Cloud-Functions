# Cloud Functions
<img src = "img/proje_mimarisi.PNG">

<p>Cloud Storage is set to trigger with Cloud Functions.</p>

<img src = "img/resim1.png">
<p>'cloud_functions_run.py' script has been written and deployed on Google Cloud. Cloud Functions is triggered when a CSV file is uploaded to Bucket. Then it writes the metadata of the data and the data in the CSV file to BigQuery tables. Separate tables were created for metadata and CSV.</p>

<h1>Dashboard</h1>
<img src ="img/resim11.png">
<img src ="img/resim12.png">

<p>A dashboard was prepared with Looker Studio. The data was visualized and analyzed. Latitude and longitude data for the map section were created using the CONCAT function. CONCAT(pickup_latitude, ",", pickup_longitude). Each point on the map represents a location.</p>