# Binder environments
Central location for binder environments, especially those used with my book, Hands-On Data Analysis with Pandas. The actual Jupyter Notebooks and content are located in separate GitHub repositories. This makes it possible to build the environment [faster](https://discourse.jupyter.org/t/tip-speed-up-binder-launches-by-pulling-github-content-in-a-binder-link-with-nbgitpuller/922/36) since each push of new content to the repository won't trigger a rebuild of the environment. 

Some helpful Binder link generators:
- [general case](https://mybinder.org/): when the environment specifications and content are in the same repository
- [nbgitpuller](https://jupyterhub.github.io/nbgitpuller/link?tab=binder): when using separate repositories for the content and the environment

## Available environments

- Hands-On Data Analysis with Pandas:
    - [2nd Edition](#hands-on-data-analysis-with-pandas--second-edition-april-2021)
    - [1st Edition](#hands-on-data-analysis-with-pandas--first-edition-july-2019)
- [Pandas Workshop](#pandas-workshop)

---

### Hands-On Data Analysis with Pandas &ndash; Second Edition (April 2021)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stefmolin/binder-environments/2nd_edition?urlpath=git-pull?repo=https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas-2nd-edition) [![Purchase the book on Amazon](https://img.shields.io/badge/Amazon-purchase-orange?logo=amazon&logoColor=orange)](https://www.amazon.com/gp/product/1800563450/) [![View repository on GitHub](https://img.shields.io/badge/Github-view%20repo-lightgrey?logo=GitHub&logoColor=white)](https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas-2nd-edition)

<a href="https://www.amazon.com/gp/product/1800563450/"><img src="https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas-2nd-edition/blob/master/_img/cover.PNG" alt="Hands-On Data Analysis with Pandas – Second Edition" height="256px" align="right"></a>

Data analysis has become an essential skill in a variety of domains where knowing how to work with data and extract insights can generate significant value. *Hands-On Data Analysis with Pandas* will show you how to analyze your data, get started with machine learning, and work effectively with the Python libraries often used for data science, such as pandas, NumPy, matplotlib, seaborn, and scikit-learn.

Using real-world datasets, you will learn how to use the pandas library to perform data wrangling to reshape, clean, and aggregate your data. Then, you will learn how to conduct exploratory data analysis by calculating summary statistics and visualizing the data to find patterns. In the concluding chapters, you will explore some applications of anomaly detection, regression, clustering, and classification using scikit-learn to make predictions based on past data.

This updated edition will equip you with the skills you need to use pandas 1.x to efficiently perform various data manipulation tasks, reliably reproduce analyses, and visualize your data for effective decision making—valuable knowledge that can be applied across multiple domains.

*The [2nd_edition branch](../../tree/2nd_edition) defines the environment needed to run the code bundle for 2nd edition of Hands-On Data Analysis with Pandas using binder.*

### Hands-On Data Analysis with Pandas &ndash; First Edition (July 2019)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stefmolin/binder-environments/1st_edition?urlpath=git-pull?repo=https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas) [![Purchase the book on Amazon](https://img.shields.io/badge/Amazon-purchase-orange?logo=amazon&logoColor=orange)](https://www.amazon.com/Hands-Data-Analysis-Pandas-visualization/dp/1789615321) [![View repository on GitHub](https://img.shields.io/badge/Github-view%20repo-lightgrey?logo=GitHub&logoColor=white)](https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas)
<a href="https://www.amazon.com/Hands-Data-Analysis-Pandas-visualization/dp/1789615321"><img src="https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas/blob/master/_img/cover.PNG" alt="Hands-On Data Analysis with Pandas" height="256px" align="right"></a>


Data analysis has become an essential skill in a variety of domains where knowing how to work with data and extract insights can generate significant value.

*Hands-On Data Analysis with Pandas* will show you how to analyze your data, get started with machine learning, and work effectively with Python libraries often used for data science, such as pandas, NumPy, matplotlib, seaborn, and scikit-learn. Using real-world datasets, you will learn how to use the powerful pandas library to perform data wrangling to reshape, clean, and aggregate your data. Then, you will learn how to conduct exploratory data analysis by calculating summary statistics and visualizing the data to find patterns. In the concluding chapters, you will explore some applications of anomaly detection, regression, clustering, and classification, using scikit-learn, to make predictions based on past data.

By the end of this book, you will be equipped with the skills you need to use pandas to ensure the veracity of your data, visualize it for effective decision-making, and reliably reproduce analysis across multiple domains.

*The [1st_edition branch](../../tree/1st_edition) defines the environment needed to run the code bundle for 1st edition of Hands-On Data Analysis with Pandas using binder.*

---

### Pandas Workshop

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stefmolin/binder-environments/pandas_workshop?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fstefmolin%252Fpandas-workshop%26urlpath%3Dlab%252Ftree%252Fpandas-workshop%252F%26branch%3Dmaster) [![View repository on GitHub](https://img.shields.io/badge/Github-view%20repo-lightgrey?logo=GitHub&logoColor=white)](https://github.com/stefmolin/pandas-workshop)

Working with data can be challenging: it often doesn’t come in the best format for analysis, and understanding it well enough to extract insights requires both time and the skills to filter, aggregate, reshape, and visualize it. This session will equip you with the knowledge you need to effectively use pandas – a powerful library for data analysis in Python – to make this process easier.

Pandas makes it possible to work with tabular data and perform all parts of the analysis from collection and manipulation through aggregation and visualization. While most of this session focuses on pandas, during our discussion of visualization, we will also introduce at a high level matplotlib (the library that pandas uses for its visualization features, which when used directly makes it possible to create custom layouts, add annotations, etc.) and seaborn (another plotting library, which features additional plot types and the ability to visualize long-format data).

*The [pandas_workshop branch](../../tree/pandas_workshop) defines the environment needed to run the Jupyter Notebooks for my "Introduction to Data Analysis Using Pandas" workshop.*

---
