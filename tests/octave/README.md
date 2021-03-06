# Unit tests for Sneedacity effects

These unit tests check the correctness of Sneedacity's effect calculations
against GNU octave. Therefore some simple deterministic and random
sample data is generated and passed to Sneedacity via mod-script-pipe.

To run a test, run: (replace `<desired_test.m>` with the correct filename)
```
./run_test.m <desired_test.m>
```

The tests will print the results to the terminal and will return 0 on
success and non-zero on error.

To run those tests you need a Linux system with GNU Octave,
octave-forge-signal and Sneedacity mod-script-pipe installed.
