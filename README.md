# luckys411-codebat_list_2_sum67-





def sum67(nums):
  flag = False
  x = 0
  result = 0

  while x < len(nums):
    if nums[x] == 6:
      flag = True

    if flag == False:
      result += nums[x]
      x+=1
      continue

    if nums[x] == 7:
      flag = False

    x+=1

  return result
