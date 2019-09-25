# MP1_AWS_with_HortonWorks--Sandbox

Overview ::: bring up a load balancer to balance load requests between 2 Amazon EC2 instances.

Step 1: Bring up 2 EC2 instances using the tutorial Using HortonWorks Sandbox on Amazon Web Services

Step 2: bring up a load balancer, which will help us distribute requests between the 2 instances

Step 3: SSH into the 2 instances in two separate terminal windows and type the following command:
       # tail -f /var/log/httpd/access_log
       
Step 4: Refresh the page with the load balancer DNS address multiple times and notice how the EC2 instances are getting requests. Each request from your browser will only be serviced by only one of the two EC2 instances.       

Step 5: Bring down 1 instance using the AWS console by terminating any ONE of the instances.

Step 6: Now refresh the browser page. the request being successful.
