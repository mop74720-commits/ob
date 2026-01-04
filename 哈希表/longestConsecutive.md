class Solution {
public:
    int longestConsecutive(vector<int>& nums) {
        unordered_set<int> num_set;
        for (const int& num : nums){
            num_set.insert(num);
        }

        int longestStreak = 0;

…                longestStreak = max(longestStreak,currentStreak);
            }
        }
        
        return longestStreak;
    }
};