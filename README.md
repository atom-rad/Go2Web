# Go2Web
CLI internet search application.

# Usage
To test the application, follow these steps:

#### Install Dependencies:
* Ensure all necessary packages are installed from requirements.txt:
    ```
    pip install -r requirements.txt
    ```

#### Create Executable:
* Generate the executable of the script using PyInstaller:
    ```
    pyinstaller --onefile go2web.py
    ```

#### Run the Executable:
* The executable will be located in the dist folder. You can run it with the following commands:
    ```
    go2web -u <URL> # make an HTTP request to the specified URL and print the response
    go2web -s <search-term> # make an HTTP request to google search the term or multiple terms and print top 10 results
    go2web -h # show this help
    ```

# Demo
![demo](https://private-user-images.githubusercontent.com/113429347/344013743-325230bf-788c-484b-89a7-7dd4cd5b1ba9.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTk1NDQwNDQsIm5iZiI6MTcxOTU0Mzc0NCwicGF0aCI6Ii8xMTM0MjkzNDcvMzQ0MDEzNzQzLTMyNTIzMGJmLTc4OGMtNDg0Yi04OWE3LTdkZDRjZDViMWJhOS5naWY_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNjI4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDYyOFQwMzAyMjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wNDM3YmU4ZmJjZGZlMWNiZDNjZmE4NDgzMDRlZTk4ZGI4MmQwMWNiY2E5ZDk2MmQxMDkwNmUzNmNiOTExNWU3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.jVktleABjL-47LFkT1F2rzJeFsdPvrvb24kNkRvXIIo)
