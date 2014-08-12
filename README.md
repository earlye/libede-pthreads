This library contains wrappers around pthreads.

There's not much here, and probably never will be, since C++11x now
has a <thread> library.

In point of fact, ```thread_local_singleton``` will likely go away in
favor of a c++11 ```thread_local_singleton``` using the new
```thread_local``` keyword.