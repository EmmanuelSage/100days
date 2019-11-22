# Day 1

For day one of this challenge, I spent most of my time thinking and sorting out what it is I want to do for the next 100 days as it relates to code.

The next few days might not be organized as much but I will try to sort it out as I progress.

Today we would be learning the basics of Go

## Crash intro to go

### installation 

- Download go from https://golang.org and install

- Type `$ go version` in terminal to ensure its installed

Or you could use the playground at https://play.golang.org

### workspace

Go has a folder structure 
```
  go (Workspace)        
    -bin
    -src
        -github.com            # for github code
            -EmmanuelSage    # github username
                -project_1
                    #files
                -project_2
                    #files
    -pkg                     #Packages are installed here

```
- run `$ go env` or `$ go env GOPATH`

- if you check the path variable the GOPATH points to your home directory create the go folder for that path

- Create the folder structure as described above

- install go extension if you are using vscode

- `$go get githuburl`


### Hello world

- create a main.go file its just like an index.js file in javascript and serves as an entry file

