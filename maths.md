<div class="white-bg">
<h2>Compilers Are Awesome At...</h2>
<h2 class="fragment">Maths!</h2>
</div>


```cpp
int test(int x, int y)
{
  return x - y;
}
```


```cpp
int mulBy65599(int a)
{
  return (a << 16) + (a << 6) - a;
  //       ^          ^
  //     a * 65536    |
  //                a * 64
  // 65536a + 64a - 1a = 65599a
}
```


<div class="white-bg">
<ul>
<li>Division</li>
<li>Modulus</li>
<li>Sums</li>
</ul>
</div>
