# coding-task-factorial
def FirstFactorial(num):       
    fac=1     
    for i in range(1,num + 1):        
        fac = fac*i     
        return fac     
        
print FirstFactorial(raw_input())
