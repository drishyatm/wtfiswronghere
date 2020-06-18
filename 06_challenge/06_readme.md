Error message shows as "Attribute error " and module ojject has no attribute num . 
checked the conf file for the attributes and found that there are 2 attributes 
num1 = 3 num2 = 5 , howeever the code shows , line 21 , as num only not num2 . Hence fixed the code .
  num1 = conf.num1
  num2 = conf.num2