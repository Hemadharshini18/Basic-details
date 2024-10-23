# Basic-details
#include <stdio.h>

int main()
{
    long int phno;
    int dd,mm,yy,regno;
    float cgpa,hsc,sslc;
    char  name[15],dep[17],college[25],mailid[20];
    printf("Enter your Reg no:");
    scanf("%d",&regno);
    printf("Enter your DOB:");
    scanf("%d/%d/%d",&dd,&mm,&yy);
    printf("Enter your phno:");
    scanf("%ld",&phno);
    printf("Enter your cgpa:");
    scanf("%f",&cgpa);
    printf("Enter your hsc mark:");
    scanf("%f",&hsc);
    printf("Enter your sslc mark:");
    scanf("%f",&sslc);
    printf("Enter your Name:");
    scanf("%s",name);
    printf("Enter your dep:");
    scanf("%s",dep);
    printf("Enter your college:");
    scanf("%s",college);
    printf("Enter your mailid:");
    scanf("%s",mailid);
    printf("Name:%s\n",name);
    printf("Department:%s\n",dep);
    printf("College Name:%s\n",college);
    printf("Mail ID:%s\n",mailid);
    printf("Register No:%d\n",regno); 
    printf("DOB:%d/%d/%d\n",dd,mm,yy);
    printf("Phone no:%ld\n",phno);
    printf("CGPA:%f\n",cgpa);
    printf("HSC:%f\n",hsc);
    printf("SSLC:%f\n",sslc);
        

    return 0;
}

