\# Setting Up EC2 Linux Server



\## 1. Project Overview

This project demonstrates the setup of an Ubuntu Linux server using Amazon Web Services (AWS) EC2 and the deployment of a Python Flask web application. GitHub is used to store and manage the application source code.



\## 2. Objectives

\- To launch an AWS EC2 Linux instance.

\- To connect to the server using SSH.

\- To install and configure Python, Flask, Git, and Nginx.

\- To run the Flask application using Gunicorn.

\- To deploy and access the website through the internet.



\## 3. Technologies Used

\- \*\*Cloud Platform:\*\* AWS EC2

\- \*\*Operating System:\*\* Ubuntu Linux

\- \*\*Programming Language:\*\* Python

\- \*\*Web Framework:\*\* Flask

\- \*\*Application Server:\*\* Gunicorn

\- \*\*Web Server:\*\* Nginx

\- \*\*Version Control:\*\* Git and GitHub

\- \*\*Frontend:\*\* HTML and CSS



\## 4. System Architecture

The system follows this architecture:



\*\*User Browser → AWS EC2 Ubuntu Server → Nginx → Gunicorn → Flask Application\*\*



GitHub stores the project source code, which is cloned onto the EC2 instance for deployment.



\## 5. Project Structure

\- `app.py` — Main Flask application.

\- `templates/` — Contains HTML templates.

\- `static/` — Contains CSS and other static files.

\- `requirements.txt` — Lists Python dependencies.

\- `screenshots/` — Contains project screenshots.

\- `README.md` — Project documentation.



\## 6. Deployment Steps

1\. Launch an Ubuntu EC2 instance on AWS.

2\. Configure the security group to allow SSH and HTTP traffic.

3\. Connect to the instance using SSH.

4\. Install Python, Git, and Nginx.

5\. Clone the project from GitHub.

6\. Create a Python virtual environment and install dependencies.

7\. Configure Gunicorn to run the Flask application as a service.

8\. Configure Nginx as a reverse proxy.

9\. Access the deployed website using the EC2 public IPv4 address.



\## 7. Result

The Python Flask web application was successfully deployed on an AWS EC2 Ubuntu Linux server. Gunicorn runs the application, while Nginx handles incoming HTTP requests.



\## 8. Conclusion

This project provides practical experience in cloud computing, Linux server administration, Python web development, web server configuration, and GitHub version control.



\## 9. References

1\. AWS EC2 Documentation: https://docs.aws.amazon.com/ec2/

2\. Ubuntu Server Documentation: https://ubuntu.com/server/docs

3\. Flask Documentation: https://flask.palletsprojects.com/

4\. Gunicorn Documentation: https://docs.gunicorn.org/

5\. Nginx Documentation: https://nginx.org/en/docs/

6\. GitHub Documentation: https://docs.github.com/



