1 继承 inherit 又被称为 子类化 subclassing

java与c++的一些区别：
最大的不同就是java没有显式的使用指针，栗子：
Java中：
int intVar; // 创建了一个变量，这个变量中保存实际的值
BankAccount bc1; // 创建了一个对象引用，这个对象中保存的是引用
C++中：
BankAccount bc1; // 创建了一个对象，流程对象的数据空间
另外赋值语句：
bc2 = bc1; // c++中所有数据都拷贝到bc2中，java中只把bc1存的地址拷贝到了bc2中
另外在释放空间上：
c++使用delete，java是自动释放的。
在操作符重载上：
c++可以重新定义+,*,=等，java不能