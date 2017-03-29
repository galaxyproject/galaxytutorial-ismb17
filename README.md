# Tutorial PM6: Making Galaxy Work for You

## Instructors
Martin Cech(1) & John Chilton(1) & Björn Grüning(2) ([@martenson](https://github.com/martenson) & [@jmchilton](https://github.com/jmchilton) & [@bjoerngruening](https://github.com/bjoerngruening))

(1) Department of Biochemistry and Molecular Biology, Penn State University, University Park, PA, USA
(2) Bioinformatics Group at Albert-Ludwigs-Universität, Freiburg, Germany


## Tutorial Overview
Galaxy is an open source web-based platform for data analysis. The goal of this tutorial is to provide a practical, hands-on guide to adapting the Galaxy platform to the specific needs of individuals attending the ISMB.

Galaxy is widely deployed and packaging your bioinformatic tools and pipelines for Galaxy is an effective way to expand the audience of your work. Galaxy deployments range in size from single user instances to large public servers serving tens of thousands of researchers. Instances provide a uniform and easy-to-use interface to sophisticated computational resources without requiring users to learn command line interfaces or Linux systems administration skills.

Participants will learn to 
Create Galaxy compatible tool and workflow definitions that are publicly accessible and make it easy for anyone instance administrator to add your work to their server. 
Deploy Galaxy and scale it up to target production-ready resources such as a Postgres database, NGINX webserver, and distributed resource managers such SLURM or PBS.

## Schedule
* 2:30 - 2:50 Introduction to Galaxy - From Data Exploration to Workflow Building
* 2:50 - 4:00 Integrating Tools into Galaxy
  * Anatomy of Galaxy Tools & Introduction to [Planemo](https://planemo.readthedocs.org)
  * Galaxy [Tool Shed](https://galaxyproject.org/toolshed/)
  * Wrapping a tool [hands-on](http://planemo.readthedocs.io/en/latest/writing_standalone.html)
  * Tool Development Q & A
* 4:00 - 4:15 Coffee Break
* 4:15 - 5:30 Deploying and Scaling Galaxy
  * Deployment and Platform Options
  * Get Basic Server Up and Running [hands-on](https://martenson.github.io/dagobah-training/02-basic-server/get-galaxy.html) 
  * Automated Deployment with Ansible [demo](https://github.com/martenson/dagobah-training/blob/master/advanced/001-ansible/ex2-galaxy-ansible.md)
  * Leveraging Compute Clusters [demo](https://martenson.github.io/dagobah-training/005-compute-cluster/compute-cluster.html)
* 5:30 - 6:00 Q & A, troubleshooting

## Participant Overview:
This tutorial is aimed at a broad audience. Some knowledge of the command-line and Unix will be assumed. Parts of the tutorial are hands-on so participants are encouraged to bring their laptops. No previous knowledge of Galaxy or particular topics in bioinformatics is required. Participants should have a desire to learn more about Galaxy, or a desire to learn how to wrap their tools and pipelines in Galaxy to facilitate others using these, or just want specific advice on setting up instance of Galaxy and scaling it up.

## Instructor bios

*John Chilton* has a Master's degree in computer science and has been a professional software developer working in the field of bioinformatics infrastructure for 10 years. John is a member of the Galaxy team, the creator of several open source projects including Planemo and Pulsar, and one of the co-founders of the Common Workflow Language.  

*Dr Björn Grüning* is with the Bioinformatics Group at Albert-Ludwigs-Universität Freiburg, in Freiburg Germany, where he heads the Freiburg Galaxy Project. His publication list includes several papers that feature Galaxy prominently, including the recent “Enhancing pre-defined workflows with ad hoc analytics using Galaxy, Docker and Jupyter” (Grüning, et al, 2016. He is a prominent contributor to, and is a driving force in, the Galaxy community. In the past year alone, he helped organize the Bioconda Contribution Fest, Swiss-German Galaxy Days, the Galaxy Training Materials Contribution Fest, the Galaxy DevOps Workshop, and the Conda Dependencies Codefest, and presented and taught at GCC2016. His research interests include data visualisation, computational chemistry, and drug discovery.

*Martin Čech*, an alumnus of Masaryk University, a fan of open source projects and communities, software enthusiast, and Galaxy developer in Anton Nekrutenko Lab at Penn State University since 2013. He enjoys training people in various Galaxy topics, untangling project's problems, enhancing UX, and being part of the Galaxy community overall.
