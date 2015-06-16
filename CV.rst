CV of Mitchell Jon Stanton-Cook
===============================

This is my Curriculum Vitae. It is being rendered by GitHub. The plain text version is located here_. If I wanted to convert it to another format I would use Pandoc_. If I wanted to make it prettier I would use pelican_ or sphinx_.  

.. _here: https://raw.githubusercontent.com/mscook/CV/master/CV.rst
.. _Pandoc: http://pandoc.org
.. _pelican: http://docs.getpelican.com/en/3.6.0/
.. _sphinx: http://sphinx-doc.org


About
-----

I am a data analyst focused on large biological datasets. I am employed as a Software Engineer and Linux Systems Administrator. I am also a Teaching Fellow (lecturer).

DOB: 07/07/1983

Location: Brisbane_, Australia.

Phone: +61 414800280

Email: m.stantoncook@gmail.com

GitHub_: mscook

My work_ profile. My personal site_.

Twitter: @Bio_mscook (professional_), @mscook (personal_)

LinkedIn_: mjstantoncook

.. _Brisbane: https://www.google.com.au/maps/place/Brisbane+QLD/@-27.4073899,153.0028595,12z/data=!4m2!3m1!1s0x6b91579aac93d233:0x402a35af3deaf40
.. _GitHub: https://github.com/mscook
.. _work: http://beatsonlab.com/pages/MitchSC
.. _site: http://deriv.es
.. _professional: https://twitter.com/Bio_mscook
.. _personal: https://twitter.com/mscook
.. _LinkedIn: https://au.linkedin.com/in/mjstantoncook


Summary
-------

I develop solutions to challenging problems with a focus on research science. My software solutions are typically written in Python_, a programming language that I have been using for over 10 years. I consider myself a *(Bio)DevOp*. I have given talks on applying DevOps principles in the research science realm (slides_). I also apply the `Lean Startup Methodology`_ to my work (validate, build, test and iterate).

I am a core developer of computational pipelines and data management procedures for next generation sequencing data in the context of high performance computing (HPC) environments. Currently I work on a HPC system with 384 compute nodes providing over 3000 CPU cores. I have recently initiated a project to make our data analysis pipelines more elastic. That is, allow them to easily and seamlessly use available HPC, cloud and internal compute resources. 

I am a system administrator of Linux servers and OS X desktops. I automate my work using orchestration/automation tools such as Ansible_ and Fabric_.

I am a `Software Carpentry Instructor`_. As an instructor I am trained to teach the Unix Shell, Python, Git and SQL to researchers.  

I have a significant number of open source repositories on GitHub_. I am a code contributor to the Xplor-NIH_ Nuclear Magnetic Resonance (NMR) molecular structure determination package. This package is one of the most widely used protein structure determination packages ( > 1500 citations).

My software solutions and my data analysis pipelines have resulted in my authorship on a number of peer reviewed International journal articles. The most up-to-date list can be found on my `Google Scholar profile`_.

I have supervised and led a number of students and staff on a variety of projects. My passion for teaching and training was rewarded in early 2015 when I was offered a joint appointment as a Teaching Fellow within the School of Chemistry and Molecular Bioscience (joint appointment with my Software Engineering/Systems Administration role).

.. _Python: https://www.python.org/
.. _`Lean Startup Methodology`: http://theleanstartup.com/principles
.. _Ansible: http://www.ansible.com/home
.. _Fabric: http://www.fabfile.org
.. _Xplor-NIH: http://nmr.cit.nih.gov/xplor-nih/doc/current/python/ref/pcsTools.html


Current Projects
----------------

An exhaustive list is at GitHub_. However, the most active/interesting are:
    * Banzai_ (public placeholder repository): a next generation sequencing pipeline tool to go from many raw sequencing reads to draft genomes in a rapid and efficient manner. Banzai removes the complexity of the high performance computing environment from users. Employs the Python fabric library. Greater than 15K lines of code. 
    * SeqFindr_: easily create informative genomic feature plots. It's a tool to detect the presence or absence of genomic features given a database describing these features and a set of draft and/or complete genomes. There have been SeqFindr spin-offs (SeqFindr-Web, plasmid-barcodes). Employs the Python NumPy, SciPy, matplotlib and Biopython libraries.
    * pipelin.es_ (with A/Prof Torsten Seemann): Pipelin.es is a next generation sequencing data analysis pipeline evaluation tool using docker_ images.
    * BanzaiDB_: a tool for pairing Microbial Genomics Next Generation Sequencing analysis with a NoSQL database (RethinkDB).

