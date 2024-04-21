## Scope & Description
Ai based proctoring system to conduct & invigilate the examination. Examiner is expected to conduct online exam with enabling web cam with the laptop/desktop. Invigilator is able to see cheating alerts during exam and he/she can take corrective exams conveniently.

## User
1.	Student/examiner : expected to perform exam without cheating  
2.	Invigilator : expected to monitor cheating incident 

## Use-case
1.	Different person to attend exam
2.	Mobile/any device usage during exam
3.	Looking at others/focus point changed to different direction during exam
4.	Talking during exam

## Functionality 
Category	Functionality	| Technique |	Priority

**Base

1. Person detection & counting	Pre-trained with YOLO	Critical
2. Object detection like mobile, device	Pre-trained with YOLO	Critical
3. Face detection	Pre-trained with YOLO	Critical

**Authentication
4. Face verification	Pre-trained with YOLO	Mid
5. Face spoofing	Pre-trained with YOLO	Low
6. Eye tracking	Image processing	Critical
7. Lips analysis	Image processing	Low

## Architecture : 
https://miro.medium.com/v2/resize:fit:2000/format:webp/1*Ds-FMTI-lL-K-sIllocbcg.jpeg

## Result analysis of PoC :
1.	Response time of alert
2.	Module performance testing

## Demo video to detect the cheating : 
https://youtu.be/td8NpTZUuC0
 
## Implementation :
Python codes socket with JS to have client sided feature to maintain high precision and low latency application.

## Future scope
1.	Multithreaded codes
2.	Fine tuning
