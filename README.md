Source code adapted from: https://preshing.com/20120515/memory-reordering-caught-in-the-act/

* Compile using `make`. You can also compile after defining `USE_CPU_FENCE` or `USE_SINGLE_HW_THREAD` in `ordering.c`. This will prevent run-time reordering. 
* Run using `./ordering`. This will display the reordering count. You can only exit by killing the process.
