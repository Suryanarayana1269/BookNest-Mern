###Project Overview :
  BookNest is a Bookstore Applications.Developed using MERN stack. BookNest Provides best User Experience via Hassle Free Browsing
  
###Cloning:
   Use Vs code and open terminal and run command :
   git clone https://github.com/Suryanarayana1269/BookNest-Mern/

###Create .env file for backend:
    -->In the backend folder create a file named with .env and define/setup the following things:
      DB_URL = 'mongodb+srv://suryanarayanabodapati1269:Surya4401@booknest.5snar.mongodb.net/' //Connect Your MongoDB URL
      JWT_SECRET_KEY = 'MySuperSuccess@1269'

###Setup and Configure Firebase for Authentication with Sign with Google and many other:
   --> Click this link https://console.firebase.google.com/?fb_gclid=Cj0KCQiAz6q-BhCfARIsAOezPxneTuOKyYX2WnX65YX7kWWX43lH7gmTI74tACGjDrkKkXE8UWxF4JkaArriEALw_wcB&_gl=1*1ey9dpu*_up*MQ..*_ga*OTIzNjM1MzUyLjE3NDA1NjkyMDE.*_ga_CW55HF8NVT*MTc0MTM3MjU2My44LjAuMTc0MTM3MjU2My42MC4wLjA.&gclid=Cj0KCQiAz6q-BhCfARIsAOezPxneTuOKyYX2WnX65YX7kWWX43lH7gmTI74tACGjDrkKkXE8UWxF4JkaArriEALw_wcB&gclsrc=aw.ds
   
-->After Clicking above link You have to create a Project and after that select Authentication 
-->Enable Sign-Methods 
--> Configure Environment varialbes:
    Eg:
    apiKey: "AIzaSyAyB9PSo2EnbZTqTHKLNxxZCd44LgPPcbk",
    authDomain: "booknest-2854f.firebaseapp.com",
    projectId: "booknest-2854f",
    storageBucket: "booknest-2854f.firebasestorage.app",
    messagingSenderId: "180863150528",
    appId: "1:180863150528:web:c21caf36386f2b57098025",
    measurementId: "G-RPT8KD82Q5"

    
###Create .evn.local in frontend folder:
    -->In the backend folder create a file named with .env.local and define/setup the following things:
        VITE_API_KEY="AIzaSyAyB9PSo2EnbZTqTHKLNxxZCd44LgPPcbk"
        VITE_Auth_Domain="booknest-2854f.firebaseapp.com"
        VITE_PROJECT_ID="booknest-2854f"
        VITE_STORAGE_BUCKET="booknest-2854f.firebasestorage.app"
        VITE_MESSAGING_SENDERID="180863150528"
        VITE_APPID="1:180863150528:web:c21caf36386f2b57098025"
        VITE_MEASUREMENT_ID="G-RPT8KD82Q5"
    
###Install Node Modules for frontend and backend:
   -> open integrated terminal for frontend and install node modules :
   eg: D:\BookNest\frontend
   D:\BookNest\frontend>npm install

   ->open integrated terminal for backend too and install node modules:
    eg: D:\BookNest\backend
    D:\BookNest\frontend>npm install

  -->Install firebase in frontend using command :
     Eg:
     D:\BookNest\frontend>npm install firebase

###Run backend and frontend terminals simultaneously:
     D:\BookNest\backend>npm start
     D:\BookNest\frontend>npm run dev

##After run the above commands the backend connected to MongoDb and Server started and the frontend started the deployment server in the localhost:5173

#####Demo Video link:
https://drive.google.com/file/d/1rMNIIJWn3BMdSqNJ4W-XtAgL3gRCSV-Z/view?usp=drive_link

#####Demo Documentation:
https://docs.google.com/document/d/1Ncz3o-1T1AWU3aHNRFMobTEdFjyHh3x4/edit?usp=drive_link&ouid=112556775906577700191&rtpof=true&sd=true

--------------------------------------------------------------------------------------------------Thank You----------------------------------------------------------------------------------------------------------
