# aim of the experiment
To find the values in recursive binary search

# brief descrpiton of binary search
• Sequential search algorithm is very slow if list contains more number of
 elements.
• If the array is not sorted ,linear search is the only solution.
• If the list is sorted , we can use a more efficient algorithm called
 the binary search.
• We should use a binary search whenever the list starts to become large.
• The binary search starts by testing the data in the element at the middle of the list.
• This determines if the target is in first half or second half of the list.
• If it is in first half , we do not need to check the second half.
• If it is in second half , we do not need to check the first half.
• In other words ,either way we eliminate half the list from further
 consideration.
• We repeat this process until we find the target or satisfy ourselves
 that it is not in the list.
• To find the middle of the list we three variables,
one to identify the beginning of the list(first)
one to identify the beginning of the list(mid)
one to identify the beginning of the list(last)
mid=( first + last )/2
1 
# step by step procedure  explaining each ouput 
=> first we have to sort the array, after sorting we have array
=> array= [11,7,9,16,21,4,15,98,67,31]
=> for output 1 the keyvalue we need to search is 16
=> for output 2 the keyvalue we need to search is 7
=> for output 3 the keyvalue we need to search is 67
=> by using loops and conditions we can obtain the output
=> first we find the mid value ,ie; mid= low+high/2
=> if keyvalue is less then mid value ,we use mid-1
=> if keyvalue is greater then mid value ,we use mid+1
=> at last in output we enter the element it to be found it gives its index or array value
=>  if the element is not in the list of the array its gives notfound or error
# output obtained

