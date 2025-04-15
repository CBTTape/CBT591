# CBT591
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 591 is from Bob Fowles of Pennsylvania State University   *   FILE 591
//*           and from Philip H. Smith III, and is a VM REXX exec   *   FILE 591
//*           whose purpose is to clean up and syntax check other   *   FILE 591
//*           REXX execs.  This is a VM exec, and it is being       *   FILE 591
//*           included here, in the hope that someone who knows     *   FILE 591
//*           both VM and MVS, will get this exec to work under     *   FILE 591
//*           TSO REXX.  Lionel Dyck has now converted this exec    *   FILE 591
//*           to an ISPF Edit Macro, included here as member        *   FILE 591
//*           REXXFORM.                                             *   FILE 591
//*                                                                 *   FILE 591
//*           Author:   BOB FOWLES     (obsolete phone number)      *   FILE 591
//*                     RBF@PSU.EDU    (this info is from 2002)     *   FILE 591
//*                     814-865-4774                                *   FILE 591
//*                                                                 *   FILE 591
//*           email:  lbdyck@gmail.com    (z/OS support)            *   FILE 591
//*                                                                 *   FILE 591
//*       Lionel Dyck has acceded to the request of Bob Fowles      *   FILE 591
//*       and has converted the VM REXXFORM into an ISPF edit       *   FILE 591
//*       macro.                                                    *   FILE 591
//*                                                                 *   FILE 591
//*       The original VM REXX exec called REXXFORM has now been    *   FILE 591
//*       renamed to member REXXFOR1, to make room for a TSO REXX   *   FILE 591
//*       exec (which is an ISPF edit macro) called REXXFORM, from  *   FILE 591
//*       Lionel Dyck.  Member REXXFORM is in TSO XMIT format,      *   FILE 591
//*       which expands to its own pds, for installing the z/OS     *   FILE 591
//*       version of REXXFORM, as an ISPF edit macro.               *   FILE 591
//*                                                                 *   FILE 591
//*       Expand the member which is now called REXXFORM, and       *   FILE 591
//*       which is in TSO XMIT format, by using the commend:        *   FILE 591
//*                                                                 *   FILE 591
//*        (TSO) RECEIVE INDS('this.pds(REXXFORM)')                 *   FILE 591
//*                                                                 *   FILE 591
//*       and answering the prompts.  Since RECEIVE is a TSO        *   FILE 591
//*       command that comes from IBM, there is a help member       *   FILE 591
//*       for it in SYS1.HELP on any MVS system that is more        *   FILE 591
//*       recent than MVS SP 1.3.5 (from the mid 1980's).           *   FILE 591
//*       The result of this RECEIVE command is the install         *   FILE 591
//*       pds for the REXXFORM z/OS product.                        *   FILE 591
//*                                                                 *   FILE 591
//*       If you are executing the RECEIVE command from the         *   FILE 591
//*       ISPF command line, you have to prefix it with the         *   FILE 591
//*       word, TSO.                                                *   FILE 591
//*                                                                 *   FILE 591
```
