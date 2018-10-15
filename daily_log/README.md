# LZ's log of PD project work

Automatically update every day.

******************************


- 
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





