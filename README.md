# remove-tag-bbcode
regex
#find [COLOR=#3b4256]
\[/?COLOR=#\d+b\d+]
#find [FONT=微软雅黑, 宋体, Verdana, Geneva, sans-serif]

\[/?F+[a-zA-Z]+=微软雅黑, 宋体, +[a-zA-Z]+, +[a-zA-Z]+, +[a-zA-Z]+-+[a-zA-Z]+]

find " style="border: 0px; outline: none; max-width: 100%; margin: 5px;
" +[a-zA-Z]+="+[a-zA-Z]+: 0px; outline: none; max-width: 100%; margin: 5px;
find URL to url
\[(URL) 
raplayce [\L\1
