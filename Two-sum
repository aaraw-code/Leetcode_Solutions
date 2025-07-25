# two-sum-leetcode
LeetCode Two Sum solution using Python and HashMap

class solution:
    def twoSum(self,nums: list[int], target: int) -> list[int]:
        num_dict = {}

        for i, num in enumerate(nums):
            complement = target - num

            if complement in num_dict:
                return [num_dict[complement],i]
            
            num_dict[num] = i
        return []



# second Method

class Solution:
    def twoSum(self, nums: list[int], target: int) -> list[int]:
        d = {}
        for i in range(len(nums)):
            need = target - nums[i]
            if need in d:                     # check krta hai hmara target no mila ya nahi
                return [d[need], i]           # agr mil gya to dono ka index return kr dega
            d[nums[i]] = i
        return[]







        
