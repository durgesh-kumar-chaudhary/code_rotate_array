def rotate_array(arr,k): # "python code for rotate an array by any random k positions
    k=k%len(arr)
    return arr[k:]+arr[:k]
arr=[1,2,3,54,12]
k=8
print(rotate_array(arr,k))

    
    
