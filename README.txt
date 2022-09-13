Hello World!

Hello World!
This is a test file...
contribution=list(map(int,input("Input:").split()))

odd= 0  
even= 0 

for i in contribution:
    
    if contribution.index(i)%2 == 0:
        even+=i
        
    else:
        odd+=i
        
if even> odd:
    print("Output:",even)
    
else:
    print("Output:",odd) 
