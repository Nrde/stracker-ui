# stracker-ui
improved UI for Stracker web interface

## changes

 - lap time table uses datatables 
 - all laptimes on one page, also possible to scroll table inside it's own container
 - strackers own paging hidden by default
 - sorting for relevant columns
 - tooltip on sector times tells the difference to best lap's sectortime
 - slightly bigger AC logo
 
 ## install
 
  - copy directories to the stracker directory replacing the 2 template files
  - modify "items_per_page" in stracker.ini to match or exceed expected total laps for example items_per_page = 200 (if you want to prevent paging)
  - stop and start webserver/stracker script. 
