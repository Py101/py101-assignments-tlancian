from functools import reduce

function_lambda= lambda x,y: x*y

def factorial4thebeer (num):
    listnum = range(1,num+1)
    result = reduce(function_lambda,listnum)
    return result

# Given a number (num), i take a list with the number from 1 to that number , and then with the reduce function i multiply everytime the first two, and then given the result of the first multiplication it continues with the third number and so on.     