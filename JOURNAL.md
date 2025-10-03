


## 10/1/2025 - Picked some parts  

Found a good high frequency NST that should work well for this project. Also found some surprisingly cheap capacitors but had to go with slower microwave diodes due to the current output of the NST. I also found a good HV meter and current meter for the power supply. ![Screenshot 2025-09-30 212257.png](https://blueprint.hackclub.com/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6ODQsInB1ciI6ImJsb2JfaWQifX0=--03adf19aa85471e2b0c97838b2031c4353bfc420/Screenshot%202025-09-30%20212257.png)
  

## 10/3/2025 12 AM - Designed a flyback transformer  

I looked at high frequency NSTs, flyback modules run from a regular MOSFET based driver, and even laser power supplies! However, nothing fit my needs. A high frequency NST was too expensive and outputted too much current. Standard small flyback modules were too weak and die quickly. I decided the best option was to wind and design my own flyback transformer. I had to perform some calculations and popped open my electronics book since induction is scary but I figured it out. I think it'll be pretty cool. Also decided that parafin wax is the best insulator since I don't have a vacuum chamber for resin and i HATE oil. ![Screenshot 2025-10-02 174216.png](https://blueprint.hackclub.com/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTMxLCJwdXIiOiJibG9iX2lkIn19--c9cbeee6adcd015d52afd89f6bc3704aa1fca86f/Screenshot%202025-10-02%20174216.png)
  

## 10/3/2025 1 AM - Created schematic (started pcb design)  

![CleanShot 2025-10-02 at 18.48.39@2x.png](https://blueprint.hackclub.com/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTMzLCJwdXIiOiJibG9iX2lkIn19--ae322957a9ca731a68130513ec67999b7c3f6dcb/CleanShot%202025-10-02%20at%2018.48.39%402x.png)
I created the schematic for the 13-stage multiplier. It should output 260,000 volts but due to losses, corona discharge, and insulation problems I'd estimate between 200kV and 250kV. I'm going to try to keep it compact so I can fit it in the power supply but that might mean I need to make awkward shapes for the PCB.![CleanShot 2025-10-02 at 18.48.45@2x.png](https://blueprint.hackclub.com/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTMyLCJwdXIiOiJibG9iX2lkIn19--bf58c8bec4c0d2cef286c2d58b24042fd497990c/CleanShot%202025-10-02%20at%2018.48.45%402x.png)
  

