# Learning Path Generation

A brief description of the files in this repository:

1.getprompt.ipynb: This file contains functions for generating personalized 
prompts to guide users in their learning journey. It includes functions for 
retrieving the access token, generating the scale of prompt, and generating 
the path of prompt based on the user's selected pool.

2.getanswer.ipynb: This file contains functions for generating answers to 
user queries. It includes functions for retrieving the access token and 
generating the answer based on the user's query.

3.estimate.ipynb: This file contains functions for generating estimates of 
user's performance based on their selected pool. It includes functions for
encoding text, calculating similarities, and generating the best fit pool.

4.creategraph.ipynb: This file contains functions for creating graph 
visualizations for the learning paths. It includes functions for plotting 
the graph, customizing the node sizes, and saving the graph as a PNG image.

## Usage

1.Setup: To use these files, first download and install Jupyter Notebook 
on your machine. Then, create a virtual environment and install necessary 
dependencies using the provided requirements.txt file.

2.Getprompt: Open the getprompt.ipynb file and execute the cells to get
personalized prompts for the user.

3.Getanswer: Open the getanswer.ipynb file and execute the cells to get answers to user queries.

4.Estimate: Open the estimate.ipynb file and execute the cells to generate estimates of user's performance.

5.Creategraph: Open the creategraph.ipynb file and execute the cells to generate graph visualizations for the learning paths.

## Notes

The getprompt.ipynb and getanswer.ipynb files require separate API keys and secret keys, which are stored in a config.json file.
The estimate.ipynb file requires the sentence-transformers package, which can be installed using the provided pip command.
The creategraph.ipynb file requires the networkx, matplotlib, and pool packages, which are listed in the requirements.txt file.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
Notes
