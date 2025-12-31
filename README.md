# **Docker Compose to CLI Converter**

A sleek, client-side web application that converts docker-compose.yml configurations into standalone shell scripts using standard docker run or docker service create commands.

## **🚀 Features**

* **Multi-Mode Output**: Choose between standard docker run commands or docker service create for Docker Swarm clusters.  
* **Instant Conversion**: Paste your YAML and get a bash script immediately.  
* **Syntax Highlighting**: Built-in highlighting for both YAML and Bash using Prism.js.  
* **Smart Mapping**: Automatically maps ports, volumes, environment variables, networks, and restart policies, adjusting flags based on the selected output mode (e.g., using \--publish and \--mount for services).  
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
3. **Select your output mode** (Run or Service) using the toggle above the generate button.  
4. Click **Generate Script**.  
5. Copy the resulting bash script from the right panel.  
6. Save the output as a .sh file and run it with bash your-script.sh.

## **💻 Local Development**

To run this project locally, simply clone the repository and open the converter.html file in your browser. No local server or build step is required.

```sh
git clone https://github.com/faytranevozter/docker-compose-converter.git 
cd compose-to-shell  
# Open index.html in your browser
```
## **📄 License**

This project is open-source and available under the [MIT License](https://github.com/faytranevozter/docker-compose-converter/tree/main?tab=MIT-1-ov-file).
