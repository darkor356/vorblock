first off thank you for trying my program this is a test project that i was thinking to make then i thought might as well do it.

        ██▒   █▓ ▒█████   ██▀███   ▄▄▄▄    ██▓     ▒█████   ▄████▄   ██ ▄█▀
       ▓██░   █▒▒██▒  ██▒▓██ ▒ ██▒▓█████▄ ▓██▒    ▒██▒  ██▒▒██▀ ▀█   ██▄█▒ 
        ▓██  █▒░▒██░  ██▒▓██ ░▄█ ▒▒██▒ ▄██▒██░    ▒██░  ██▒▒▓█    ▄ ▓███▄░ 
         ▒██ █░░▒██   ██░▒██▀▀█▄  ▒██░█▀  ▒██░    ▒██   ██░▒▓▓▄ ▄██▒▓██ █▄ 
          ▒▀█░  ░ ████▓▒░░██▓ ▒██▒░▓█  ▀█▓░██████▒░ ████▓▒░▒ ▓███▀ ░▒██▒ █▄
          ░ ▐░  ░ ▒░▒░▒░ ░ ▒▓ ░▒▓░░▒▓███▀▒░ ▒░▓  ░░ ▒░▒░▒░ ░ ░▒ ▒  ░▒ ▒▒ ▓▒
          ░ ░░    ░ ▒ ▒░   ░▒ ░ ▒░▒░▒   ░ ░ ░ ▒  ░  ░ ▒ ▒░   ░  ▒   ░ ░▒ ▒░
           ░░  ░ ░ ░ ▒    ░░   ░  ░    ░   ░ ░   ░ ░ ░ ▒  ░        ░ ░░ ░ 
            ░      ░ ░     ░      ░          ░  ░    ░ ░  ░ ░      ░  ░   
           ░                           ░                  ░               

---

# Programming Language to Executable Converter

Convert your programming language scripts into standalone Linux executables with ease.

---

## About the Program

This tool transforms scripts written in Python, Ruby, Shell, Go, Java, and C into executable files that run directly on Linux. By leveraging the right compilers and tools, it simplifies the process of script distribution and execution.

---

## How It Works

1. **Select the language**: Choose the language of your source code.
2. **Input your script**: Provide the filename of your script.
3. **Convert to executable**: The tool uses language-specific methods (e.g., `pyinstaller` for Python or `gcc` for C) to generate an executable.
4. **Run the executable**: Use the resulting file on your Linux system.

---

## Supported Languages and Examples

### **1. Python (.py)**

#### **Requirements**
- Install `pyinstaller`:
  ```bash
  pip install pyinstaller
  ```

#### **Example**
If your script is named `hello.py`:
```python
# hello.py
print("Hello, World!")
```

Run the program, select Python, and generate the executable:
```bash
pyinstaller --onefile hello.py
```

---

### **2. Ruby (.rb)**

#### **Requirements**
- Install the `ocra` gem:
  ```bash
  gem install ocra
  ```

#### **Example**
If your script is named `hello.rb`:
```ruby
# hello.rb
puts "Hello, World!"
```

Run the program, select Ruby, and generate the executable:
```bash
ocra hello.rb
```

---

### **3. Shell Scripts (.sh)**

#### **Requirements**
- Linux environment with standard shell utilities.

#### **Example**
If your script is named `hello.sh`:
```bash
#!/bin/bash
echo "Hello, World!"
```

Run the program, select Shell, and package it:
```bash
chmod +x hello.sh
```
Your script is now directly executable.

---

### **4. Go (.go)**

#### **Requirements**
- Install the Go compiler:
  ```bash
  sudo apt install golang
  ```

#### **Example**
If your script is named `hello.go`:
```go
// hello.go
package main
import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

Run the program, select Go, and generate the executable:
```bash
go build hello.go
```

---

### **5. Java (.java)**

#### **Requirements**
- Install Java Development Kit (JDK):
  ```bash
  sudo apt install openjdk-11-jdk
  ```

#### **Example**
If your program is named `HelloWorld.java`:
```java
// HelloWorld.java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Compile and package it:
```bash
javac HelloWorld.java
java HelloWorld
```

---

### **6. C (.c)**

#### **Requirements**
- Install GCC:
  ```bash
  sudo apt install gcc
  ```

#### **Example**
If your code is named `hello.c`:
```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

Run the program, select C, and compile:
```bash
gcc hello.c -o hello
```

---

## How to Use the Converter

1. Download the program:
   ```bash
   curl https://drive.google.com/file/d/11CQ_eMDGFNCQxWVQou0VA6Mv7ucP3SlE/view?usp=drive_link
   ```
2. Run the program:
   ```bash
   ruby converter.rb
   ```
3. Follow the prompts to:
   - Select the language.
   - Provide the filename of your script.
   - Generate the executable.

---

## Limitations

- Designed for **Linux only**.
- Ensure **dependencies** (e.g., compilers, libraries) are installed.
- Some languages may require **additional setup** (e.g., `ocra` for Ruby).

---
