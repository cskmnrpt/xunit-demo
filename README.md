# qase-robotframework

This is an example repository with tests in the `tests/examples/` directory. To run the tests :

1. Clone the repository with `git clone https://github.com/cskmnrpt/xunit-demo.git`.
   To clone a different branch, other than `main`, use this command - <br> `git clone --single-branch --branch <branch-name> https://github.com/cskmnrpt/xunit-demo.git`

2. Run `dotnet restore` to install the dependencies.

3. Create a `qase.config.json` in the root of the repository, and add your token, and project code.

4. Run `QASE_MODE=testops dotnet test`
