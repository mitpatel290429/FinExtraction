

📊 Financial Data Extractor and Screener Fetcher  

This project is a **Streamlit-based web application** that extracts financial data from uploaded PDFs using **Google Gemini API** and fetches company financials from **Screener.in**.  

🚀 Features  

- **Upload PDFs** and extract financial metrics using AI.  
- **Fetch financial data** directly from Screener.in using authentication.  
- **Interactive UI** built with Streamlit.  
- **Secure API handling** (Use environment variables for sensitive data).  

 🛠️ Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```  

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```  

3. **Set up API Keys** (Replace with your actual API key in an `.env` file or environment variables)  
   ```bash
   export GOOGLE_API_KEY="your_google_api_key"
   export SCREENER_USERNAME="your_screener_username"
   export SCREENER_PASSWORD="your_screener_password"
   ```  

 📌 Usage  

Run the application with:  
```bash
streamlit run app.py
```  

 **Options in the App**  

1. **Upload PDF**  
   - Upload a financial report in PDF format.  
   - Extract key financial metrics using the **Gemini API**.  

2. **Fetch from Screener.in**  
   - Enter a company symbol (e.g., TCS, INFY).  
   - Fetch financial details like revenue, net profit, EPS, etc.  

 🔑 Environment Variables  

- `GOOGLE_API_KEY` → API key for **Google Gemini AI**.  
- `SCREENER_USERNAME` & `SCREENER_PASSWORD` → Screener.in login credentials.  

⚠️ **Do NOT hardcode sensitive credentials in the script. Use environment variables!**  

 📜 Dependencies  

- `streamlit`  
- `google-generativeai`  
- `requests`  
- `beautifulsoup4`  

Install all dependencies with:  
```bash
pip install -r requirements.txt
```  

 🤝 Contribution  

1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Commit your changes (`git commit -m "Added new feature"`).  
4. Push to the branch (`git push origin feature-branch`).  
5. Open a **Pull Request**.  

 📝 License  

This project is licensed under the **MIT License**.  

