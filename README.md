# Django Stock Tracker Project

This Django-based application helps users track stock performance and receive news updates via SMS. Users can save their preferred stocks, set upper and lower limits for stock price changes, and receive relevant news notifications when the stock moves beyond these thresholds. The project integrates Twilio for SMS notifications and NewsAPI for gathering stock-related news.

## Features
- User profile creation: Allows users to register and save their preferred stocks.
- Stock tracking: Users can track the performance of their favorite stocks and set upper and lower price limits.
- News updates: Fetches relevant news articles related to the stocks when significant price movements occur.
- SMS notifications: Sends SMS notifications using Twilio when stock price limits are breached.
- API integration: Uses Alpha Vantage for stock data and NewsAPI for company-related news.

## API's Used
- [Twilio](https://www.twilio.com/) (for sending SMS)
- [Alpha Vantage API Key](https://www.alphavantage.co/) (for stock data)
- [NewsAPI Key](https://newsapi.org/) (for fetching stock news)

## Installation 
Open the folder in your preferred IDE and execute the following commands <br>
Note: **it is preferred to creta a virtual environment first** <br>
- 1) pip install -r requirements.txt (Install dependencies) <br>
- 2) python manage.py migrate (setup sqlite3 db) <br>
- 3) python manage.py runserver (Run the Django development server) <br>

That's it! Access the web app at the URL provided by the Django development server (usually http://127.0.0.1:8000).

**Note
Login as superuser: After running the development server, visit /admin, log in as the superuser, and navigate to the stock tracking page and their you can add new user as well as phone number on which the sms should be received.

Screenshots

<img width="1920" height="1080" alt="Screenshot 2026-03-26 184325" src="https://github.com/user-attachments/assets/c685c893-9357-4369-8ab8-4d9186f0e302" />

<img width="1920" height="1080" alt="Screenshot 2026-03-26 184354" src="https://github.com/user-attachments/assets/2dc51c7e-a907-4bae-9ec4-47ce05c4f314" />

<img width="1920" height="1080" alt="Screenshot 2026-03-26 184758" src="https://github.com/user-attachments/assets/7e05ed96-12bd-451f-beef-39a199648200" />

















