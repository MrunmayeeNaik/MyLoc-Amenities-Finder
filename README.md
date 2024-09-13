# MyLoc-Amenities-Finder
The MyLoc-Amenities Finder aims to help individuals who are new to a particular area become more familiar and comfortable with their surroundings. It accomplishes this by taking the user's location as an input and then identifying nearby facilities, which are classified into categories like food, shopping, medical, and grocery. The K-means clustering algorithm is used to create clusters of facilities within each category. Finally, these clusters are displayed on a map, providing a visual representation of the available amenities in the area.

## Problem Statement
A person who moves to a new location may find it difficult to figure out the locality as well as the basic amenities available nearby. The aim of this project is to assist user to quickly locate nearby amenities.

## Project Goals
To build an interactive website where user's can :
* Search for nearby amenities.
* Identify rating shown through varying colors in the drop location.
* User can select multiple amenities .

## Technologies Used
**Python Libraries:**
* Numpy and Pandas - For Data Manipulation.
* Seaborn and Matplotlib - For data visualization.
* Folium - To plot data points on map.
* Sklearn - To import machine learning algorithms.

**Machine Learning Algorithms:**
* K-Means : Used to cluster locations based on their characteristics and categorize them into groups like grocery, medical, shopping and dining. This clustering gave a clean and intuitive interface for users to find what they need.
* Random Forest : Used this to classify shop names into their respective categories. This improved the accuracy of categorization and gave users precise information about local amenities. 
