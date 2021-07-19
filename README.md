# Tracefiles-Parsers
## Utilities to parse tracefiles
These notebooks are not meant to complement tkprof and trcsess.
Both oracle binaries provide full and detailed analysis of a session or multiple sessions.
These notebooks are just meant to viusalise and speed up the analysis process.
### sessions_timeline.ipynb
Once a whole bunch of tracefiles have been collected, thses script will parse them, producing a scatter diagram and a dataset detailing how long they took.
This is done using the min and max value of 'tim' in the traces.

### single_session.ipynb
Analyses in detail the waits in a trc file and visualises them.
