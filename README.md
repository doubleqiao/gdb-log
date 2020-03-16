# gdb-log
## The process of debugging:
- 1.Compile the code using the debug mode(to attach debugging symbols) with the command:
```
catkin_make -DCMAKE_BUILD_TYPE=DEBUG
```
- 2.Go to the place where the executable is located (devel/lib/package_name), and type the command:
```
gdb name_of_excutable
```
- 3.Use "r" to run the code and the error messages are printed on the screen.
- 4.Use the debug commands from gdb to track the bug.

## Reference websites:
- condor.depaul.edu/glancast/373class/docs/gdb.html
- https://stackoverflow.com/questions/25085465/using-gdb-with-eigen-c-library
