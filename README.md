Hello!
I am Prathamesh Pawar.I am Learning Programming Languages---
On 12-Feb-2026 I Wrote a program of Checking a number is Armstrong number or not & also in same program checking Armstrong numbers upto enterd sequence.
I did't used any AI.You can checkout my written code!
-----------------
def single(num):
    num_str=str(num)
    num_len=len(num_str)
    total=0
    for i in range(0,num_len):
        total+=int(num_str[i])** num_len
    if total == int(num_str):
        print(f"{num_str} is Armstrong Number")
    else:
        print(f"{num_str} != 1{total} So {num_str} Is Not Armstrong Number")
    print()
def seq(limit):
    for i in range(0,limit+1):
        limit_str=str(i)
        limit_len=len(limit_str)
        sum=0
        for j in range(0,limit_len):
            sum +=int(limit_str[j]) ** limit_len
            if sum == int(limit_str):
                print(sum,end=" ")    
    print()

x="For Single number -->1 & For Sequence--->0"
print(x.center(80,'-'))
num=input(f"\n\n What You Want:")
num=int(num)
if num == int(1):
    value=int(input("Enter Number:"))
    single(value)
elif num == int(0):
    val=int(input("Enter Upto Sequence:"))
    seq(val)
else:
    print("You Entered Wrong Thing!--\n")

-------------------------------
:wq

