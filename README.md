# Google Cloud 4 Words

A project to work with Google Cloud services using concise commands or "4-word" instructions. This repository is designed to simplify Google Cloud management and automation by leveraging short, clear command structures.

## Features

- **Execute** Google Cloud operations with simple commands
- **Configure** various Google Cloud resources easily
- **Secure** your cloud assets and automate best practices
- **Manage** resources, permissions, and deployments efficiently
- **Find and Fix** duplicate code issues (work in progress)
- **Error Handling** for robust and reliable operations
- **Vulnerability Hiding** to help protect sensitive code

## Getting Started

### Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
- Proper authentication set up with `gcloud auth login`

### Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/nodoubtz/google-cloud-4-words.git
   cd google-cloud-4-words
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables** as needed for your Google Cloud project.

### Usage

- Run the main script:
  ```bash
  python main.py
  ```

- Provide your 4-word Google Cloud command as input.
  - For example: `create vm instance fast`
  - The script will interpret and execute the corresponding Google Cloud operation.

### Example Commands

- `deploy cloud function quick`
- `secure bucket make private`
- `find duplicate codes fix`
- `list compute engine instances`

## Project Structure

```
google-cloud-4-words/
├── main.py
├── requirements.txt
├── modules/
│   ├── config.py
│   ├── executor.py
│   └── ...
├── utils/
│   ├── duplicate_finder.py
│   └── error_handler.py
└── README.md
```

## Contributing

Contributions, issues, and feature requests are welcome!  
Please open an issue to discuss improvements or report bugs.

## Security

- Sensitive code and secrets should not be committed.
- Vulnerabilities are actively hidden and mitigated in this project.
- Follow Google Cloud security best practices.

## License

[MIT License](LICENSE)

---

**Pay me for projects:**  
If you need custom Google Cloud automation or consulting, please contact [nodoubtz](mailto:nodoubtz@gmail.com).
