# analyse_ab_tests_results
Apply inferential statistics and probability to the analysis of A/B Tests results.  
The code goes through the result of an A/B test run by an e-commerce website. The objective is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

# Analysis steps
1. We explored conversion probabilities for an individual in the control group and for another one in the treatment group.  
2. We ran Hypothesis Testing first using confidence intervals and then simulation under the Null Hypothesis. We observed the p-value.   
3. As an alternative method, we used stats.proportions_ztest to compute our test statistic and p-value.  
4. We applied logistic regression using statsmodels to assess the significance of the involved variables for more deeper insights.   

# Installation
1. [Download and install Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html). I suggest Miniconda which is quick and easy

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

