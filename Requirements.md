# Requirements

0. build and run on Linux, Windows, MacOSX (or at least work very well dockerized) 
1. has to be top-performant. I was looking at: https://www.techempower.com/benchmarks/#section=test&runid=d6f9832a-d586-478c-84a0-8a89cccfcc2a&hw=cl&test=composite&a=2
2. has to work well with postgres and mysql (at least) AND cache to Redis
3. has to run wasm3 or a wasm interpreter with gas metering
4. handle JSON very fast

## Options

* https://drogon.docsforge.com/ with https://github.com/wasm3/wasm3
