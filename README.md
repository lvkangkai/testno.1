# testno.1
test
// #include <stdio.h>
//#include <Eigen/Core>
// int main()
// {
    //int i,j,a[10];
    //printf("please input your ten numbers:\n");
   // for(i=0;i<9;i++)
   // {
    //    scanf("%d ",&a[i]);
   // }
// int i,j,b[3][2];
// int a[2][3]={{1,2,3},{4,5,6}};//赋值
// printf("array a:\n");
// for(i=0;i<=1;i++)
// {
//     for(j=0;j<=2;j++)
//     {
//         printf("%5d",a[i][j]);//循环打印矩阵a
//         b[j][i]=a[i][j];//矩阵值互换
//     }
//     printf("\n");
// }
// printf("array b:\n");
// for(i=0;i<=2;i++)
// {
//     for(j=0;j<=1;j++)
//     {
//         printf("%5d",b[i][j]);//循环打印矩阵b
//     }
//     printf("\n"); 
// }

//    return 0;
// }

// #include <stdio.h>
// int main()
// {
//     char str1[5],str2[5],str3[5];
//     scanf("%s%s%s",str1,str2,str3);
//     printf("-\n--\n---\n\n");
//     printf("%s %s %s",str1,str2,str3);
   

//     return 0;
// }
// #include <stdio.h>
// int main()
// {
//     char str1[11];//
//     gets(str1);
//     printf("%s",str1);//puts gets scanf printf 可以混合使用

//     return 0;
// }
// #include <stdio.h>
// int main()
// {
//     char str1[]="People's Republic of ";
//     char str2[]="China";
//     printf("%s",strcat(str1,str2));
//     return 0;
// }
// #include <stdio.h>
// int main()
// {
//     char c[200];
//     int i,num=0,word=0;
//     char d;
//     gets(c);
//     for(i=0;(d=c[i])!='\0';i++)
//     {
//       if(d==' ')
//       {
//         word=0;
//       }
//       else if(word==0)  //如果不是空格字符且word原值为0
//        {
//           word=1;
//           num++;
//        }
//     }
//     printf("There are %d words in this line.\n",num);
//     return 0;
// }
// #include <stdio.h>
// int main()
// {
//     int a,b,c,d,m;
//     int max4(int aa,int bb,int cc,int dd);//声明函数max4
//     int max2(int aaa,int bbb);//声明函数max2
//     printf("please input four numbers\n");//提示输入
//     scanf("%d %d %d %d",&a,&b,&c,&d);//输入函数
//     m=max4(a,b,c,d);//调用函数1
//     printf("the max number is %d.\n",m);//输出函数
    
//     return 0;
// }
// int max4(int aa,int bb,int cc,int dd)//函数max4编写  形参应该是（int a,int b,int c,int d）
// {
//     int max2(int a1,int a2);//调用函数max2
//     return max2(max2(max2(aa,bb),cc),dd);

// }
// int max2(int aaa,int bbb)//函数max2编写  形参(int a,int b)
// {
//     return(aaa>bbb?aaa:bbb);
// }
// #include <stdio.h>
// int main()
// {
//     int fac(int a);//声明fac函数
//     int n,y;
//     printf("please input a number(n>=0):");//提示输入  printf分号结束后自动换行
//     scanf("%d",&n);//输入计算数字
//     if(n<0)//如果小于0，就不进行递归的计算
//     printf("the data is error!");
//     else 
//     {
//     y=fac(n);
//     printf("%d!=%d",n,y);
//     }
//     return 0;
// }
// int fac(int a)
// {
//     int f;
//     if(a==1||a==0)
//     {f=1;}//1或0的阶乘等于1
//     else
//     {f=fac(a-1)*a;}//递归函数，重复计算   递归的重点
//     return f;//返回f值
// }
#include <stdio.h>
int main()
{
    
    return 0;
}