.. _Banzai: https://github.com/mscook/Banzai-MicrobialGenomics-Pipeline
.. _SeqFindr: https://github.com/mscook/SeqFindR
.. _pipelin.es: https://github.com/pipelines
.. _BanzaiDB: https://github.com/mscook/BanzaiDB
.. _docker: https://www.docker.com/


My Tech Stack
-------------

Linux Systems Administration. Variety of distributions. Greater than 10 years experience. 

Significant experience in High Performance Computing (HPC) environments. PBS Pro, PBS, Torque, SLURM, modules and HSM of data. Greater than 7 years experience.

Experience using academic and commercial cloud providers. I have used Nectar, DigitalOcean, Azure and AWS.

Proficient in mathematical optimisation inclusive of the Python libraries NumPy, SciPy, MatplotLib, Biopython, IPython notebook, and pandas.

Experience in the use of Fabric and Ansible for systems orchestration and management.

Use of Vagrant (with packer) and Docker for testing, deployment and packaging.

Understanding of web application design and frameworks (Flask, bootstrap and pelican).

Familiar with databases NoSQL/SQL and ORM (RethinkDB, MongoDB/PostgreSQL, MySQL and peewee and Pony ORM).

Currently learning Apache Spark. Spark is a fast and general engine for large-scale data processing.

*I will (generally) write my code in Python. The code will be stored in a git repository. Dependencies will be pinned using a requirements.txt file and all work will be carried out in a virtual environment. The code is unittested with py.test. Documentation is written with sphinx and a hook will be used to push it to Read the Docs. I apply continuous integration principles using Travis CI. The code quality is constantly evaluated using landscape.io. At release time bumpversion is used to semantically version the release, place a tag in the git repository before pushing the release to GitHub and PyPI.*


Employment history
------------------

**2015 - Current:** School of Chemistry and Molecular Bioscience `Teaching Fellow`_. I prepare and deliver lectures and lead both undergraduate and postgraduate students in The University of Queensland Bioinformatics courses SCIE2100_ and BIOL3014_.

**2011 - Current:** Software Engineer/Systems Administrator in `The Beatson Microbial Genomics Laboratory`_. 

**2007 - 2011:** PhD scholar on an Australian Postgraduate Association Scholarship. Stipend while performing full time study towards PhD.

**2006 - 2011:** Casual bulk tutor in undergraduate subjects at the University of Queensland. Led and instructed students in the courses BIOL1014, COSC2000 and BIOL3004.

**2002 - 2006:** Laboratory Assistant in the preanalytical department of `Sullivan and Nicolaides Pathology`_.

.. _SCIE2100: http://www.courses.uq.edu.au/student_section_loader.php?section=1&profileId=71951
.. _BIOL3014: https://www.uq.edu.au/study/course.html?course_code=BIOL3014&offer=53544c554332494e
.. _`Teaching Fellow`: http://www.uq.edu.au/teaching-learning/internal-uq-funding-opportunities     
.. _`The Beatson Microbial Genomics Laboratory`: http://beatsonlab.com
.. _`Sullivan and Nicolaides Pathology`: http://www.snp.com.au


Education
---------

`Australian National University`. **PhD (incomplete). 2007-**. `Computational structural biology`_.

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

`Mozilla Science Lab Global Sprint 2015`_ (2015): **UQ Site**. Worked on establishing infrastructure for Australian based library carpentry workshops.

Unearthed_ (2015): **Team RockMe**. Developed an OpenCV based particle size classifier. Produced a working tool that was live demoed to the judges.

`TANDA hackathon`_ (2015): **Team Dark Magic**. Performed exploratory data analysis of TANDA's time and attendance data using python. Developed an interactive geolocated salary visualisation tool. Backend was RethinkDB. Frontend was custom D3.js visualisation.

Docker's 2nd Birthday Party (2015): **Redhat Brisbane site**. `Wrote code`_. Saved whales.

