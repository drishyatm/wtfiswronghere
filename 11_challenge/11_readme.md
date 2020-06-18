There were no error message , but fizzbuzz was not shown any where in the output. 
The fizzbuzz was not shown in the output as it was the last elseif statement and was not executed,hence corrected the  code. 
for i in range(1,max_num):
        # % or modulo division gives you the remainder 
        if i%3==0 and i%5==0:
            print(i,"fizzbuzz")
        elif i%3==0:
            print(i,"fizz")
        elif i%5==0:
            print(i,"Buzz") 

and it worked . 