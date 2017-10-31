# eq-taurus-performance-tests
Contains performance tests for eq-survey-runner

## Setup
Only dependency is BZT (blazemeter) run `pip install bzt` from terminal

## Run
To run the command is `bzt <script>`, and thats it!
Taurus takes care of rest.  
To run with different execution, i.e. change the number of concurrent users or
the number of iterations by each user run `bzt <script> -o execution.<index>.<option>=<requirement>`
