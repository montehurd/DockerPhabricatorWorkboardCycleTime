
Based on repo from [Flask Debugging in VS Code with Hot-Reload 🔥](https://blog.theodo.com/2020/05/debug-flask-vscode/).

## 🔧 Prerequisites

- **VS Code**
- **Docker**
- **Docker Compose**
- The [**VS Code Python extension**](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

## 🎉 Getting Started

- Install the requirements
    ```bash
    make install
    ```
- Run the app with `make` command :
  - Using `flask` runner
    - Server with Hot-Reloading
      ```bash
      make flask
      ```
    - Server with Debugger and Hot-Reloading
      ```bash
      make flaskdebug
      ```
  - Using `gunicorn` runner
    - Server with Hot-Reloading
      ```bash
      make gunicorn
      ```
    - Server with Debugger and Hot-Reloading
      ```bash
      make gunicorndebug
      ```
- Run the app with `VSCode Tasks`

    ```bash
    Press simultaniously CTRL + ALT + T and you will get a popup widow were you can choose your option 
    ```