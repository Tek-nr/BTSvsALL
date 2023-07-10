# BTSvsALL

The BTSvsALL project focuses on analyzing the success and impact of BTS, one of the most influential representatives of K-pop culture. BTS has achieved global recognition, transcending the boundaries of the K-pop industry. This project conducts various analyses and comparisons based on the success of BTS.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Datasets](#datasets)
- [Analysis](#analysis)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The BTSvsALL project is divided into three main parts, aiming to provide insights into the K-pop industry and BTS's accomplishments.

1. **General Structure Analysis:** <br>
   In this part, we analyze a dataset comprising idols, girl groups, and boy groups to understand the overall structure of the K-pop industry. We explore technical characteristics such as average group size, debut dates, etc. This analysis helps us answer questions such as the number of members in a group, the countries idols come from, gender ratios, and the number of debuts over the years.

2. **Spotify API Analysis:** <br>
   In the second part, we use the Spotify API to gather data for various groups. We initially comment on the average values of K-pop songs based on this data. Additionally, we create a dataset with BTS as the target cluster (coded as 1) and other groups as non-target clusters (coded as 0). We train different models using this dataset and evaluate their performance using metrics such as Test Score, F1 Score, and AUC. We ensure our model does not overfit and compare the performance values to select the model with the highest performance. We also extend this analysis and comparisons to other globally successful artists by collecting their Spotify data.

3. **Album Analysis and Text Mining:** <br>
   In the final stage, we gather data on all the albums released by BTS. Utilizing text mining techniques, we conduct various analyses and visualizations on this dataset to gain insights into the themes, sentiments, and overall content of BTS's albums.

## Installation

To use the BTSvsALL project, follow these steps:

- Clone the repository:

   ```shell
   git clone https://github.com/Tek-nr/BTSvsALL.git

## Datasets
The project utilizes various datasets, including K-pop industry data, Spotify API data, and BTS album data. Please note that the datasets used in this project are not publicly available within the repository. You may need to source the relevant datasets separately and follow the data preprocessing steps provided in the project code.

## Analysis
The BTSvsALL project includes a range of analyses and visualizations to explore and compare the success and impact of BTS. The analyses performed cover general K-pop industry characteristics, Spotify data analysis, and album analysis using text mining techniques. The project provides insights into the structure of the K-pop industry, compares BTS's performance with other artists, and delves into the themes and sentiments expressed in BTS's albums.

## Contributing
Contributions to the BTSvsALL project are welcome! If you have any suggestions, feature requests, or improvements, please open an issue or submit a pull request.

## License
The BTSvsALL project is licensed under the MIT License. 
Feel free to further customize and modify this template to match your specific project details and requirements.

