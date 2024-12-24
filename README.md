# Expo CLI Random Server Crashes

This repository demonstrates a bug where the Expo CLI development server crashes randomly without providing any error messages in the terminal.  The issue is intermittent and highly disruptive to the development process.  The provided codebase attempts to replicate the conditions leading to the crashes but may not always reproduce the error directly due to its seemingly unpredictable nature. 

## Steps to Reproduce

While we haven't been able to pinpoint a definitive cause, the bug appears to be related to the Expo environment. It may involve memory issues, conflicting dependencies or a race condition, though this has not been confirmed. To attempt to reproduce, run `expo start`.  The crash may or may not happen.

## Solution

The provided solution focuses on improving monitoring and logging which assists in detecting the crash more easily.  A full resolution requires further investigation into potential root causes.