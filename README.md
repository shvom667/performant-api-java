# performant-api-java


## Simple Hello World!

Command: wrk -t1 -c100 -d30s http://localhost:8000/

Running 30s test @ http://localhost:8000/

  1 threads and 100 connections

  Thread Stats   Avg      Stdev     Max   +/- Stdev

    Latency     1.29ms    3.34ms 190.36ms   99.75%
    Req/Sec    84.67k     8.69k   91.83k    97.00%

  2526444 requests in 30.00s, 214.44MB read

Requests/sec:  84205.92

Transfer/sec:      7.15MB


## Counter: 2527010


Command:  wrk -t1 -c100 -d30s http://localhost:8080/

Running 30s test @ http://localhost:8080/

  1 threads and 100 connections

  Thread Stats   Avg      Stdev     Max   +/- Stdev

    Latency     1.35ms    4.03ms 193.55ms   99.68%
    Req/Sec    84.70k     7.72k   89.31k    96.67%

  2526909 requests in 30.00s, 220.65MB read

Requests/sec:  84223.22

Transfer/sec:      7.35MB


