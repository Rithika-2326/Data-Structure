int searchInsert(int *nums,int numsize,int target)
{
    //Binary Search 
    int l=0;
    int h=numsize-1;
    while(l<=h)
    {
        int mid=(l+h)/2;
        if(nums[mid]<target)
        {
         l=mid+1;
        }
         else if(nums[mid]>target)
         {
         h=mid-1;
         }
         else
         {
          return mid;
         }
    }
    return l;
}

