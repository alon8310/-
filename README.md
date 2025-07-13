video link https://drive.google.com/file/d/1a0dRraF1caNWnsypQ5Qbg5lNkBrbC98O/view?usp=sharing

# Advanced Programming Final Project – Reactive Computation Graph
wroten by alon levi and ziv ossi 13.7.25
## 🧠 Background

This project simulates a simple reactive computation system using a message-passing model. 

Each **Agent** listens to one or more **Topics**, performs a computation (e.g. addition, multiplication), and publishes the result to another Topic. The flow of information is defined by a configuration file.

The system runs on a **custom HTTP server**, which provides a web interface to:
- Load an agent configuration from a file.
- Send messages to a specific topic.
- View the current state of all topics.
- See a graphical representation of the computation graph.

The design follows a clear MVC-style separation:
- **Model**: Agents, Topics, Messages
- **Controller**: HTTP Servlets (e.g. `/upload`, `/publish`)
- **View**: Dynamic HTML pages with tables and graphs

---

## 🛠️ Installation

To compile and run the project:

1. Open the project folder (e.g. `tar6`) in Eclipse or any IDE that supports Java 17+.
2. Make sure the folder structure contains:
   - `project_biu/` with all `.java` files
   - `web/` folder with HTML files (e.g. `from.html`, `temp.html`)
3. Make sure JDK 17+ is installed and configured in your system.
 ## ▶️ Run Instructions
 1.import the zip file
 2.click run
 3.copy the https address and paste it on browser.
 4.upload a config file (we added complete conf file in configs_files folder
 5.try to play with the website and see what happens :)

link to javadoc
[docs.zip](https://github.com/user-attachments/files/21204821/docs.zip)

מטלה בתכנות מתקדם
