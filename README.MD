## Description :
This Project is a webserver that takes a sample of text and returns the ascii art form of that text
it can handle the carriage return \r as well as the newline charactor \n and can be set to standard 
ascii shadow or thinkertoy

## Authors :
Steven - username : Stevenpearson
Nathan - username : Nathan
Helena - username : AthenaHTA2


## Usage :
- step 1 : Goto directory where program is stored in the console
- step 2 : Type `go run main.go`
- step 3 : Goto `127.0.0.1:8080` in your browser
- step 4 : Select a banner and enter the text you want converted you can 
         also press enter or insert a \n to get multiline output
- step 5 : Click submit and check out the result


## Implementation details :
We used the same algorithm as ascii art with a few tweaks mainly to handle the carriage return as well
which was a little different from the newline and we used a pre html tag to display the ascii art output 
because it deals with pre formatted text which made the ascii art easier to show and made the final 
product borderless which we thought looked better
