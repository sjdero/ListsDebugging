# ListsDebugging
def newTestAvg(newTests):
    newSum = sum(newTests)
    newAvg = newSum / 5  
    return newAvg


def main(): 
    tests = [0,0,0,0,0,0,0,0,0,0]
    
    # loading list with test scores
    for index in range(0, len[tests]):  
        newTests = input("Enter a test score:  ") 
        tests[index] = newTests

    # calling function newTestAvg
    getNewTestAvg = newTestAvg(tests)    
    # printing out results to user
    print("Your average test score is", getNewTestAvg)

    
main()
