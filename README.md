# generate-a-python-list-of-all-th-even-number-between-4to30-using-function.
def even(num1,num2):
    if num1>num2:
        return
    print(num1,end=" ")
    return even(num1+2,num2)
num1=4;num2=30
even(num1,num2)
