# FinanceManager - finman

     _____   ___   _   _   __  __      _      _   _ 
    |  ___| |_ _| | \ | | |  \/  |    / \    | \ | |
    | |_     | |  |  \| | | |\/| |   / _ \   |  \| |
    |  _|    | |  | |\  | | |  | |  / ___ \  | |\  |
    |_|     |___| |_| \_| |_|  |_| /_/   \_\ |_| \_|

# Personal Finance Managing CLI Application

This project is a CLI application for managing personal finances. It includes features for tracking income, expenses, and overall balance.

## Installation

#### **Highly recommanded to use pipx for installation to avoid dependency conflicts**

```bash
pipx install finman
```

You can install it a traditional way using pip or by clining repository 
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using `python main.py`.

you can use it using finman command
## Usage

Manage your financial records with FINMAN 
- Monitor your balance, total income and expense
```bash
finman balance # Returns budget data 
```
- Add a record specifying the amount of money and category (Income / Expense)
```bash
finman add -a '500' -c - -m Fruits # Adds and 500 expense for Freuits 
```
- Edit an existing saved records
```bash
finman edit --id 687sdf7 # Starts editing Record with ID 687sdf7
```
- List all records or find a spicific one by adding filters 
```bash
finman list # Lists all records
finman list --income 200 # Lists all incomes with amount 200
```

### For more Information about each command, see 
```bash
finman [command] --help
```

## Author
- Idris Taha
- Email: dri.taha24@gmail.com
- Telegram: @idristaha
## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
