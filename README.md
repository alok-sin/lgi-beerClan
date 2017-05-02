# Moses
The implementation of LGI

## How to start a controller?
`java -cp libs/*:Moses.jar Moses`, with necessary arguments.

## How to start an interactive agent for testing?
`java -cp libs/*:Moses.jar InteractiveAgent`, with necessary arguments.

For instance:

`java -cp libs/*:Moses.jar InteractiveAgent 127.0.0.1 9000 ./pingpong.law foo {}`

If no argument is provided, the help message will be displayed.