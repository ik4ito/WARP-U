# WARP+ UNLIMITED (New Methods!😊)
<b>Get Unlimited amount of Data in Cloudflare's WARP/WARP+ VPN</b>
<h2><b>🆕What's New</b></h2>
<p><b>1.Now get Hosted Script info on Telegram itself!</b></p>
<p><b>2.Added Jupyter Server deployment method!</b></p>
<p><b>3.Termux http/SSL Error now resolved!</b></p>
<p><b>4.Railway app deployment will now not cause false ban.</b></p>
<p><b>5.FAQ is now added to clear your doubts.</b></p>
<h2><b>📑 Features</b></h2>
<h4><b>1.Get 1GB Per 10 Seconds!🔥</b></h4>
<h2><b>🪧Before you Proceed</b></h2>
<p><b>1.Using this code on Google Colab will only work for 24 Hours if Time out preventer is used and that Tab is opened in your Phone or PC.</b></p>
<p><b>2.If you deploy this Code through Heroku or Railway app then it will run for lifetime!</b></p>
<p><b>3.It does not matter this trick works on both that's on WARP or WARP+.</b></p>
<h2><b>⚙️ How to use ?</b></h2>
<h4><b>1.First Get your WARP/WARP+ ID by going into Settings > Advanced > Diagnostics and copy the ID under CLIENT CONFIGURATION section</b></h4>
<img src="Img/1.jpg" height="50%" width="40%" alt="1">
<h2><b>🕹️ Run on Google Colab</b></h2>
<h4><b>2.First Open this Code on Google Colab:<a href="https://colab.research.google.com/github/TheCaduceus/WARP-UNLIMITED-ADVANCED/blob/main/Wrap_Unlimited_Advanced.ipynb" alt="Open-Colab"> Open Code!</a>
<h4><b>3.Now Run the Timeout Preventer to prevent Google Colab from getting timeout</b></h4>
<img src="Img/2.png" alt="2">
<h4><b>4.Then Run The WARP+ (1.1.1.1) Code and Enter your Warp ID (Also Hit Enter after it!) as shown in the Image</b></h4>
<img src="Img/3.png" alt="3">
<h4><b>5.After that! Let the code run, It will give you 1GB per 10 Seconds. But you have to update the value in the app! To do it<br>Go to Settings > Advanced > Connection options and press on Reset security keys</b></h4>
<h4><b><i>❗You have to manually update the Value in the app as written in above step❗</i></b></h4>
<h2><b>⚡Host on Heroku</b></h2>
<h4><b>1.First Click the below Deploy button.</b></h4>
<a href="https://heroku.com/deploy?template=https://github.com/TheCaduceus/WARP-UNLIMITED-ADVANCED/tree/Heroku"><img src="Img/Heroku Deployment Button.png" alt="Deploy on Heroku"></a>
<h4><b>2.Now Enter the following values and click "Deploy" button:</b></h4>
  <p><b>
    1.App Name: Give a unique name to your app name.<br>
    2.WARP_ID: Enter your WARP/WARP+ ID.<br>
    3.SEND_LOG: If you want to receive info about your deployed script like script working?,amount of data generated or number of failed attempts. 0 for No and 1 for Yes.<br>
    4.BOT_TOKEN: Enter BOT API TOKEN from Bot father which will send you the log in your channel or group. Bot must be admin in specific channel or group to send log. Required if SEND_LOG is 1.<br>
    5.CHANNEL_ID: Enter Channel/Group ID (Channel/Group must be Public) with @ in which you want log to be send. Like @example or @mychannel.
    </b></p>
<img src="https://user-images.githubusercontent.com/87380104/169484438-7ec8270e-864e-40ef-a0ea-f525cc2c741b.png" alt="4">
<h4><b>3.After Deployment! Click "Manage App" button and then click "Resources" Tab and enable the dyno.</b></h4>
<img src="Img/5.png" alt="5">
<h4><b>4.Enjoy! Now you will get 1GB per 10 Seconds for Lifetime until your Heroku Account exist and you will start getting info about your script if SEND_LOG is enabled.</b></h4>
<h4><b><i>❗You have to manually update the Value in the app To do it<br>Go to Settings > Advanced > Connection options and press on Reset security keys</b></h4>❗</i></b></h4>
<h2><b>🧿 Host on Railway App</b></h2>
<h4><b>1.First Create Account or Login on <a href="https://railway.app/">Railway App</a></b></h4>
<img src="Img/3.1.png">
<h4><b>2.Now click the following Railway deployment button:</b></h4>
<a href="https://railway.app/new/template/M78z7V?referralCode=PFHpF8"><img src="https://railway.app/button.svg" alt="Railway deploy button"></a>
<h4><b>3.After it! Enter the following values:</b></h4>
<p><b>
    1.WARP_ID: Enter your WARP/WARP+ ID.<br>
    2.SEND_LOG: If you want to receive info about your deployed script like script working?,amount of data generated or number of failed attempts. 0 for No and 1 for Yes.<br>
    3.BOT_TOKEN: Enter BOT API TOKEN from Bot father which will send you the log in your channel or group. Bot must be admin in specific channel or group to send log. Required if SEND_LOG is 1.<br>
    4.CHANNEL_ID: Enter Channel/Group ID (Channel/Group must be Public) with @ in which you want log to be send. Like @example or @mychannel.
    </b></p>
