![MMM_Pic.pdf](https://github.com/Amiteshwar-Kukreja/Media-mix-modelling/files/10680085/MMM_Pic.pdf)

# Media-mix-modelling

## Key Objectives
Companies spend significant budgets on different media such as TV, online, social, print etc. to promote sales of their products and services. In order to optimize these spends and ensure that they give the best impetus to sales, it is important to understand the impact of each media on sales. <br> 

* Create a media mix model to extract the impact of different media on a company's sales. 
* Calculate the Return on Ad Spend for each media.


## Model

The model built here is based on two important and well documented effects of advertising:

**Carryover**: Advertising can have an impact not just in the immediate advertising period (day/week), but in future as well. This results from the fact that many consumers may not immediately act on an advertising they have seen for reasons such as purchase cycles, decision making time, product distribution, inertia etc. The effect that advertising has in future time periods is known as the "carryover" effect of advertising.

**Saturation**: Saturation essentially implies that the impact of any advertising medium will tend to taper and ultimately plateau as more and more money is spent on that medium. Put another way, spending an infinite amount of money on advertising will not lead to infinite sales. 

The model we will create here  can be mathematically represented as:

### &emsp;&emsp; $Y_{t} = Trend_{t} + Media Effect_{t} + \epsilon_{t}$

where 

$Y_{t}$ is the sales in time period (t).

$Trend_{t}$ is the underlying sales trend in time period (t) i.e. sales that takes place without any marketing spend.

$Media Effect_{t}$ is the amount of sales that can be attributed to the media spend. media_effect can be dervied for each medium separately.

$\epsilon_{t}$ is the noise and accounts for the unexplained part of sales.


## Dataset

The dataset used in this project is a synthetic dataset sourced from Kaggle. It has around 4 years of weekly data on sales and spends across TV, radio and newspaper. 
