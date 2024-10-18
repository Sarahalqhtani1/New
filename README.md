Open the `data.xlsx` file.
2. Review the formulas in the designated cells:
   - **Cell A1**: Total Sum of values from A2 to A10 using `=SUM(A2:A10)`.
   - **Cell B1**: Average of values in B2 to B10 using `=AVERAGE(B2:B10)`.
   - =IFERROR(A1/B1, "Error in calculation")
=SUMIF(A1:A10, ">10", B1:B10)
