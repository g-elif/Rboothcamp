# code view
1. Data Preparation

Check that:

Raw data is not modified directly.
Data types are appropriate.
Date/time variables are correctly formatted.
Missing values are identified and handled appropriately.
Duplicates are checked.
2025 data is correctly selected where required.
Data-cleaning steps are clearly explained in the QMD.
No unnecessary data manipulation is performed.
Actual column names are used; do not invent variables.

2. Data Joining

Check that:

At least two datasets are meaningfully joined.
The join key is appropriate and clearly explained.
Date/time formats are compatible before joining.
The join does not unintentionally duplicate observations.
Row counts before and after joining are checked where appropriate.
Missing values created by the join are investigated.
The joining process is reproducible.

3. R Code

Check that:

The code runs without errors.
Packages are loaded correctly.
Functions are used appropriately.
The code is readable and reasonably concise.
The native R pipe |> is preferred.
No unnecessary packages or overly complicated code are used.
File paths are reproducible and preferably relative.
Hard-coded computer-specific paths are avoided.
Code chunks have appropriate labels/options where useful.
The code and the written explanation are consistent.

Do not rewrite working code unnecessarily.
