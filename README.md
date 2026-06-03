second=int(input("inter the number of second ")) 
hours=second//3600
minutes=(second%3600)//60
extra_second=second%60
print(f" you have {hours} hours,{minutes}minutes,and{extra_second}seconds")
