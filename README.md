```sh
#include <stdio.h>
int main()
{
    int a[1000],i,n,min,max;
    printf("Enter size of the array : ");
    scanf("%d",&n);
    printf("Enter elements in array : ");
    for(i=0; i<n; i++) 
    {
        scanf("%d",&a[i]);
    }
    min=max=a[0];
    for(i=1; i<n; i++)
    {
         if(min>a[i])
          min=a[i];
           if(max<a[i])
            max=a[i];
    }
     printf("minimum of array xis : %d",min);

          printf("\nmaximum of array is : %d",max);

    return 0;

}
```

```sh
#include<stdio.h>  
 int main()    
{    
int n,r,sum=0,temp;    
printf("enter the number=");    
scanf("%d",&n);    
temp=n;    
while(n>0)    
{    
r=n%10;    
sum=sum+(r*r*r);    
n=n/10;    
}    
if(temp==sum)    
printf("armstrong  number ");    
else    
printf("not armstrong number");    
return 0;  
}
```

```sh
#include <stdio.h>
#define n 3
int transpose(int ma[][n], int tr[][n])
{
        int i, j;
        for (i = 0; i < n; i++)
                for (j = 0; j < n; j++)
                        tr[i][j] = ma[j][i];
}
int main()
{
        int ma[n][n] = { { 1, 1, 1 },
                        { 2, 2, 2 },
                        { 3, 3, 3 } };

        int tr[n][n], i, j;
        transpose(ma, tr);

        printf("Result matrix is \n");
        for (i = 0; i < n; i++) {
                for (j = 0; j < n; j++)
                        printf("%d ", tr[i][j]);
                printf("\n");
        }
        return 0;
}
```

##  WELCOME 🤗😊


<p><center> 
📌 𝚅𝙸𝚂𝙸𝚃𝙾𝚁𝚂 𝙲𝙾𝚄𝙽𝚃 📌
 <img src="https://profile-counter.glitch.me/freeCodeCamp/count.svg" />
</p></center>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=shubhamg0sai&show_icons=true&locale=en&layout=compact" alt="shubhamg0sai" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=shubhamg0sai&show_icons=true&locale=en" alt="shubhamg0sai" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=shubhamg0sai&" alt="shubhamg0sai" /></p>
