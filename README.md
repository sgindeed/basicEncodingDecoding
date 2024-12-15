# 🔠✨ **Basic Encoding and Decoding** ✨🔠  

Welcome to the **Basic Encoding and Decoding** project! 🌐 This script demonstrates how to encode and decode text in Python using custom input encoding and error-handling methods.  

---

## 📚 **About the Project**  

This project focuses on:  
- **Reading a text file line by line.**  
- **Encoding text** into a specified byte format.  
- **Decoding text** back into a human-readable string.  
- Understanding **error-handling** during encoding/decoding.  

It’s a beginner-friendly exploration of Python’s encoding and decoding capabilities using the `sys` module.  

---

## 🚀 **How It Works**  

1. **Input Parameters**:  
   The script takes three command-line arguments:  
   - `input_encoding`: The desired text encoding (e.g., `utf-8`, `ascii`).  
   - `error`: The error handling strategy (`strict`, `ignore`, `replace`).  

2. **Text File**:  
   Reads from `textfile.text` (default file in UTF-8 encoding).  

3. **Process**:  
   - Encodes each line of text into the specified byte format.  
   - Decodes it back into the string format for validation.  
   - Displays both the byte string and decoded string.  

---

## 🛠️ **How to Use**  

### 1️⃣ Clone the Repository  
```bash  
git clone https://github.com/sgindeed/basicEncodingDecoding.git  
cd basicEncodingDecoding  
```  

### 2️⃣ Create Your Input File  
Create a file named `textfile.text` with the text you want to process.  

### 3️⃣ Run the Script  
Use the following command:  
```bash  
python script.py <input_encoding> <error_handling>  
```  
Example:  
```bash  
python script.py utf-8 strict  
```  

---

## ✨ **Features**  

- **Custom Encoding**: Supports different encodings like `utf-8`, `ascii`, etc.  
- **Error Handling**: Choose from `strict`, `ignore`, or `replace`.  
- **Dynamic Processing**: Handles text files line by line.  
- **Educational**: Learn how encoding and decoding work in Python!  

---

## 📂 **Repository Structure**  

📁 **basicEncodingDecoding**  
- `script.py`: The main Python script.  
- `textfile.text`: Example text file for testing.  

---

## 💡 **Why Use This Project?**  

🔹 Gain insights into encoding/decoding processes.  
🔹 Experiment with error-handling techniques.  
🔹 Build a foundation for text processing in Python.  

---

## 💌 **Get in Touch**  

Have questions or want to collaborate? Connect with me on GitHub: [sgindeed](https://github.com/sgindeed) 🚀  

---  

🌟 *Decode the mysteries of encoding with this simple yet powerful Python script!* 🌟  
