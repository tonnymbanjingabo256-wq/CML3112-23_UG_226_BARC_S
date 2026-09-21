# CML3112 A2: Proof of Life

Student: 23/UG/226/BARC-S

## Program
My notebook, 23_UG_226_BARC-S_W02.ipynb, sets my student ID and cohort, prints a hello message and works out proof_sum (2 + 2 = 4). It adds 5 to readings each time a cell runs. It then reads the four records from site_inspection_log.csv into rows.

## File list
- 23_UG_226_BARC-S_W02.ipynb: my completed notebook, saved with outputs showing
- site_inspection_log.csv: the supplied data file with four records
- README.md: this file

## How to run
1. Open the notebook in Google Colab (File > Open notebook > Upload).
2. Upload site_inspection_log.csv using the Files panel on the left.
3. Check that STUDENT_ID in the first cell is correct.
4. Click Runtime > Restart session and run all.
5. Check that proof_sum is 4, readings is 17 and rows holds 4 records.

## What changed when I repeated a cell
I ran the cell readings = readings + 5 three times. The result grew each time: 17, 22, 27. The notebook remembers the value of readings between runs, so each run starts from the last result.

## What Restart and Run All does
It clears everything the notebook remembers, then runs every cell once from top to bottom. This proves the notebook works from a clean start. After it, readings was back to 17.

## One engineering problem and the error I repaired
I opened a blank notebook (Untitled1) instead of proof_of_life.ipynb, so I could not find STUDENT_ID. I fixed it by using File > Open notebook > Upload to open the correct file.
