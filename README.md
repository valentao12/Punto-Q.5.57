# Punto-Q.5.57
Further Analysis
Q.5.57 Load and run the program of Example 5.10.
format compact

>> M = eye(11);

>> N = fliplr(M);

>> addMN = M+N

 addMN =

1 0 0 0 0 0 0 0 0 0 1

0 1 0 0 0 0 0 0 0 1 0

0 0 1 0 0 0 0 0 1 0 0

0 0 0 1 0 0 0 1 0 0 0

0 0 0 0 1 0 1 0 0 0 0

0 0 0 0 0 2 0 0 0 0 0

0 0 0 0 1 0 1 0 0 0 0

 0 0 0 1 0 0 0 1 0 0 0

 0 0 1 0 0 0 0 0 1 0 0

 0 1 0 0 0 0 0 0 0 1 0

 1 0 0 0 0 0 0 0 0 0 1

>> mesh(addMN)

>> AX = [0 12 1 12 0 2]

 AX =

 0 12 1 12 0 2

>> axis(AX)

>> xlabel(‘X’), ylabel(‘Y’), zlabel(‘Z’)
