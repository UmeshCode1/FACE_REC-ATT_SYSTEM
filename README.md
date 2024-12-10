# FACE_REC-ATT_SYSTEM

## Introduction
FACE_REC-ATT_SYSTEM is a facial recognition-based attendance system designed to streamline the process of tracking attendance using facial recognition technology.

## Features
- Real-time facial recognition
- Secure and efficient attendance recording
- User-friendly interface
- Support for multiple users

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/UmeshCode1/FACE_REC-ATT_SYSTEM.git
    cd FACE_REC-ATT_SYSTEM
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the application:
    ```bash
    python main.py
    ```
2. Follow the on-screen instructions to register users and mark attendance.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Graph Example
Here is a sample graph showing attendance data using matplotlib:

```python
import matplotlib.pyplot as plt

# Sample data
names = ['Alice', 'Bob', 'Charlie', 'David']
attendance = [20, 15, 30, 25]

plt.figure(figsize=(10, 5))
plt.bar(names, attendance, color='blue')
plt.xlabel('Names')
plt.ylabel('Attendance Count')
plt.title('Attendance Graph')
plt.show()
