def binarysearch(a,n,key):
    if(n==1):
        if(a[0]==key):
            return 1
        else:
            return "not found"
    low=0
    high=n-1
    mid=(low+high)//2
    while(low<=high):
        if(key==a[mid]):
            return mid
        elif(key>a[mid]):
            low=mid+1
            mid=(low+high)//2
        elif(key<a[mid]):
            high=mid-1
            mid=(low+high)//2
    return "not found"
a=[1,2,4,5,6]
print(binarysearch(a,6,0))