`Startup Health Weekend`_ (2015): **Team Triosk**. Designed, validated and delivered a Kiosk for Emergency Department triage. The Triosk design rationale document is available_. Won_ Best Pitch and Best Collaboronaut.

`Startup Weekend`_: (2015): **Team RentUrWay**. Designed, validated and mocked a privacy aware tenant-landlord communication tool. Simple web development and D3.js charts (for mocks-ups).

.. _Unearthed: http://unearthed.solutions
.. _`TANDA hackathon`: https://www.tanda.co/tanda-open-data-hackathon-this-weekend-17th-18th-april/
.. _`Startup Health Weekend`: http://www.up.co/communities/australia/startup-weekend/4813
.. _`Startup Weekend`: http://www.rivercitylabs.net/event/startup-weekend-brisbane/
.. _`Mozilla Science Lab Global Sprint 2015`: https://www.mozillascience.org/global-sprint-2015
.. _available: http://triosk.co/triosk_overview.pdf
.. _Won: http://www.ilabaccelerator.com/2015/04/its-a-wrap-australias-first-startup-weekend-for-health/
.. _`Wrote code`: http://docker.party


Recent Talks
------------

**Doing bioinformatics better**. Australian Bioinformatics Conference, Melbourne Australia, 2014 (slides_). DevOps principles for bioinformaticians. SemVer, Dependency pinning, virtual environments, software revisioning, virtualisation and containerisation.

**An Introduction to RethinkDB and how we use it**. Brisbane NoSQL Users Group, Brisbane Australia, 2014. An hour long presentation introducing all aspects of RethinkDB, followed by live demoing of our tool BanzaiVis. Spun up a set of RethinkDB instances for attendees to get hands on usage experience. 

.. _slides: http://www.slideshare.net/mscook/australian-bioinformatics-conference-abic-2014-talk-doing-bioinformatics-better
.. _event: https://twitter.com/mscook/status/509150503167475713
 

Miscellaneous
-------------

I designed, organised and facilitated the inaugural Australian MIcrobial GenOmics Symposium (AMIGOS_) hackathon. AMIGOS_ was a two day hackathon bringing together 45 Australian based Microbial Genomics researchers.

I am a certified `Software Carpentry Instructor`_. Through Software Carpentry I teach researchers basic software skills (BASH shell, python programming, software revision control and simple SQL databases). I am the lead instructor for a two day bootcamp `in July`.

I am a co-organiser of the `2015 HealthHack`_ in Brisbane. HealthHack is a data hack for medical researchers. The goal is to bring to focus the importance of software engineers in medical research fields.

I am a member of `River City Labs`_. `River City Labs`_ is a coworking community where members come together to promote and develop early stage and start up businesses and engage in entrepreneurial activity.

.. _AMIGOS: http://theamigos.space
.. _`Software Carpentry Instructor`: http://software-carpentry.org/pages/team.html
.. _`in July`: http://bio-swc-bne.github.io/2015-07-02-UQ/
.. _`2015 HealthHack`: http://www.healthhack.com.au
.. _`River City Labs`: http://www.rivercitylabs.net


Publications
------------
For the most up-to-date list (and metrics) see my `Google Scholar profile`_.

**Molecular characterization of a multidrug resistance IncF plasmid from the globally disseminated Escherichia coli ST131 clone**.
Phan MD, Forde BM, Peters KM, Sarkar S, Hancock S, **Stanton-Cook M**, Ben Zakour NL, Upton M, Beatson SA, Schembri MA.
PLoS One
doi: `10.1371/journal.pone.0122369`_

**Draft Genome Sequence of Pseudomonas fluorescens SRM1, an Isolate from Spoiled Raw Milk**.
Lo R, **Stanton-Cook MJ**, Beatson SA, Turner MS, Bansal N.
Genome Announc
doi: `10.1128/genomeA.00138-15`_

**Third-generation cephalosporin resistance conferred by a chromosomally encoded blaCMY-23 gene in the Escherichia coli ST131 reference strain EC958**.
Phan MD, Peters KM, Sarkar S, Forde BM, Lo AW, **Stanton-Cook M**, Roberts LW, Upton M, Beatson SA, Schembri MA.
J Antimicrob Chemother
doi: `10.1093/jac/dkv066`_

