# Assignment 2 - Application Load Balancer

- This assignment focused on building multiple EC2 instances placed behind an AWS Application Load Balancer. The goal was to understand how load balancing, health checks, and secure network isolation work together in real cloud environments.

## VPC Setup
- I setup a VPC utilising two public subnets.
- Internet gateway was attached to the VPC.
- Route table setup with internet gateway & associated with the subnets.
<img width="1615" height="677" alt="Screenshot 2025-12-08 205207" src="https://github.com/user-attachments/assets/83be05ed-1b87-41b2-b806-7a413d18378a" />
<img width="1597" height="587" alt="Screenshot 2025-12-08 205227" src="https://github.com/user-attachments/assets/b5844de8-ffae-4809-814f-176d4df2eeeb" />

## ALB Setup
- The ALB was setup allowing HTTP from anywhere with registered targets as the two ec2 instances.
<img width="1622" height="755" alt="image" src="https://github.com/user-attachments/assets/d0220104-ca59-401c-9a8a-037ae5005ff6" />
<img width="1612" height="743" alt="image" src="https://github.com/user-attachments/assets/15865adb-ebc0-4ee9-be0a-aff6f093442e" />

## EC2 Setup
- The ec2 instances are across two AZ's for increased availability.
- The security group goes through the ALB security group.
- ALB then balances internet traffic to the instances by providing two different websites everytime the page is refreshed.
<img width="1913" height="967" alt="image" src="https://github.com/user-attachments/assets/3d0296ad-d273-4bae-974f-923a75bbe8b9" />
<img width="1918" height="917" alt="image" src="https://github.com/user-attachments/assets/a05b1a7a-a305-426a-9cf7-077645c4773b" />


