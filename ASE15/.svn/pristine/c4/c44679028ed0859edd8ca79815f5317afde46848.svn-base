#define hello1 (a)
#define id(a) a
id(1)
id hello1

#ifdef x
#endif
# ifdef y
# endif
a #ifdef x
b #endif
  //# hello world!

#define a(x, y) x ## y
a(100, 200 300)
a(,hello)
a(,)

#define inc(x) x+1
#define add hello inc
add ()
add ## dec

add2#####################
#define add2 a ## d ## d
add2 (x)
add2 ## c
#define left (
#define right )
add left x right

add3########################
#define add3(x, y, z) x ## y ## z
add3(a, d, d)

#define new a ## add2(x)
#define str(x, y) (x##y)
str(1, 2)


include#####################
id
#include"a.h"
(100)


### open close parenthesis macros
#define open (
#define close )
#define testopen(x) str x 1, 100) 
testopen (open)
str open 1, 100)


######## test directive within directives
#define xx #define yy zz
xx
yy


####### arguments under ## and # are not expanded!
#define xxxx cc
str( xxxx , b)
str(add2, b)
#define concat2(xxx) xxx ## 22, xxx
concat2( new )

####### when a macro will be expanded twice?
#undef xxxx
#undef id
#define xxxx id
#define id(x) x

xxxx(xxxx)
id(id)(xx)


###### macro expansion test
#define plus(x) x + x
#define p (x)
plus p
id (plus p)


#### mix macro and directives
plus 
#ifdef plus
(x)
#endif
#undef x
plus (
#ifdef plus
#define x 100
#ifdef x
x
#else
200
#endif
#endif
)
#undef x
#define x #pragma once
x
     
