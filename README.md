# Bubble-sort


       int arr[]={2,4,5,7,8,1};
       for(int i=0; i<arr.length-1; i++)
       {
         for(int j=0; j<arr.length-i-1; j++)
         {
           if(arr[j]>arr[j+1])
           {
            int temp=arr[j+1];
             arr[j+1]=arr[j];
             arr[j]=temp;
           }
         }
       }
       
       for(int i=0; i<arr.length; i++)
       {
         System.out.print(arr[i]+" ");
       }
