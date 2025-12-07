Project Description

So basically, this project is about creating a VPC on AWS using Terraform, which helps in automating the infrastructure setup instead of doing everything manually from the console.
Inside this VPC I created a subnet, an internet gateway, and a route table to make the network actually work.

From what I understand so far:

a VPC (Virtual Private Cloud) is like my own private network inside AWS; it’s where all my resources live.
the internet gateway is what connects that private network to the Internet, kind of like the main gate of a society.
a subnet is just a smaller piece of the VPC network where instances or other resources are placed.
the route table acts like a road map telling traffic inside the subnet where to go — in this case, it sends Internet traffic out through the internet gateway.
Basically, I used Terraform to automate setting up a small network on AWS that’s ready for public access if I want to add servers later.
