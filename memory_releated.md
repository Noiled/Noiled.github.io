
tools for debug memory issues

focus on Mobile platform

- Android

    Dmalloc  http://dmalloc.com/

    Valgrind http://valgrind.org/
    

- iOS

    xcode diagnostics option  

- All

    Address Sanitizer used for debug memory underflow or overflow bugs, very useful. learn more at [MallocDebug](https://developer.apple.com/library/content/documentation/Performance/Conceptual/ManagingMemory/Articles/MallocDebug.html#//apple_ref/doc/uid/20001884-CJBJFIDD)


    gcc & clang introduce ASan feature, just add -fsanitize=address, very useful options

    this feture rely on google's open source prjoect  [sanitizers] (https://github.com/google/sanitizers)



    












