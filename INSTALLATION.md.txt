## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/chat-with-pdf.git
cd chat-with-pdf

### 2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate  # macOS/Linux

### 3️⃣ Install Dependencies
pip install -r requirements.txt

### 4️⃣ Configure Environment Variables

Create a .env file in the root directory:

OPENAI_API_KEY=your_api_key_here

### 5️⃣ Run the Application
streamlit run chatpdf1.py

