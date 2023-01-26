
fastcws中使用到的boost header-only容器。

注意此项目被故意命名成了`boost_containers`，因为其并没有包含`boost::container`的全部内容，而且还包含了一些其他库的内容。

基于`bcp`工具生成：

``` bash
./dist/bin/bcp boost/container/vector.hpp boost/container/map.hpp boost/container/string.hpp boost/container/list.hpp boost/container/set.hpp  boost/container/deque.hpp boost/unordered_map.hpp boost/unordered_set.hpp boost_containers/
```

