# Comparing the Performance of RPT and DCPT Prefetching Algorithms
[GitHub pages](https://mariugul.github.io/RPT-DCPT-Prefetcher/). This has been the project of spring 2020 in the course **TDT4260 - Computer Architecture** at the Norwegian University of Science and Technology, Trondheim. The project was to simulate processor prefetchers in a hardware simulator, M5, and see how well the different prefetchers can improve the performance of the processor. The abstract to the report can be read in the next section and the full report can be opened in GitHub from [here](https://github.com/mariugul/DCPT-Prefetcher/blob/master/Report.pdf).



### Abstract
In modern day computing, the memory gap is one of
the largest problems we face. As processor performance increases
almost exponentially every year, memory access times do not. By
implementing a prefetcher, we can decrease the impact of the
memory gap and increase overall processor throughput. 

In this paper, we’ve explored how the implementation of a Reference Prediction Table (RPT) and Delta-Correlating Prediction
Table (DCPT) compare when it comes to processor performance.
The results showed that we were able to increase performance on
average by 2% for the RPT prefetcher and 10% for the DCPT
prefetcher. We were able to reduce misses by 18.7% and 68.1%,
respectively.
