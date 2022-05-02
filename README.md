bugRecreate
### Describe the bug
The message says "Error	CS0101	The namespace 'WebApplication1.Pages' already contains a definition for 'MyClass'", while in fact, i have class MyClass stored in Pages/MyClass. Apparently for asp.net project it is not allowed. Classes in Pages folder, has to be named alike folder name.

### To Reproduce
I have stored minimal reproduceable project at .
Now it is broken and on build attempt will show CS0101 error.
To get it working, just rename class MyClass into MyClassSafe, in MyClass.cshtml.cs and in MyClass.cshtml

### Expected behavior
Error will say something like "naming convention violation, please consult link.ms.com"
