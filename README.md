## Environment

Node version : >9
npm version: 6.0.0

## Setup

To Start the Project :
1. `npm install`
2. For dev mode : `npm run dev`
3. For production build : `npm run prod`. dist directory will be created.
4. test coverage of unit test cases: `npm run test` 


After starting the project :

1. User will be asked to start the project in either of the two mode:
    a. Read the input from the files : enter `1`
    b. Read the input from the shell command: enter `2`.
2. If user creates the parking lot again it will get merged with previously created lot.
3. Ticket and payment mode details are saved separately in order to generate the reports.
4. If user tries to empty the spot which is already empty, will see an error.
5. If user enters the empty file name will get the error.
6. If user enters the file name which doesn't contains the file will get the error.
7. If user enters the 0 or not a integer value for no. of parking slots, will get the error.
8. User can exit the prompt, by typing exit.
9. User can move to main menu by typing `back`.

## Build

1. `npm install` : to install the packages
2. `npm run dev` : For starting the dev mode.
3. `npm run build`: To create the dist directory. Converting the typescript to javacript of ES5 version.
4. `npm run test`: Running unit test case and checking the test coverage.
4. `npm run prod`:

