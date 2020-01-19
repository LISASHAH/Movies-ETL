# Movies-ETL
<p><strong>Python file name: Challenge.py</strong></p>
<p><strong>transform_etl</strong> takes in three agruments for accepting wiki, kaggel metadata and ratings data. It will do the validation, transformation and loading into the database tables.</p>
<p>Analysis</p>
<p>The ETL process is the perfect process to extract raw data, clean that data and load it into database for further analysis. Data clean up can be based on what data we get every time in the files. But to automate this process, we have to assume the data format will be similar to the current data.</p>
<p>Assumptions</p>
<p>1. The .csv files movies_metadata.csv &amp; ratings.csv should be loaded in the same folder every time.</p>
<p>2. The file naming convention will remain the same. There will be no additional prefix or suffix added to the name.</p>
<p>3. The field names will remain consistent in new files as well. There will not be any case change or any prefix or suffix to the name.</p>
<p>4. The number of fields on the files will remain consistent and in the same sequence.</p>
<p>5. Datatype for each field will not change.</p>
<p>6. Web location to pull the wikipedia.movies.json&nbsp;file remains the same.</p>
<p>7. Tables always exists in the database.</p>
<p>8. Database is never renamed. The name of the database will remain consistent.</p>
<p>9. Database username/password and the port remain the same.</p>
