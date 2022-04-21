# Interactive Dot Plots Using Dash

A bird's eye view of the valence of people's responses (and responses themselves) when asked to predict unexpected events that might occur after everyday scenarios. 

Data was collected and labelled for studies in [Quinn, Campbell, & Keane (2021)](https://doi.org/10.1016/j.cognition.2020.104520) published in Cognition. In this paper, we described how the unexpected events people predict will occur after everyday scenarios (such as going shopping, making breakfast, taking a trip), are largely negatively-valenced, but this can change depending on the valence of the original scenario. The data from this paper are available in a [Mendeley Repository](https://doi.org/10.17632/kkt999sn7b.1) with corresponding [Data in Brief paper](https://doi.org/10.1016/j.dib.2021.106935).

Using the data from these experiments, I have made interactive dot plots (à la [Arkes & Gaissmaier (2012)](https://doi.org/10.1177/0956797612437428)) with the responses for each scenario presented, colored by their labeled valence.

![Example Showing Expt 1](images/colab_capture.gif) 

The static dot plots themselves were largely based on [this blog]( https://blog.matteoferla.com/2019/10/pictograms-with-plotly-and-fontawesome.html), and the braces showing overall percentage for positive and/or negative are 90-degree rotated versions of [this stackoverflow answer](https://stackoverflow.com/a/61454455).

To use the interactive plots, open the [interactive_plots_colab.ipynb](interactive_plots_colab.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MollySQuinn/interactive_unexpected_events/blob/main/interactive_plots_colab.ipynb) file in Google Colab. The last cell defines the DASH app and will display the app in-line in the notebook.
