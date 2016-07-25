CV of Mitchell Jon Stanton-Cook
===============================

This is my Curriculum Vitae. It is being rendered by GitHub. The plain text version marked up in reStructuredText_ is located here_. If I wanted to convert it to another format I would use Pandoc_. If I wanted to make it prettier I would use pelican_ or sphinx_.  

.. _reStructuredText: http://docutils.sourceforge.net/rst.html
.. _here: https://raw.githubusercontent.com/mscook/CV/master/CV.rst
.. _Pandoc: http://pandoc.org
.. _pelican: http://docs.getpelican.com/en/3.6.0/
.. _sphinx: http://sphinx-doc.org

.. image:: CC.png


About
-----

I am a DevOps Engineer. I spend most of my time in the AWS clouds. I take ownership of information security. Previously I was a Research Software Engineer and Linux System Administrator.

Location: Brisbane_, Australia

Phone: +61 414800280

Email: m.stantoncook@gmail.com

GitHub_: mscook

LinkedIn_: mjstantoncook

Twitter_: mscook


.. _Brisbane: https://www.google.com.au/maps/place/Brisbane+QLD/@-27.4073899,153.0028595,12z/data=!4m2!3m1!1s0x6b91579aac93d233:0x402a35af3deaf40
.. _GitHub: https://github.com/mscook
.. _LinkedIn: https://au.linkedin.com/in/mjstantoncook
.. _Twitter: https://twitter.com/mscook


Summary
-------

I am a DevOp Engineer in a small agile infrastructure team. In a small team I get to solve challenging infrastructure problems end-to-end. My cloud of choice is AWS. I'm a jinja ninja with my configuration management tool of choice being Ansible_. I typically use Python_ when custom DevOps/automation tooling is required. I have been using Python_ for over 10 years.

I'm a polyglot DevOp, currently working across two different accounts (QLD Government and NSW Government) which are on different cloud providers (Rackspace and AWS) and with significantly different operating system, networking and application layers. I manage many environments including being on-call for production environment incidents. 

I am the internal security officer. I am in charge of our ISO27001 and PCI-DSS 3.0 compliance projects.

I administrator many Linux servers at once. I automate my work using orchestration/automation tools such as Ansible_ and Fabric_.

I am a `Software Carpentry Instructor`_ and `Data Carpentry Instructor`_. As an instructor I am trained to teach the Unix Shell, Python, R, Git, SQL and Cloud Computing to researchers with limited technical skills. This has taught me how to translate/explain highly technical topics to non-technical people.  

I have a significant number of open source repositories on GitHub_. When time and my employer permits I like to work on these and other open source projects. 

My software, infrastructure and analysis tools has resulted in authorship on a number of peer reviewed International journal articles. The most up-to-date list can be found on my `Google Scholar profile`_.

I have supervised and led a number of undergraduate students and staff on a variety of software and infrastructure projects. 


.. _Ansible: http://www.ansible.com/home
.. _Python: https://www.python.org/
.. _Fabric: http://www.fabfile.org 
.. _`Software Carpentry Instructor`: http://software-carpentry.org/pages/team.html
.. _`Data Carpentry Instructor`: http://www.datacarpentry.org/
.. _`Google Scholar profile`: https://scholar.google.com.au/citations?user=MGafrX4AAAAJhl=en


My Tech Stack
-------------

Linux System Administration. Variety of distributions. Greater than 10 years experience. 

Significant experience in High Performance Computing (HPC) environments. PBS Pro, PBS, Torque, SLURM, modules and HSM of data. Greater than 7 years experience.

Experience using and building on academic and commercial cloud providers. I have used Nectar, DigitalOcean, Rackspace, Azure and AWS. 2 years experience.

Proficient in AWS console and API. Experience with VPC, EC2 (ELB and ENA), RDS, S3, Route53, CloudFront, CloudWatch, Directory Service, IAM and CloudFormation.

Experience in the use of Fabric and Ansible for systems orchestration and management. Greater than 3 years experience.

Use of Vagrant, Packer and Docker for testing, deployment and packaging.

