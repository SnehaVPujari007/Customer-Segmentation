# Customer Segmentation Project
<h3> Overview </h3>
<p>This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis and clustering techniques to group customers based on their purchasing behaviors. Customer segmentation helps businesses to tailor marketing strategies, improve customer satisfaction, and drive targeted sales efforts.</p>

<h3>Table of Contents </h3>
<li>Overview </li>

<li>Dataset </li>
<li>Methodology </li>

<li>Results </li>
<li>Contributing</li>
<li>License </li>

<h3>Dataset </h3>

<ol>The dataset used is a transactional dataset of an online retail store, which includes the following columns: </ol>

<li>InvoiceNo: Unique invoice number for each transaction. </li>
<li>StockCode: Product code. </li>
<li>Description: Product description. </li>
<li>Quantity: Quantity of product purchased. </li>
<li>InvoiceDate: Date and time of the transaction. </li>
<li>UnitPrice: Price per unit.</li>
<li>CustomerID: Unique identifier for each customer. </li>
<li>Country: Customer’s country. </li>


<h3>Methodology</h3>
<li>Data Preprocessing: </li>

<ol>Cleaned data by handling missing values and removing invalid entries. </ol>
<ol>Filtered relevant columns and converted data types.</ol>
<li>Feature Engineering with RFM Analysis:</li>

<ol>Calculated Recency (days since last purchase), Frequency (total purchases), and Monetary (total spending) for each customer.<ol>
<ol>Standardized RFM values for clustering.</ol>
<li>Clustering: </li>

<ol>Used K-means clustering to segment customers into distinct groups.</ol>
<ol>Determined the optimal number of clusters using the Elbow Method and Silhouette Score.</ol>
<li>Visualization:</li>

<ol>Visualized clusters to interpret customer segments and analyze behaviors.</ol>



<h3>Contributing</h3>
<b>Contributions are welcome! Please submit a pull request for any changes, or open an issue to discuss further improvements.</b>

<h3>License</h3>
<li>This project is licensed under the MIT License.</li>

