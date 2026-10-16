XProf trace exports from the October 2026 Native CROSS and HEIR Prepared TPU profiling captures.

Files are compressed Chrome Trace Event JSON suitable for Perfetto and the website's interactive trace timeline.

The four files native-alexnet-tiny-32k, native-lenet-8k, native-lenet-16k, and native-lenet-32k are size-optimized public versions with bulky per-event auxiliary properties removed. Their recorded event names, ordering, timestamps, durations, process/thread identifiers, and retained HLO categories have not been changed. This preserves the execution timeline while avoiding overly large GitHub uploads. Other files are the originally staged sanitized exports.

Profiling traces are diagnostic; benchmark medians are reported separately on the Results page.
