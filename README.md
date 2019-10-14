# onedot-tasks
Actions executed to secure docker images:
-Node runs with node user
-Nginx runs with nginx user
-Chose small base image
-Base images verified
-Only opened ports on EC2 host are 7000 (where nginx listens) and 22

Reasons to choose Alpine as base image:
-Less software means less potential vulnerabilities
-Smaller=Faster
-Small image is a requirement

Reasons to choose Amazon Linux 2 as EC2 Host
-Tried a few images and it was the fastest
