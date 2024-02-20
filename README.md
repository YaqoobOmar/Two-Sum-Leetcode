// # Two-Sum-Leetcode
// https://leetcode.com/problems/two-sum/
class Solution {
    public static void main(String[] args);

    public int[] twoSumHashing(int[]nums,int target){
//create a hashmap
Map<Integer , Integer>Map = newHashMap<Integer , Integer>();
        for(int i=0;i<nums.length;i++){
            // Get the complement using the target value
            int complement=target-num[i];
            //Search for hashmap for complement , if found we found our pair.

            if(map.containsKey(complement)){
                return new int[]{map.get(complement),i};

                //put the element in hashmap for subsequent searches.
                map.put(num[i],i);
            }
            throw new IllegalArgumentException("No two sum solution");
        }
        
    }
}
