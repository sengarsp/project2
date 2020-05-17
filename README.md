# Automatic webdeployment and Sending mail to Devloper
# Summery of project
  I Created container image that’s has Jenkins installed using dockerfile 
  When we launch this image, it automatically starts Jenkins service in the container.
  I Created a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins 
# Job1 : 
  I Pull the Github repo automatically when some developers push repo to Github.
# Job2 :
  By looking at the code or program file, Jenkins should automatically start the respective language interpreter install image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed ).
# Job3 : 
  Test your app if it is working or not.
  if app is not working , then send email to developer with error messages.
#	Create One extra job job4 for monitor :
  If container where app is running. fails due to any reson then this job should automatically start the container again.
# Author
  Shyamendra pratan singh sengar
