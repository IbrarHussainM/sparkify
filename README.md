<article class="markdown-body entry-content container-lg" itemprop="text">
    <h1><a id="user-content-sparkify-project-from-data-scientist-nanodegree">Sparkify Project for Data Scientist Nanodegree</a></h1>
    <h2><a id="user-content-introduction">Introduction</a></h2>
    <p>This is a project provided by Udacity and the goal of this project is to build a model
        that predicts the churn of a user based on variables such as gender and information about how the user uses the app. We will show the phases of the project.          There is an article in medium:
    </p>
    <p><a href="https://medium.com/@ibrarhussainse/big-data-pipelines-with-pyspark-to-detect-churned-users-f4cd8e27423f" rel="nofollow">Medium article</a></p>
    <h2><a id="user-content-loading-and-cleaning-the-dataset">Loading and cleaning the dataset</a></h2>
    <p>We load and clean the dataset, checking for invalid or missing data; for example, records without userids or sessionids.</p>
    <h2><a id="user-content-exploratory-data-analysis">Exploratory data analysis</a></h2>
    <p>We defined the variable churn and after that we do some exploratory analysis in order to find good predictors.</p>
    <h2><a id="user-content-modelling">Modelling</a></h2>
    <p>We split the full dataset into train, test, and validation sets. We tested out a random forest model with default values. Moreover, we evaluated the f1 metric, we do not use tuning parameters because it turns out to be computational expensive. Finally, the model works well in a small dataset, but this does not mean that work well in the full dataset.</p>
    <h2><a id="user-content-project-components">Project components</a></h2>
    <p><a href="https://raw.githubusercontent.com/ricardoues/sparkify-project/master/Sparkify.ipynb" rel="nofollow">Sparkify.ipynb</a>: a notebook file containing the analysis.</p>
    <p><a href="https://github.com/ricardoues/sparkify-project/blob/master/mini_sparkify_event_data.json.zip?raw=true">mini_sparkify_event_data.json.zip</a>: training json file.</p>
    <h2><a id="user-content-how-to-run-the-project">How to run the project</a></h2>
    <p>In order to run the jupyter notebook, first of all you have to install Apache Spark, the following web site is a good resource:</p>
    <p><a href="https://computingforgeeks.com/how-to-install-apache-spark-on-ubuntu-debian/" rel="nofollow">Installing Apache Spark</a></p>
    <p>In addition to that you should clone the repository and inside of the main directory, you must have to install the dependencies with the following command:</p>
    <div class="highlight highlight-source-shell"><pre>pip install -r requirements.txt</pre></div>
</article>
