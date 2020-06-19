+++
title = "Introduction to databases on Cedar"
slug = "databases"
+++

This is a **2-day** course.

**Instructors**: Alex Lopes and Wolfgang Richter (SFU / WestGrid)

**Course plan**:

1. Short introduction to SQL on Cedar Databases
  - why databases
  - frontends
  - basic commands
1. Overview of the two database servers on Cedar: cedar-mysql-vm (MariaDB MySQL v.10.2) and
   cedar-pgsql-vm (PostgreSQL v.10.1 with PostGIS v.2.4)
1. Deeper dive into PostgreSQL on Cedar
  - how to get a Postgres account and database on the server for your research
  - how to use the _psql_ client from the Compute Canada headnode to interactively issue SQL commands or
    simply pipe in a set of commands to be executed
  - using a scripting language such as Python to access Postgres
  - tips on optimizing your SQL commands; importance of creating indexes; explain a long running command
    to see where it can be optimized

**Target audience**: general

**Level**: beginner

**Prerequisites**: This is an introductory course, no previous experience is required. We will provide
guest accounts on Cedar cluster.

**Software**: All attendees will need a remote secure shell (SSH) client installed on their computer in
order to participate in the course exercises. On Windows we recommend
[the free Home Edition of MobaXterm](https://mobaxterm.mobatek.net/download.html). On Mac and Linux
computers SSH is usually pre-installed (try typing `ssh` in a terminal to make sure it is there).

**Background information**: The database services in WestGrid are now offered through high-performance
database MySQL and Postgres servers on Cedar and Graham. Here is the
<a href="https://docs.computecanada.ca/wiki/Database_servers" target="_blank">official documentation</a>.

<!-- Alex is planning to pre-record most of the material and have live sessions only to address questions
and kickstart the course. -->
<!-- Alex should have videos ready by June-12 ("end of that week") -->

**Materials**:

- [Online slides](https://docs.google.com/presentation/d/1hRX7wViDG-PgXrn3vq-GQ_NH1TlWEo0QAHLGKJnZ-tg)
- [Git repository](https://gitlab.rcg.sfu.ca/alopes/db_workshop.git)

**June-24**
{{< zoom >}}
<b>9am-9:30am Pacific</b> Introduction and Syllabus
{{< /zoom >}}

{{< video >}}
54 min
{{< /video >}}<br>

1. BasicCmds - Basic commands and SQL queries 
1. ExploreCmds - Learning further about basic SQL
1. DeepDivePostgres1 - How to use the cedar postgres
1. DeepDivePostgres2 - Second part
1. SqlGroupBy - Queries on cedar and Exercises
1. PostgresSlurm - Create programs and slurm jobs that connects to the database

**Day 1 exercises**:
- Quiz: https://www.w3schools.com/sql/sql_quiz.asp
- Take some time to review the queries and examples on the w3schools website

{{< zoom >}}
<b>2pm-3pm Pacific</b> Exercises discussion and problem debugging (optional)
{{< /zoom >}}

**June-25**
{{< video >}}
22 min
{{< /video >}}<br>

1. ShallowDiveMySQL - Introduction to MySQL on cedar
1. DeepDiveMySQL1 - How to use Mariadb on cedar
1. MySQLSlurm - Create programs and slurm jobs that connects to the database

Optional videos:

- Opt-SSHWindows - If you need help to connect to cedar SSH interface on windows
- CedarDBOverview - Quick overview about database servers

**Day 2 exercises**:
- Creating tables and experiment commands on cedar databases
- Submit a job that connects to the database and execute an operations
- Take a look at the perl examples at the end of the slides if you would like to learn more

{{< zoom >}}
<b>11am-noon Pacific</b> Live session: Wrap up and questions
{{< /zoom >}}

<!-- Live session: 30-40 min presentation blocks. -->
