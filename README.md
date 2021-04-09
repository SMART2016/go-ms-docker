# go-ms-docker

    1) Go to GitHub and login or sign up.
    2) Create a new repository.
    3) Use the Clone or download button to get your repo locally
        - cd to your work folder
        - git clone <repository-url>.git
    4) Initialize the repository:
        $ mkdir src
        $ cd src
        //https://golang.org/ref/mod#build-commands
        $ export GOFLAGS=-mod=vendor
        $ export GO111MODULE=on
        //Go Modules: https://blog.golang.org/using-go-modules
        $ go mod init github.com/YOUR_GITHUB_USER/YOUR_REPOSITORY_NAME 
        # (example: go mod init github.com/smart2016/go-ms-docker)


    5) Implement the View and conf packages for the config and the views
    6) Implement the  main.go for the application logic
    7) Install the  dependencies for the  go application:
        $ go mod download
        $ sudo go mod vendor
        $ sudo go mod verify