**This project is a client-server application developed using Java, utilizing the Open Client-Server Framework (OCSF) to manage communication between the client and server. It includes various components such as the client-side application, server-side setup, and the integration of OCSF for efficient message handling. The project also features logging capabilities and data management with an SQL database. It is designed to handle dynamic client-server interactions with robust error handling and communication protocols. The application can be extended for multiple use cases in distributed systems, with the ability to support a wide range of client-server interactions.**

Key features:

Client-side application for interaction with the server.

Server-side application to process client requests and manage data.

OCSF integration for managing communication protocols.

Logging to track server events and client interactions.

SQL-based data storage for persistent data management.

**To Run The Project:**
**Client-Server Application Setup and Execution
Prerequisites**
Ensure the following software is installed:

Java Development Kit (JDK) 8 or above

Maven

Step 1: Clone the Repository
Clone the repository to your local machine:

bash
Copy
git clone <repository-url>
Step 2: Build the Project
Navigate to the server directory where the pom.xml file is located:

bash
Copy
cd /path/to/G6_Assignment3-Project/server
Build the project using Maven:

bash
Copy
mvn clean install
Step 3: Run the Server
Once the build is complete, run the server:

bash
Copy
mvn exec:java -Dexec.mainClass="com.example.ServerMainClass"
Replace com.example.ServerMainClass with the actual main class if different.

Step 4: Run the Client
Open a new terminal window and navigate to the client directory:

bash
Copy
cd /path/to/G6_Assignment3-Project/client
Run the client application:

bash
Copy
mvn exec:java -Dexec.mainClass="com.example.ClientMainClass"
Replace com.example.ClientMainClass with the correct main class for the client if needed.

Step 5: Check Logs and Interaction
The server will start and wait for client connections.

The client will interact with the server.

Logs are available in the DECEMBER2024.log and JANUARY2025.log files for tracking activity.
