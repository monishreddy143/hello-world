# hello-world
#list revers

arr =[2,3,4,6,7]
i,j=0,len(arr)-1

while i<j:
  arr[i],arr[j]=arr[j],arr[i]
  i+=1
  j+=1
 print(arr)
