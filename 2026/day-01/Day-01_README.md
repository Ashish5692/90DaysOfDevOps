  Understanding of Devops and Cloud Engineering

  Devops - Dev + Ops 
           Development team -  Writes codes, designs feature and fixes the bug
           Operation Team - Responsible for servers, network, security, scaling and keeping the application 24/7 running.
                            Note: Ops are not customer support that answer to customer phone calls rather they are highly technical engineers 
                                  who manages the servers/cloud that runs the software.

Dev - Builds the product. (focus on change)
Ops - Runs the product keeping in mind about the scalability, stability, cost optimization, reducing the TTM.

Traditional IT seperates Dev and Ops which create the wall of confusion.Releases are slow,risky and painful.
"IT WORKS ON MY MACHINE" is the comman problem of tradional approach.

Devops is not a tool, it is a culture and a method. It combines the Development and Operations into one team.
Instead of "you build it, I run it" mindset shifted to "You build it, you run it".

Note: More than 90% apploication runs on Linux

DEVOPS INFINTE LOOP looks like:
-------------------------------------------------------------------------------------------------------------------------------
PLAN -> CODE -> BUILD -> TEST -> RELEASE -> DEPLOY -> OPERATE -> MONITOR -> same cycle continues which is refered as CI/CD Loop
-------------------------------------------------------------------------------------------------------------------------------

Plan - Decide what to build
Code - Write the software
Build - Package the code into an executable file
Test - Check for bugs
Release - Approve the changes
Deploy - Put it on the live servers
Operate - Keep it running 
Monitor - Watch for errors and user feedback

Dev - Plan, Code, Build, Test
Ops - Deploy, Operate, Monitor

Eg: A game developer Plans a new level, Codes it, Builds the game file, Tests it for
glitches, Releases it to the app store (Deploy), ensures servers handle the
players (Operate), and checks if players are crashing (Monitor).

Devops Mindset
---------------
Development Teams collaborate with Operation Teams : 

- Time to Market (Reduce)
- Collboration (tools effective) - Git / Slack / Jira
- Scale (on-premise -> Cloud Transition)
- Automate (reduce repeated tasks) - Python / Shell

Real World Example: Amazon used to have very slow systems, but by adopting Devops they moved to releasing the code every 11.7 seconds allowing them to become the giant they are
                    today.

What is C.A.L.M.S Framework
----------------------------
- Culture: Communication and Trust
- Automation : Automate Manual Tasks
- Lean: Minimize waste and wait times
- Measurement: Use data to improve
- Sharing: Share knowledge and success

Example: Etsy uses "Blameless Post-Mortems", If an engineer accidentally deletes data, they don't fire them. They rather ask "How can we change the system so it's impossible to accidently delete data next time?"

Tools without culture will fail. Culture > Tools
Follow Blameless Culture
Automate everything possible.

CI/CD
-----
CI - Whenever a developer makes changes to the code, they automatically merge (integrate) their work into a shared version control repository (like GitHub or GitLab)

CD - CD is the second half, which extends CI by automatically preparing the validated code for release.

Delivery: Code can be deployed anytime, but a human pushes the button.
Deployment: Code goes to customers automatically without human intervention.


Example: When Facebook updates its app color from blue to slightly lighter blue, they
don't manually copy files. A developer commits the change, a CI/CD pipeline
tests it, and it updates on your phone automatically.

Pipeline - The set of automated steps code goes through (Build -> Test -> Deploy)


Bonus Points
Automation & Infrastructure as Code (laC)
-----------------------------------------
Automation: Using tools to do boring tasks so humans don't have to.

Infrastructure as Code (laC): Instead of physically plugging in cables or
clicking buttons to set up a server, you write a text file (script) that describes
the server. The computer reads the file and creates the server for you.

Declarative: You tell the tool what you want (e.g., "I want 3 servers"), and it
figures out how to do it.
Version Control: You can save your infrastructure scripts in Git, just like
software code.

Real-World Example
------------------
A company needs 50 servers for a Black Friday sale. Instead of hiring 10
people to click buttons for a week, they run one Terraform script, and 50
servers appear in minutes.

Common Beginner Confusions
--------------------------
Confusion: "Is laC writing software?"
Correction: It is writing configurations for servers using code-like syntax, but
you aren't building an app; you are building the environment for the app.


----------------
CLOUD COMPUTING : 
-----------------
Cloud computing is "renting" someone else's computer over the internet.
Cloud is physicsl hardware sitting in massive, secure warehouses(data centers) on the ground.

