* 35.翻转链表
```python
"""
Definition of ListNode

class ListNode(object):

    def __init__(self, val, next=None):
        self.val = val
        self.next = next
"""

class Solution:
    """
    @param head: n
    @return: The new head of reversed linked list.
    """
    def reverse(self, head):
        # write your code here
        result = None
        while head != None:
            temp = head.next
            head.next = result
            result = head
            head = temp
        return result
```
