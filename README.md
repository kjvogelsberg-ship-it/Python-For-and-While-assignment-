# Python-For-and-While-assignment- AI usage 
Promt:
answer = "yes" 
while answer == "yes": 
 
for i in range(10,0,-1): 
        print(i) 
 
print("Happy New Year!") 
 
print ("next loop") 
 
for num in range(1,101, 2): 
    print(num) 
 
print ("next loop") 
 
num = 2 
while num <= 100: 
    print(num) 
    num = num + 2 
 
answer = input("Do you want to see the loops again? yes/no:") 
the loop just keeps repeating it does not stop and ask if i want it to loop again 

AIs answer:
The problem is indentation. Right now, only your countdown is inside the while answer == "yes": loop, so it repeats forever and never reaches the question.

You need to indent all the code, including the question, underneath the first while:

Prompt 2: i still just running without stopping also it not showing happy new year or next loop
That tells me your first for loop is probably still indented incorrectly in the code you're running. It should only count 10 down to 1 once, then immediately show Happy New Year! 
Delete that section and copy/paste this exact code:
answer = "yes"

while answer == "yes":
    for i in range(10, 0, -1):
        print(i)
        print("Happy New Year!")
    print("next loop")

   for num in range(1, 101, 2):
        print(num)

  print("next loop")

  num = 2
    while num <= 100:
        print(num)
        num = num + 2
        answer = input("Do you want to see the loops again? yes/no: ")
