class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        mini = prices[0]
        maxi = prices[0]
        old_max =0
        old_min=0
        max_profit=0
        max_l=[]
        for i in prices:
            if i < mini:
                old_max= maxi
                old_min = mini
                mini=i
                maxi=i
            elif i > maxi:
                maxi=i
            max_l.append(maxi-mini)
        max_profit = max(max_l)
        return max_profit
