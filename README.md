## c++の実行ファイルをruby, python, zshで動かしてみた

### Hello Worldをprint (C++)
### 10回ループ (other language)

* C++の実行ファイルの中身 (Consoletest)
```
#include <stdio.h>

int main(int argc, const char * argv[])
{
    // insert code here...
    printf("Hello, World!\n");
    return 0;
}
```

* python での実行
```
python main.py
```

* ruby での実行
```
ruby main.rb
```

* shell での実行
```
sh main.sh
```
