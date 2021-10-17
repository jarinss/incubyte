# incubyte

prerequisites:
1)aws EC2 instance
2)docker
4)github repository

steps:
1)install docker,java,jenkins on centos machine.
2)create one repository on git hub.
3)clone that repository and push the code on that particular repository.
4)configure jenkins.
5)make one ec2-instance on aws as a deployment server.
configure pipeline using jenkins as:
job1:fetch-code -->job2:build-image -->job3:execute-container  
