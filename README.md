# Project name

OneTimePadLocalRouter
# Project Description

The project is a password management tool, aiming to provide users with secure, efficient and easy-to-use password management services. Users can use the tool to generate, store, and manage their passwords, thereby avoiding security issues caused by using the same password or a simple password.

The project uses OTP (One-Time Pad) and RSA encryption algorithms, as well as server programs written in the Go language, to provide strong security for users. Users can easily manage their passwords through a web interface without having to download any client software.
# Installation Guide

The server program for the project runs in the Go language environment, and you need to install the Go language before installation.
First, you need to get the source code from GitHub. You can use Git to clone the source code locally:

` ` `
git clone https://github.com/Microsoft-tele/OneTimePad_LocalRouter
` ` `

Go to the project directory and compile and run the server program with the following command:
` ` `
go build
./OneTimePadLocalRouter
` ` `

The program listens to the local port 8080 and starts running. You can now use the program by pointing your browser to http://localhost:8080.

# User Guide

Register an account: Before you can use the program, you need to register an account. In the login interface, click the "Register" button and fill in the required information to complete the registration.

Login: After registration is complete, you can log in to the program using your email address and password.

Generate OTP Password: After logging in successfully, you can click the "Generate OTP" button and fill in the relevant information to generate a new OTP password.

View OTP passwords: In the OTP list, you can view all the OTP passwords you have generated.

Encrypt Password: On the Encrypt page, you can encrypt your password using the OTP algorithm.

View Personal information: After successfully logging in, you can view your personal information, including your stored OTP password, in the home page.

# Contact Information

If you have any questions or suggestions, please feel free to contact us. You can contact us at liweijun0302@gmail.com.