<h4><b><i>❗The Major Advantage of the Railway app is that, it never restarts. So it will generate more Amount of Data in 24 Hours if compared with Heroku.❗</i></b></h4>
<h2><b>🪬 Host on Okteto (Temporary Not Working!)</b></h2>
<h4><b>Okteto is also a best Platform like Railway, people like it because it does not restart your deployed app after 24 Hours unlike Heroku do. There are only some points we need to keep in our mind to use it effectively you will see it in this Section!</b></h4>
<h4><b>1.First Create your okteto Account, You need one GitHub account as okteto supports only one Method to either Create or Login: <a href="https://cloud.okteto.com/#/login">Create Account</a></b></h4>
<img src="Img/1.1.png">
<h4><b>2.Now fork this Repository and go to Okteto and click "Launch Dev Environment" button as shown in the image.</b></h4>
<img src="Img/1.2.png">
<h4><b>3.After that, Select GitHub from the pop-up and select your forked repository named "WARP-UNLIMITED-ADVANCED" and choose Branch "Okteto" and add following variables carefully!</b></h4>
<p><b>
    1.WARP_ID: Enter your WARP/WARP+ ID.<br>
    2.SEND_LOG: If you want to receive info about your deployed script like script working?,amount of data generated or number of failed attempts. 0 for No and 1 for Yes.<br>
    3.BOT_TOKEN: Enter BOT API TOKEN from Bot father which will send you the log in your channel or group. Bot must be admin in specific channel or group to send log. Required if SEND_LOG is 1.<br>
    4.CHANNEL_ID: Enter Channel/Group ID (Channel/Group must be Public) with @ in which you want log to be send. Like @example or @mychannel.
    </b></p>
<img src="https://user-images.githubusercontent.com/87380104/169487986-0aa2896b-44bd-4f78-bd12-eba92bac3a47.png">
<h4><b>4.Finally! You are ready to click "Launch" button and then okteto will do everything automatically. Enjoy!🎉</b></h4>
<img src="Img/1.4.png">
<h4><b>❗Okteto turns sleeping mode on your Deployed app, if its provided Domain don't got pinged within 24 Hours! So to prevent this follow the below steps❗</b></h4><b>5.To prevent your app from going into sleep! Copy its URL provided by the Okteto, to get it click on warp as shown in the image.</b></h4>
<img src="Img/1.5.png">
<h4><b>6.Now go to <a href="https://cron-job.org/en/">Cron Job</a> and click Sign Up and make your Account</b></h4>
<img src="Img/1.6.png">
<h4><b>7.After creating your account! Click "CREATE CRONJOB".</b></h4>
<img src="Img/1.7.png">
<h4><b>8.It will now ask you for Title and URL. Give any title and paste the copied URL and set Execution to after 60 Minutes and press "CREATE" button.</b></h4>
<img src="Img/1.8.png">
<h4><b>9.Your Script is now all good and will not cause any problem if you follow above written steps carefully!😎</b></h4>
<h2><b>🖥️ Run on Computer</b></h2>
<h4><b>Running this script on your Computer is simple than ABC!</b></h4>
<h4><b>1.If your PC not have python, then install it first: <a href="https://www.python.org/downloads/">Download Python</a></b></h4>
<h4><b>2.Now first open the WRAP+ Unlimited Script code and paste it in notepad and save it as "warp.py" don't forget to type ".py":<a href="https://github.com/TheCaduceus/WARP-UNLIMITED-ADVANCED/blob/View-Script/Warp.md"> Show Code</a></b></h4>
<h4><b>3.After it run the code as shown in the Image and Enter WARP ID and Hit Enter and Enjoy!</b></h4>
<img src="Img/6.png" alt="6">
<h4><b><i>❗The Script will run and give you 1GB data / 10 Second until your PC is on and the Window is open. Make sure that your PC or Local System is connected to INTERNET CONNECTION.❗</i></b></h4>
<h2><b>🧫 Deploy Through GitHub Actions</b></h2>
<h4><b>This Method is too much easier and best for users who want to deploy this script multiple times on Heroku without login on Heroku again and again!</b></h4>
<h4><b>1.First fork my different Repository <a href="https://github.com/TheCaduceus/GA-1OFM-">here</a></b></h4>
<img src="Img/1.9.png">
<h4><b>2.Now open the settings of your Forked Repository and click Secrets->Actions.</b></h4>
<img src="Img/2.0.png">
<h4><b>3.After doing that, create Following Secrets:</b></h4>
<p><b>
  1.HEROKU_API_KEY - Enter your Heroku API Key as value.<br>
  2.HEROKU_APP_NAME - A unique app name in small letters only.<br>
  3.HEROKU_EMAIL - Your Heroku Email ID.<br>
  4.WARP_ID - Enter your WARP/WARP+ ID. In capital only!<br>
  5.SEND_LOG - If you want to receive info about your deployed script like script working?,amount of data generated or number of failed attempts. 0 for No and 1 for Yes.<br>
  6.BOT_TOKEN: Enter BOT API TOKEN from Bot father which will send you the log in your channel or group. Bot must be admin in specific channel or group to send log. Required if SEND_LOG is 1.<br>
  7.CHANNEL_ID: Enter Channel/Group ID (Channel/Group must be Public) with @ in which you want log to be send. Like @example or @mychannel.
  </b></p>
  <img src="Img/2.1.png">
