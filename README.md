# goswagger-tutorials

### Links

[Simple Server · GitBook](https://goswagger.io/tutorial/todo-list.html)

### Installing goswagger

OSX
```
brew tap go-swagger/go-swagger
brew install go-swagger
```

Linux
```
echo "deb https://dl.bintray.com/go-swagger/goswagger-debian ubuntu main" | sudo tee -a /etc/apt/sources.list
```

### Tutorial highlights

Initialize a blank swagger.yml
```
swagger init spec \
  --title "A Todo list application" \
  --description "From the todo list tutorial on goswagger.io" \
  --version 1.0.0 \
  --scheme http \
  --consumes application/io.goswagger.examples.todo-list.v1+json \
  --produces application/io.goswagger.examples.todo-list.v1+json
```
