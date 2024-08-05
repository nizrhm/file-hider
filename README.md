File Hider Java Project

Overview
The File Hider Java Project is an innovative application designed to provide a comprehensive learning experience in file security. This project incorporates essential security concepts including encryption, One-Time Passwords (OTP), and email authentication. By working through this project, users will gain hands-on experience with crucial security practices used in real-world applications.

Key Features
File Encryption: Encrypt and decrypt files using robust encryption algorithms to ensure data confidentiality.
OTP Implementation: Generate and verify one-time passwords for secure access and authentication.
Email Authentication: Implement email-based verification to confirm user identity and secure accounts.
Installation
Follow these steps to set up the File Hider Java Project on your local machine:

Clone the Repository

git clone https://github.com/nizrhm/file-hider.git

Navigate to the Project Directory

cd file-hider

Set Up Your Development Environment

Ensure you have Java Development Kit (JDK) 11 or higher installed.
Optionally, you can use an Integrated Development Environment (IDE) like IntelliJ IDEA or Eclipse.

Compile the Project

Navigate to the project directory and compile the Java source files:

javac -d bin src/**/*.java

Run the Application

To start the application, use the following command:

java -cp bin com.example.file_hider.Main

Make sure to replace com.example.file_hider.Main with the appropriate main class path if it's different.

Usage

After starting the application, you can use the following features:

Encrypt a File: Use the GUI or command-line interface to select a file and apply encryption.
Decrypt a File: Decrypt previously encrypted files using the correct decryption key.
Generate OTP: Create one-time passwords for secure login or verification processes.
Authenticate via Email: Implement and test email authentication mechanisms for user registration and login.
