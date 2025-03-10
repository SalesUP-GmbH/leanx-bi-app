# leanx-bi-app
Codebase for the LeanX BI Module offering Business Intelligence capabilities.


## Technologies Used

* **Application:** Python, Flask
* **Database:** MongoDB (Data Warehouse)
* **Other:** Docker, GitHub Actions, AWS

## Getting Started

### Prerequisites

* Python 3.7 or higher
* MongoDB
* Docker (optional, for deployment)

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/SalesUP-GmbH/leanx-bi-app.git
    ```

2.  Create a virtual environment:

    ```bash
    python3 -m venv venv
    ```

3.  Activate the virtual environment:

    * **macOS/Linux:**

        ```bash
        source venv/bin/activate
        ```

    * **Windows (Command Prompt):**

        ```bash
        venv\Scripts\activate
        ```

    * **Windows (PowerShell):**

        ```bash
        venv\Scripts\Activate.ps1
        ```

4.  Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5.  Configure the database:

    * Create a MySQL database for the application.
    * Update the database connection details in `config.py`.

6.  Run the application:

    ```bash
    python run.py
    ```

## Deployment

* **Docker:**
    * Build the Docker image:

        ```bash
        docker build -t leanx-bi-app .
        ```

    * Run the Docker container:

        ```bash
        docker run -p 5000:5000 leanx-bi-app
        ```

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

