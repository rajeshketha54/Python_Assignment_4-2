# Python_Assignment_4-2
def triple(lst):                            #Sample List: [1, 2, 3, 4, 5, 6, 7]         
    result=list(map(lambda n:n*3,lst))      
    print(result)                          #Expected Output: [3, 6, 9, 12, 15, 18, 21]
lst=eval(input())                          
triple(lst)                                #My output: [3, 6, 9, 12, 15, 18, 21]
