# Doctor_appointment_chatbot

# 🩺 Doctor Appointment Chatbot 

A smart, user-friendly chatbot system built using **Django** that allows patients to book doctor appointments seamlessly. The chatbot interacts in real-time, guides users through appointment scheduling, and stores information securely.

## 🚀 Features

- 🤖 AI Chatbot interface for doctor appointment queries  
- 🗓️ Book appointments based on doctor availability  
- 👨‍⚕️ Admin panel for managing doctors and appointments 
- 📩 Email notifications (optional) for confirmation  
- 🧠 Natural language handling for patient-friendly interactions  

## 📌 Problem Statement

Patients often struggle to schedule medical appointments quickly, especially during emergencies or when facing long queues. Traditional methods lack real-time communication and smart handling. This chatbot automates the booking process and makes appointment management efficient and accessible.

## 💡 WOW Factors

- Real-time chatbot interaction using Django views  
- Scalable architecture with modular design  
- Clean UI for both patients and admins  
- Future-ready: Can integrate AI/ML for symptom analysis  
- REST API ready for mobile integration  

## 🛠️ Tech Stack

- **Framework:** Django (Python)  
- **Frontend:** HTML, CSS, Bootstrap  

## 👥 End Users

- **Patients:** Can interact with chatbot to book, reschedule, or cancel appointments  
- **Doctors/Admins:** Manage availability, view appointments via admin panel  

## 📦 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/doctor-chatbot.git
cd doctor-chatbot

# Set up virtual environment
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser for admin access
python manage.py createsuperuser

# Run the server
python manage.py runserver
