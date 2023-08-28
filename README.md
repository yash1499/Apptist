# Apptist

## Tools Required
- **Git:** Installation guide
- **Node:** Installation guide
- **AWS Amplify:** Installation guide

## Step 1: Cloning the Repository
1. Clone the repository: `git clone https://github.com/Nisarg851/ApptistV2.git`
2. Navigate to the project directory: `cd ApptistV2`

## Step 2: Linking Backend Infrastructure
1. Run the following command to link the backend infrastructure to the local environment:
amplify pull --appId d3cwba7tcuiu9n --envName dev


## Step 3: Answering App-Env Questions
1. When prompted with questions about app-env, choose the following answers highlighted in blue.

## Step 4: Pulling Changes and Meta-Data
1. Run the following command to pull changes and meta-data about infrastructure from the cloud to the local environment:
amplify pull


## Step 5: Installing Dependencies and Starting Dev Server
1. Run the following commands to install all the development dependencies and start the development server:
npm install
npm start

If prompted by a request for webpack-cli installation, type 'yes' and run `npm start` again.

Note: Ignore the "MODULE NOT FOUND" error for "webpack-dev-server.js"; this module isn't required now and will be removed in the next patch.

If everything is correct, you should see the following response:
"Before checking the website, make sure the build is complete."

After the build is complete, you can browse the website at [http://localhost:3002/](http://localhost:3002/). For the sake of development, URLs are directly accessible, so the app's flow might work as expected. All completed pages can be accessed through the following paths:
- Home Page: [http://localhost:3002/](http://localhost:3002/)
- Login Page: [http://localhost:3002/login](http://localhost:3002/login)
- Verification Code Page: [http://localhost:3002/login/verify-code](http://localhost:3002/login/verify-code)
- Registration Page: [http://localhost:3002/register](http://localhost:3002/register)
- Instructor Dashboard Page: [http://localhost:3002/instructor-dashboard](http://localhost:3002/instructor-dashboard)
- Student Edit Profile Page: [http://localhost:3002/setting-edit-profile](http://localhost:3002/setting-edit-profile)
