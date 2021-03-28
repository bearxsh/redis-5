### Debug Redis-5.0.11 With CLion On MacOS
1. open project
2. build project
3. check redis-server -> edit configurations -> before lunch -> run external tool -> tool settings -> 
   program: make, arguments: MALLOC=jemalloc CFLAGS="-g -O0"