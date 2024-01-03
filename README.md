To split a sequence of letters into different columns - =MID($B3, COLUMNS($B$3:B$3), 1)
To concatenate different columns of 95% CI into one considering two digits - =CONCAT(TEXT(AE5,"0.00")," (", TEXT(AF5,"0.00"),"-",TEXT(AG5,"0.00"),")")
