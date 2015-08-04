# to-learn-ios-
int a[5] = {1,3,2,4,5};
BOOL f = 1 ;
int t =0 ;
    for (int  i = 0;  i <  5 -1 &&f; i++) {
        f = 0;
        for (int j = 0;  j < 5 -1 -i; j++) {
            if (a[j] < a[j+1]) {
                t = a[j];
                a[j] = a[j+1];
                a[j+1] = t;
                f =1;
            }
        }
    }
    
    for(int i = 0; i < 5;i++)
      {
         printf("%d ",a[i]);
      }
