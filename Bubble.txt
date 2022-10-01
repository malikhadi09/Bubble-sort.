def bubblesort(arr):
  n=len(arr)
  for i in range(n-1):
    for j in range(n-i-1):
      if arr[j]>arr[j+1]:
        arr[j],arr[j+1]=arr[j+1],arr[j]
arr=[1,3,10,6,7]         
bubblesort(arr)
for i in range(len(arr)):
  print(arr[i]) 