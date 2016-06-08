# cli-parser
Uses DFA to validate/parse a "command string"

# How it works
 - Create a cli-parser object
 - Specify the DFA table file
 - use .validate(<string>) to check if <string> is valid
 - use .parse(<string>) to validate and fetch list of corresponding numbers for keywords
