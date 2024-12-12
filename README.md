#  Invoice Data Extractor using Gemini  
**Invoice Data Extractor using Gemini** is an AI-powered tool that helps extract and understand data from invoices in multiple languages. By uploading an image of an invoice, the app leverages **Gemini** API to analyze and answer specific questions about the invoice contents.  
#DEMO
You can see a demo of the **Invoice Data Extractor** in action below:
<img width="654" alt="Screenshot 2024-12-12 at 11 20 03 AM" src="https://github.com/user-attachments/assets/5a0d3530-1637-44f5-87ad-e06aba06b2d7" />
1. **Upload an Invoice**: Upload an image of your invoice to the app.  
2. **Ask Questions**: Type a question like “Explain me about invoice?”.
<img width="566" alt="Screenshot 2024-12-12 at 11 20 51 AM" src="https://github.com/user-attachments/assets/39849125-be11-4dcc-b1b2-8895fa0469ca" />
3. **Response**:  
<img width="523" alt="Screenshot 2024-12-12 at 11 21 21 AM" src="https://github.com/user-attachments/assets/23f5f2aa-5a36-4558-aea1-f17afc6deff9" />

## 🌟 Features  
- **📸 Invoice Image Upload**: Upload invoice images in JPEG, PNG, or JPG formats.  
- **🧾 Multi-language Support**: Extract and interpret invoice data in different languages.  
- **🤖 AI Invoice Understanding**: Uses **Gemini** AI to analyze invoice data and answer questions.  
- **💻 Interactive Interface**: Simple web interface built using **Streamlit** for easy user interaction.  

## 🛠️ Technologies Used  
- **Gemini**: For invoice data extraction and analysis.  
- **Python**: The main programming language.  
- **Streamlit**: To build the web interface.  
- **Pillow**: For image handling.  
- **dotenv**: To securely manage environment variables.  

## 📥 Installation Guide  
Ensure that you have **Python 3.7+** and **pip** installed on your system.

### Step 1: Clone the Repository  
Clone the repository to your local machine:  
`git clone https://github.com/mohanganesh3/invoicedataextractorusinggemini.git`  
`cd invoicedataextractorusinggemini`  

### Step 2: Set Up a Virtual Environment  
It's recommended to use a virtual environment to manage dependencies:  
`python3 -m venv venv`  
`source venv/bin/activate`  # On Windows, use `venv\Scripts\activate`  

### Step 3: Install Required Dependencies  
Install the necessary Python libraries by running:  
`pip install -r requirements.txt`  

### Step 4: Set Up Environment Variables  
Make sure to set up the required **Google API key** for **Gemini**. You can add it to a `.env` file in the root of your project:  
`GOOGLE_API_KEY=<your_google_api_key>`  

### Step 5: Run the Application  
Start the application using **Streamlit**:  
`streamlit run app.py`  
This will open the app in your default browser. You can upload an invoice image and start interacting with the tool.

## 💡 Usage  
1. **Upload Invoice Image**: Choose an image of the invoice (JPEG, PNG, JPG).  
2. **Enter Prompt**: Input a prompt regarding the invoice content.  
3. **Get Invoice Data**: Click the button to extract data and get answers about the invoice.

## ⚙️ How It Works  
1. **Image Upload**: The user uploads an invoice image.  
2. **Data Extraction**: The **Gemini** API processes the image to extract invoice data.  
3. **Question Answering**: Based on the extracted information, **Gemini** answers any questions about the invoice.  
4. **User Interaction**: Users input their questions, and the AI generates responses based on the content of the uploaded invoice.

## 📝 Example  
### Sample Interaction:  
1. **Upload Invoice Image**: Upload an invoice image.  
2. **Input Prompt**: “Tell me about the invoice.”  
3. **Response**:  
