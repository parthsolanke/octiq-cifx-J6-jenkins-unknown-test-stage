# CI detection fixture

A stage literally named 'Test' running a script the detector cannot read. Must be 'unknown', never 'CI has no test step'. Regression for 23e37f2.

Expected verdict line in the Octiq chat:

    Tests not run - stage `Test` runs `./run-ci.sh`
