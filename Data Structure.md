###链表                                                      
1.1 
//定义：
struct List
{
  T _Value; 
  List * _Next;
 }
 
 //遍历
 void show(List * head)
 {
    while(head!=nullptr)   //nullptr是为了避免重载二义性和隐式类型指针转换。
    {
      cout<<head->_Value<<" ";
      head=head->_Next;
    }
