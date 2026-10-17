Quickstart Guide
================

*How to use:*

import ci_course as cic

To load sample data, use the following syntax to define a dictionary of your data:

your_dictionary = cic.load_measurements(path_to_your_csv, errors_you_expect)

To summarise the data, use the cic.summarise() function.

summarised_data_dictionary = cic.summarise_all(your_dictionary)

To write a report on the data:

path_to_report = write_report(summarised_data_dictionary, path_to_report)



 





