## User Role Screen changes
- [ ]  S2
![[S2.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S3
![[S3.png]]
BE only.
403 if Yk28 returned PARAM~TRUE in main GET request
If Yk28 returned PARAMLIST, filter notifications.
<br><br>
- [ ]  S12
![[S12.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S13
![[S13.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S14
![[S14.png]]
![[S14_K7_button.png]]
No changes needed. Yk28 call will happen in S15 main GET request.
<br><br>
- [ ]  S15
![[S15.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S17
![[S17.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE or PARAMLIST in main GET request
<br><br>
- [ ]  S26
![[S26.png]]
![[S26_button.png]]
BE only.
remove userservice check from S2
<br><br>
- [ ]  S28
![[S28.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S40
![[S40.png]]
Mostly BE. mb some FE, so that 403 response is handled and screen does not completely block. 
Clarify what endpoint is used to retrieve insurance period information when dropdown value changes.

<br><br>
- [ ]  S48
![[S48.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S61
![[S61.png]]
![[S61_K41.png]]
![[S61_K41_button.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S67
![[S67.png]]
![[S67_K8.png]]
![[S67_K8_button.png]]
BE/FE. 
403 if Yk28 returned PARAM~TRUE in main GET request
S67-K8: Yk28 call will happen in main S40 GET request.
FE should handle 403 and not navigate to S40 in case user does not have right. 
<br><br>
- [ ]  S74
![[S74.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S75
![[S75.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S78
![[S78.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request
<br><br>
- [ ]  S81
![[S81.png]]
![[S81_K2.png]]
BE only. 
403 if Yk28 returned PARAM~TRUE in main GET request (clarify main endpoint with FE)
<br><br>
- [ ]  S82
![[S82.png]]
![[S81_K10.png]]
FE/BE
clarify where S82 link info is relayed
<br><br>