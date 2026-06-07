class Solution {
  public:
    void sort012(vector<int>& arr) {
        // code here
        int temp, i,j=0,k=0,l=0;
        for(i=0;i<arr.size();i++){
            if(arr[i]==0){
                j++;
            }else if(arr[i]==1){
                k++;
            
            }else if(arr[i]==2){
                l++;
            }
        }
        for(i=0;i<j;i++){
            arr[i]=0;
        }
        
        for(i=j;i<j+k;i++){
            arr[i]=1;
        }
        for(i=j+k;i<j+k+l;i++){
            arr[i]=2;
        }
    }
};