<h4><b>4.If you want! then at place of creating secrets of WARP_ID,SEND_LOG, BOT_TOKEN and CHANNEL_ID, just write their values in the <a href="https://github.com/TheCaduceus/GA-1OFM-/blob/Heroku/config.env">config.env file</a> given in the repository and directly deploy it by just providing HEROKU_API_KEY, HEROKU_APP_NAME and HEROKU_EMAIL.</b></h4>
<h4><b>5.Go to Actions Tab then click "Deploy on Heroku" and "Run Workflow". Now it will be automatically got deployed on given Heroku Account!😉</b></h4>
<img src="Img/2.2.png">
<h4><b>5.It will take maximum 10 Seconds to start the Workflow and minimum 1-2 Minutes to get deployed!</b></h4>
<h2><b>📲 Host on Mobile Phone</b></h2>
<h4><b>1.First Download the Termux app <a href="https://github.com/termux/termux-app/releases">from here</a>.</b></h4>
<h4><b>2.Now run the following commands in it one by one!</b></h4>
<p><b>
  1.pkg install python - This Command will Download Python.<br>
  2.pkg install git - This Command will Download Git.<br>
  3.git clone https://github.com/TheCaduceus/WARP-UNLIMITED-ADVANCED - This Command will clone this Repository in your Device.<br>
  4.cd WARP-UNLIMITED-ADVANCED - This Command will set Directory to this Repository's created Folder.<br>
  5.python3 warp.py - This Command will run the main Script.<br>
  <!---SSL is by default never comes--->
  6.Getting <http>/SSL Error? Run following code to fix it:<br>
  termux-setup-storage && pkg update && pkg i git python wget -y && pkg upgrade && pip install --upgrade pip
  <img src="Img/Termux-Error-1.jpeg">
  </b></p>
  <h4><b>3.After above! Now Enter your WARP ID and get started.😚</b></h4>
<h2><b>🎲Run on Replit</b></h2>
<h4><b>1.Open the "WARP UNLIMITED" repl:<a href="https://replit.com/@TheCaduceus/WARP-UNLIMITED"> Open it</a></b></h4>
<h4><b>2.Enter your WARP/WARP+ ID and press Enter to run the script. Enjoy!🙃</b></h4>
<img src="Img/repl-1.png">
<h2><b>🧰Run on Jupyter Server</b></h2>
<h4><b>This method is best & effective alternative of "Run on Computer" method! Before using this method, let see how to Download & Setup Jupypter server which is too lightweight.</b></h4>
<h5><b>Setting up the Jupyter Server:</b></h5>
<h4><b>1.First install Python:<a href="https://www.python.org/downloads/" alt="Download Python"> From Here</a></b></h4>
<h4><b>2.Now run the CMD as Administrator and execute following commands one-by-one:</b></h4>
<p><b>1.pip install jupyter - To install Jupyter<br>
  2.pip install notebook - To install Notebook<br>
  3.pip install voila - To install Voila
  4.python -m notebook - Start Jupyter Server
