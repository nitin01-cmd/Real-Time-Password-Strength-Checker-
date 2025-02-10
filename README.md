# 🔐 Real-Time Password Strength Checker

A lightweight Chrome extension that checks password strength in real time as you type, helping users create stronger passwords for better security.

---

## 🚀 Features
✅ Real-time password strength analysis  
✅ Color-coded strength indicators (Weak, Moderate, Strong)  
✅ Works on any website with a password field  
✅ Lightweight and easy to use  

---

## 📌 Installation
1. **Download the repository** or clone it using:
   ```sh
   git clone https://github.com/nitin01-cmd/password-strength-checker.git
   ```
2. **Open Chrome** and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** (toggle at the top right).
4. Click **Load unpacked** and select the downloaded folder.
5. The extension will be added to Chrome! 🎉

---

## 🛠 How It Works
1. Go to any website with a password field.
2. Start typing a password.
3. A **real-time strength indicator** appears below the input field, guiding you to create a stronger password.

---

## 📂 File Structure
```
📁 password-strength-checker
├── 📁 icons            # Extension icons
│   ├── images1.png
│   ├── images2.png
│   └── images3.png
├── 📜 manifest.json    # Chrome extension config file
├── 📜 content.js       # Main script to check password strength
├── 📜 style.css        # Styling for the strength indicator
└── 📜 README.md        # Project documentation
```

---

## 📜 manifest.json
```json
{
  "manifest_version": 3,
  "name": "Real-Time Password Strength Checker",
  "version": "1.0",
  "description": "Check password strength in real-time as you type.",
  "icons": {
    "16": "icons/images3.png",
    "48": "icons/images2.png",
    "128": "icons/images1.png"
  },
  "permissions": ["activeTab"],
  "host_permissions": ["<all_urls>"],
  "content_scripts": [
    {
      "matches": ["<all_urls>"],
      "js": ["content.js"],
      "css": ["style.css"],
      "run_at": "document_end"
    }
  ]
}
```

---

## 🔧 Future Improvements
- Add more security checks (e.g., common password detection)
- Provide suggestions for stronger passwords
- Support for multiple languages

---

## 🎯 Contribution
Feel free to fork the repository, create a new branch, and submit a pull request with improvements!

---

## 📢 Connect with Me
📧 Email: [nitin152105@gmail.com](mailto:nitin152105@gmail.com)  
🔗 LinkedIn: (https://www.linkedin.com/in/nitin-singh-731793275/)  

---

### ⭐ If you found this project useful, please consider giving it a **star** on GitHub! ⭐
