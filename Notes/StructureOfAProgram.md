<h1>Structure Of A C++ Program</h1>
<hr />

<h2>Introduction</h2>
<p>
  <strong><code>C++</code></strong> was developed by <strong>Bjarne Stroustrup</strong> at Bell Labs as an extension to <strong>C</strong>, starting in 1979. The language adds many new features to the C language, and is perhaps best thought of as a superset of C<br />
  <br /><strong>C++</strong>’s claim to fame results primarily from the fact that it is an <strong>Object-Oriented Language</strong>.
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
   <h3>The <a href="https://en.cppreference.com/w/cpp/language/main_function">Main()</a> Function <code>(2)</code> </h3>
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
  
</ul>



