Members: Mei Man Teng, Terri Tai

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.


Answer: 1. Within a Github action that runs whenever code is pushed.

Explanation: we want to make sure every time code is pushed that it passes the automated tests so that bugs do not pile up as we keep editing/adding code. We want these tests to be embedded in our pipeline (within a Github action) so that there is no buggy code when merging to the main branch. 

2) Would you use an end to end test to check if a function is returning the correct output? No

3) What is the difference between navigation and snapshot mode?

Navigation mode will provide performance stats after the page loads (such as accessibility, best practices, SEO). Snapshot mode will do the same diagnostics but only on the current snapshot/state of the website without fully reloading the website.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

Performance (2/4 on Snapshot mode), resizing the images to a proper size, and the cache restoration.