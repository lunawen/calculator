[![Board Status](https://dev.azure.com/xinw0085/6319b3dd-1d92-49de-8a77-03f038a38b3a/00d941b4-3c7e-4978-868b-728e988300e8/_apis/work/boardbadge/bb3598d2-edd6-4461-94b1-d953d2d34e6c)](https://dev.azure.com/xinw0085/6319b3dd-1d92-49de-8a77-03f038a38b3a/_boards/board/t/00d941b4-3c7e-4978-868b-728e988300e8/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/xinw0085/Parts%20Unlimited/_apis/build/status/lunawen.calculator?branchName=master)](https://dev.azure.com/xinw0085/Parts%20Unlimited/_build/latest?definitionId=5&branchName=master)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

