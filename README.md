# fix-RAID-controller
How to fix RAID controller

After hot pluging, the state of two HDD has been *Frn-Bad*, it can be fixed by these steps.

> 1. Press *ctrl+R* to inter the RAID controller's BIOS.

> 2. Press *ctrl+N* to the PD Mgmt page.

> 3. Select the *Frn-Bad* disk and press *F2*, select *Mamke unconfigureed good*, convert *Frn-Bad* (Foreign-Unconfig Bad) to *Foreign*.

> 4. Press *ctrl+N* to the Foreign View page.

> 5. Select the RAID controller and press *F2*, select *Foreign Config* to *Import*, the disk will be *Online* state.

> 6. If there is a disk still be *Rebuild* state, repeat the step 2~4.

> 7. Select the RAID controller and press *F2*, select *Foreign Config* to *Clear*, the disk will be *Offline* state.

> 8. Select the *Offline* state disk and press *F2*, select *Place drive Online*.

> 9. Press *esc* to exit and reboot.