</b></p>
<h4><b>3.Once you start your Server! Then Jupyter will give you its link (as shown in Image), just open it on your Browser.</b></h4>
<img src="Img/jp-1.png">
<img src="Img/jp-2.png">
<h4><b>4.Now Download the "Warp-on-Jupyter-Server.ipynb" file:<a href="https://www.caduceus.ml/files/Warp-on-Jupyter-Server.ipynb" alt="Warp-on-Juypter-Server"> From Here only</a></b></h4>
<h4><b>5.After downloading it! Locate that file through your Jupyter server and open it as shown in the image and click Run.</b></h4>
<img src="Img/jp-3.png">
<h4><b>6.Now enter your WARP/WARP+ ID and press Enter to continue.Enjoy!😉</b></h4>
<img src="Img/jp-4.png">
<h2><b>📈Update Values</b></h2>
<h4><b>After Successfully Deploying or Running your Script! You have to update the "Data Remaining Value in your App."</b></h4>
<h3><b>📲For Mobile:</b></h3>
<h4><b>Go to Settings-->Advanced-->Connection Options-->Press Reset Security Keys</b></h4>
<h3><b>🖥️For PC:<b></h3>
<h4><b>Just again Enter your Activation key! For getting Activation key, Open App in Mobile-->Settings-->Account-->Copy Key</b></h4>
<h2><b>🎯Points to be Remembered</b></h2>
<h4><b>1.You have to manually update the Value in the app.</b></h4>
<h4><b>2.The Major Advantage of the Railway app is that, it never restarts. So it will generate more Amount of Data in 24 Hours if compared with Heroku</b></h4>
<h4><b>3.On your Computer,The Script will run and give you 1GB data / 10 Second until your PC is on and the Window is open.</b></h4>
<h4><b>4.This Tricks works on both! That's WARP or WARP+.</b></h4>
<h4><b>5.If you are hosting this Script on your PC or Local System then confirm that it is connected to INTERNET CONNECTION.</b></h4>
<h4><b>6.Okteto turns sleeping mode on your Deployed app, if its provided Domain don't got pinged within 24 Hours! Please Refer to STEPS 5-9 under Okteto section to know how to prevent it.</b></h4>
<h2><b>❓FAQ</b></h2>
<h4><b>1.How much scripts can I host/run for same account?</b></h4>
  <p><b>I will recommend to host/run 3 or less than 3 (<3) scripts for each account because Cloudflare is API have request limits. Hosting/Running too many scripts can cause "Too many Requests" error which indicates that API getting too many requestes from same account and that is why there is a cooldown timer of 10 seconds to prevent this.</b></p>
<h4><b>2.How to resolve "Too many request" Error?</b></h4>
  <p><b>As already discussed above! Hosting/Running too many scripts for same account cause this. So just switch off the sripts and bring down the number to 3 or >3 scripts for same account. Please refer to <a href="https://github.com/TheCaduceus/WARP-UNLIMITED-ADVANCED/issues/3">Issue #3</a> for more details on this.</b></p>
<h4><b>3.Will this script cause any type of ban from Cloudflare?</b></h4>
  <p><b>No, this script don't cause ban because it just use the API provided by Cloudflare for referral system. Neither this script create any type of load or bypass any limit set by Cloudflare for there API nor it hack anything or changes any official record.</b></p>
<h4><b>4.Script not working & producing error as shown in the image in Termux. How to solve?</b></h4>
  <img src="Img/Termux-Error-1.jpeg">
  <p><b>This problem happens due to missing files! you can run the below given command in Termux to fix it easily:<br>termux-setup-storage && pkg update && pkg i git python wget -y && pkg upgrade && pip install --upgrade pip</b></p>
<h4><b>5.Deploying this on Heroku/Rilway/Okteto/Vercel cause any ban?</b></h4>
  <p><b>No, this script comes in category of Cron-Job because this script just take the WARP/WARP+ ID from user and arrange it in a particular format and start pining it in an interval of 10 seconds.This script is lightweight and don't have any load on system.</b></p>
<h2><b>🖥️How to use this Data on PC!</b></h2>
<h4><b>Open the WARP or 1.1.1.1 app in your Phone and go to Settings > Account > Key and copy the License Key | Now paste that Key in your Warp app in Windows or MacOS</b></h4>
<h2><b>⛑Contact Us!</b></h2>
<h4><b>Join our Update Channel at Telegram:<a href="https://telegram.me/TheCaduceusUPDATE"> Join Now!</a></b></h4>
<h4><b>Directly Contact the Developer using Telegram <a href="https://telegram.me/HelpAutomatted_Bot">@HelpAutomatted_Bot</a></b></h4>
<h2><b>❤️Credits & Thanks</b></h2>
<p><b><a href="https://github.com/TheCaduceus">Dr.Caduceus</a>: For heavy modification as well as making New 7 Methods and this all in one Guide.</b></p>
<p><b><a href="https://github.com/ALIILAPRO">ALI-B</a>: The Original Developer of the Base Script</b></p>
