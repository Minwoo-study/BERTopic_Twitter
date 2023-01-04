# BERTopic_Twitter

<!--- These are examples. See https://shields.io for others or to customize this set of shields. You might want to include dependencies, project status and licence info here --->

This project is a English `BERTopic` by MaartenGr(https://github.com/MaartenGr/BERTopic.git). 
Topic modeling analysis about `Twitter` data.

Example data was collected from Twitter API, which contains the hashtag #britishmuseum.

This data was used for personal Master thesis.

## Prerequisites

Before you begin, ensure you have met the following requirements:
<!--- These are just example requirements. Add, duplicate or remove as required --->
* You have installed the `Python` over Python 3.7.
* install the BERTopic by running the code below.
```
!pip install bERTopic
```
## Using TripAdvisor Review Crawling

To use <BERTopic>, follow the twitterBERTopic.ipynb file.

There are four steps in the project.

1. Import Data(#britishmuseum_no_retweet_raw.csv)
2. Install and import packages
3. EDA(Visualize the number of tweets over time, find word frequency)
4. BERTopic
5. Visualize the topics over time

** The models used in this project are **
1. vectorizor : CountVectorizer
2. stopwords : stopwords from spacy(https://spacy.io/)
3. clustering : KMeans clustering(cluster=10)
4. max documents frequency : 0.7


you can adjust models or parameters above.


## Contributing to <BERTopic twitter>
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
To contribute to <pBERTopic twitte>, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).


## Contact

If you want to contact me you can reach me at <david1224@g.skku.edu>.

