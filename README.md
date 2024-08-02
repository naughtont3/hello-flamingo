# hello-flamingo
Testing repository for sphynx based documentation.


Brief
-----
Source files for the hello-flamingo documentation

The content is written in ReStructured Text (RST) format and
uses the Sphinx package to format the document.

Building Docs Manually
----------------------

 * Step 0: FIRST TIME ONLY

   shell$ python3 -m venv ve3
   shell$ source ve3/bin/activate
   shell$ pip install -r requirements.txt


 * Step 1: Standard usage for edit and build

   shell$ source ve3/bin/activate
   shell$ make
   shell$ vi myfile.rst
   shell$ make

 *  Step 2: View HTML results (e.g., using ``open`` utility on macOS)

   shell$ open _build/index.html


