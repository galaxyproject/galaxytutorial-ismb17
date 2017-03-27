# Tutorial PM6: Making Galaxy Work for You

Presenters
Martin Cech - Department of Biochemistry and Molecular Biology, Penn State University, University Park, PA, USA
John Chilton - Department of Biochemistry and Molecular Biology, Penn State University, University Park, PA, USA

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
