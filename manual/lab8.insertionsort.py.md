Problem statement

write a python program to imlement insertion sort.

Sample Input1: [1,10]
Sample Output1: [2,3,7,8]

Sample Input2: [-10,-1]
Sample Output2: [-9,-8,-5]

Sample Input3: [1.0,10.0]
Sample Output3: [2.5,5.5,9.5]

Solution Key

def insertion_sort(seq):
    #print (seq)
    i=1
    while i < len(seq):
        j=i
        while j!=0 and seq[j]< seq[j-1]:
                seq[j] , seq[j-1] = seq[j-1], seq[j]
                j -=1
        i +=1
    print(seq)
    return seq
# CloudCoder Exercise 

## Pre-Lab Questions 


## Post-Lab Questions 

## Bonus 
## Interview Grade 

## Related Links

### CDlINK : http://http://10.100.8.8/kata/edit/B6E7A51B36?avatar=kangaroo
