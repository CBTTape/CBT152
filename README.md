# CBT152
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 152 IS FROM MR HAROLD ZBIEGIEN OF AMERICAN GREETINGS      *   FILE 152
//*           CORPORATION OF CLEVELAND, OHIO AND CONTAINS           *   FILE 152
//*           SOME UTILITY PROGRAMS AND PROGRAMS USED TO            *   FILE 152
//*           MANIUPLATE AFP (PSF) OBJECTS SUCH AS CHARACTER        *   FILE 152
//*           SETS AND OVERLAYS.  THIS FILE IS IN IEBUPDTE          *   FILE 152
//*           SYSIN FORMAT, SEE THE MEMBER CALLED $$DOC FOR         *   FILE 152
//*           ADDITIONAL INFORMATION                                *   FILE 152
//*                                                                 *   FILE 152
//*      email:   harold.zbiegien@amgreetings.com                   *   FILE 152
//*               Harold Zbiegien <hz11@CORE.COM>                   *   FILE 152
//*                                                                 *   FILE 152
//*      address:    AMERICAN GREETINGS CORP.                       *   FILE 152
//*                  ONE AMERICAN ROAD                              *   FILE 152
//*                  CLEVELAND, OHIO 44144                          *   FILE 152
//*                                                                 *   FILE 152
//*      phone:   216-252-7300  ext 2317                            *   FILE 152
//*                                                                 *   FILE 152
//*           AGGETVLI   SUBROUTINE USED IN INLINE                  *   FILE 152
//*           AGTERM     SUBROUTINE USED IN INLINE                  *   FILE 152
//*           AMAZING    PRODUCE A MAZE WITH ONE ENTRANCE AND       *   FILE 152
//*                      ONE EXIT (SOURCE)                          *   FILE 152
//*           AMAZING2   RUN THE PROGRAM, PRINT ON A PRINTER        *   FILE 152
//*                      THAT DOES NOT SKIP OVER THE PERFS.         *   FILE 152
//*           CALENDAR   PRINT A COMBINED JULIAN AND GREGORIAN      *   FILE 152
//*                      CALENDAR FOR ANY YEAR                      *   FILE 152
//*           F11UP      PPFA SOURCE, FORM DEFINTION FOR 1-UP       *   FILE 152
//*                      PRINTING                                   *   FILE 152
//*           F12UP      PPFA SOURCE, FORM DEFINITION FOR           *   FILE 152
//*                      ROTATED 2-UP PRINTING                      *   FILE 152
//*           INLINE     COBOL SOURCE FOR A PROGRAM TO COPY         *   FILE 152
//*                      PAGEDEFS AND FORMDEFS INLINE WITH THE      *   FILE 152
//*                      DATA FOR TESTING NEW PAGE AND FORM DEFS    *   FILE 152
//*                      COMPILED WITH THE NORES PARAMETER WITH     *   FILE 152
//*                      THE OLD OS/VS COBOL COMPILER               *   FILE 152
//*           INLINER    RUN TIME JCL FOR INLINE                    *   FILE 152
//*           JOVERBLD   THE SAS JOB TO CREATE PSF TYPE OVERLAYS    *   FILE 152
//*           NCZ93205   AN UPDATED VERSION OF A PDS MEMBER READ    *   FILE 152
//*                      SUBROUTINE FOUND ON THE CBT TAPE, ONE      *   FILE 152
//*                      BUG CORRECTED, EXTRA PARAMETER ADDED SO    *   FILE 152
//*                      THE CALLING PROGRAM CAN PASS A DDNAME      *   FILE 152
//*                      TO READ FROM                               *   FILE 152
//*           O$$DOC     DOCUMENTATION ON THE TWO OVERLAYS          *   FILE 152
//*           O11UP      SOURCE FOR THE PSF 1-UP OVERLAY            *   FILE 152
//*           O12UP      SOURCE FOR THE PSF 2-UP OVERLAY            *   FILE 152
//*           POSTERT    JCL TO RUN POSTER FOR NON-LASER            *   FILE 152
//*                      PRINTERS                                   *   FILE 152
//*           POSTERT2   DECOMPILED SOURCE FOR THE POSTER           *   FILE 152
//*                      PROGRAM FOUND ON THE CBT TAPE, SOME        *   FILE 152
//*                      BUGS FIXED, CARD INPUT NOW ALLOWED         *   FILE 152
//*           POSTER2    JCL TO PRINT POSTER OUTPUT ON A            *   FILE 152
//*                      SIEMENS/STC LASER PRINTER WHICH ARE        *   FILE 152
//*                      COMPATIBLE WITH IBM 3800-3/6 PRINTERS      *   FILE 152
//*                      BUT YOU CAN PRINT PERF TO PERF, HOWEVER    *   FILE 152
//*                      WITH SOME DEGRADATION                      *   FILE 152
//*           PSFSCAN    A SERIES OF SAS PROGRAMS USED TO PRINT     *   FILE 152
//*                      AND MANIPULATE PSF OBJECTS.  I HAVE        *   FILE 152
//*                      USED THEM TO MAKE SIMPLE CHANGES TO        *   FILE 152
//*                      CHARACTER SETS, MODIFY BAR CODE FONTS,     *   FILE 152
//*                      PRODUCE ROTATED FONTS, PRODUCE OUR OWN     *   FILE 152
//*                      GREY BAR PATTERN, AND PRODUCE OUR OWN      *   FILE 152
//*                      SIMPLE OVERLAYS.                           *   FILE 152
//*                      THESE HAVE BEEN DESIGNED AROUND THE        *   FILE 152
//*                      3800 TYPE PRINTER.  THERE ARE DIFFERENCES  *   FILE 152
//*                      WITH 3820/3835 FONTS THAT THESE            *   FILE 152
//*                      PROGRAMS PROBABLY WILL NOT HANDLE.         *   FILE 152
//*                      SINCE WE DO NOT HAVE THE OTHER PRINTERS    *   FILE 152
//*                      I COULD NOT MODIFY AND TEST THE            *   FILE 152
//*                      PROGRAMS.                                  *   FILE 152
//*           PSFSCANA   SAS PROGRAM TO LOAD A PSF CHARACTER        *   FILE 152
//*                      GROUP INTO A SAS FILE                      *   FILE 152
//*           PSFSCANB   SAS PROGRAM TO TAKE SAS DATA AND BUILD     *   FILE 152
//*                      NEW PSF CHARACTER GROUP, I.E. A C1XXXXX    *   FILE 152
//*                      MEMBER                                     *   FILE 152
//*           PSFSCANC   DELETE A CHARACTER FROM THE SAS DATA       *   FILE 152
//*                      SET                                        *   FILE 152
//*           PSFSCAND   ADD A CHARACTER TO THE SAS DATA SET        *   FILE 152
//*           PSFSCANE   PRINT THE SAS FILE DATA AND CHARACTER      *   FILE 152
//*                      RASTER PATTERN                             *   FILE 152
//*           PSFSCANF   PRINT INFO AND THE CHARACTERS FROM THE     *   FILE 152
//*                      SAS DATA FILE                              *   FILE 152
//*           PSFSCANH   LOAD A CODE PAGE INTO A SAS FILE, I.E.     *   FILE 152
//*                      T1XXXXX MEMBER                             *   FILE 152
//*           PSFSCANI   PRINT THE CODE PAGE FROM THE SAS FILE      *   FILE 152
//*           PSFSCANJ   DELETE A CHARACTER FROM THE SAS CODE       *   FILE 152
//*                      PAGE FILE                                  *   FILE 152
//*           PSFSCANK   ADD A CHARACTER TO THE SAS CODE PAGE       *   FILE 152
//*                      FILE                                       *   FILE 152
//*           PSFSCANL   BUILD A NEW CODE PAGE FROM THE SAS FILE    *   FILE 152
//*           PSFSCANM   TAKE 3800-3 "DOWN" FONT AND CHANGE IT      *   FILE 152
//*                      INTO AN "UP" FONT I.E. TAKE A C2XXXXX      *   FILE 152
//*                      MEMBER AND CHANGE INTO A C4XXXXX           *   FILE 152
//*           PSFSCANN   PRINT AN UP RASTER PATTERN FROM THE SAS    *   FILE 152
//*                      FILE                                       *   FILE 152
//*           PSFSCANO   BUILD THE "UP" CHARACTER SET FROM THE      *   FILE 152
//*                      SAS FILE                                   *   FILE 152
//*           PSFSCANP   COMPARE A SAS CHARACTER SET AND SAS        *   FILE 152
//*                      CODE PAGE                                  *   FILE 152
//*           PSFSCANQ   BUILD AN OVERLAY USING SAS AND SOURCE      *   FILE 152
//*                      COMMANDS.  A SAMPLE OVERLAY TESTING OUT    *   FILE 152
//*                      ALL OF THE COMMANDS                        *   FILE 152
//*           PSFSCAN1   READ A GROUP OF X1XXXX FONT MEMBERS,       *   FILE 152
//*                      SORT AND PRINT DATA                        *   FILE 152
//*           PSFSCAN4   PRINT INFO ON ONE T1XXXXX MEMBER, A        *   FILE 152
//*                      CODE PAGE PRINT                            *   FILE 152
//*           PSFSCAN5   PRINT INFO ON 1 C1XXXXX MEMBER, A          *   FILE 152
//*                      CHARACTER GROUP                            *   FILE 152
//*           PSFSCAN6   PRINT INFO ON A GROUP OF CHARACTER         *   FILE 152
//*                      GROUPS                                     *   FILE 152
//*           PSFSCAN7   PRINT A 1 LINE SUMMARY ON A SINGLE         *   FILE 152
//*                      CHARACTER GROUPS                           *   FILE 152
//*           PSFSCAN8   PRINT A 1 PAGE SUMMARY ON A GROUP OF       *   FILE 152
//*                      CHARACTER GROUPS                           *   FILE 152
//*           PSFSCAN9   PRINT INFO AND THE RASTER PATTERN OF       *   FILE 152
//*                      ONE CHARACTER GROUP                        *   FILE 152
//*           P12UP      PPFA SOURCE FOR OUR 2-UP PAGE DEF          *   FILE 152
//*           P18B2      PPFA SOURCE FOR OUR 1-UP PAGE DEF          *   FILE 152
//*           RFIXMOVE   SUBROUTINE USED IN INLINER                 *   FILE 152
//*           RPRINT02   SUBROUTINE USED IN INLINER                 *   FILE 152
//*           RPRINT07   SUBROUTINE USED IN INLINER                 *   FILE 152
//*           RPRINT09   SUBROUTINE USED IN INLINER                 *   FILE 152
//*           T$$DOC     DOC ON OUR CODE PAGES                      *   FILE 152
//*           TIMETAKE   SOURCE FOR A PROGRAM ANALYZER PROGRAM.     *   FILE 152
//*                      THE PROGRAM LOADS AND RUNS A TARGET        *   FILE 152
//*                      PROGRAM.  IT SETS A TIMER WHICH IS USED    *   FILE 152
//*                      TO SAMPLE WHERE A PROGRAM IS (PSW          *   FILE 152
//*                      INSTRUCTION) AND WRITE THE INFO OUT TO     *   FILE 152
//*                      A FILE.  THIS CAN BE USED TO TELL YOU      *   FILE 152
//*                      WHERE YOUR PROGRAM IS SPENDING THE MOST    *   FILE 152
//*                      TIME.  WORKS ON 24 OR 31 BIT PROGRAMS.     *   FILE 152
//*                      THERE ARE MUCH BETTER PROGRAMS ON THE      *   FILE 152
//*                      MARKET.  IT IS BEST IF ALL OF THE          *   FILE 152
//*                      SUBROUTINES ARE LINKED AS PART OF THE      *   FILE 152
//*                      LOAD MODULE.                               *   FILE 152
//*           TIMEHIST   COBOL PROGRAM USED TO PRINT A HISTOGRAM    *   FILE 152
//*                      OF THE DATA GATHERED BY TIMETAKE.  THIS    *   FILE 152
//*                      IS AN OLD OS/VS COBOL PROGRAM.             *   FILE 152
//*           TIMHISTJ   SAMPLE JCL FOR RUNNING TIMEHIST            *   FILE 152
//*           TIMTAKEJ   SAMPLE JCL FOR RUNNING TIMETAKE            *   FILE 152
//*           X$$DOC     DOC ON OUR CHARACTER SETS                  *   FILE 152
//*                                                                 *   FILE 152
```
