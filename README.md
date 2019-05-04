# analyse_ab_tests_results
Apply inferential statistics and probability to the analysis of A/B Tests results.  
The code goes through the result of an A/B test run by an e-commerce website. The objective is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

# Installation
1. [Download and install Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html) I suggest Miniconda which is quick and easy

2. Install all the other dependencies using the "environment.yml" file included :
```
${HOME}/miniconda/bin/conda create -f environment.yml
```

3. Activate the new environment as suggested by conda
```
${HOME}/miniconda/bin/conda activate wrangling
```

4. launch jupyter using the notebook
```
$ jupyter-notebook wrangle_act.ipynb
```

