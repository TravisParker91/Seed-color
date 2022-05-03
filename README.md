# Seed-color

ImageJ/Java information: ImageJ 1.52d; Java 1.8.0_221 or later.
 
Images of seeds must be scanned with background color different than seed color, ideally blue. Macro development was conducted with a Brother DCP-7065DN scanner and blue paper background.

Batch Processing:

Process-> Batch -> Macro

Paste desired macro into box. Select input folder and output folder.

Step 1: Pigmented "colored" pixels in the scan are quantified. The exact RGB values used to threshold vary based on seed color in scans. Colors isolated here include black, red, gold, and "sunrise" (orange, approximately).

Step 2: Total seed area is then quantified.

Output from Macro is a results table. Save as an .xlsx, .csv, etc. for further analysis. % pigmented area can be divided by % seed area to determine what proportion of seed coats are pigmented vs. white.
