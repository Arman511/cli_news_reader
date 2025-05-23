# CLI News Reader

CLI News Reader is a command-line application written in Rust that allows users to fetch news articles directly from their terminal. It leverages my `newsapi` crate to interact with the News API and provides a simple and customizable interface for consuming news.

## Features

-   Fetch the latest news articles from various sources.
-   Lightweight and fast.

## Installation

1. Ensure you have [Rust](https://www.rust-lang.org/tools/install) installed on your system.
2. Clone this repository:
    ```bash
    git clone https://github.com/your-username/cli_news_reader.git
    cd cli_news_reader
    ```
3. Build the project using Cargo:
    ```bash
    cargo build --release
    ```
4. Run the binary:
    ```bash
    ./target/release/cli_news_reader
    ```

## Usage

Run the application with the following command:

```bash
./cli_news_reader
```

You can customize the behavior of the application by editing the configuration in `theme.rs` or by passing command-line arguments (if implemented).

## Project Structure

-   `src/main.rs`: Entry point of the application.
-   `src/theme.rs`: Handles terminal theme customization.
-   `newsapi/`: Contains the `newsapi` crate for interacting with the News API.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

-   [News API](https://newsapi.org/) for providing the news data.
