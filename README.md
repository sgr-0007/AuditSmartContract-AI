
# AuditSmartContract CLI

## Overview

AuditSmartContract CLI is a command-line tool designed to audit smart contracts using OpenAI's GPT-based models. The tool analyzes smart contracts for security, performance, and other key aspects to help developers and auditors improve the quality of their smart contract code.

## Features

- Analyzes smart contracts using OpenAI's GPT models
- Provides audit reports, metric scores, and suggestions for improvement
- Easy-to-use CLI interface

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your local machine
- An OpenAI API key to interact with OpenAI models

## Installation

To install the tool locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/sgr-0007/auditsmartcontract-cli.git
    ```

2. Navigate to the project directory:

    ```bash
    cd auditsmartcontract-cli
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Link the CLI tool globally:

    ```bash
    npm link
    ```

## Usage

### Basic Commands

- To check and analyze a smart contract, run:

    ```bash
    auditai check <path_to_contract_file>
    ```

- You will be prompted to enter your OpenAI API key.

Example usage:

```bash
auditai check ./contracts/test.sol
```

## API Key

You will need an OpenAI API key to use this tool. If you don’t have one, sign up at [OpenAI](https://beta.openai.com/signup/).

When you run the tool, it will prompt you to enter the API key, which will be used to analyze the smart contract.

## Example Output

The tool provides the following information:

1. **Audit Report**: A detailed audit report covering security, performance, and other relevant aspects.
2. **Metric Scores**: Key metrics such as security, performance, gas efficiency, code quality, and documentation, each rated between 0-10.
3. **Suggestions for Improvement**: Actionable suggestions to improve the contract’s security, performance, and other weaknesses.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

If you want to contribute to the project, feel free to create a pull request, or reach out via issues.
