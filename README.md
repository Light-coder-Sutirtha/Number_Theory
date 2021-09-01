# Number_Theory
//C++_CP_ code_for_Number_Theory

//  GCD of two numbers
ll int GCD(ll int a,ll int b)
{
     if(b==0)
     {
          return a;
     }
     else
     {
          return GCD(b,a%b);
     }
}
