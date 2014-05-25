RPy
======================
### What is RPY?

RPy is a simple, easy-to-use interface to R from Python. It enables one to enjoy the elegance of Python programming while having access to the rich graphical and statistical capabilities of R.

In its simplest form, shown here, one includes in one's Python code a statement
<pre><code>
from rpy2.robjects import r
</code></pre>
- This launches an execution of R, with communication to the original Python program. 
- The Python class instance r includes various functions for remote execution of R commands, including those involved with data produced by the Python program.
- RPy is a very simple, yet robust, Python interface to the R Programming Language.	 
- It can manage all kinds of R objects and can execute arbitrary R functions (including the graphic functions).	
- All errors from the R language are converted to Python exceptions.	 
- Any module installed for the R system can be used from within Python.
- Two flavours are available: **rpy** and **rpy2**.
