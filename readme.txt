Requirements:

-Python 3.10 or later

-Git

-A modern browser


Setup Instructions:


1. Create a Virtual Environment:

python -m venv .venv



2. Activate the Virtual Environment:

-On macOS/Linux:
source .venv/bin/activate

-On Windows (PowerShell):
.\.venv\Scripts\Activate.ps1

-On Windows (CMD):
.\.venv\Scripts\activate.bat


3. Install Dependencies:
pip install -r requirements.txt


4. Run the Server:
python manage.py runserver


5. Access the Application:
Open your browser and go to:
http://127.0.0.1:8000

Note: The only file that is relevant to optimizing the upload and summary is core/views.py