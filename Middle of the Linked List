class Solution {
    public static int size(ListNode head){
        int cnt=0;
        while(head!=null){
            head = head.next;
            cnt++;
        }
        return cnt;
    }
    public ListNode middleNode(ListNode head) {

        ListNode temp = head;
    
        int size = size(head);

        for(int i=0; i<size/2; i++){
            temp=temp.next;
        }

        return temp;

        
        
    }
}
