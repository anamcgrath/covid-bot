# rasa-install

This repository contains all the files to make COVID-19 Symptom Checker chatbot! Along with this chatbot, I have created a Chatbot generator! Visit [anamcgrath.ca/chatbot](anamcgrath.ca/chatbot) to try it out. The below describes my process of building the app and chatbot and making them work together. I used the script from the [WebChat repository](https://github.com/botfront/rasa-webchat) to put the bot on the app. Using this script, I coded a generator that would take the script, add the user’s unique variables and generate them a personalized script. Along with that script I generate what their bot widget in the bottom corner of the site.

To deploy this project, I suggest using two separate virtual machines. In my opinion, the back end deploying of the project is one of the more complex parts of my project. Rasa runs using docker containers and nginx. I used [this tutorial](https://rasa.com/docs/rasa-x/installation-and-setup/docker-compose-script/) from Rasa to help me with the install. Once rasa x is up and running on your IP address, you have to connect it to your GitHub repository. Once the GitHub repo is connected, your changes will be pushed and saved to the git server. 

On the separate vm I use a pre-installed LAMP stack vm from google cloud. I built my website using visual studio code on my local machine. Once the site was done I connected the vm to code-anywhere and uploaded the files to the /var/www/html folder. From code-anywhere I built the app itself. To deploy the app and site you would need to download the html directory, put it on your personal server and make sure that the LAMP stack is preinstalled with PhpMyAdmin. 

To connect both virtual machines to each other, go to the lamp stack vm. In the `/var/www/html/chatbot/bot-result.php` file, change the url in the ‘web chat’ script tag to your rasa server’s ip address. There are two places to change this url on that page as well as one script tag with this url on  `/var/www/html/chatbot/users/dashboard.php`. Now the chatbot from your rasa server will be fully integrated into your website vm! The chatbot will appear in little widgets in the bottom right of the bot-result.php page. 
