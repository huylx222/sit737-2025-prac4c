# Ensure you have the following installed:

Git: https://git-scm.com/
Visual Studio Code: https://code.visualstudio.com/
Node.js (v16 or higher recommended): https://nodejs.org/en/download/

# Run these commands to create project directory
## Create project directory
mkdir sit737-2025-prac4p
cd sit737-2025-prac4p

## Initialize a new Node.js project
npm init -y

## Install dependencies: Express and Winston
npm install express winston

# Run this command to start the service
node calculator.js

# Run this command to use the Exponentiate service (choosing different numbers if you want to)
http://localhost:3000/exponentiate?num1=2&num2=5

# Run this command to use the Sqrt service (choosing a different number if you want to)
http://localhost:3000/sqrt?num1=9

# Run this command to use the Modulo service (choosing different numbers if you want to)
http://localhost:3000/sqrt?num1=9$num2=4
