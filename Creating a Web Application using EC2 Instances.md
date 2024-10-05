![image](https://github.com/user-attachments/assets/9b4b8bd2-ef90-4aad-9cf8-78a7a490e0db)


Steps
Launch an EC2 Instance
Sign in to your AWS Management Console.
Navigate to the EC2 Dashboard.
Launch a single EC2 instance.
Choose an appropriate instance type and configure security groups to allow HTTP traffic.
2. Set Up Web Server

Install a web server (e.g., Apache, Nginx) on the EC2 instance.
Create a simple HTML file with the “Happy Learning, Mr.CloudExplorer!” message.
3. Assign a Public IP

If the instance does not have a public IP assigned by default, allocate an Elastic IP address and associate it with the instance. This gives your instance a static public IP.
4. Test the Application

Access the instance’s public IP or DNS name in a web browser to see the “Happy Learning, Mr.CloudExplorer!” message.
5. Cleanup

Terminate the EC2 instance to avoid incurring additional charges.
