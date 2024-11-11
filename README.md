# Valorant Firearms Analysis using PCA

## Project Description
This project analyzes firearms data from the game *Valorant* using Principal Component Analysis (PCA) to explore and visualize weapon characteristics. In *Valorant*, each weapon has unique attributes such as damage, fire rate, accuracy, and range, which affect gameplay strategies and outcomes. By applying PCA, we can reduce the dimensionality of this data, uncover underlying patterns, and visualize weapon similarities and differences in a lower-dimensional space.

## Objective
The main objective of this project is to use PCA to:
- Identify core components that influence weapon characteristics.
- Reduce the complexity of firearm data while retaining essential information.
- Visualize firearms in a lower-dimensional space to aid in comparing weapon types and understanding their roles in gameplay.

## Insights and Applications
The insights gained from this analysis can help *Valorant* players better understand weapon advantages and trade-offs, potentially informing weapon selection and usage strategies. Additionally, this project provides a framework for future analysis of weapon data across updates or patches, where balance adjustments may alter weapon attributes.

## Project Structure

- **1. Importing Libraries**: Loading essential libraries for data manipulation, PCA, and visualization.
- **2. Loading and Understanding Data**: Importing firearms data from *Valorant*, including attributes like damage, accuracy, range, and more.
- **3. Data Cleaning**: Preparing the dataset by handling missing values, outliers, and ensuring data consistency.
- **4. Data Preprocessing**: Scaling and normalizing data to ensure each feature contributes proportionately to the PCA.
- **5. Applying PCA**: Performing PCA to reduce the dataset to a few principal components that capture most of the variance.
- **6. Visualization of PCA Components**: Plotting the reduced data to visualize firearm similarities and categorize weapons based on primary characteristics.
- **7. Interpretation and Analysis**: Analyzing the principal components to understand key attributes influencing weapon performance.

---

## Tools and Techniques
- **Pandas** and **NumPy**: For data handling and preprocessing.
- **Scikit-Learn (PCA)**: For dimensionality reduction and analysis.
- **Matplotlib** and **Seaborn**: For visualizing the relationships among firearms in reduced dimensions.

## Conclusion
This project provides a dimensionality-reduced view of *Valorant* firearms, making it easier to understand weapon characteristics and their similarities. By using PCA, we condense complex weapon data into core components, facilitating strategic analysis and potential application in gameplay optimization.

--- 

