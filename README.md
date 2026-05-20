# Peak-Element-in-array
nums = list(map(int,input("Enter numbers: ").split()))
n = len(nums)
r = nums[0]
res = 0
for i in range(1, n):
    if r < nums[i]:
        r = nums[i]
        res = i
print("Peak Element index is:", res)
