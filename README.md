# Devops-Learning-AWS

## Assignment 1 - VPC & Networking

In this assignment I created a custom VPC with one public and one private subnet, set up the correct routing for internet access, and deploy EC2 instances across them.

## Step 1 - Create a VPC with public & private subnet

<img width="1591" height="472" alt="image" src="https://github.com/user-attachments/assets/ffb5e555-9242-4e4a-aaa6-12dfa94be609" />
<img width="1607" height="382" alt="image" src="https://github.com/user-attachments/assets/6e489503-7a83-4b9a-99ef-2fe53d207b8b" />

## Step 2 - Create an internet and NAT gateway

<img width="1617" height="400" alt="image" src="https://github.com/user-attachments/assets/782e12b2-889c-4754-9ad2-b1ab87098ba0" />
<img width="1617" height="632" alt="image" src="https://github.com/user-attachments/assets/c0d0d46f-368b-4355-9520-2de11a1c5ceb" />

## Step 3 - Route Tables
- Public route table via the internet gateway
- Private route table via via the NAT gateway

<img width="1607" height="660" alt="image" src="https://github.com/user-attachments/assets/66a37643-e71f-4e57-891f-5f35c5df2ac5" />
<img width="1612" height="655" alt="image" src="https://github.com/user-attachments/assets/cd8fab34-24f0-455e-992e-a63a8f67d0cd" />

## Step 4 - Public & Private EC2 Instances

<img width="1282" height="617" alt="image" src="https://github.com/user-attachments/assets/95fcf640-d35e-4f69-8f27-28d1d49fc2cf" />
