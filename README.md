# Generating Generators Demo!

This is a demo project for [gengen - the generator-generator][gengen].

For documentation see [gengen][gengen].

## Usage

```shell
# Clone the project
git clone https://github.com/tmr232/gengen-demo

cd gengen-demo

# Download dependencies
go mod tidy 

# Run go-generate to generate the generator implementation
go generate -tags gengen

# Run the package to see the results
go run .
```

[gengen]: https://github.com/tmr232/gengen