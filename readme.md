Gaffa View Compiler
==========

Gaffa View Compiler is a file watcher and view parser for JavaScript Gaffa views.

When you save changes to a file being watched Gaffa View Compiler automagicly runs the view definition code, serialises the resulting object and saves it as [viewName].json.

Installation
------------

	npm install -g gaffaviewcompiler
	
	
Usage
---------

   Usage gvc [options]

Options:

    -h, --help               output usage information
  
    -V, --version            output the version number
  
    -v, --verbose            Verbose output
  
    -w, --watch [path]       Watch Path [default ./]
  
    -o, --output [path]      Output Path [default ./]
  
	-T, --throttle [milliseconds]  Minimum time between processing (milliseconds) [default 300]
  
  
Warranty
---------

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
