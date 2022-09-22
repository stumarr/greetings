## Go Tutorial from https://go.dev/doc/tutorial/create-module

A module is a collection of Go packages stored in a file tree with a go.mod file at its root. The go.mod file defines the module’s module path, which is also the import path used for the root directory, and its dependency requirements, which are the other modules needed for a successful build. Each dependency requirement is written as a module path and a specific semantic version.

In this tutorial you'll create two modules. The first is a library which is intended to be imported by other libraries or applications. The second is a caller application which will use the first.