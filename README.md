# CLI Uptimer ⏱️

CLI-Uptimer is a simple Go CLI tool that periodically checks the availability of specified websites and prints their status. Perfect for keeping an eye on your favorite sites! 🕵️‍♀️

## Features 🌟
- **Automated checks**: Continuously checks websites at configurable intervals.
- **Status reporting**: Prints out if sites are up or down with their respective HTTP status codes.
- **Easy setup**: Simply edit the code to adjust sites, acceptable status codes, and frequencies.

## Getting Started 🚀
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/cli-uptimer.git
   cd cli-uptimer
   ```
   
2. **Build the binary**:
   ```bash
   make build
   ```
   
3. **Run the tool**:
   ```bash
   make run
   ```
   
4. **Check output**:  
   You will see output like:
   ```
   https://google.com is up with status code of 200
   https://go.dev is up with status code of 200
   http://localhost.cs is down with status code of 0
   ```
   
## Customization ✨
- Update the `sites` slice in `main.go` to add/remove websites, change acceptable status codes, and tweak frequencies.
- Rebuild and run again to see the changes reflected.

## License 📜
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.