Deep understanding of ISO27001, PCI-DSS 3.0 controls (at a policy and implementation level) and OWASP Top 10 standards.

Intermediate penetration testing (physical, infrastructure and web application) abilities.

Proficient in mathematical optimisation inclusive of the Python libraries NumPy, SciPy, MatplotLib, Biopython, IPython notebook, and pandas.

Understanding of python web application design and frameworks (Flask, pylons/pyramid bootstrap and pelican).

Familiar with databases NoSQL/SQL and ORM (RethinkDB, MongoDB/PostgreSQL, MySQL and peewee and Pony ORM).

Proficient with Atlassian suite (JIRA, Confluence, Bitbucket, Bamboo, HipChat, ...)

Currently learning Apache Spark. Spark is a fast and general engine for large-scale data processing.

Used to an on-call 24/7 2 week on, 4 week off roster for production websites. Incident management handled by PagerDuty with triggers from cloud native and 3rd party monitoring applications (CloudWatch alarms, NewRelic, Runscope, ...).

*I will (generally) write my code in Python. The code will be stored in a git repository. Dependencies will be pinned using a requirements.txt file and all work will be carried out in a virtual environment. The code is unittested with py.test. Documentation is written with sphinx and a hook will be used to push it to Read the Docs. I apply continuous integration principles using Travis CI. The code quality is constantly evaluated using landscape.io. At release time bumpversion is used to semantically version the release, place a tag in the git repository before pushing the release to GitHub and PyPI.*


Open source Projects
--------------------

An exhaustive list is at GitHub_. Open source activity has unfortunately dropped since joining XVT. The most interesting are:
    * Banzai_ (public placeholder repository): a next generation sequencing pipeline tool to go from many raw sequencing reads to draft genomes in a rapid and efficient manner. Banzai removes the complexity of the high performance computing environment from users. Employs the Python fabric library. Greater than 15K lines of code. 
    * SeqFindr_: easily create informative genomic feature plots. It's a tool to detect the presence or absence of genomic features given a database describing these features and a set of draft and/or complete genomes. There have been SeqFindr spin-offs (SeqFindr-Web, plasmid-barcodes). Employs the Python NumPy, SciPy, matplotlib and Biopython libraries.
    * pipelin.es_ (with A/Prof Torsten Seemann): Pipelin.es is a next generation sequencing data analysis pipeline evaluation tool using docker_ images.
    * BanzaiDB_: a tool for pairing Microbial Genomics Next Generation Sequencing analysis with a NoSQL database (RethinkDB).

.. _Banzai: https://github.com/mscook/Banzai-MicrobialGenomics-Pipeline
.. _SeqFindr: https://github.com/mscook/SeqFindR
.. _pipelin.es: https://github.com/pipelines
.. _BanzaiDB: https://github.com/mscook/BanzaiDB
.. _docker: https://www.docker.com/


Employment history
------------------

**Sep 2015 - Current:** DevOps Engineer/Open Data consultant at `XVT Solutions`_.  

**Jan 2015 - Sep 2015:** School of Chemistry and Molecular Bioscience `Teaching Fellow`_. Prepare and deliver lectures and lead both undergraduate and postgraduate students in The University of Queensland Bioinformatics courses SCIE2100_ and BIOL3014_.

**Jun 2011 - Sep 2015:** Software Engineer/Systems Administrator in `The Beatson Microbial Genomics Laboratory`_. 

**2007 - 2011:** Postgraduate scholar on an Australian Postgraduate Association Scholarship. Stipend while performing full time study towards PhD.

**2006 - 2011:** Casual bulk tutor in undergraduate subjects at the University of Queensland. Led and instructed students in the courses BIOL1014, COSC2000 and BIOL3004.

**2002 - 2006:** Laboratory Assistant in the preanalytical department of `Sullivan and Nicolaides Pathology`_.

