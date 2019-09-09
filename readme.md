# Programming With C Language

Sun Sep 8, 2019 [https://youtu.be/eKOKGKuGaEc]

Git repo directory: `introduction`

- Introduction & Installation
- Mingw(Windows gcc) Link to download
  [https://sourceforge.net/projects/mingw-w64/]
  - After installing in Windows set `Path` environment variable to access `gcc` command from command prompt i.e., `cmd`
  - First Copy the path of mingw upto bin directory ex (not this). `C:\.....\bin`
  - Go to 'System Property' (by searching in Start)
  - Click on 'Environment Variables'
  - In 'Environment Variables', Select 'Path' in 'System Variables' then click to edit
  - In `Edit Environment Variable` click on `New`
  - Paste copied path & press 'Ok'
  - Now open/re-open cmd prompt
  - Go to your program's directory & type `gcc yourprogram.c`
  - Congratulations!

* Compiler vs Interpreter
* Demo Program
* Tokens

# Programming With C Language

Mon Sep 9, 2019 [https://youtu.be/VxQq1SpNewY]

Git repo directory: `introduction`

- tokens
- compilation processes
  - preprocessing
    - `gcc -E demo.c -o demo.i`
  - compilation
    - `gcc -S demo.i -o demo.s`
  - Assembly code generation
    - `gcc -c demo.s -o demo.o`
  - Linking
    - `gcc demo.o -o demo.out` [Linux]
    - `gcc demo.o -o demo.exe` [Windows]
- To execute/run
  - `demo.exe` [Windows]
  - `./demo.out` [Linux]
