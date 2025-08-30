# Jackpot-machine
𝐈𝐧 𝐭𝐡𝐢𝐬 𝐩𝐫𝐨𝐣𝐞𝐜𝐭, 𝐈 𝐜𝐫𝐞𝐚𝐭𝐞𝐝 𝐚 𝐉𝐚𝐜𝐤𝐩𝐨𝐭 𝐦𝐚𝐜𝐡𝐢𝐧𝐞 𝐬𝐢𝐦𝐢𝐥𝐚𝐫 𝐭𝐨 𝐭𝐡𝐨𝐬𝐞 𝐟𝐨𝐮𝐧𝐝 𝐢𝐧 𝐚𝐦𝐮𝐬𝐞𝐦𝐞𝐧𝐭 𝐩𝐚𝐫𝐤𝐬 𝐭𝐡𝐚𝐭 𝐫𝐚𝐧𝐝𝐨𝐦𝐥𝐲 𝐬𝐞𝐥𝐞𝐜𝐭𝐬 𝐰𝐢𝐧𝐧𝐞𝐫𝐬. 











import random
def slot_machine():
    x=["apple" , "grapes" , "banana" , "orange"]
    a=random.choice(x)
    b=random.choice(x)
    c=random.choice(x)
    print(a,b,c)
    if a==b==c:
        print("jackpot")
slot_machine()
while True:
    y=input("do you want to continiuo")
    if y.lower()=='yes':
        slot_machine()
    else:
        break
