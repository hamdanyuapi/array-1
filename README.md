# array-1

    #include <stdio.h.>
    void cetak_mundur (char S[])
    {
    int i,n;
    for (n=0;n<S[n];n++);
    printf("panjag array = %d\n",n);
    for(i=n-1;i>0;i--)
    {
        printf("%c",S[i]);
    }
    }
    int main()
    {
    char str[50] = "anton";
    cetak_mundur (str);
    }
    
    
    
    
    
    
hasil

![img](https://github.com/hamdanyuapi/array-1/blob/master/array.png?raw=true)
