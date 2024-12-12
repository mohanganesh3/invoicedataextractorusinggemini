#  Invoice Data Extractor using Gemini  
**Invoice Data Extractor using Gemini** is an AI-powered tool that helps extract and understand data from invoices in multiple languages. By uploading an image of an invoice, the app leverages **Gemini** API to analyze and answer specific questions about the invoice contents.  

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
