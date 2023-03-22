# SuicideAnalysis

-   authors: Mehwish Nabi

# Table of Contents

-   [Suicide Analysis on render](#SuicideAnalysisonrender)
-   [Motivation and research questions](#Motivation-and-research-questions)
-   [Description of the app](#Description-of-the-app)
-   [Installation](#Installation)
-   [Get Involved](#Get-Involved)
-   [Contact us](#Contact-us)
-   [License](#license)

## Suicide Analysis on render 

The dash app has been deployed on render.com It can be accessed [here](https://suicideanalysis.onrender.com/).

![](img/demo.gif)

## Motivation and research questions

Target audience: Our main target audience includes mental heath graduate research students who are interested in root cause of mental health illness including suicide , and is interested in identifying the patterns and trends that can help form effective prevention strategies.

The main research questions addressed by DS-Salaries are:

- Are suicide rates more prevelant in certain age groups? 
- Is suicide rate in a country impacted by its gdp?
- Are suicide rates decreasing or increasing in a country?
- Is suicide  more common in a certain gender ? 
- Which countries have a highest suicide rate ?

## Description of the app

Based on the motivation and aim of this app, it has a landing page that shows the suicide rate worldwide and the bar plot showing the countries with highest suicide rate. 

The first global option is a drop down which allows to select a particular country, showing the plot for that country  or in case of without selection it shows worldwide line plot  and a bar plot of 10 countries with highest suicide rate.
 
The second global drop down option allows to group the data by age , gender or gpd when a country is selected in previous dropdown. It allows the data to be analyzed across multiple group. However, when the previous selection is worldwive, the groupings provided in this drop down are gender and age only.  These groupings are shown as a plot and the sum for that particular category as bar plot(Except for gdp).

## Installation

To install `SuicideAnalysis` locally, you can:

1. Clone this repository with:

```
https://github.com/MNBhat/SuicideAnalysis
```

2. Install the environment of this project in your terminal at the root directory with the following code:

```
conda env create --file analysis.yaml
```

3. Then, change your environment to this project's environment with the following code:

```
conda activate analysis

```
4.  To run the app locally 

    - Open `VSCode`, navigate to the `src` folder under the root directory of the project, open `app.py` and run it by clicking Run Python file button on the top-right corner.

    - Open a command line, navigate to the `src` folder under the root directory of the project, run the following command to run the app locally:

        ```
        python app.py
        ```

## Get Involved

If you are interested in contributing to the app we welcome to share your thoughts. Particularly we would appreciate:

-   Additional data. This app is constantly evolving and being updated with new data. If you posses data related to Data Science salaries that can be applied to this Dashboard we would highly appreciate your contribution.

## Contact us

If you would like to help with the development of this Dashboard feel free to contact us after referring to our [contributor's guidelines](CONTRIBUTING.md)

## License

Licensed under the terms of the [MIT license](LICENSE).


```python

```
