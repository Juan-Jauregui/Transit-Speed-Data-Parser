# Transit-Speed-Data-Parser
A simple console script to analyze the output from the Speed-Data Android app by suryaharshan1 and calculate vehicle speeds

The base application, which can be found at https://github.com/suryaharshan1/Speed-Data, is a simple stopwatch that records start and end time for many vehicles, presumably over a pre-determined distance, and outputs a formatted text file with each recorded vehicle's type, start time, and end time. 

The purpose of this script is to parse the text files that this application outputs, calculate each vehicle's speed using a specific distance determined when originally collecting the data, and output these values to another text file. 

This was a small part of a larger project to collect transit data on the University of Florida campus for research purposes. It was written in java in hopes that it might be run on a terminal emulator on the same phone used to run the original app, though it turned out to be more convenient to just run it on a laptop and just import the .txt file into Google Sheets straight away.
