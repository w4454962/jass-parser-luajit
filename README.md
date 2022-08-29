# jass-parser-luajit
jass parser by luajit



Parsing 300000 lines of 27mb jass syntax tree takes only 2 seconds

`
bin\luajit.exe -jon -O3 src\main.lua

common.j pass

blizzard.j pass

war3map.j pass

2.059


`

