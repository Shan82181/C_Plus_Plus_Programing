# Basic Input&Output
- iostream: iostream stands for standard input-output stream. This header file contains definitions of objects like cin, cout, cerr, etc.
- **using namespace std;** is used to access the library files for input and output.
- if we don't want to use this then we need to add **std::** in every line.
## COUT:
- The cout object in C++ is an object of class iostream. It is defined in iostream header file. It is used to display the output to the standard output device i.e. monitor. It is associated with the standard C output stream stdout. The data needed to be displayed on the screen is inserted in the standard output stream (cout) using the insertion operator(<<).
- Program 1:
- // C++ program to illustrate the use
  // of cout object
  #include <iostream>
  using namespace std;
  // Driver Code
  int main()
  {
	// Print standard output
	// on the screen
	cout << "HELLO WORLD";
  return 0;
  }

## CIN:
-  It is used to accept the input from the standard input device i.e. keyboard. It is associated with the standard C input stream stdin. The extraction operator(>>) is used along with the object cin for reading inputs.
-  **PROGRAM:**
-  #include <iostream> 
- using namespace std; 
- int main() 
- { 
- string s;
- INT A,B;
- // Take SINGLE input
- cin >> s;
- // Take MULTIPLE input
- cin >> A >> B;
- return 0;
- }

## cerr:
- it is used to display error.
- it does not store message into memory.
- **PROGRAM**
- #include <iostream>
- using namespace std;
- int main()
- {
- // This will print "Welcome to GfG"
- // in the error window
- cerr << "Welcome to GfG! :: cerr";
- // This will print "Welcome to GfG"
- // in the output window
- cout << "Welcome to GfG! :: cout";
- return 0;
- }
- **OUTPUT:**
- Welcome to GfG! :: cerr
- Welcome to GfG! :: cout 

## MANIPULATORS
- Manipulators are helping functions that can modify the input/output stream. It does not mean that we change the value of a variable, it only modifies the I/O stream using insertion (<<) and extraction (>>) operators.
- To access manipulators, the file **iomanip.h** should be included in the program.
### Types of Manipulators :
- There are various types of manipulators:
- **Manipulators without arguments:**
  - endl
  - ends
  - flush
- **Manipulators with Arguments:**
  - setw (val)
  - setfill (c)
  - setprecision (val)
  - hex 
  - oct 
  - dec
  - many others 

