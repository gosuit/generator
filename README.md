# Generator

Generator provides functions for generating random numbers and secret keys.

## Installation

```zsh
go get github.com/gosuit/generator
```

## Features

- **Random Number Generation**: Create a string of random numbers of a specified length.
- **Secret Key Generation**: Generate a secure secret key of a specified length.

## Usage

```golang
import "github.com/gosuit/generator"

func main() {
    randomNum := generator.GetRandomNum(10)

    secretKey, err := generator.GetSecret(32)
}
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
