# AWS DynamoDB To-Do Project in C

This is a simple **AWS DynamoDB To-Do project** written in **C**. It demonstrates how to structure a request payload for DynamoDB using the AWS C SDK and simulates sending a task to a DynamoDB table.

> 🚀 This project is a simulation and does not perform actual API requests. It’s designed for learning purposes and understanding AWS SDK usage in C.

## 📂 Project Structure

AwsDynamoTodo/
├── main.c
└── README.md


## 🔧 Prerequisites

- Visual Studio with "Desktop development with C++" workload installed  
- AWS C SDK libraries (optional if running as a simulation)  
- A basic understanding of C programming  

## 📖 Features

- Initializes the AWS SDK libraries  
- Prepares a sample JSON payload for DynamoDB’s `PutItem` operation  
- Prints the payload to the console  
- Simulates adding a task to the DynamoDB table  

## 🚀 How to Run

1. Clone or download this repository.  
2. Open the project in Visual Studio.  
3. Add `main.c` to the project.  
4. Build and run the application.

### Using GCC (optional):

```bash
gcc main.c -o AwsDynamoTodo
./AwsDynamoTodo
