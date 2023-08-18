<h1>Structure Of A C++ Program</h1>
<hr />

<h2>Introduction</h2>
<p>
<strong>C++</strong> is a high-performance programming language that was developed by <strong>Bjarne Stroustrup</strong> as an extension to the <strong>C</strong> language. It is a <strong>cross-platform</strong> language that gives programmers a high level of control over system resources and memory. C++ is an <strong>object-oriented</strong> programming language that allows code to be reused, lowering development costs. It is portable and can be used to develop applications that can be adapted to multiple platforms. This programming language is one of the world’s most popular programming languages and can be found in today’s operating systems, Graphical User Interfaces, and Embedded Systems. 
</p>    

<hr />
<h2> Hello World!</h2>
<p>The best way to learn a programming language is by writing programs. Typically, the first program beginners write is a program called 'Hello World' , which simply prints <strong><code>Hello World</code></strong> to your computer screen. Although it is very simple, it contains all the fundamental components C++ programs have:</p>

```C++
#include <iostream>  // (1)

using namespace std; 

int main() // (2)
{
  cout << "Hello World" << endl; // (3)

  return  0; // (4)

}
```
<ul>
  <li>
    <h3>The <a href="https://en.cppreference.com/w/cpp/header/iostream">Iostream</a> Library <code>(1)</code></h3>
    <p><strong>C++</strong> doesn't define any statement that supports <strong>IO</strong> (Input/Output). Instead the language includes an extensive <strong>standard library</strong> , the <strong>iostream</strong> library , that provides IO and other facilities.</p>
  </li>
  <li>
   <h3>The <a href="https://en.cppreference.com/w/cpp/language/main_function">Main</a> Function <code>(2)</code> </h3>
   <p>The <strong><code>main()</code></strong> Function is a special function in all C++ programs. It's the function called when the program is executed. The execution of all C++ programs begins with this                function, regardless of where it's actually located within the code.<br />
      <br />The open brace <strong><code>{</code></strong> indicates the beginning of the main's function definition, and the closing brace <strong><code>}</code></strong>  indicates its end. Everything between          these braces is the <strong>function's body</strong> that defines what happens when main() is called
   </p>
  </li>
 <li>
    <h3>The <a href="https://en.cppreference.com/w/cpp/io/cout">Standard Output</a> <code><strong>(3)</strong></code></h3>
    <p>
      This is the line that actually produces the output. It prints the string literal <code><strong>Hello World!</strong></code> followed by a newline;<br />
      In C++ a <strong>string literal</strong> is a sequence of characters enclosed in double quotations marks <code><strong>" "</strong></code>
    </p>
  </li>
  <li>
    <h3>The <a href="https://en.cppreference.com/w/cpp/language/return">Return</a> Statement <code>(4)</code></h3>
    <p>
      <code><strong>return</strong></code> is a statement that terminates a function and sends a value back to the function caller . <br />
      In the main function it's a <strong>status indicator</strong> , if return  sends 0 it indicates success .
      A nonzero return indicates that an error occured
    </p>
  </li>
  
</ul>
<br />

<hr />
<footer>
  <p>
    © Durim Delilaj. All rights reserved @2023<br />
    Contributions are accepted!
  </p>
</footer>


