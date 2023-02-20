# Enhanced Indexation

### Description

Enhanced Indexation is a research about building portfolios to gain a profit that can beat the market. In other words, it is about finding the combinations of several stocks that have **better performance** than the market index, such as S&P 500, Dow 30, NASDAQ, etc.

There are a lot of related work in this area. What I did in my past research was to propose a new Enhanced Indexation model to find such portfolils. My motivation is to evaluate the portfolio behavior in an appropriate way, and control the possible **excess return and risk** by probability, because I assumed that there should be a distribution that can describe these two parts well. However, these constraints are hard to deal with. Another difficulty is that it is a **Sparse Optimization Problem**, because the idea is to select only several stocks from the tens of thousand stocks in the market. This comes from a practical view, since we may only have limited capital for investment. To solve such problems, I need to convert the model first and use some genetic algorithms to solve this NP-hard problem.

### Techniques

- Sparse Optimization Problem
- Genetic Algorithm
- Dual Theory and Distributional Robust Method
- Performance Evaluation Ratio

### Algorithm code

I used MATLAB to conduct the experiment. First, solve the optimization model by using the package 'CVX' in MATLAB. Then, use Hybrid Genetic Algorithm to solve the problem. I am trying to translate the code to Python now. Thankfully for the coming of ChatGPT recently, I tried to ask it to write a Hybrid Genetic Algorithm for me and got a really good result. Therefore, I am goint to post it in this folder for use (PS: tune it before usage).

