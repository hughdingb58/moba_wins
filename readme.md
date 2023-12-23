This is a repository containing files for our completed **MOBA win condition analysis** project. They were done as part of our University of Michigan Master of Applied Data Science (MADS) milestone projects. All work was done in Python through Jupyter notebooks.

Our project sections and corresponding notebooks are organized as follows:

- **Milestone 1**: we performed exploratory data analysis on League of Legends and Dota 2 datasets. Notebooks are as follows:
	- **notebooks/1_dota_exploration.ipynb**: cleaning and exploration of Dota 2 data.
	- **notebooks/2_league_exploration.ipynb** (to be added): cleaning and exploration of League of Legends data.
	- **notebooks/3_cross_game_exploration.ipynb** (to be added): comparison of Dota 2 and League of Legends datasets.
- **Milestone 2**: building upon our work in milestone 1 for the Dota 2 dataset only, we modelled relationships between winning and in-game features, including manually engineered features like chat analysis. Notebooks are as follows:
	- **notebooks/chat.ipynb** (to be added): chat sentiment and polarity feature engineering on Dota 2 chat logs.
	- **notebooks/supervised.ipynb**: supervised modelling and analysis on the Dota 2 dataset, including chat features. Includes cleaning and exploration from 1_dota_exploration.ipynb (implementing milestone 1 feedback).
	- **notebooks/unsupervised.ipynb** (to be added): unsupervised clustering on the Dota 2 dataset.

**Contributors**:

- Abhay Baliga
- Hugh Ding
- Seth Fleming

# Data

Our data involves the following two Kaggle datasets:

- [Dota 2 Matches](https://www.kaggle.com/datasets/devinanzelmo/dota-2-matches)
- [League of Legends Ranked Matches](https://www.kaggle.com/datasets/paololol/league-of-legends-ranked-matches)

Running the notebooks for our project will require this data. To do so, the datasets should be saved within the *dota* and *league* subfolders of the *data* folder. The overall file structure should be as follows:

- moba_wins
	- data
		- dota
			- *.csv files*
		- league
			- *.csv files*
	- intermediate
		- grids.pickle *(used in supervised.ipynb)*
		- *other intermediate files*
	- notebooks
		- 1_dota_exploration.ipynb
		- 2_league_exploration.ipynb
		- 3_cross_game_exploration.ipynb
		- chat.ipynb
		- supervised.ipynb
		- unsupervised.ipynb
