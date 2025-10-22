# prohandel

artikelstatistik.
OUTPUT TO c:\temp\artstat90542.csv.
FOR EACH artstat NO-LOCK WHERE filnr = 1 AND liefnr = 90542:
EXPORT artstat.
//DISPLAY plan.
END.
OUTPUT CLOSE.
