# init go module
```
go mod init example/hello
```

# create main.go
```
package main

import "fmt"

func main() {
	fmt.Println("Hello, World!")
}
```

# commit to git
```
git config --global --add safe.directory /workspaces/devcontainer-demo
git init
git add -A
git commit -m "first commit"
git checkout -b main
git remote add origin https://github.com/robwafle/demo-devcontainer.git
git push -u origin main
```