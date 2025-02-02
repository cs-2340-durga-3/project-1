# GT Movies

TA: Durga Pranati Duvvuri \
Meeting times: Friday 3:00pm (Online)

## Installation

1. Create a virtual environemnt

    ```sh
    python -m venv .venv
    ```

2. Activate virtual environment \
    a. Windows

    > [!TIP]
    > Note On Microsoft Windows, it may be required to enable the Activate.ps1 script by setting the execution policy for the user. You can do this by issuing the following PowerShell command: \
    > `PS C:\> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser` \
    > See [About Execution Policies](https://learn.microsoft.com/en-sg/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.5) for more information.

    ```powershell
    . .venv\Scripts\Activate.ps1
    ```

    b. POSIX (zsh/bash)

    ```sh
    source .venv/bin/activate
    ```

3. Install required packages
    ```sh
    pip install -r requirements.txt
    ```

4. Run development server
    ```sh
    python manage.py runserver
    ```
