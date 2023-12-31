# HTTP3 vs HTTP2 Benchmark Aggregator
A Jupyter Notebook that processes [HAR](https://en.wikipedia.org/wiki/HAR_(file_format)) files 
containing network traces generated by the [HTTP testing script](https://github.com/KiweeEu/http3-test).

## Description
Call `show_results(path)` function where the path parameter is the directory location containing HAR files to process.
It can be absolute or relative to the current one.
As a result it prints the summary of network connection times + file download times:
* median 
* mean
* 90th percentile
* 99th percentile
* min & max response times
* visualization using a violin plot.
