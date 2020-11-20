s1=(input())
s2=(input())
def m1(s1,s2,n,k):
    l=[[0]*(k+1) for i in range(n+1)]
    for i in range(n+1):
       for j in range(k+1):
           if i==0 or j==0:
               l[i][j]=0
           elif s1[i-1]==s2[j-1]:
               l[i][j]=1+l[i-1][j-1]
           else:
               l[i][j]=max(l[i][j-1],l[i-1][j])
    return l[n][k]
print(m1(s1,s2,n,k))


'''
INPUT:
ABCDGH
AEDFHR
OUTPUT:
3
'''
