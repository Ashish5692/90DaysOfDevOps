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

What is C.A.L.M.S Freamwork
Culture: Communication and Trust
Automation : Automate Manual Tasks
Lean: Minimize waste and wait times
Measurement: Use data to improve
Sharing: Share knowledge and success

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
. Automation: Using tools to do boring tasks so humans don't have to.

. Infrastructure as Code (laC): Instead of physically plugging in cables or
clicking buttons to set up a server, you write a text file (script) that describes
the server. The computer reads the file and creates the server for you.

. Declarative: You tell the tool what you want (e.g., "I want 3 servers"), and it
figures out how to do it.
. Version Control: You can save your infrastructure scripts in Git, just like
software code.

Real-World Example
------------------
. A company needs 50 servers for a Black Friday sale. Instead of hiring 10
people to click buttons for a week, they run one Terraform script, and 50
servers appear in minutes.

Common Beginner Confusions
--------------------------
. Confusion: "Is laC writing software?"
. Correction: It is writing configurations for servers using code-like syntax, but
you aren't building an app; you are building the environment for the app.


CLOUD COMPUTING : 


           
