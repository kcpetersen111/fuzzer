This is an example of how to use the fuzzer built into the go testing package.  To run the fuzzing test run "go test -fuzz=*" any string should take the spot of the *.  Let the fuzzer run to show that it works, but the fuzzer only stops running when an error is encountered and this code should not have an error.  To stop it after starting it use ctrl+c.