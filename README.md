# holarectangular
r=6
m=10
for i in range (1,r+1):
    for j in range(1, m+1):
        if i==1 or i==r or j==1 or j==m:
            print("*", end=" ")
        else:
            print(" ", end=" ")
    print()