.. _XVT Solutions: https://xvt.com.au
.. _SCIE2100: http://www.courses.uq.edu.au/student_section_loader.php?section=1&profileId=71951
.. _BIOL3014: https://www.uq.edu.au/study/course.html?course_code=BIOL3014&offer=53544c554332494e
.. _`Teaching Fellow`: http://www.uq.edu.au/teaching-learning/internal-uq-funding-opportunities     
.. _`The Beatson Microbial Genomics Laboratory`: http://beatsonlab.ecogenomic.org/people/
.. _`Sullivan and Nicolaides Pathology`: http://www.snp.com.au


Education
---------

`Australian National University`. **Postgraduate studies 2007-2011**. `Computational structural biology`_.

`The University of Queensland`. **Honours Degree. 2006-2007**. `First Class Honours`_ (>85%) in the field of Biochemistry.

`The University of Queensland`. **Undergraduate Degree. 2002-2006**. Bachelor of Science majoring in Bioinformatics_. GPA = 6 (of 7).

.. _`Computational structural biology`: http://comp-bio.anu.edu.au
.. _`First Class Honours`: http://www.scmb.uq.edu.au/honours
.. _Bioinformatics: https://www.uq.edu.au/study/plan.html?acad_plan=BIINFW2030
.. _`Australian National University`: http://www.australianuniversities.com.au/rankings/
.. _`The University of Queensland`: http://www.australianuniversities.com.au/rankings/


Lead/Supervision
----------------

`Tom Robinson`_ (research assistant): **Elastic-Banzai**. Re-engineering our genomics analysis pipeline to make use of all available compute resources. Stack: Apache Mesos, Flask, Celery Queue, Apache Libcloud and docker.

`Jun Ling`_ (project student and research assistant): **SeqFindr-web**. Dynamic SeqFindr visualisation in a web-app. Stack: Flask, Celery Queue, Bootstrap and D3.js.

`Marisa Emerson`_ (project student and research assistant): **BanzaiDB** and **BanzaiVis**. Storage and visualisation of bacterial genomics data. Stack: RethinkDB, Flask, Bootstrap  D3.js.

`Hamza Khan`_ (International summer research scholar): **Plasmid-barcodes** and **SeqFindr-web**. Visualisation of plasmid material. Stack: Matplotlib and D3.js.

`Hitesh Arora`_ (International summer research scholar): **Plasmid-hunter**. Classification of plasmid material. Stack: Python scripts and machine learning frameworks.

.. _`Tom Robinson`: http://github.com/tomjrob
.. _`Jun Ling`: http://github.com/jling90
.. _`Marisa Emerson`: http://github.com/m-emerson
.. _`Hamza Khan`: http:///github.com/hamzakhanvit
.. _`Hitesh Arora`: https://github.com/hitesh11


Hackathons etc.
---------------

`Sunshine Coast Council's Hackfest 2015`_ (2015): **Towards smart councils**. Created an improved planning notification tool using Python, Socrata API, RethinkDB and KeenIO. 

`Mozilla Science Lab Global Sprint 2015`_ (2015): **UQ Site**. Worked on establishing infrastructure for Australian based library carpentry workshops.

Unearthed_ (2015): **Team RockMe**. Developed an OpenCV based particle size classifier. Produced a working tool that was live demoed to the judges.

`TANDA hackathon`_ (2015): **Team Dark Magic**. Performed exploratory data analysis of TANDA's time and attendance data using python. Developed an interactive geolocated salary visualisation tool. Backend was RethinkDB. Frontend was custom D3.js visualisation.

Docker's 2nd Birthday Party (2015): **Redhat Brisbane site**. `Wrote code`_. Saved whales.

`Startup Health Weekend`_ (2015): **Team Triosk**. Designed, validated and delivered a Kiosk for Emergency Department triage. The Triosk design rationale document is available_. Won_ Best Pitch and Best Collaboronaut.

`Startup Weekend`_: (2014): **Team RentUrWay**. Designed, validated and mocked a privacy aware tenant-landlord communication tool. Simple web development and D3.js charts (for mocks-ups).

