<!-- This works while repo is private -->
<a href="https://crucible.dreadnode.io">
    <img src="media_collateral/crucible_logo/crucible-icon-dark-transparent.png" alt="Crucible logo" title="Crucible" align="right" style="width:75px" />
</a>

# Crucible Resources

The following resources are provided to get you started on interacting with the challenges hosted on the Crucible CTF platform. If you have participated in Kaggle challenges or the previous AI Village DECON 30/31 CTFs, then you have been exposed to [Jupyter Notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html). If not, don't worry we have you covered with a starter kit. This is supposed to be fun and exploratory - lets begin!

## How To

### Environment Setup

There are a few options available to you when getting started with the provided Jupyter Notebook(s).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dreadnode/crucible-resources/main) [![Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dreadnode/crucible-resources/blob/main/test.ipynb) [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/dreadnode/crucible-resources/blob/main/test.ipynb)

#### Easy
Use the [MyBinder link](https://mybinder.org/v2/gh/dreadnode/crucible-resources/main) to launch a Jupyter Lab environment in the cloud with all the environment variables satisfied and no additional hardware/infrastructure startup issues.

#### Schmedium Easy
Use a cloud providers Jupyter Notebook offering (e.g., AWS SageMaker, Azure ML Studio, CoCalc, Databricks, [Google Colab](https://colab.research.google.com/github/dreadnode/crucible-resources/blob/main/test.ipynb), IBM Watson, [Kaggle Kernels](https://kaggle.com/kernels/welcome?src=https://github.com/dreadnode/crucible-resources/blob/main/test.ipynb), Saturn Cloud) and load the Notebooks into their infrastructure and create the Python environment with the requirements.txt file. Free tiers are common to get users onto the platform, but expect costs for increased compute requirements and additional features.

#### Medium Hard
Use a local environment (e.g., Visual Studio Code, Jupyter Lab, Conda) to run your Jupyter Notebooks in and manage your own Python environments with Virtualenv/venv, Poetry, Conda, etc. VSCode is the team's preferred long term solutions as it provides a lot of natively supported features for the ipython kernel and keeps you in an IDE with all your favorite tools (Copilot, linting, autocomplete, etc.)

### Challenges

Our Crucible community tier provides access to 10 rotating challenges that are pulled from previous DEFCON CTF challenge pools. The following is the recommended approach to interacting with the Crucible CTF challenges:

1. Start with the [test challenge](/test-challenge) to make sure you have good two way communications with our Crucible servers.
2. Progress through Easy -> Hard challenges as you warm up and stretch your offensive AI/ML muscles. There is no guarantee that Easy, Medium, and Hard challenges will be present in the random 10 that have been chosen for the Community plan, in which case we encourage you to roll up your sleeves and still give it a go. Dive into the Recommended Reading section for some tutorial *spoiler alerts* to get you through tough spots.
3. Optional - should you feel like you have this content mastered, please reach out to us <support@dreadnode.io> to suggest new Community challenges or submit one for consideration.

## test.ipynb Jupyter Notebook

The [test challenge](/test-challenge) is the recommended starting point for first time users of the CTF platform. This gets you comfortable with the API token issued to you at the start of your interaction with challenges. The Jupyter Notebook titled test.ipynb provides you an input field to copy and paste your API token into and then test your access to the backend servers to ensure that you are correctly forming your HTTP requests to submit follow-on flag submissions. This is the only purpose of this Notebook as it is provided, but feel free to build and experiment with this as you try additional challenges.

### Demo

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dreadnode/crucible-resources/main)

Quick demo video of launching from the MyBinder link, into their JupyterLab environment, and then executing the required cells for a successful completion of test.ipynb.



## Recommended Reading / References

 For more in-depth challenge specific hints/solutions (*spoiler alert*) check out:

* DEFCON 30 AI Village CTF challenge <https://www.kaggle.com/competitions/ai-village-ctf>
* DEFCON 31 AI Village CTF challenge <https://www.kaggle.com/competitions/ai-village-capture-the-flag-defcon31>
