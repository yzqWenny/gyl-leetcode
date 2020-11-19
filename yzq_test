class Solution {
public:
    int findRepeatNumber(vector<int>& nums) {
        int *array=NULL;
        int size=100000;
        array=(int *)malloc(size*sizeof(int));
        for(int i=0;i<size;i++){
             array[i]=0;
        }
     for(int i=0;i<nums.size();i++){
           array[nums[i]]+=1;
           if(array[nums[i]]==2)
               return nums[i];        
         }
         return 0;
     }
};
