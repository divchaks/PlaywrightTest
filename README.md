# Cross - skilling 

This repository is part of my personal learning journey as I focus on cross-skilling in automation tools. It was inspired by the QE-led Cross-Skilling initiative and serves as a structured space for me to explore, practice, and deepen my understanding of Playwright.

Here, I’ll be working through various test scenarios and practice exercises as I move through different focus areas and gradually building confidence and expertise in using Playwright. This repository will grow and evolve over time, reflecting both my progress and the skills I’m developing along the way.



To set up playwright ,first we have check if have node.js installed. You can check whether Node.js and npm are already installed by running the following command in your terminal:

```bash

npm -v
```
If it's installed, you’ll see a version number like:

```bash

10.2.0
```
To check the Node.js version specifically:

```bash

node -v
```

#### How to Install Node.js
Go to the official Node.js website:
https://nodejs.org/

Download the LTS (Long Term Support) version for your operating system (Windows, macOS, or Linux).

LTS is more stable and preferred for most projects.

Run the installer and follow the instructions. It will install both node and npm.

After installation is complete, restart your terminal and verify the installation:

```bash

node -v
npm -v
```
You should now see version numbers for both.





## Cloning the Project and Running Playwright Tests Locally
Before you can run Playwright tests, you need to get a copy of the project on your local machine. This means cloning the repository from GitHub and setting up your environment.


### Create a Folder and Clone the Repository
Before running any Playwright tests, you first need to clone the test project repository onto your local machine. Here’s how you can do that step-by-step.

🔹 Step 1: Open Terminal / Command Line
First, open a terminal or command prompt on your machine.

On Windows, you can use Git Bash, Command Prompt, or PowerShell

On macOS or Linux, use the Terminal app

🔹 Step 2: Navigate to Your Preferred Directory
Use the cd (change directory) command to move into the folder where you want to keep all your Playwright projects.

For example, to go into your Documents folder:

```bash

cd Documents
```


🔹 Step 3: Create a Folder for the Project
Now create a new folder named Playwright using the mkdir (make directory) command:

```bash

mkdir Playwright
```
This command creates a new folder called Playwright in your current directory.

Next, move into the new folder:

```bash

cd Playwright
```
🔹 Step 4: Clone the Git Repository
Now that you're in the right place, use git clone to copy the Playwright test project from GitHub to your local machine:

```bash

git clone https://github.com/your-username/your-playwright-repo.git

```
✅ Replace https://github.com/your-username/your-playwright-repo.git with the actual URL of your GitHub repository.

This will:

Create a new folder named after your repo (e.g. your-playwright-repo)

Download all the files, test scripts, and Git history into that folder

 Step 5: Move Into the Project Folder
Once cloned, change into the project directory like this:

```bash

cd your-playwright-repo
```
You are now inside the Playwright test project directory and ready to set it up!

### How to Run Playwright Tests After Cloning the Repo
Once you’ve cloned the repository to your local machine and installed the dependencies, you’re ready to run the Playwright tests. Here’s how you can do that step-by-step:

🔹 Step 1: Navigate to the Project Directory
First, open your terminal and move into the folder where the cloned project lives. For example:

```bash

cd Documents/Playwright/your-playwright-repo
```
Make sure you’re inside the root of the Playwright project where the package.json and playwright.config.ts files are located.

🔹 Step 2: Install Project Dependencies
Before running any tests, install the required packages listed in the project’s package.json:

```bash

npm install
```
This command installs all the  dependencies your test project needs

It also sets up the node_modules/ folder

🔹 Step 3: Install Playwright Browsers
Playwright uses its own version of Chromium, Firefox, and WebKit for consistent automation. Install them with:

```bash

npx playwright install
```
This will download the browser binaries and store them locally in the .playwright/ directory.





##  Setting Up Playwright and Running Tests

This section outlines how to install Playwright, set up the environment, and run tests in various modes.

### Install Playwright and Dependencies

Login into VSTS and open the project folder where you have cloned the repo.Using the terminal type the comman below to set up Playwright 

```bash
npm init playwright@latest
```
###  Running Tests
You can run your tests in different modes depending on whether you're debugging locally or running in CI (Continuous Integration).

#### Run all tests in headless mode (default)
```bash

npx playwright test
```

#### Run tests in headed mode (browser visible)
```bash

npx playwright test --headed
````


#### Run a single test file

```bash

npx playwright test tests/example.spec.js
```


#### Run tests using the Playwright Test UI

```bash

npx playwright test --ui
```


#### View the HTML test report
After running tests, Opens a full HTML report with test results, screenshots, and video recordings (if enabled).

```bash

npx playwright show-report
```


### Step 3: Customize Test Settings 
You can modify the playwright.config.js file to set global options like timeouts, retries, headless mode, screenshots, and more.


## Working with Git hub 




