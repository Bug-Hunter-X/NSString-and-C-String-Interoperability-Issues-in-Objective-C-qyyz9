# Objective-C NSString and C String Conversion Errors

This repository demonstrates a common error in Objective-C related to converting between `NSString` objects and C-style strings (`char*`).  Specifically, it highlights the problems of memory leaks and improper null termination when converting back from `NSString` to `char*`.

The `bug.m` file contains code illustrating the problematic conversion, while `bugSolution.m` presents a corrected version that addresses these issues.  This example is crucial to understanding proper memory management and safe string handling in Objective-C.