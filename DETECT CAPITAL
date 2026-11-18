class Solution {
    public boolean detectCapitalUse(String word) {
        int upperCount = 0;
        int n = word.length();
        
        for (int i = 0; i < n; i++) {
            if (Character.isUpperCase(word.charAt(i))) {
                upperCount++;
            }
        }
        
        // Case 1: All uppercase
        if (upperCount == n) return true;
        
        // Case 2: All lowercase
        if (upperCount == 0) return true;
        
        // Case 3: Only the first letter is uppercase
        if (upperCount == 1 && Character.isUpperCase(word.charAt(0))) return true;
        
        return false;
    }
}
