# Ai-unit-convertor
# 🔁 AI Unit Converter

An AI-powered unit conversion tool built with **Streamlit** and **Google Generative AI (Gemini API)**. This chatbot exclusively handles unit conversion requests and presents the output in a structured table format.

## 🚀 Features
- ✅ Converts units across different measurement categories.
- ✅ Ensures responses are always formatted in a table.
- ✅ Rejects non-conversion-related queries with an appropriate response.
- ✅ User-friendly chat-based interface using **Streamlit**.

## 🛠️ Technologies Used
- 🐍 **Python** (Backend Logic)
- 🎨 **Streamlit** (Web UI)
- 🤖 **Google Generative AI (Gemini-2.0-Flash)**
- 🔐 **Dotenv** (For environment variable management)

## 📦 Installation


1. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
2. **Set up environment variables:**
   - Create a `.env` file in the project root.
   - Add your **Gemini API Key**:
     ```sh
     GEMINI_API_KEY=your_api_key_here
     ```

## ▶️ Usage
Run the Streamlit app with the following command:
```sh
streamlit run app.py
```
Then, open the provided **local URL** in your browser and start converting units!

## 🌍 Deployment
To deploy on **Streamlit Cloud**:
- Ensure `requirements.txt` and `.streamlit/secrets.toml` (for API keys) are properly configured.
- Push your repository to GitHub and deploy via Streamlit Cloud.

## 💡 Example Queries
```plaintext
Convert 10 kilometers to meters.
How many grams are in 2 kilograms?
Convert 5 feet to inches.
```

## 🔒 Notes
- If a request is **not** related to unit conversion, the chatbot will respond with:
  ```plaintext
  I can only perform unit conversions.
  ```
- If invalid units are provided, it will respond with:
  ```plaintext
  Cannot convert between these units.
  ```

## 📜 License
This project is **open-source**. Feel free to modify and enhance it!

---

Made with ❤️ using AI! 🚀

