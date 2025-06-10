# Palindrome_Linked_List\


🚀 Problem Title
Clear, concise, and searchable (e.g., "Reverse Linked List in Groups of K")

📌 Problem Statement
*1-2 sentences describing the task:*
"Given the head of a singly-linked list, reverse the nodes in groups of size K (if the remaining nodes are < K, leave them unchanged). Return the modified list."

🔍 Examples

plaintext
Input: 1 → 2 → 3 → 4 → 5, K = 2  
Output: 2 → 1 → 4 → 3 → 5  
🎯 Approach
Short bullet points:

Use iterative reversal in chunks of K nodes.
Track prev, curr, next pointers for in-place reversal.
Time: O(N), Space: O(1).

⚠️ Constraints
0 <= Node.val <= 1000
1 <= K <= N

📝 Notes
Mention edge cases (empty list, K=1, K=N).*
Optional: Include visual diagrams.
