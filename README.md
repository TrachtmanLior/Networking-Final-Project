# QUIC - Final Project
***Computer Networking (Communication Networks) @ Ariel University***

This project consists of a set of Python scripts designed to demonstrate a server-client architecture with functionality for data generation, API integration, and unit testing. Below is a comprehensive breakdown of each file in the assignment and its purpose.

---

## File Descriptions

### 1. `server.py`

- **Purpose:** Implements the server-side logic for handling client requests and managing the communication protocol.
- **Key Features:**
  - Listens for incoming client connections.
  - Processes requests and responds with appropriate data.
  - Ensures proper communication flow between server and client.

### 2. `main.py`

- **Purpose:** Serves as the entry point for running the application.
- **Key Features:**
  - Orchestrates interactions between different components such as the server, data generator, and API.
  - Provides an interface to start the server and test its functionality.

### 3. `data_generator.py`

- **Purpose:** Generates test data for use in server-client communication and other processes.
- **Key Features:**
  - Creates mock data to simulate real-world inputs.
  - Can be extended to support various data formats and structures.

### 4. `api.py`

- **Purpose:** Contains API-related functions to extend the server's capabilities.
- **Key Features:**
  - Handles external API calls and responses.
  - Acts as a bridge between the server and external services.

### 5. `client.py`

- **Purpose:** Implements the client-side logic to interact with the server.
- **Key Features:**
  - Sends requests to the server.
  - Receives and processes responses.

### 6. `UnitTesting.py`

- **Purpose:** Contains unit tests for the various components of the project.
- **Key Features:**
  - Validates the functionality of individual modules.
  - Ensures code reliability and correctness through automated tests.

### 7. `README.pdf`

- **Purpose:** Provides an overview and instructions for using the project.
- **Key Features:**
  - Details setup instructions, usage examples, and project structure.
  - Acts as a reference document for users.

---

## Setup Instructions

1. **Environment Setup:**

   - Install Python (version 3.7 or higher).
   - Ensure the required Python libraries are installed (refer to `requirements.txt` if provided).

2. **Running the Server:**

   - Execute `server.py` using the command:
     ```bash
     python server.py
     ```

3. **Running the Client:**

   - Start the client using:
     ```bash
     python client.py
     ```

4. **Generating Data:**

   - Generate test data by running:
     ```bash
     python data_generator.py
     ```

5. **Unit Tests:**

   - Run the tests using:
     ```bash
     python UnitTesting.py
     ```

---

## Usage Examples

### Example 1: Server-Client Interaction

1. Start the server using `server.py`.
2. Run the client script `client.py` to send requests.
3. Observe the communication between the server and the client in the console.

### Example 2: Data Generation

1. Run `data_generator.py` to create mock data.
2. Verify the generated data in the specified output location.

### Example 3: API Calls

1. Use the functions in `api.py` to fetch data from external services.
2. Integrate these API responses into the server's workflow.

---

For additional details, refer to the `README.pdf` provided in the project.


[Wireshark recordings](https://drive.google.com/file/d/1EXYuANiR3pqC6cdIF-t0JYZJJLrRIqF-/view?usp=sharing)

[README pdf (HE)](README.pdf)

[Assignment (HE)](ASSIGNMENT.pdf)

