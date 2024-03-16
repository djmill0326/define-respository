the secret `operator==`: converts two boolean expressions into corresponding setters and getters, using inverse boolean logic or something idk
  
operators are self-implementing
  
parsing occurs as a side-effect of evaluation
  
\- `line 0` every source implicitly begins with the line `define define`, otherwise the whole thing blows up.

\- `line 1` the self-defining function `define` takes only one argument, as functions are only supposed to take one argument. anything otherwise is parameter idolatry and stack neglect.

\- `line 2` the `new` function is variadic... behavior is defined by its usage.

\- `line 3` `delete` is uninitialized memory `or`ed with the bitwise inversion of `new`. don't think too hard about that one

\- `line 4` -*snip*-

templates are evaluated with the assistance of Bing AI