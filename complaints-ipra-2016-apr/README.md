# complaints-ipra-apr2016

This dataset contains records of complaints against police officers, obtained from IPRA in April 2016 filling a FOIA request by the Invisible Institute. The corresponding [**complaints-cpd-june2016**](https://github.com/invinst/chicago-police-data/tree/master/complaints-cpd-june2016) dataset was obtained from CPD using an indentical FOIA request. 

The files in this directory have been formatted and cleaned to facilitate use. The raw files from IPRA and copies of the FOIA documents can be found in the **raw/** subdirectory. 

## List of Columns
* Accused\_Officer\_FName
* Accused\_Officer\_LName
* Accused\_Appointment\_Date
* Accused\_Detail
* Accused\_Position
* Accused\_Star
* Accused\_Unit
* Address	Beat
* CURRENT\_CATEGORY
* CURRENT\_CATEGORY\_CODE
* CURRENT\_STATUS
* Complaint\_Number
* Discipline\_Code
* FINDING\_CODE
* INITIAL\_CATEGORY
* INITIAL\_CATEGORY\_CODE
* IPRA\_Closed\_Date
* IPRA\_Investigator\_FirstName
* IPRA\_Investigator\_LastName
* Incident\_Time\_End
* Incident\_Time\_Start
* Involved\_Officer\_Age
* Involved\_Officer\_Detail
* Involved\_Officer\_FName
* Involved\_Officer\_Lname
* Involved\_Officer\_Position
* Involved\_Officer\_Race
* Involved\_Officer\_Sex
* Involved\_Officer\_Unit
* LOCATION\_CODE
* Notification\_Date
* Recommended\_Number\_Of\_Days
* Street


## Cleaning Notes

- Original folder contained separate files for years 2012-2016YTD
  - these separate files were collapsed into one file  
- Fixed **Accused\_Officer\_FName** column
  - Originally had three different spellings: Accused\_Officer\_FName, Accsued\_Officer\_FName, AccusedOfficer\_FName
  - Collapsed these columns together after confirming that there were no conflicts across the different columns

### Summary Table
| Year | Row Count | Unique CRID Count |
|------|-----------|-------------------|
| 2012 |   48293   |       1877        |
| 2013 |   39561   |       1913        |
| 2014 |   32454   |       1663        |
| 2015 |   14727   |       1392        |
| 2016 |   1720    |       330         |

### Unique CRID Count per Category

| Category                                                  | INITIAL\_CATEGORY Count | CURRENT\_CATEGORY Count |
|-----------------------------------------------------------|------------------------|------------------------|
| ALTERCATION / DISTURBANCE - OTHER                         | 2                      | 2                      |
| CHOKED                                                    | 33                     | 97                     |
| CIVIL SUITS - THIRD PARTY                                 | 179                    | 169                    |
| CLOSED HAND STRIKE (PUNCH)                                | 109                    | 310                    |
| COERCION - THREAT OF ARREST/CHARGES                       | 1                      | 1                      |
| COERCION - VIOLENCE                                       | 6                      | 8                      |
| DOMESTIC ALTERCATION - PHYSICAL ABUSE                     | 145                    | 118                    |
| DOMESTIC INCIDENT - NOT PHYSICAL                          | 134                    | 112                    |
| DRAGGED                                                   | 10                     | 21                     |
| EXCESSIVE FORCE - USE OF FIREARM / OFF DUTY - INJURY      | 1                      | 0                      |
| EXCESSIVE FORCE - USE OF FIREARM / OFF DUTY - NO INJURY   | 3                      | 2                      |
| EXCESSIVE FORCE - USE OF FIREARM / ON DUTY - INJURY       | 5                      | 2                      |
| EXCESSIVE FORCE - USE OF FIREARM / ON DUTY - NO INJURY    | 6                      | 5                      |
| EXCESSIVE FORCE / OFF DUTY - INJURY                       | 38                     | 27                     |
| EXCESSIVE FORCE / OFF DUTY - NO INJURY                    | 11                     | 7                      |
| EXCESSIVE FORCE / ON DUTY - INJURY                        | 1254                   | 524                    |
| EXCESSIVE FORCE / ON DUTY - NO INJURY                     | 587                    | 224                    |
| FALSE                                                     | 1                      | 1                      |
| FIREARM DISCHARGE NO HITS - HANDGUN                       | 1                      | 2                      |
| FIREARM DISCHARGE WITH HITS - HANDGUN                     | 79                     | 49                     |
| FIREARM DISCHARGE WITH HITS - RIFLE / ASSAULT WEAPON      | 2                      | 1                      |
| FIREARM DISCHARGE WITH HITS / OFF DUTY                    | 10                     | 16                     |
| FIREARM DISCHARGE WITH HITS / ON DUTY                     | 59                     | 85                     |
| FIREARM USED AS AN IMPACT WEAPON                          | 9                      | 10                     |
| HANDCUFF TOO TIGHT                                        | 20                     | 79                     |
| HARASSMENT                                                | 12                     | 23                     |
| ILLEGAL ARREST / FALSE ARREST                             | 3                      | 5                      |
| IMPACT WEAPON - AUTHORIZED (BATON / ASP)                  | 15                     | 33                     |
| IMPACT WEAPON - UNAUTHORIZED (FLASHLIGHT, HANDCUFFS, ETC) | 4                      | 12                     |
| IMPROPER SEARCH OF PERSON                                 | 3                      | 6                      |
| IMPROPER SEARCH OF VEHICLE                                | 1                      | 0                      |
| INADEQUATE / FAILURE TO PROVIDE SERVICE                   | 2                      | 2                      |
| INJURY                                                    | 31                     | 41                     |
| INSUBORDINATION                                           | 2                      | 1                      |
| INTOXICATED OFF DUTY                                      | 1                      | 0                      |
| KICKED                                                    | 22                     | 78                     |
| KNEE STRIKE                                               | 4                      | 20                     |
| MISCELLANEOUS                                             | 419                    | 968                    |
| MISUSE OF DEPARTMENT RECORDS                              | 2                      | 2                      |
| NEGLECT OF DUTY                                           | 10                     | 8                      |
| NO INJURY                                                 | 27                     | 53                     |
| OC CHEMICAL WEAPON                                        | 3                      | 6                      |
| OC DISCHARGE                                              | 56                     | 65                     |
| OPEN HAND STRIKE (SLAP)                                   | 17                     | 70                     |
| PROPER CARE - INJURY / DEATH                              | 162                    | 165                    |
| PROPERLY DIRECT SUBORDINATE                               | 1                      | 0                      |
| PUSH/PULL/GRAB                                            | 98                     | 292                    |
| PUSHED TO GROUND                                          | 7                      | 26                     |
| RACIAL / ETHNIC, ETC.                                     | 422                    | 412                    |
| RELIGIOUS AFFILIATION                                     | 1                      | 3                      |
| SEARCH - PERSON / PROPERTY                                | 3                      | 2                      |
| SEARCH OF PERSON - PROPERTY / USC TAKEN                   | 1                      | 0                      |
| SEXUAL ORIENTATION                                        | 41                     | 42                     |
| SHOTS FIRED - DESTRUCTION OF ANIMAL                       | 272                    | 271                    |
| SHOTS FIRED - NO HITS                                     | 122                    | 122                    |
| STALKING                                                  | 1                      | 6                      |
| STOMPED / STEPPED ON                                      | 15                     | 20                     |
| TAKE DOWN (THROWN TO GROUND)                              | 44                     | 158                    |
| TASER (CONTACT STUN)                                      | 1                      | 2                      |
| TASER (PROBE DISCHARGE)                                   | 13                     | 25                     |
| TASER (SPARK DISPLAYED)                                   | 1                      | 0                      |
| TASER DISCHARGE                                           | 1820                   | 1820                   |
| THREATS                                                   | 11                     | 19                     |
| TWISTED EXTREMITIES (WRIST/ARM/LEG)                       | 9                      | 21                     |
| U CONVERTED TO C.R. (RECORDS KEEPING ONLY, INITIAL)       | 2                      | 3                      |
| UNJUSTIFIED POINTING OF FIREARM - HANDGUN                 | 1                      | 0                      |
| UNNECESSARY DISPLAY OF WEAPON / OFF DUTY                  | 34                     | 35                     |
| UNNECESSARY DISPLAY OF WEAPON / ON DUTY                   | 237                    | 237                    |
| UNNECESSARY PHYSICAL CONTACT / OFF DUTY - NO INJURY       | 20                     | 14                     |
| UNNECESSARY PHYSICAL CONTACT / ON DUTY - NO INJURY        | 406                    | 171                    |
| USE OF PROFANITY                                          | 5                      | 6                      |
| VEHICLE                                                   | 4                      | 9                      |
| VERBAL ABUSE                                              | 5                      | 5                      |
| VIOLATION OF COURT ORDER                                  | 1                      | 1                      |
| CONDUCT UNBECOMING                                        | 0                      | 1                      |
| ELBOW STRIKE                                              | 0                      | 6                      |
| FAILURE TO IDENTIFY                                       | 0                      | 1                      |
| IMPROPER SERVICE OF WARRANT                               | 0                      | 1                      |
| MISUSE OF DEPARTMENT EQUIPMENT / SUPPLIES                 | 0                      | 1                      |
| PROPERTY - FAILED TO INVENTORY                            | 0                      | 1                      |
| TASER (LASER TARGETED)                                    | 0                      | 1                      |