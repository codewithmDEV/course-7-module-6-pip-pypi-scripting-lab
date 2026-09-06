# Pip, PyPI & Scripting Automation Lab

## Description
A small collection of standalone Python scripts demonstrating package management, file I/O, and API consumption — the fundamentals of scripting automation.

## Scripts

### lib/generate_log.py
`generate_log(data)` takes a list of log entries, validates the input, and writes each entry to a date-stamped file (`log_YYYYMMDD.txt`). Raises a `ValueError` if the input isn't a list. Returns the generated filename.

### lib/fetch_data.py
Uses the `requests` library to fetch a post from the JSONPlaceholder public API and prints its title. Wrapped in `if __name__ == "__main__":` for standalone execution.

## Setup
\`\`\`
pip install -r requirements.txt
\`\`\`

## Running
\`\`\`
python lib/generate_log.py
python lib/fetch_data.py
\`\`\`

## Running Tests
\`\`\`
pytest testing/test_generate_log.py
\`\`\`
