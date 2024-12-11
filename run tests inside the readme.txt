Testing Cloud-Based POS Features :

Setup
Install required dependencies:
bash

npm install
Run the application in a test environment. Use mock APIs to simulate offline and online modes.
Running Tests
Run All Tests:

bash

npm test
Simulate Offline Mode:
Use the following to simulate offline scenarios:

bash

export OFFLINE_MODE=true
npm test
Sync and Validate:
After running offline tests, ensure data syncs correctly by returning to online mode:

bash

export OFFLINE_MODE=false
npm test