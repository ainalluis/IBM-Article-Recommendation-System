# IBM-Article-Recommendation-System
## Motivation
Recommendation systems play a key role in helping users discover relevant content in environments with large volumes of information. Platforms that provide technical articles, tutorials, or documentation benefit significantly from effective recommendation engines that improve user engagement and learning outcomes.

The motivation of this project is to explore and compare multiple recommendation strategies to suggest relevant articles to users based on their interaction history and article content. By implementing different approaches, this project aims to highlight the strengths, limitations, and appropriate use cases of each recommendation technique.

##Dataset

This project uses interaction data from the IBM Watson Studio platform, which includes records of users interacting with technical articles. The dataset contains information about users, article identifiers, article titles, and user–article interactions.

## Software Dependencies

The project was developed using Python and the following main libraries:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

All analysis, modeling, and evaluation are performed in a Jupyter Notebook.

## File Descriptions
- Recommendations_with_IBM.ipynb: Main Jupyter notebook containing the full analysis, implementation of recommendation systems, and results.
- README.md: Project documentation and overview.

## How to Interact with This Project
1. Clone the repository
2. Install the required Python libraries
3. Open the Jupyter notebook
4. Run the notebook cells sequentially to reproduce the analysis and results


## Results Summary

The project demonstrates that different recommendation techniques are suitable for different user scenarios:

Rank-based recommendations are effective for cold-start users.

Content-based recommendations work well for users with limited interaction history.

Collaborative filtering and matrix factorization provide stronger personalization for users with rich interaction histories.

Matrix factorization (SVD) captures latent relationships between articles that are not immediately evident from text similarity alone.

Overall, the results highlight the importance of using a hybrid recommendation strategy that adapts to user behavior and data availability.


## Licensing

This project is provided for educational purposes only. The dataset is provided as part of the Udacity program and is subject to the corresponding usage guidelines.


## Authors
Aina Lluís Huelmo

## Acknowledgments
- IBM Watson Studio for providing the interaction dataset
- Udacity course instructors and materials for guidance on recommendation systems and the data science process
