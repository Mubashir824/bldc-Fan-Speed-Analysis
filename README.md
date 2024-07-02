# bldc-Fan-Speed-Analysis
We have a dataset where new rows are generated with each data change. To ensure consecutive minute intervals, I will calculate the mean for multiple readings within the same minute. For missing minutes, I will insert rows using the values from the preceding minute. This will ensure consistent, consecutive data.
