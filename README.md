# Arduino_Temperature_Tracker

## Summary
  This is my attemp to create an Arduino based temperature tracker with the following features
  * Two sensors
  * Sample Temp & Humitidy every minute
  * Display
    * Current date & time
    * Temperature (F&C) & humidity
    * 24 hour max/min temp
    * 24 hour max/min humidity
    * Activate display
      * When button is pushed
      * Keep active for 1 min
      * Cycle through elements
  * Log to CSV file on SD card
    * Date/Time stamp
    * Temp C
    * Temp F
    * Humidity

## Hardware elements
  * Foundation
  * Arduino
  * Temp/humid sensor
  * Display
  * Real Time Clock (RTC)
  * SD Card Module
  * Power Source
  * Button

## Software Milestones
  1. Read temp & humid
  2. Output temp & humid to display
  3. Incorporate RTC
  4. Display Date/Time
  5. Illuminate display only for 1 min after button pressed
  6. 24 hour max/min
  7. Save data to SD Cadr

