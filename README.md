Modeling the Effects of Nutrition with Mixed-Effect Bayesian Network
--------------------------------------------------------------------

This work proposes Mixed-Effect Bayesian Network (MEBN) as a method for modeling the effects of nutrition. It allows to identify both typical and personal correlations between nutrients and their bodily responses. Predicting a personal network of nutritional reactions would allow interesting applications at personal diets and in understanding this complex system. Brief theory of MEBN is given followed by implementation in R and Stan. A real life dataset from a nutritional Sysdimet study is then analyzed with the method and the results are visualized with an interactive JavaScript-visualization.

[Open HTML-version of the notebook here](http://htmlpreview.github.io/?https://github.com/turkiaj/StanCon2018/blob/master/PersonalEffectsOfNutrition.html)

Contents
--------

Main body of the presentation is found here as fully functional RMarkdown notebook, and also HTML and PDF renderitions of it. The notebook uses my R-package "MEBN" for constructing a Mixed-Effect Bayesian Network that models the effects of nutrition from a real life nutritional dataset. The fully Bayesian estimation of the local mixed-effect models at the network is done with Stan. Visualization of the network is created with JavaScript library sigma.js and some customizations of it.

-   PersonalEffectsOfNutrition.Rmd : RMarkdown notebook
-   PersonalEffectsOfNutrition.html : HTML knit of the notebook with active JavaScript visualization
-   PersonalEffectsOfNutrition.pdf : PDF knit of the notebook
-   population\_graph.htm : HTML document for graph visualization
-   biblio.bib : References for the notebook in BibLatex format
-   data-folder: The dataset that is used in the notebook analysis
-   mebn-folder: The R-code for constructing MEBN and stan-model definitions
-   visualization-folder: JavaScript code for graph visualization
-   models-folder: Sampled Stan-models are cached in this folder once the notebook is executed. It is empty by default.
