# uri-1174.py
A = []
c = 0
for i in range(100):
    x = input()
    A.append(x)

for i in range(100):
    if float(A[i]) <= 10:
        print("A[%d] = %.1f" % (i, float(A[i])))
    else:
        continue
#-------------------------------------------------
#-------------------------------------------------
"""A = []
i = 0
for j in range(100):
    x = input()
    A.append(x)
for c in A:
    if float(c) <= 10:
        print("A[%d] = %.1f" % (i, float(c)))
        i += 1
    else:
        i += 1"""
#-------------------------------------------------
#-------------------------------------------------
"""y = 0
l = []
aux = 0

while y<100:
  x = input()
  l.append(x)
  
  y+=1

for n in l:
  if float(n)<=10:
    print("A[%d] = %.1f" %(aux, float(n)))
    aux+=1
  else:
    aux+=1"""   
