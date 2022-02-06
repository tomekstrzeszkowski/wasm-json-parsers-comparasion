# enigma-stats

## installation

This project requires environmnents for: 
 - Go
 - nodejs/yarn
 
### frontend installation

Go to the (you can use --cwd as well)

`cd cmd/server/front`

And run installation 

`yarn`

### server installation

Go to the location

`cd cmd/server/`

And run

`go build`

### go wasm app installation

Go to the location

`cd cmd/wasm`

And follow the installation chapter in the README.md file 

## Running project

Build frontend app using this command:

`yarn build`

As a result a new file should be created in `assets/dist/`

Now run the server:

`cd cmd/server`

`./server`

### Screenshot

![image](https://user-images.githubusercontent.com/40120335/152691314-9325925c-e6b3-4f11-ba39-002c9150571b.png)
