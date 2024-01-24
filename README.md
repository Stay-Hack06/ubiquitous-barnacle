Convert a date range consisting of two dates formatted as YYYY-MM-DD into a more readable format.
The friendly display should use month names instead of numbers and ordinal dates instead of cardinal (1st instead of 1).
Do not display information that is redundant or that can be inferred by the user: if the date range ends in less than a year from when it begins, do not display the ending year.
Additionally, if the date range begins in the current year and ends within one year, the year should not be displayed at the beginning of the friendly range.
If the range ends in the same month that it begins, do not display the ending year or month.


change yyyy-mm-dd to Month - date(cardinal) - year. 
slicing the date range to only the the dates.
don't add the ending year if it's less than 12 months from now
if the date is current year and ends within 12 months the year at the beginning date should not have year 
if the dates are in the same month don't use year or month for ending date 

format with new date
to local date string
if statements that include the slicing needed# ubiquitous-barnacle
