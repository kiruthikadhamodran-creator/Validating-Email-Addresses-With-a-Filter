Algorithm
Read the number of email addresses.
For each email address:
Check whether it matches the required format.
Verify that the username, website name, and extension satisfy the given rules.
Keep only the valid email addresses.
Sort the valid email addresses in lexicographical order.
Print the resulting list.
Example

Input

3
lara@hackerrank.com
brian-23@hackerrank.com
britts_54@hackerrank.com

Output

['brian-23@hackerrank.com', 'britts_54@hackerrank.com', 'lara@hackerrank.com']
Explanation
lara@hackerrank.com → Valid
brian-23@hackerrank.com → Valid (- allowed in username)
britts_54@hackerrank.com → Valid (_ allowed in username)

After filtering, the valid emails are sorted alphabetically and printed.

Time Complexity
O(N × M) for validating emails, where:
N = number of email addresses
M = average length of an email address
Sorting requires O(N log N).
Space Complexity
O(N) for storing the valid email addresses.
