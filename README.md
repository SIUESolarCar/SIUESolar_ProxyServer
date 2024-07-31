# Introduction
This repository holds the Docker Compose for the team's Proxy Service.

# Setup

1.  Create a file called `.env` in your project directory and paste the following code in:

    ``` 
    Admin_Port=81
    ```

2. Modify the `.env` file to your use case. 

> [!CAUTION]
> Use secure passwords!! These services can be accessed on the open internet. Be Smart

3. Run the Docker Compose in the terminal.

    ```
    $ docker compose up