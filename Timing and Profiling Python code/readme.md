# Profiling and Timing Code   <a href="https://colab.research.google.com/github/Ahmad-Zaki/Python-Notes/blob/main/Timing%20and%20Profiling%20Python%20code/timing-and-profiling.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab" title="Open and Execute in Google Colaboratory"></a>

When you Create a function to do some task, there are often different implementations you can use to get the task done. Therefore, it can be useful sometimes to dig into the performance of each implementation to see how it performs or if it can be optimized in any way. Sometimes it's useful to check the execution time of a given command or set of commands; other times it's useful to measure a multiline process and determine where the bottleneck lies in a series of operations. 

IPython provides different commands for timing and profiling your code. We'll go over the following IPython magic commands:

- ``%time``: Time the execution of a single statement.
- ``%timeit``: Time repeated execution of a single statement for more accuracy.
- ``%prun``: Run code with the profiler.
- ``%lprun``: Run code with the line-by-line profiler.
- ``%memit``: Measure the memory use of a single statement.
- ``%mprun``: Run code with the line-by-line memory profiler.

The last three commands are not bundled with IPython–you'll need to get the ``line_profiler`` and ``memory_profiler`` extensions, which we will discuss This notebook.