# C++

[TOC] 



### 1.aligned_storage

![image-20230826115327188](../../imgs/C++/image-20230826115327188.png)

### 2.命名空间案例

```C++
namespace Math {
  int add(int a, int b) {
    return a + b;
  }
}

namespace Physics {
  int add(int a, int b) {
    return a * b;
  }
}

int main() {
  int result1 = Math::add(2, 3);
  int result2 = Physics::add(2, 3);
  return 0;
}
```

### 3.模版参数和普通参数选择

![image-20230826120239016](../../imgs/C++/image-20230826120239016.png)

### 4.函数对象工厂

![image-20230826121651169](../../imgs/C++/image-20230826121651169.png)