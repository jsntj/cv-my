# My CV Webpage

This project is a simple web application built using Flask to showcase a personal CV. It includes a main page that displays the CV information in a structured format.

## Project Structure

```
my-cv-webpage
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── templates
│   │   └── index.html
│   └── static
│       ├── css
│       │   └── styles.css
│       └── js
│           └── scripts.js
├── venv
├── requirements.txt
├── app.py
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/my-cv-webpage.git
   cd my-cv-webpage
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000` to view your CV webpage.

## License

This project is licensed under the MIT License.