.. _Unearthed: http://unearthed.solutions
.. _`TANDA hackathon`: https://www.tanda.co/tanda-open-data-hackathon-this-weekend-17th-18th-april/
.. _`Startup Health Weekend`: http://www.up.co/communities/australia/startup-weekend/4813
.. _`Startup Weekend`: http://www.rivercitylabs.net/event/startup-weekend-brisbane/
.. _`Mozilla Science Lab Global Sprint 2015`: https://www.mozillascience.org/global-sprint-2015
.. _available: http://triosk.co/triosk_overview.pdf
.. _Won: http://www.ilabaccelerator.com/2015/04/its-a-wrap-australias-first-startup-weekend-for-health/
.. _`Wrote code`: http://docker.party
.. _`Sunshine Coast Council's Hackfest 2015`: https://innovationcentre.com.au/event/sunshine-coast-hackfest-2015/


Recent Invited Talks
--------------------

**Tips and tricks for working with open data portals**. `GovHack Connections Event`_, RiverCity Labs, 11 July 2016. I spoke about the usage (browser and API based) of open data portals with a particular focus on QLD CKAN based open data portals.

**Doing bioinformatics better**. Australian Bioinformatics Conference, Melbourne Australia, 2014 (slides_). DevOps principles for bioinformaticians. SemVer, Dependency pinning, virtual environments, software revisioning, virtualisation and containerisation.

**An Introduction to RethinkDB and how we use it**. Brisbane NoSQL Users Group, Brisbane Australia, 2014. An hour long presentation introducing all aspects of RethinkDB, followed by live demoing of our tool BanzaiVis. Spun up a set of RethinkDB instances for attendees to get hands on usage experience. 

.. _`GovHack Connections Event`: https://www.eventbrite.com.au/e/govhack-qld-connections-event-tickets-26344006633#
.. _slides: http://www.slideshare.net/mscook/australian-bioinformatics-conference-abic-2014-talk-doing-bioinformatics-better
.. _event: https://twitter.com/mscook/status/509150503167475713
 

Miscellaneous
-------------

I am a technical mentor at the 2016 Brisbane GovHack_ event.

I designed, organised and facilitated the inaugural Australian MIcrobial GenOmics Symposium (AMIGOS_) hackathon. AMIGOS_ was a two day hackathon bringing together 45 Australian based Microbial Genomics researchers.

I am a certified `Software Carpentry Instructor`_. Through Software Carpentry I teach researchers basic software skills (BASH shell, python programming, software revision control and simple SQL databases). I co-organised and taught at a two day bootcamp `in July 2015`.  In September 2015 I taught Software Carpentry in Nanning, China_.

I am a certified `Data Carpentry Instructor`_. Data Carpentry develops and teaches workshops on the fundamental data skills needed to conduct research.

I co-organised the `2015 HealthHack`_ in Brisbane. I was also the one of two National facilitators. HealthHack is a data hack for medical researchers. The goal is to bring to focus the importance of software engineers in medical research fields. I have returned as an organiser for the 2016 event.

I am a member of `River City Labs`_. `River City Labs`_ is a co-working community where members come together to promote and develop early stage and start up businesses and engage in entrepreneurial activity.


.. _GovHack: http://portal.govhack.org/mentors/mitchell-stanton-cook.html
.. _AMIGOS: http://theamigos.space
.. _`in July 2015`: http://bio-swc-bne.github.io/2015-07-02-UQ/
.. _China: http://www.cls.zju.edu.cn/binfo/C3/2016/programme.html
.. _`2015 HealthHack`: http://www.healthhack.com.au
.. _`River City Labs`: http://www.rivercitylabs.net


Publications
------------

Software, infrastructure and analysis I have developed has resulted in authorship on 20 peer reviewed journal articles.

For the most up-to-date list (and metrics) see my `Google Scholar profile`_.

Of note/in the media:

*Global dissemination of a multidrug resistant Escherichia coli clone* (cited over 100 times): tracking the the global footprint and transmission of an almost completely antibiotic resistant urinary tract infection causing bacteria.

*Hospital-wide eradication of a nosocomial Legionella pneumophila serogroup 1 outbreak*: tracking a Legionella outbreak in Brisbane's Wesley hospital. 


References
----------

Provided on request.

