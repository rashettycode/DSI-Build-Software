# NY Times AI Article Analysis Package

This Python package is designed to interact with the New York Times API to fetch and analyze articles related to Artificial Intelligence. It sorts articles based on their popularity and provides statistical insights.

# Key Features
Fetch AI-related articles from the NYT API. Analyze articles to find the most popular ones. Perform simple statistical analyses, like calculating mean word count. Visualize data through basic plotting.

# Requirements
The package requires the following Python libraries:

requests: For making API requests. PyYAML: For handling YAML configuration files. numpy: For numerical operations. matplotlib: For generating plots. scipy: For statistical functions. 

To install these, run pip install -r requirements.txt.

python analysis.py job_config.yml

# Usage
After setting up your API key in the configuration files, you can use the package to fetch articles, analyze data, and plot results.

# Testing Run Python -m unittest to execute tests and ensure the functionality of the package.

# Troubleshooting
If you encounter issues with making API calls, ensure that your Python environment has internet access and that you've correctly configured the API URL, parameters, and API key.

# Credits
New York Times API - For providing the API used in this example. Feel free to modify and use this example for making API calls in your projects. Happy coding!

# Steps to use

pip install git+https://github.com/torontodeveloper/dsi-build-software-project

# on Google Colab
clone the package first !git clone link to the github repo
!pip install .

import sys
sys.argv = ['analysis.py', 'job_config.yml']  # The first argument is ignored, it's just a placeholder for the script name.
from analysis import Analysis  # Import the Analysis class

Instantiate and use the Analysis class, the argument is just a placeholder and will be overridden by sys.argv
analysis = Analysis('placeholder_for_job_config')

analysis.plot_data()




