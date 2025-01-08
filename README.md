# API Booker K6 Performance Testing

This repository contains a K6 performance testing script for the RESTful Booker API. The tests are designed to be run in a CircleCI pipeline.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [K6](https://k6.io/)
- [CircleCI CLI](https://circleci.com/docs/2.0/local-cli/)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/api-booker-k6-performance.git
    cd api-booker-k6-performance
    ```


## Running Tests Locally

To run the K6 performance tests locally, use the following command:
```sh
k6 run script.js
```

## CircleCI Configuration

The CircleCI configuration file (`.circleci/config.yml`) is set up to run the K6 performance tests in the CI pipeline.



## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.