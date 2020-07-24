Original article: https://alistapart.com/article/coding-with-clarity/

[Part 1](https://alistapart.com/article/coding-with-clarity)
- The single responsibility principle: code smell: "and" in function name
- Command-query separation: function should be either command or query. When mixing, you get [Missing Missy](http://www.27bslash6.com/missy.html)
- Loose coupling: tight coupling should be refactored into a class. Build lego not jigsaw puzzle pieces. Use option object as opposed to primitive parameters.
- High cohesion: smell: a common folder that has unrelated files; property used by only one method; non-reusable methods. When in conflict, choose cohesion over low-coupling.

[Part 2](https://alistapart.com/article/coding-with-clarity-part-ii)
- Law of Demeter, principle of least knowledge: be abstract. Let other class handle their business. Don't micro-manage.
- Data behavior separation: more difficult in JavaScript than other OOP language
- Interface segregation principle: code smell: a boolean flag to branch at the very beginning.
- The open/closed principle.
