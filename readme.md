# Customer Segmentation Project

## Overview
This project applies **RFM (Recency, Frequency, Monetary)** analysis and clustering techniques to segment customers based on purchasing behavior. By identifying customer segments, businesses can improve marketing strategies, enhance customer satisfaction, and boost sales.

---

## Table of Contents
1. [Overview](#overview)  
2. [Dataset](#dataset) 
3. [Methodology](#methodology)  
 

  
4. [License](#license)  
5. [Contributing](#contributing)  


---

## Dataset

### Description
The dataset is a transactional record of an online retail store. It contains the following fields:

| **Column Name** | **Description**                                  |
|------------------|--------------------------------------------------|
| **InvoiceNo**    | A unique number assigned to each invoice.        |
| **StockCode**    | The product code of the purchased item.          |
| **Description**  | Text description of the product.                |
| **Quantity**     | Number of units purchased for a specific item.  |
| **InvoiceDate**  | Date and time when the transaction occurred.    |
| **UnitPrice**    | Price per unit of the item.                     |
| **CustomerID**   | Unique identifier assigned to a customer.       |
| **Country**      | The country where the customer is located.      |

---

## Methodology

This project follows a structured approach to segment customers based on their purchasing behavior. The key steps are outlined below:

### 1. Data Preprocessing
- Handled missing values by removing records with missing `CustomerID`.
- Filtered out transactions with invalid or negative values (e.g., negative quantities or prices).
- Converted the `InvoiceDate` to a standard datetime format.
- Created relevant features for analysis:
  - **Total Sales**: Computed as `Quantity * UnitPrice` for each transaction.

### 2. RFM Analysis
- Calculated three key metrics for each customer:
  - **Recency**: Days since the customer’s last transaction.
  - **Frequency**: Number of transactions made by the customer.
  - **Monetary**: Total revenue generated by the customer.
- Scaled the RFM values to ensure balanced clustering.

### 3. Clustering
- Used **K-means clustering** to segment customers based on RFM scores.
- Determined the optimal number of clusters using the **Elbow Method**:
  - Evaluated distortion (sum of squared distances) for different cluster sizes.
- Grouped customers into distinct clusters based on their purchasing behavior.

### 4. Visualization
- Plotted customer clusters to gain insights into the segments.
- Created visualizations for RFM distributions and cluster characteristics.

---

### Rationale for RFM Analysis
RFM analysis is a proven method to segment customers, focusing on:
- **Recency**: Helps identify how recently customers interacted, targeting re-engagement strategies.
- **Frequency**: Measures customer loyalty and repeat purchase behavior.
- **Monetary**: Assesses the customer’s total contribution to revenue.

This methodology ensures actionable insights, enabling businesses to develop personalized marketing strategies and improve customer satisfaction.
---
## License

This project has the MIT license 

---
## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. **Fork the Repository**:  
   Click the "Fork" button on the top-right corner of this repository to create a copy in your account.

2. **Clone Your Fork**:  
   Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/SnehaVPujari007/customer-segmentation.git
   cd customer-segmentation

   





