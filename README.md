# HortiPedia
Brief update of our project

# Features:
1. Hortipedia is a question and answer website for professional and developing farmers.
2. It has a chat forum where the farmers or students can get live interacted with professionals.
3. Auto Weather forecasts detect the system location and send the current temperature and humidity. 
4. It has an economic statistics page for investors and buyers where they can get the data on their crops for future production. 

# Tech Stack:
1. Reactjs
2. Nextjs
3. REST API
4. Mongodb
5. Expressjs
6. Nodejs
7. Socket.io(for live chatting)
8. peerjs (peer-to-peer data transfer)
9. axios
10. nprogress (nanoscopic progress bar)

# Installation:
1.  git clone https://github.com/SurajSinghDevloper/HortiPedia.git
2.  cd HortiPedia
3.  cd client -> npm install or yarn add -> npm run dev -- -p 3006 <br/>
    // open a new terminal to install server
4.  cd server -> npm install or yarn add -> npm run dev <br/>
    // open a new terminal to install Farm-Community
5.  cd client -> cd Farm-Community -> npm install or yarn add -> npm run dev
 <br/>
    // to run the peerjs network
6.  cd client -> cd Farm-Community -> npm i -g peer ->peerjs --port 3001
   // to run the weather application
7.  cd client -> cd weather-app -> npm start 

Note: Create a .env file in your server folder <br/>
         Add DATABASE_URL= "YOUR MONGO URI"
