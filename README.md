# InterviewQuestions

## Best Time to Buy and Sell Stock

Question
You are given an array of integers where the items correspond to stock prices and the indexes of the array correspond to sequential days. Write a function getMaxProfit that calculates the maximum amount you can earn by buying once and selling once. The worst you can do is a profit of $0 (you buy/sell even or don’t buy/sell at all).

You can only sell a stock on a day after you bought it.

You can’t sell before you buy
You can’t sell on the same day that you buy
Sample Input and Output
Example 1:

Input: [9,2,4,3,8,5]
Output: 6
Explanation: Buy on day 1 (price = 2) and sell on day 4 (price = 8), profit = 8-2 = 6.
Example 2:

Input: [9,8,7,6,5]
Output: 0
Explanation: Since all pricing are decreasing, we would never buy, so max profit = 0.
