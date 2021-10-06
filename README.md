# Sales Forecast based on Investment budget
Details on algebra and statistics. <br />
I'm Long. This is my project in Data Analysis suject at term 20202, Hanoi University of Science and Technology. <br />
Other creators: Dang Nguyen Hai, Phong Tran Hai, Chi Linh Nguyen, Nhung Hong Dang, Thu Pham Ngoc Thi.

#### Table of contents
1. [Introduction](#intro)
2. [Practical examples](#ex)

# <a name="intro"></a> Introduction

Linear regression is a popular machine learning algorithm, but many people still do not understand this algorithm deeply. Our research goal is to build a linear regression model based on mathematics such as Gauss theorem, test in statistics like F-test, t-test and clarify many important but many people ignored:
  - Geometry of Least Squares
  - Confidence intervals of regression coefficients
  - Hypothesis testing of regression coefficients
  - Inferences from the Estimated Regression Function
  - Leverage
  - More

# <a name="ex"></a> Practical examples

After clarifying the theoretical basis, we build a linear regression model with real data. 

We have data on sales of a product (`Sales`) of a company in 200 different markets, along with advertising investment budget for that product in 3 media: `TV`, `Radio` and `Newspape`r.

The company cannot directly increase product sales. On the other hand, they can control the cost of advertising on each media. Therefore, if we determine that there is a link between advertising and sales, we can guide the company to adjust its advertising budget, thereby indirectly increasing sales. In other words, our goal is to develop an accurate model that can be used to predict sales on the basis of advertising budgets.
