<h1 align="center">🎧 Spotify Mood Clustering</h1>

<p align="center">
  <b>Unsupervised Machine Learning Project</b><br>
  Clustering Spotify songs into moods using audio features and KMeans.
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
  This project uses Spotify audio features like <code>valence</code>, <code>energy</code>, <code>danceability</code>, etc., to group songs into mood-based clusters using the <b>KMeans</b> algorithm. The dataset contains no track names — it focuses purely on audio characteristics.
</p>

<h3>🎯 Goals:</h3>
<ul>
  <li>Perform mood-based clustering on songs</li>
  <li>Use audio features only (no lyrics or track names)</li>
  <li>Apply data preprocessing and feature scaling</li>
  <li>Visualize mood clusters using PCA</li>
  <li>Predict mood cluster of new songs based on features</li>
</ul>

<hr>

<h2>📁 Dataset</h2>
<p>
  Dataset used: <a href="https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset" target="_blank">Spotify Music Dataset</a><br>
  Contains audio features like:
</p>
<ul>
  <li><code>energy</code></li>
  <li><code>valence</code></li>
  <li><code>danceability</code></li>
  <li><code>loudness</code></li>
  <li><code>acousticness</code></li>
  <li><code>speechiness</code></li>
  <li><code>instrumentalness</code></li>
  <li><code>tempo</code></li>
  <li><code>liveness</code></li>
</ul>

<hr>

<h2>🧠 Techniques Used</h2>
<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Task</th>
      <th>Method</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Feature Scaling</td>
      <td>StandardScaler (scikit-learn)</td>
    </tr>
    <tr>
      <td>Clustering</td>
      <td>KMeans (scikit-learn)</td>
    </tr>
    <tr>
      <td>Cluster Visualization</td>
      <td>PCA + Seaborn Scatterplot</td>
    </tr>
  </tbody>
</table>

<hr>


<h2>📦 Dependencies</h2>

<ul>
  <li>pandas</li>
  <li>numpy</li>
  <li>scikit-learn</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ul>

<hr>

<h2>📌 Project Status</h2>
<p>✅ Feature extraction and clustering complete.<br>🟡 Deployment not included as per scope.</p>