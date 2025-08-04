# Cross - skilling 

This repository is part of my personal learning journey as I focus on cross-skilling in automation tools. It was inspired by the QE-led Cross-Skilling initiative and serves as a structured space for me to explore, practice, and deepen my understanding of Playwright.

Here, I’ll be working through various test scenarios and practice exercises as I move through different focus areas and gradually building confidence and expertise in using Playwright. This repository will grow and evolve over time, reflecting both my progress and the skills I’m developing along the way.



## Cloning the Project and Running Playwright Tests Locally
Before you can run Playwright tests, you need to get a copy of the project on your local machine. This means cloning the repository from GitHub and setting up your environment.


### Create a Folder and Clone the Repository
First, choose where you want to keep the project. You can create a folder for your projects like this:

```bash

mkdir Playwright
cd Playwright
```

Now, clone the Playwright test project into that folder using:

```bash
cd playwright
git clone https://github.com/your-username/your-playwright-repo.git
```


After this step, the project will be on your local machine inside the your-playwright-repo folder.


### Install Dependencies
Once you’re inside the project folder, install the required Node.js dependencies:

```bash

npm install
```
This command will:

Create a node_modules/ folder with all required packages

Set up any testing tools or utilities that are already listed in package.json



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




