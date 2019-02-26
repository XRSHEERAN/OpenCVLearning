### Goal
Learn CPP
### Target
Machine Learning
### Read
All References

#### Chapter One
* Header file
```CPP
namespace myHeader
{
  class example
  {
    public:
    void show();
  }
  //also functions
  void mfunc();
}
```
It's more like a convention to avoid faults and make the code more neat to have a header file.
```CPP
#include "myheader.h";
```

* Don't forget to predefine functions before using, if no headers used
```CPP
void myfunc();
int main(){
}
void myfunc(){
  return;
}
```

#### Chapter Two
Nothing special, just an introductions about data types. wchar for Unicode, char for UTF-8
