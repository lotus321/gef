---
name: Bug report
about: Help us improve GEF by filing up this report correctly
title: ''
labels: triage
assignees: ''

---

Your issue will be closed unless you confirm the following (insert `x` in the brackets if done/agreed):
  * [ ] Did you use the latest version of GEF from `master` branch?
  * [ ] Did you read the [documentation](https://gef.readthedocs.org/en/latest/) first?
  * [ ] Did you check [closed issues](https://github.com/hugsy/gef/issues)?


### Step 1: Describe your environment

  * Operating System / Distribution: 
  * Architecture:
  * GDB version (including the Python library version) copy the output of `$ gdb -ex "pi import sys;print(gdb.VERSION);print(sys.version)"`: 


### Step 2: Describe your problem

#### Steps to reproduce

  1.

#### Minimalist test case

Adding a test case goes a long way to help reproduce the issue. This can be done by either attaching a test binary, or providing a test case as a source code, **with** its compilation environment and options.
```c
// compile with gcc -fPIE -pic -o my_issue.out my_issue.c
int main(){ return 0; }
```

#### Observed Results

  * What happened?  This could be a description, log output, etc.


#### Expected results

  * What did you expect to happen?


#### Traces

Feel free to include in this section screenshots or stack traces.

If you enable `gef.debug` (`gef config gef.debug 1`), gef will display a
full stack trace when an exception occurs. It is a good idea to copy/paste it here
(and/or add a screen shot) as it contains useful information that will make it easier
to reproduce. 

**The more info is provided, the more likely your issue will be confirmed and handled**
