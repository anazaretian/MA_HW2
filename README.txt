Ad Testing: Which Algorithm Wins? (Homework 2)
This homework compares two different ways of picking the best advertisement. We simulate 20,000 trials to see which method finds the "best" ad the fastest and makes the most "profit" (reward).

What's in this folder?
marketing_analytics_hw2.ipynb: The file with all the code, graphs, and explanations.

results.csv: A spreadsheet that saves every single ad pull and reward from the test.

README.md: This summary file.

The Two Methods Tested
Epsilon-Greedy: This method mostly picks what it thinks is the best ad, but it occasionally picks a random ad to see if something else works better. As time goes on, it stops guessing and sticks to the best option.

Thompson Sampling: This is a "smarter" math-based approach. It looks at the data it has gathered and calculates the probability of which ad is best. It is usually faster at finding the winner.

What we measured
Learning Curve: Graphs that show how the algorithms "figured out" the true value of each ad.

Total Reward: How much total "value" we got over 20,000 trials.

Regret: How much value we lost by picking the wrong ads while we were still learning.

The results show that Thompson Sampling is better for marketing because it finds the best ad quickly, which saves money and increases total rewards.

How to use it
Make sure you have numpy, pandas, and matplotlib installed on your computer.

Open the .ipynb file in Jupyter Notebook.

Run the code to see the graphs and generate the results.csv file.