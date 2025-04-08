# 🏠 Home Energy Saving Advisor

A rule-based expert system that provides personalized energy-saving recommendations for homeowners.

![image](https://github.com/user-attachments/assets/3d52fe6e-f9fc-4322-86f4-69c1ab003223)

## Features
- Rules covering energy consumption issues across 5 categories
- SQLite database for efficient rule storage
- Web interface
- Personalized recommendations based on home profile

## 🚀 How to Run

### Google Colab (Recommended)
1. Open the link to the notebook by going to: https://colab.research.google.com/drive/18FN0HSfL7CwiH2T5oEp2RcZTlQWdcbQ3?usp=sharing (or upload `app.py`)
2. Run these commands in order:
```python
!pip install flask pyngrok
!ngrok authtoken YOUR_TOKEN  # Get from https://dashboard.ngrok.com/get-started
python app.py
```
3. Click the ngrok URL provided in the output

## Demo Combinations to Try
- High electricity bill + Old appliances
![image](https://github.com/user-attachments/assets/161e9147-548a-4b77-97f4-d1656e6cf511)
- Drafty windows + High heating costs
![image](https://github.com/user-attachments/assets/0f4bf9d5-936c-4239-854b-d3f6cdb08d0a)
- Poor lighting + Outdoor lighting
![image](https://github.com/user-attachments/assets/52a205bf-5459-44aa-bc26-e1e6383d5d9e)

## 📚 Technologies Used
- Python
- Flask (Web framework)
- SQLite (Database)
- Ngrok (Tunneling)
- HTML/CSS (Frontend)

*Developed for Knowledge-Based Systems APT3020B in USIU-A, Summer 2025*
