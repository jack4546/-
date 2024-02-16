# 主要思想
## 以阶乘为例

```C
int f(int n){
  if(n==1) retrun 1;
  return f(n-1)*n;
}
```
