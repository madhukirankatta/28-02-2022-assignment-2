# 28-02-2022-assignment-2
x=[1,2,1,2,2,2,4,2,5,4,6,5,7,6,4]
l1=[]
l2=[]
for i in x:
        if i not in l1:
            if x.count(i)==1:
                l1.append(i)
print(l1)



output:
======================== RESTART: C:/Python37/list.py ========================
[7]
>>>
