# Ticketless Entry System

A ticketless entry system for museums and monuments using QR codes.

## How to Clone
```bash
git clone https://github.com/Kishore276/Entry-Management-System.git
cd Ticketless-Entry-System-to-Museums
```

## How to Run

1. Backend Setup:
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

2. Frontend Setup:
```bash
cd Frontend
npm install
npm start
```

1. Clone the repository:
```bash
git clone https://github.com/Kishore276/Entry-Management-System.git
cd Ticketless-Entry-System-to-Museums
```

2. Set up Backend:
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

3. Set up Frontend:
```bash
cd Frontend
npm install
npm start
```

## Project Structure

```
├── Backend/            # Django backend server
├── Frontend/           # React frontend application
│   ├── public/        # Static files
│   ├── src/           # React source code
│   └── build/         # Production build
├── qrscan/            # QR code handling
├── media/             # Uploaded files
├── manage.py          # Django management
└── requirements.txt   # Python dependencies
```
