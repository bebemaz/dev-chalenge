# dev-chalenge
Webserver challenge
I would use terraform for this solution
Start it by the following commands
Terraform init
Then generate the plan
Terraform plan
Respond Y to deploy the cluster
Terraform Apply

Then to verify the output 
Curl $(terraform output elb_dns_name
This will show the public dns name of the ELB and then I can also place it in a browser to view the output.
