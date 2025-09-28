# 🧭 QR Code Generator CLI

A simple **Node.js Command-Line Application** that generates a **QR code image** from any **URL** provided by the user and also saves the **URL locally** in a text file.

---

## 🚀 Features

- 📥 Takes user input via the command line  
- 🖼️ Generates a **QR code image** (`qr_img.png`)  
- 📝 Saves the **entered URL** in a text file (`URL.txt`)  
- ⚡ Lightweight and **easy to use**

---

## 🛠️ Tech Stack

**Node.js**  
**Inquirer** – for interactive command-line prompts  
**qr-image** – for generating QR codes  
**fs** – Node.js file system module

---

## 📦 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/qr-code-generator-cli.git
   cd qr-code-generator-cli

2. **Install Dependencies**

   npm install

3. **Run the application**

   node index.js

---

## 💡 Usage
1. When prompted, enter the URL you want to generate a QR code for.
2. The app will:
     - Generate a **QR image** named **qr_img.png** in the current directory.
     - Save the **original URL** to **URL.txt**

   Example:- 

     **Input** 

         ? Type in your url: https://openai.com

     **Output**

         The file has been saved!

     **Now you'll find:**

         - 🖼️ qr_img.png → QR code for your URL

         - 📝 URL.txt → Contains the entered URL

---

## 📁 Project Structure
.

├── index.js        # Main app file

├── package.json    # Project dependencies

├── URL.txt         # Saved URL (auto-generated)

└── qr_img.png      # QR code image (auto-generated)

---

## 📋 Dependencies

| Package      | Description                  |
| ------------ | ---------------------------- |
| **inquirer** | For interactive CLI prompts  |
| **qr-image** | For generating QR codes      |
| **fs**       | For file handling in Node.js |

---

## 🧠 Future Enhancements

🔹 Add custom file name option for the QR image

🔹 Support for multiple URLs in one session

🔹 Save QR codes in different formats (SVG, PDF, etc.)

---

## 👨‍💻 Author
  **Kanishka Jha**
  
  📧 https://kanishka-jha-portflio.netlify.app/  
  
  🌐 https://github.com/spidey1311
