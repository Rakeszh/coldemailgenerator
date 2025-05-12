# coldemailgenerator
This project automates creating personalized cold emails for job applications. Users provide a job listing URL, and the system matches it with candidate profiles. The AI then generates a tailored email highlighting the candidate's skills. It saves time and helps job seekers apply more effectively to job openings.
## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
