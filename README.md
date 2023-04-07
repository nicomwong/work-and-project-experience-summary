# Work and Project Experience Summary

DevOps:
- operations: shadow on call a few times; no monitoring
- sprint planning, standups, development, ran test suite locally before publishing a code review via git, resolved merge conflicts with mainline, merged CR, watched through pipeline to release; if a build failed with one of my changes, i would go in and investigate; one time it did fail so i looked into the commits and the error logs; it didn’t look like my error so i consulted the teammate who was in charge of the pipeline builds for that week; he said it was his change that broke it.

Unix/Linux:
- Commands: directory navigation (ls, pwd, cd); remote login (ssh, scp); vim; grep; (looking into sed); networks and processes (ps, netstat)

CI-CD pipeline:
- added putObject permission to AWS IAM policy
- added parameter to pipeline alpha and beta stage configurations that makes it so when a build fails, a JUnit report is uploaded to our team's AWS S3 bucket
- Used CloudFormation to set IAM policy permissions and pipeline alpha and beta stage configuration parameters

Scripting languages:
- familiar with Python; a little bash and i’m okay at javascript

Config management tools:
- CloudFormation task
- very Interested in learning TerraForm since it seems to be very popular in the devops and cloud space

K8s:
- i’m familiar with the containerized concept; haven’t used it before; interested in learning since it seems very useful

SQL:
- basic knowledge and experience

Interpersonal / Collaboration:
- helped and collaborated with fellow new hire on understanding new codebase and general Amazon and SWE practices and tools; specifically during the api migration project to understand how parts of the code worked and how dependency injection works as well as some minor Java features
- gave tips to help other new hire onboard because i had run into many problems with the onboarding process and i wanted to help those who would onboard in the future; i wasnt given much guidance in the beginning (at Amazon)

API migration:
- Task: consolidate API calls to reduce size of codebase; Result: I shipped two of these APIs mostly by myself and was working on a third when lay-off happened

Bug Fix:
- traced logic and consulted teammate who had worked on that area of the code

Expand unit test coverage:
- Challenge: difficult because new technologies: mockito, google guice modules and dependency injection; different pieces all over the codebase to understand and the codebase was large
