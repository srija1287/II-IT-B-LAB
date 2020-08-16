# aim of the experiment
to find the values in iterative_linear_search
# brief description of linear search
• Sequential search is used whenever the list is not ordered.
• Generally we use the technique only for small lists or lists that are
not
 searched often.
• In the sequential search , we start searching for the target from the
 beginning of the list, and we continue until the we find the target or
 until we are sure that it is not in the list.
• This gives us two possibilities:
either we find it or
we reach the end of the list
# step by step procedure
=> we have the array elements[11,7,9,16,21,4,15,98,67,31]
=> for the output 1 key element we need to search is 15 
=> for the output 2 key element we need to search is 99
=> in the iterative process we check if the element and key value are same
=> in iteration 1 a[0] = 11 is not equal to 15 & 99 ,so the case fails
=> in iteration 2 a[2] = 7  is not equal to 15 & 99 ,so the case fails
=> in iteration 3 a[3] = 9  is not equal to 15 & 99 ,so the case fails
=> similaryly iteration continues until the element and key values are same
=> in iteration 7 a[6] = 15 is equal to 15 so case passed
=> in the function the iteration takes place and the element with index is printed to the output
=> if the all iteration cases fails then it returns element not found to the output
# output obtained:
