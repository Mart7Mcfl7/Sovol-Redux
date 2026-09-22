Better starting profiles for the Zero printer

Sovol builds some great printers, but their profiles can be very much lacking. What I've done is ported a lot of profiles from a Prusa Core One, this has a nice base to start with. The Zero is a very fast printer, but it's mostly setup in a show off way, very little thought has gone into quality settings. These profiles are no-where near as fast, but its fast enough and has done some great quality prints

When I have a enough time I may add some faster, tuned profiles but for now this is a solid base.

Various layer height profiles for each nozzle

Various nozzle sizes and more thought out line widths (nozzle size 0.2-0.8)

To use these profiles, copy/extract the files to C:\Program Files\OrcaSlicer\resources\profiles (or where your orca slicer is installed) Now when re-starting orca, add a printer and search for Zero, you should see 'Sovol Zero Redux' in the list.

I have added all assets needed and setup the bed sizes, start print gcode, should be ready to go. (Orca 2.4.2) I've done my best, but please don't assume there are no bugs. If you find one, please reach out so I can fix it.

Update 3

#3 Fixed default line width for 0.8 nozzles, they were inheriting 0.45 from parent.
