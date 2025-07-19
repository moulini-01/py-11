# py-11
diamond shape printing
n=5
for i in range(n):
    for j in range(n-i-1):
	 	  print("  ", end="")
    for k in range(i+1):
  	 	  print("*",end=" ")
    for l in range(i):
  	      print("*",end=" ")
    print( " ")
k=5
for m in range(k):
    for n in range(m+1):
	 	  print("  ", end="")
    for o in range(k-m-1):
  	 	  print("*",end=" ")
    for p in range(k-m-2):
  	      print("*",end=" ")
    print(" ")
