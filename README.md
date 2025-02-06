# timelog
Simple Timelogger script for consultancy work.

# Usage

## Log Work Hours

  timelog add 7.5 "Worked on project xxx API"

Logs 7.5 hours for today with description.

## Summarize a Month

  timelog summary 2025-02

## Export 

Export a Specific Month to CSV

  timelog export 2025-02

Creates:
  📂 ~/timelog-2025-02.csv

Export All Months to a Single CSV
  
  timelog export all

Creates:
  📂 ~/timelog-all.csv

(Includes all months logged!)
