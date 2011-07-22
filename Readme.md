# 15 minutes of Biometric Fame display

## FaceTemplate::Ptr
    to keep multiple collections of pointers to face templates and delete templates when all pointers are removed
    - at the moment this is broken and FaceTemplate::Ptr is defined as FacePointer*

## TODO lists

[ ] daily maintainance script (on startup):
    [ ] log rotate, compress old logs
    [ ] probably kill the oldest pictures / templates in Faces/new
    [ ] also for the robot

[ ] "feeding to internet" animation
    [ ] clear display after 100% + some delay

[ ] hide the cursor

[ ] translate search terms


[ ] no match - clear old text
[ ] make sure display is cleared on new display (in addition to timeout)


