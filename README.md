# ots-generate-password
This script is for generating passwords and creating onetime links for a secure password exchange.
You can define a password by yourself and hand it over to the script or let the script generate one.
This also works with a list of usernames and passwords in a file. 
The file should use the following format:

- no line for a header
- use "TAB" as delimeter
- Usernames must be defined in the first column
- Passwords are optional, but must be definded in the second column

## Dependencies
Beside awk and sed, you should also have curl and jq installed. This tools are use to work
with the api and the output.

## Planned Features
nothing yet

## Bugreport
Please use the issue function or merge requests, if you find a nasty bug.

## Featurerequest 
Therefore you can also use the issue function.
