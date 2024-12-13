# **Password Manager**  

A secure and user-friendly password manager designed to help you store, organize, and protect your credentials for various websites. This tool generates strong passwords, stores them efficiently, and even copies them to your clipboard for hassle-free use. It’s perfect for simplifying your password management while keeping your accounts safe and organized.  

---

## **Features**  

- **Password Generation**:  
  Create strong, secure passwords instantly.  

- **Clipboard Integration**:  
  Automatically copy generated passwords to your clipboard for easy pasting.  

- **Credential Storage**:  
  Save website credentials (website name and password) securely in a local document.  

- **Password Retrieval**:  
  Quickly find and retrieve previously saved passwords by entering the corresponding website name.  

- **Error Handling**:  
  - Provides user-friendly messages for invalid entries or missing passwords.  
  - Ensures smooth and intuitive user interaction.  

---

## **Screenshots**  

### **User Interface**  
The main interface for generating, storing, and retrieving passwords.  
![User Interface](https://github.com/EdgarQuinones/Password-Manager/blob/main/Images/UI.png)  

### **Password Storing**  
Passwords are saved locally in a file for easy reference.  
![Password Storing](https://github.com/EdgarQuinones/Password-Manager/blob/main/Images/Password%20File.png)  

### **Password Finder**  
Quickly retrieve passwords by searching for the website name.  
![Password Finder](https://github.com/EdgarQuinones/Password-Manager/blob/main/Images/Password%20Found.png)  

### **Error Handling**  

- When no password is found:  
  ![No Password Found](https://github.com/EdgarQuinones/Password-Manager/blob/main/Images/No%20Password%20Found.png)  

- For invalid or missing input:  
  ![Invalid Entry](https://github.com/EdgarQuinones/Password-Manager/blob/main/Images/Invalid%20Entry.png)  

---

## **Notes**  

- **Case Sensitivity**:  
  Website names are case-sensitive. For example, "Facebook" and "facebook" are treated as different entries.  

- **Security Reminder**:  
  This program stores passwords in plain text. For enhanced security, it is strongly recommended to use encryption software to protect your stored credentials. Leaving passwords unencrypted can pose significant security risks.  

---

## **Getting Started**  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/EdgarQuinones/Password-Manager.git  
   ```  

2. Install required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Run the application:  
   ```bash  
   python password_manager.py  
   ```  

4. Start generating, storing, and managing your passwords!  

---

## **Dependencies**  

The program uses the following Python modules:  

- `tkinter`  
- `pyperclip`  

Install them with:  
```bash  
pip install tkinter pyperclip  
```  

---

## **Future Improvements**  

- Implement encryption for password storage to enhance security.  
- Add support for multiple users with unique credential sets.  
- Integrate cloud-based storage for easy access across devices.  
- Expand error handling for a smoother user experience.  

---

Feel free to contribute or raise issues for additional features and improvements! 😊  
