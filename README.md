# LCM-GCD

int gcd1(int a,int b){ if(b==0)return a;

return gcd1(b,a%b);
}

#lcm

int lcm1(int a ,int b){

return (a/gcd1(a,b))*b;

}
