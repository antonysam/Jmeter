Steps to create the test 

1. Starting the Jmeter
2. Create a TestPlan
3. Create a Thread Group(users)
4. Add a sampler(Http) 
5. Add Listeners 
6. To run the test


# Test Plan
It is like a container 

It contins all test element to run a test

# WorkBench
All the temporary test elements will be stored

Note: This will not store your changes

# Thread Group

`Number of Threads (users)` -> count of users

`Ramp-up period (seconds)` -> will add users as per the timeinterval to hit the page

e.g

if number of threads are 10 and Ramp-up Period is 20, means users will be added for every 2 seconds

# Stop
forcefully stop all the execution

# Shut down
It will stop the currently running thread and when all the threads are stops it will stop the test
