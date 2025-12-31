# **Docker Compose to Shell Converter**

A sleek, client-side web application that converts docker-compose.yml configurations into standalone shell scripts using standard docker run commands.

## **🚀 Features**

* **Instant Conversion**: Paste your YAML and get a bash script immediately.  
* **Syntax Highlighting**: Built-in highlighting for both YAML and Bash using Prism.js.  
* **Smart Mapping**: Automatically maps ports, volumes, environment variables, networks, and restart policies.  
* **Modern UI**: Clean, dark-themed interface built with Tailwind CSS.  
* **Clipboard Support**: One-click copying of the generated script.  
* **No Backend Required**: Runs entirely in the browser using js-yaml.

## **🛠️ Built With**

* **HTML5/CSS3**  
* **JavaScript (Vanilla)**  
* **Tailwind CSS**: For responsive, modern styling.  
* **JS-YAML**: For robust parsing of Docker Compose files.  
* **Prism.js**: For beautiful code syntax highlighting.

## **📖 How to Use**

1. Open converter.html in any modern web browser.  
2. Paste your docker-compose.yml content into the left editor.  
3. Click **Generate Script**.  
4. Copy the resulting bash script from the right panel.  
5. Save the output as a .sh file and run it with bash your-script.sh.

## **📄 License**

This project is open-source and available under the [MIT License](https://github.com/faytranevozter/docker-compose-converter/tree/main?tab=MIT-1-ov-file).
