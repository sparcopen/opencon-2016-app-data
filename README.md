#OpenCon 2016 Application Open Data 

OpenCon is the conference and community for students and early career professionals interested in advancing Open Access, Open Education and Open Data. In the spirit of openness and transparency, we are releasing the accompanying data collected during the OpenCon 2016 application process.

##Download & Technical Information

The OpenCon 2016 application dataset can be downloaded in CSV format from GitHub here: https://github.com/RightToResearch/OpenCon-2016-Application-Data

The file uses UTF8 encoding, comma as field delimiter, quotation marks as text delimiter, and no byte order mark.

##License and Requests

This dataset is released to the public under a [CC0 Universal 1.0 Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/). 

We do have a few requests of anyone who uses the data. First, we’d love it if you would let us know what you are doing with it, and share back anything you develop with the OpenCon community. Second, it would also be great if you would include a link to the OpenCon 2016 website (www.opencon2016.org) wherever the data are used, so that people can find out more about OpenCon. You are not obligated to do any of this, but we'd really appreciate it!

##Data Fields

Below is more information about each of the data fields. You can also find the original text of the application form [here](https://github.com/RightToResearch/opencon-2016-application-data/APPFORM.md). All fields below were mandatory questions unless marked as optional.

<table cellpadding="6"><tr align="left"><th>Field</th><th>Additional Information</th></tr>
<tr><td>unique id</td><td>This is a unique ID assigned to each applicant. Numbers were assigned using a random number generator.</td></tr><tr><td>submission type</td><td>Applicants were given the choice of whether to submit their application or save it for later editing. Saved applications were accepted as final at the relevant deadline.</td></tr><tr><td>timestamp</td><td>This was the timestamp recorded by the server when the data was recorded. For "submitted" applications, the timestamp is when the data was submitted. For "final at deadline" applications, this is the date the data was last saved. The general application process began at 12:00 UTC June 6, 2016 and ended at 03:59 UTC on July 12, 2016. There were a number of applications submitted after this date due to reasons including exceptions granted for technical difficulties, error corrections (requiring manual re-submission), and applications for scholarships funded by sponsors that requested a later deadline.</td></tr><tr><td>citizenship</td><td>Country of Citizenship. Choose one option from list of countries, or select &ldquo;Country Not Listed&rdquo;. List sourced from Wikipedia.</td></tr><tr><td>residence</td><td>Country of Residence. Choose one option from list of countries, or select &ldquo;Country Not Listed&rdquo;. List sourced from Wikipedia.</td></tr><tr><td>gender</td><td>Choose one option or fill-in an answer. In cases where a person filled in the exact word &ldquo;male&rdquo; or &ldquo;female&rdquo;, the response was treated as though the person had checked the corresponding box.</td></tr><tr><td>degrees held</td><td>Choose all that apply from list or select &ldquo;None of the Above&rdquo;. </td></tr><tr><td>area of interest</td><td>Choose one option. Many applicants have multiple areas of interest, and they were instructed to select the most important one. </td></tr><tr><td>event participation</td><td>Choose all that apply from list or select &ldquo;None of the Above&rdquo;.</td></tr><tr><td>occupation</td><td>Choose up to three options. </td></tr><tr><td>career experience</td><td>Choose one option. People were instructed to not count time as a full time student or PhD candidate as career experience.</td></tr><tr><td>academic field</td><td>Choose one option. List of options was sourced from OECD.</td></tr><tr><td>skills</td><td>Optional. Choose all that apply from list and/or fill-in other.</td></tr><tr><td>how heard</td><td>Optional. Choose all that apply from list and/or fill-in other.</td></tr></table>

##Data Collection & Cleaning

This dataset consists of information collected from people who applied to attend OpenCon 2016, including both our general application process and applications for sponsored scholarships. The general application period began at 12:00 UTC June 6, 2016 and ended at 03:59 UTC on July 12, 2016. Application periods for sponsored scholarships were open as late as 03:59 UTC on October 1, 2016. 

Applications were collected at the OpenCon 2016 website at https://secure.opencon2016.org, using [free software](https://github.com/RightToResearch/django-opencon2016-app) developed specifically for this purpose. PDF and Google Doc versions of the form were made available, but only a handful of applications were submitted in this manner.

Applicants were required to enter a unique e-mail address to begin filling out the form, which significantly cut down on duplicates. Only 56 duplicates were found. We searched for duplicates by looking for applications with identical names and essay questions, then we hand-screened them. In cases where a person had multiple applications, we kept the version with the most recent timestamp.

Applicants were given the choice of whether to submit their application immediately or save it for later editing. Saved applications were accepted as final when the application deadline expired. We automatically created saved applications for those who applied in 2015, so that if they entered the same e-mail address, they would be able to begin from last year's data. This database only includes those saved applications with answers for all mandatory fields above, and it excludes all 2015 saved applications that went unedited.

Applicants were required to acknowledge before submitting the form that they understood that responses to questions marked with a caret (^) would released as depersonalized, aggregate open data. 

##About OpenCon

OpenCon is the conference and community for students and early career academic professionals to advance Open Access, Open Education, and Open Data. OpenCon 2016 was held on November 12-14, 2016 in Washington, DC. OpenCon is organized by the [Right to Research Coalition](http://righttoresearch.org/), [SPARC](http://sparcopen.org/), and an [Organizing Committee](http://www.opencon2016.org/about_organizingcommittee) of students and early career researchers from around the world. The OpenCon annual meeting convenes students and early career academic professionals from around the world and serve as a powerful catalyst for projects led by the next generation to advance openness in research and education.

A unique aspect of OpenCon is that attendance at the annual conference is by application only, and the majority of participants who apply are awarded travel scholarships to attend. This model creates a conference environment where highly dedicated and impactful advocates can attend, regardless of where in the world they live or whether they have access to travel funding. The purpose of the application process is to conduct these selections fairly through a community-driven review process. We hope that by sharing this data, we can better understand the OpenCon community and the state of student and early career participation in the Open Access, Open Education, and Open Data movements. 

##Contact & Resources

For inquires about the OpenCon 2016 application data, please contact [Nicole Allen](https://github.com/txtbks) at nicole@sparcopen.org. 

Resources:
* [Code for the OpenCon 2016 application software](https://github.com/RightToResearch/django-opencon2016-app)

* [OpenCon 2016 application form](https://github.com/RightToResearch/opencon-2016-application-data/APPFORM.md)

* [Data from the OpenCon 2015 application process](https://github.com/RightToResearch/OpenCon-2015-Application-Data)
