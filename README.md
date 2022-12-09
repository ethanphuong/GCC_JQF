Apache Maven and Java 9+ required to run the fuzzer

Clone the repository and move to the test location (src/test/java/examples) in the terminal.

Run command: mvn test-compile and mvn jqf:fuzz -Dclass=examples.CompilerTest -Dmethod=[test_name] -Dtime=[time of fuzzing]

Results will show in the terminal after the fuzzing has terminated.

Fuzz data located in the fuzzlog in target/fuzz-results/examples.CompilerTest/(test_name)/fuzz.log

Additionally, raw data is located in target/fuzz-results/examples.CompilerTest/(test_name)/plot_data
