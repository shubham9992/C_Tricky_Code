# C_Tricky_Code
Addition of two numbers without using + operator


    #include<stdio.h>
    main()
    {
       int n1,n2,n3,result,diff;
       printf("enter the two numbers n1 and n2\n");
       scanf("%d%d",&n1,&n2);

       if(n1 > n2)
        {
            n3 = n1 * 2;
            diff = n1 - n2;
            result = n3 - diff;
            printf("%d\n",result);
        }
      
      if(n2 > n1)
      {
          n3 = n2 * 2;
          diff = n2 - n1;
          result = n3 - diff;
          printf("%d\n",result);
      }
    
      if(n1 == n2)
      {
          result = n1 * 2;
          printf("%d\n",result);

      }
    }
