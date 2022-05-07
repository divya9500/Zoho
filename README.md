# Palindrome

int n=123;
int rem,ans=0;
while(n!=0){
rem=n%10;
ans=(ans*10)+rem;
n=n/10;
}
System.out.println(ans);
