# Bigquery, Pandas, GoogleSheets test task

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Conclusion](#conclusion)

## Installation

1. Clone the repository:

    ```bash
    https://github.com/YKonoplyov/bigquery-pydantic-test-task.git
    ```

2. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source venv/bin/activate
        ```

4. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Obtain Google Cloud API credentials:

    - Follow the instructions [here](https://gspread.readthedocs.io/en/latest/oauth2.html) to create a service account and download the JSON key file.

7. Place the where you need it.

8. Create `.env` file following `.env.example`


## Dependencies

- aiohttp
- gspread
- gspread_asyncio
- tqdm_asyncio
- Pillow (PIL)

## Conclusion
This project successfully fetches data from BigQuery, processes it using Pandas, and updates Google Sheets. The asynchronous nature of the code is facilitated by the asyncio and gspread_asyncio libraries. 
### Execution time ~6 minutes.
### [Sheet](https://docs.google.com/spreadsheets/d/1gkBvCLKLbYHOjaRUb_3tOvnUuOvl7BHYmBTcnfCH6Jg/edit?usp=sharing)
