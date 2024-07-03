# golicense

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Go Version](https://img.shields.io/badge/go-1.16%2B-blue.svg)

`golicense` is a command-line tool written in Go that makes it easy to add license files to your local projects. It allows you to select from popular open-source licenses and write them directly to your project directory. This tool is designed to streamline the process of managing licenses, making your projects compliant and ready for distribution.

<img width="829" alt="Screenshot 2024-06-29 at 12 22 09 PM" src="https://github.com/ABHIGYAN-MOHANTA/golicense/assets/110360901/3b21b4aa-3334-4f30-8b1d-1ac00bdf4ba7">

## Features

- **Simple Command-Line Interface**: Add licenses with a single command.
- **Multiple License Options**: Choose from popular licenses such as MIT, Apache-2.0, and more.
- **Automatic License File Creation**: Writes the selected license text to a `LICENSE` file in your project directory.
- **Easy Integration**: Suitable for use in build scripts or automated workflows.

## Installation

To install `golicense`, you need to have Go installed. Run the following command:

```bash
go get github.com/abhigyan-mohanta/golicense
go install github.com/abhigyan-mohanta/golicense
```

## Usage

```bash
golicense add --type MIT
```

Replace `MIT` with the desired license type (e.g., `Apache-2.0`, `GPL-3.0`, `BSD-3-Clause`,`MPL-2.0`). This will create a `LICENSE` file in your current directory containing the selected license.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contributing

Contributions are welcome! Fork the repo, make your changes, and submit a pull request. Please ensure your code adheres to the Go standards and includes appropriate tests.

## Issues

If you encounter any problems, please [open an issue](https://github.com/abhigyan-mohanta/golicense/issues) on GitHub.

## Acknowledgments

- Inspired by the need to simplify license management in open-source projects.
- Built with [Go](https://golang.org/).
