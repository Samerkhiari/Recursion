# Recursion
Function Palindrome ( ch:string):Boolean
Var
n:integer
rslt: Boolean

Begin

n:= ch.length
if (ch= "") or (n=1) Then
rslt:=True
Else if (ch [0] = ch [n -1]) Then
Palindrome (ch [1:n-2])
Else
rslt:=False
End If
return rslt

End