**Molecular analysis of asymptomatic bacteriuria Escherichia coli strain VR50 reveals adaptation to the urinary tract by gene acquisition**.
Beatson SA, Ben Zakour NL, Totsika M, Forde BM, Watts RE, Mabbett AN, Szubert JM, Sarkar S, Phan MD, Peters KM, Petty NK, Alikhan NF, Sullivan MJ, Gawthorne JA, **Stanton-Cook M**, Nhu NT, Chong TM, Yin WF, Chan KG, Hancock V, Ussery DW, Ulett GC, Schembri MA.
Infect Immun
doi: `10.1128/IAI.02810-14`_

**The complete genome sequence of Escherichia coli EC958: a high quality reference sequence for the globally disseminated multidrug resistant E. coli O25b:H4-ST131 clone**.
Forde BM, Ben Zakour NL, **Stanton-Cook M**, Phan MD, Totsika M, Peters KM, Chan KG, Schembri MA, Upton M, Beatson SA.
PLoS One
doi: `10.1371/journal.pone.0104400`_

**Global dissemination of a multidrug resistant Escherichia coli clone**.
Petty NK, Ben Zakour NL, **Stanton-Cook M**, Skippington E, Totsika M, Forde BM, Phan MD, Gomes Moriel D, Peters KM, Davies M, Rogers BA, Dougan G, Rodriguez-Baño J, Pascual A, Pitout JD, Upton M, Paterson DL, Walsh TR, Schembri MA, Beatson SA.
Proc Natl Acad Sci USA
doi: `10.1073/pnas.1322678111`_

**uPEPperoni: an online tool for upstream open reading frame location and analysis of transcript conservation**.
Skarshewski A, **Stanton-Cook M**, Huber T, Al Mansoori S, Smith R, Beatson SA, Rothnagel JA.
BMC Bioinformatics
doi: `10.1186/1471-2105-15-36`_

**Engineering [Ln(DPA)3] 3- binding sites in proteins: a widely applicable method for tagging proteins with lanthanide ions**.
Jia X, Yagi H, Su XC, **Stanton-Cook M**, Huber T, Otting G.
J Biomol NMR
doi: `10.1007/s10858-011-9529-x`_

**Generation of pseudocontact shifts in protein NMR spectra with a genetically encoded cobalt(II)-binding amino acid**.
Nguyen TH, Ozawa K, **Stanton-Cook M**, Barrow R, Huber T, Otting G.
Angew Chem Int Ed Engl
doi: `10.1002/anie.201005672`_

**Tunable paramagnetic relaxation enhancements by [Gd(DPA)(3)] (3-) for protein structure analysis**.
Yagi H, Loscha KV, Su XC, **Stanton-Cook M**, Huber T, Otting G.
J Biomol NMR
doi: `10.1007/s10858-010-9416-x`_

**Numbat: an interactive software tool for fitting Deltachi-tensors to molecular coordinates using pseudocontact shifts**.
Schmitz C, **Stanton-Cook MJ**, Su XC, Otting G, Huber T.
J Biomol NMR
doi: `10.1007/s10858-008-9249-z`_

.. _`Google Scholar profile`: https://scholar.google.com.au/citations?user=MGafrX4AAAAJhl=en
.. _`10.1371/journal.pone.0122369`: http://doi.org/10.1371/journal.pone.0122369
.. _`10.1128/genomeA.00138-15`: http://doi.org/10.1128/genomeA.00138-15
.. _`10.1093/jac/dkv066`: http://doi.org/10.1093/jac/dkv066
.. _`10.1128/IAI.02810-14`: http://doi.org/10.1128/IAI.02810-14
.. _`10.1371/journal.pone.0104400`: http://doi.org/10.1371/journal.pone.0104400
.. _`10.1073/pnas.1322678111`: http://doi.org/10.1073/pnas.1322678111
.. _`10.1186/1471-2105-15-36`: http://doi.org/10.1186/1471-2105-15-36
.. _`10.1007/s10858-011-9529-x`: http://doi.org/10.1007/s10858-011-9529-x
.. _`10.1002/anie.201005672`: http://doi.org/10.1002/anie.201005672
.. _`10.1007/s10858-010-9416-x`: http://doi.org/10.1007/s10858-010-9416-x
.. _`10.1007/s10858-008-9249-z`: http://doi.org/10.1007/s10858-008-9249-z


References
----------

Provided on request.

