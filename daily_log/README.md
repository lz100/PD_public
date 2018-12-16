# LZ's log of PD project work

Automatically update every day.

******************************


- 
***


2018-12-15-23:00 Sat

- 
***


2018-12-14-23:00 Fri

- 
***


2018-12-13-23:00 Thu

- Learning python. Write the first instance of bwa. Working, but not perfect, may need Lee to help improve later.
- Want to write a program to track CPU, mem use for every a few seconds so I can profile and plot program performance.
- Current packages in bash or python only checks for overall time, CPU, mem, not customizable with my need. 
***


2018-12-12-23:00 Wed

- Reading Lee's scripts and try to rewrite.
***


2018-12-11-23:00 Tue

- Learning python
***


2018-12-10-23:00 Mon

- Visiting Scripps
***


2018-12-09-23:00 Sun

- 
***


2018-12-08-23:00 Sat

- 
***


2018-12-07-23:00 Fri

- CNVs all done. Plots generated.
- Not the ideal results, but works well on our current needs.
***


2018-12-06-23:00 Thu

- Didn't get much done today. 
***


2018-12-05-23:00 Wed

- Solved the sex chromosome calling problem. Segment calls are done, waiting for plotting tomorrow.
- Start to write R scripts for cell line identification and report generation
***


2018-12-04-23:00 Tue

- Sketching the workflow outline design.
- Learning some python.
***


2018-12-03-23:00 Mon

- Regular lab meeting
- Went to clinic for health issues.
- Working on the last piece of CNV calls.
***


2018-12-02-23:00 Sun

- 
***


2018-12-01-23:00 Sat

- 
***


2018-11-30-23:00 Fri

- Zoom conference meeting.
- Went to a series of talks of genomics in the afternoon.
***


2018-11-29-23:00 Thu

- Still trying to finish CNV calls but male samples with female PoN give wrong number? I guess. Asked GATK people but haven't heard back for more than 2 days.
- Anyway, will proceed to the final step.
***


2018-11-28-23:00 Wed

- Trying to finish all CNV calls. This time should give me segment calls not just dot calls.
- Install dual monitor solution for my work station. Now works on dual monitors with only one USB3 port. 
***


2018-11-27-23:00 Tue

- Start to write scripts for the whole PD QC pipeline.
- Plan to try with docker container and can transfer to singularity later.
***


2018-11-26-23:02 Mon

- System maintenance, unable to work on cluster.
***


2018-11-25-23:00 Sun

- 
***


2018-11-24-23:00 Sat

- 
***


2018-11-23-23:00 Fri

- Break
***


2018-11-22-23:00 Thu

- Break 
***


2018-11-21-23:00 Wed

- Finally finished all CWL workflow building.
- CNV calls are behind, need to catch up quickly.
- This week is short. Hope I can do more if there is time later this week.
- Will start PD QC workflow writing next Monday.
***


2018-11-20-23:00 Tue

- still fixing bugs from CWL. They built the workframe stupidly which makes it very hard to work on. 
***


2018-11-19-23:00 Mon

- Bugs happened to CWL workflow. Fixing bugs and generate workflow for human and non-human.
- Didn't get time to work on my CNV, need to catch up tomorrow.
***


2018-11-18-23:00 Sun

- 
***


2018-11-17-23:00 Sat

- 
***


2018-11-16-23:00 Fri

- Go back to work on the CNV calling in the afternoon time. 
- PoN recreated by different genders.
- calling segmented CNVs not just in dots this time.
***


2018-11-15-23:00 Thu

- CWL workflow is amlost done. The workflow diagram is in my google drive folder.
***


2018-11-14-23:00 Wed

- Work on CWL and need to learn some javascript. CWL is highly depending on js and makes it uneasy to interact.
***


2018-11-13-23:00 Tue

- Visited San Diego
***


2018-11-12-23:00 Mon

- Holiday 
***


2018-11-11-23:00 Sun

- 
***


2018-11-10-23:00 Sat

- 
***


2018-11-09-23:00 Fri

- work on cwl. Trying to add more scripts to each step. Most steps scripts should be finished by today.
***


2018-11-08-23:00 Thu

- still work on cwl, template has been created, just need to add more scripts for each step
***


2018-11-07-23:00 Wed

- Work on CWL pipeline 
***


2018-11-06-23:00 Tue

- Working on GATK CWL pipeline 
***


2018-11-05-23:00 Mon

- Project planning with Roy.
- Work on GATK work flow in CWL this week. Not too much of PD project will be done this week.
***


2018-11-04-23:00 Sun

- 
***


2018-11-03-23:00 Sat

- 
***


2018-11-02-23:00 Fri