Instead of buying a server and putting it in your office closet, you pay Amazon, Microsoft, or Google to use their massive data centers.

Features : 
--------
On-Demand: Get a server whenever you want.
Pay-as-you-go: Pay only for what you use, like a utility bill.
Broad Network Access: Access via the internet.
Scalability: Ability to grow or shrink based on traffic.
Speed: Dev can get a new server in minutes not in weeks.
Reliability: Cloud Providers have backup power and redundancy.
Elasticity - Automatic scaling up and down
Cost Efficiency - No wasted resources.
Global Reach - Deploy code to Japan, US, and Europe instantly.

Real-World Example
------------------
- Netflix does not own data centers. It rents massive computing power from
AWS (Amazon Web Services) to stream movies to you.
- Zoom experienced massive growth during the pandemic. If they had to buy
physical servers, they would have failed. Using the cloud, they scaled up
instantly to support millions of new users.

Cloud Service Models
--------------------
IaaS: (Infrastructure as a Service)- Host - Renting the raw hardware (like plot of land).
----  You build everything on top. It gives control. 
AWS EC2, Google Compute Engine, you manage OS and Apps
Eg: Startup rent VM on AWS to host custom DB.

PaaS: (Platform as a Service) - Build - Renting the tools and environment (like a house --------frame). You just add the furniture(code).
Heroku, Google App Engine, You manage only the Code.
Eg: A developer upload code to Heroku to run a blog without setting up servers.

SaaS: (Software as a Service) - Consume -  Renting the finished product(like a hotel room). You just use it. It give convenience.
Gmail, Salesforce, Dropbox, You manage nothing but your settings.
Eg: HR uses Salesforce to track employees.

Cloud Deployment Models
-----------------------
- Public Cloud (AWS, Azure, GCP) - Shared Resources, cost Effective
- Private Cloud (On premise) - Dedicated resources, High security
- Hybrid Cloud (AWS + Azure) - Multiple Vendors

Real World Example : A bank keeps customer financial records in a Private Cloud (security) but uses a Public Cloud to run their public website and email marketing (cheaper).

DevOps + Cloud Together
-----------------------
DevOps is the "Method", and Cloud is the "Toolbox."
You can do DevOps without Cloud, but it's hard.
You can use Cloud without DevOps, but it's slow.
Together, they are a "Power Couple" for speed.

- Cloud allows DevOps to automate infrastructure (laC).
- Cloud provides the unlimited resources needed for continuous testing and deployment.

Key Concepts
Cloud-Native: Building apps specifically to run on the cloud (using
containers/microservices).

Programmable Infrastructure: The cloud allows hardware to be controlled by code, which is essential for DevOps automation.

Real-World Example
Netflix uses DevOps practices (automated testing) on AWS Cloud (scalable servers) to update their streaming service globally without downtime.

Notes: 
------
DevOps is how you work. Cloud is where you work. They just
work perfectly together.

Quick Revision Summary
----------------------
Cloud enables DevOps automation.
DevOps optimizes Cloud usage.
They enable faster time-to-market.
Together, they allow "Infrastructure as Code".

Code travels from a developer's laptop to a cloud server through an automated pipeline.

- Source Control (Git): Developer saves code.
- CI Server (Jenkins/GitHub Actions): Robot picks up code and tests it.
- Artifact Registry: Robot saves the approved application.
- Cloud Deploy: Robot sends app to AWS/Azure.

Real-World Example
------------------
A developer fixes a typo on the website. They push the change to Git. GitHub Actions sees the change, runs a spell-check test, passes it, and updates the website on AWS S3 automatically in 2 minutes.

- Code --> Repository ---> CI Pipeline ---> Testing  ---> Deployment.
- Everything is automated where possible.
- Feedback loops return to the developer.

<img width="1531" height="820" alt="image" src="https://github.com/user-attachments/assets/25bd375b-a1d6-4d9b-9041-366e6c62ee6f" />


Career Paths 
-----------
Junior DevOps: Knows Linux, basic Scripting, and Git. Can manage simple
pipelines.
Senior DevOps: Knows Cloud architecture, Security (DevSecOps), and
complex automation.
SRE (Site Reliability Engineer): A specialized role focused purely on reliability
and scaling (Google's version of DevOps).

Real-World Example
------------------
A System Administrator learns Python and AWS. They start automating their
daily tasks. They eventually become a DevOps Engineer helping developers
automate their releases.

