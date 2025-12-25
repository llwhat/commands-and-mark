# commands-and-mark

# 系统架构
uname -a

# 内核版本
uname -r

# 发行版本
lsb_release -a

# 检查端口冲突
sudo lsof -i :5902


# 为什么C++构造函数不能virtual？
来个一锤定音的回答： virtual函数会通过虚函数表指针调用，而虚函数表是在对象实例化之后存在的，对象实例化必然经过构造函数，所以如果构造函数virtual化 会自相矛盾。
这种提问太做作

