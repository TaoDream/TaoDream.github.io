# C++ Template

## 容器类

### Pair 类

Q 用一个数据结构表示string和int的整体

A pair<string, int> a("renwang", 100);

Q pair类在哪个头文件中

A algorithm

Q pair有哪些成员

A first, second

### multiset 类

Q 如何引用multiset类

A include<set>

Q 如何声明一个multiset

A multiset<int> a;

Q 如何将3插入到multiset<int> a

A a.insert(3);

Q 如何查找5是否出现在multiset<int> a

A multiset<int>::iterator it = a.find(3); if (it != a.end()) cout << *it << endl;

Q multiset和set的区别

A multiset允许重复元素

## multimap

Q 如何引用multimap

A #include<multimap>

Q 选择一个数据结构，保存用户ID和分数

A score_map.insert(pair<string, int>("renwang", 34);

Q 选择一个数据结构，给定用户ID，输出分数

A multimap<string, int>::iterator it = score_map.find("renwang"); if(it!= score_map.end()) cout << it->first << endl;


