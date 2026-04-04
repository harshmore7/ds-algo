Problem: Two Sum
Link: LeetCode

Approach:
- Use HashMap
- Store value → index
- Check complement

Time Complexity: O(n)
Space Complexity: O(n)


- to add test cases
```
public static void main(String[] args) {
    int[] nums = {2, 7, 11, 15};
    System.out.println(Arrays.toString(twoSum(nums, 9)));
}
```