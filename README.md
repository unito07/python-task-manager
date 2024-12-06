# Python Task Manager

A simple command-line task manager demonstrating Python project structure and GitHub features.

## Features
- Add, list, update, and delete tasks
- Mark tasks as complete
- Save tasks to a JSON file
- Command-line interface

## Installation
```bash
git clone https://github.com/unito07/python-task-manager.git
cd python-task-manager
pip install -r requirements.txt
```

## Usage
```bash
python -m taskmanager.cli
```

## Project Structure
```
python-task-manager/
├── taskmanager/          # Main package directory
│   ├── __init__.py      # Package initialization
│   ├── cli.py           # Command line interface
│   └── manager.py       # Core task management logic
├── tests/               # Test directory
│   └── test_manager.py  # Tests for task manager
├── README.md            # Project documentation
└── requirements.txt     # Project dependencies
```

## Contributing
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License
MIT License