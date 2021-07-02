# code-export-browserstack-mocha

This project is a fork of the [code-export-javascript-mocha](https://github.com/SeleniumHQ/selenium-ide/tree/v3/packages/code-export-javascript-mocha).
It adds to the exporter a little extra cheese to make the integration with browserstack better. 
The exported code should:
- carry the name of the test through the selenium capabilities and update the browserstack session name accordingly. 
- update the test session status in the browserstack dashboard

This code exporter can be used through the [browserstack-side-runner](https://github.com/mattonem/browserstack-side-runner) to run `.side` files on against the browserstack grid. 
