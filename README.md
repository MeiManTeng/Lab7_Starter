1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.


1. Within a Github action that runs whenever code is pushed.

Explanation: we want to make sure every time code is pushed that it passes the automated tests so that bugs do not pile up as we keep editing/adding code. We want these tests to be embedded in our pipeline (within a Github action) so that there is no buggy code when merging to the main branch. 

2) Would you use an end to end test to check if a function is returning the correct output? No