- Out of lab today for a supercomputer workshop.
- A bug happened with the email sending scripts that sent 3 emails, fixed. SORRY
***


2018-11-01-23:00 Thu

- Project update report.
- Trying to fix an issue that caused CNV allele count step to be super slow
- Initial annotation for SVs are done.
***


2018-10-31-23:00 Wed

- Broad replied my issues: allosome chromosomes need to be called separately and create PoN separately on different genders. Need to rerun everything of CNVs
- Add a interval file this time to remove unnecessary regions.
- Annotating SVs
***


2018-10-30-23:00 Tue

- Annotating SVs
- refine CNV calls
***


2018-10-29-23:00 Mon

- Lab seminar report.
- Spent some time with cluster admin and learned some important knowledge.
- Post on Broad GATK try to ask some technical issues.  
- [x] CNV validation for all types are done
***


2018-10-28-23:00 Sun

- Raw CNV calls for all samples are generated. 
***


2018-10-27-23:00 Sat

- 
***


2018-10-26-23:00 Fri

- A problem with crontab not taking my R libraries, and prevented email sending. It's the Rscript environment bug, fixed 
***


2018-10-25-23:00 Thu

- First CNV sample worked, will try more real samples tomorrow.
- Configured cluster, wrote a script to find out max RAM and CPU used to better arrange jobs later.
***


2018-10-24-23:00 Wed

- Writing scripts for CNV. Test data panel worked, can apply to real samples.
- New server worked out, should have fixed the problem.
***


2018-10-23-23:00 Tue

- Server is broken, changed a server today.
- Writing CWL scripts for GATK pipeline.

***


2018-10-19-23:00 Fri

- [x] Roy said he would like to have me sending my log or a remainder so he can remember to check. After a few days of development, and tests, the system should be working. Weekly log pdf will be sent automatically.

***


2018-10-18-23:00 Thu

- Worked on slides to represent SV array validation
- Zoom meeting report
- Wokred on auto-email system
***


2018-10-17-23:00 Wed
- try to plot validated SVs
- Continue to work on SV, CNV slides
- [x] SV validation on arrays done
- [ ] Annotation of SV
***


2018-10-16-23:00 Tue

- Worked on supplement ppt: SNV and SV
- Tried to calculate allele frequency for SVs
***


2018-10-15-23:00 Mon

- Visited TSRI and reported 
***


2018-10-14-23:00 Sun

- 
***


2018-10-13-23:00 Sat

- 
***


2018-10-12-23:00 Fri

- Learning CWL workflow, finished the user guide. Trying to find a good example to build complex workflow.
***


2018-10-11-23:00 Thu

- virtualenv is not compactable with python3, tried to fix but didn't work. Trying with compile my own python3.
- [x] virtualenv fixed at the end of the day. Now running with python3 and pip3 no problem
- First instance of cwl workflow worked.
***


2018-10-10-23:00 Wed

- [ ] Testing the cwl to run GATK CNV workflow
- [x] vim now support cwl syntax
- learning cwl.
***


2018-10-09-23:00 Tue

- Working on the GATK CNV calling 
- Read reports on DREAM Challenge comparison, DELLY, MANTA are good, novoBreak is another always being on the top list.
***


2018-10-08-23:00 Mon

- Genome STRiP 2.0 added to the new function of duplication calling but this program requires minimum 20-30 samples to call common CNVs, not the tumor pair we want, give up on this one.
- Try this pipe [GATK somatic CNV Calling](https://gatkforums.broadinstitute.org/gatk/discussion/9143/how-to-call-somatic-copy-number-variants-using-gatk4-cnv). Try to test with my own scripts instead of fire cloud. The billing account is still under Lee's, can't use Firecloud until it switches to Summit. 
- will create a virtualenv environment to use CWL(common work flow language) so it's convenient for future pipeline development.
- 
***


2018-10-07-23:00

- 
***


2018-10-06-23:00

- 
***


2018-10-05-23:00

- Fixed a bug in update script that will push every minute. Luckily my assertions prevented actual push.
- Read CNV calling papers
- 
***


2018-10-04-23:00

- updated the main page of project\
- searched for validation data sets to used, seems the DREAM Challenge Somatic calling will be a good resource. They have both real cancer/normal pairs and simulated data to use.
- Want to find additional data set besides DREAM.
- Searched different callers to call real duplication not the tandem duplication. LUMPY, MANTA, DELLY all don't support this. GATK published their workflow for CNV calling. Research that tomorrow.

***


2018-10-03-23:00

- The log system is online today! Everything tested, should update automatically right
- Spent a few days to get my vim work properly, including some plugins.
- Talked to Roy of current SV status.





