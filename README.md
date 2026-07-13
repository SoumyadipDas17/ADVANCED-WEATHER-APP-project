# WEATHER-APP-PROJECT
This is an API based project that uses wttr.in API in order to get the information about the weather.
On running the program, it will show you the MAIN MENU containing four options  
1. CURRENT WEATHER REPORT
2. SEARCH HISTORY
3. DELETE SEARCH HISTORY
4. EXIT

<img width="1036" height="276" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/c957fd02-5ffb-425c-b49d-762f32a545c4" />

You can see a number is present before each option. The user has to enter the number present before the option in order to use it.

Now let's understand the functionalities of the four options of the MAIN MENU.

##CURRENT WEATHER REPORT
Enter the integer 1 in order to use this option. Then you have to enter the name of the city whose current weather conditions you want to know. The temperature (°C), humidity(%), weather description and wind speed(in kilometer per hour) will be displayed
<img width="1063" height="350" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/8e5d7bbc-2451-4cbc-b393-cc12ddc9f895" />

A message will appaer  at the bottom. Here if you Enter 'y' or 'Y', the weather forecast of the present day and upcoming two days will be displayed
<img width="1061" height="851" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/275bf491-f143-4a1d-a1ab-d410384e8856" />
 Note that in the output, date is in YYYY-MM-DD format.

 You can see at the bottom, the MAIN MENU appears, this is because the program is running in an infinite loop. In order to close the program you have to use the EXIT option by entering the integer 4. This will make the program to break the infinite loop and to exit from the program. Let's see the current weather repot of two more cities but here we are not interested to know thew forecast.
 <img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/4b71dbdf-cb3c-487c-98aa-6060c0301b08" />

##SEARCH HISTORY

Enter the integer 2 in order to use the SEARCH HISTORY of the MAIN MENU. You will get the entire search historhy containing the searched locations in newest to oldest order i.e. the city which you have searched at first will appear at the bottom and the city which you have searched at last will appear in the top.
<img width="1920" height="1080" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/c90143be-9068-47f7-8699-342e5f7164c1" />

The names of the cities in the searchrd history are stored in a binary file so that can be stored in the computer memory permanently and the data will not lost if the computer is switched off.
You can see integers before the searched cities. You can enter the integer present before the name of the cities in order to get the current weather conditions of the city from the search history itself. For example we want to get the curent weather conditions of kolkata, we have to enter 3.

<img width="1068" height="374" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/52b5d7df-f9ad-41de-a8d3-8a71118436f0" />

Again by entering 'y' or 'Y' you can have the weather forecast of that day and upcoming two days. Else press enter key if you don't want to have the weather report .

Now we are going to see the search histoey again.
<img width="1060" height="677" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/745e5292-8a35-4818-9748-627fb8013f91" />
You can see that KOLKATA is in the top having number 1 before it. This is because, from the search history we have searched kolkata , which is the last search we have done. The remaining cities in the search history can get a new position and accordingly a new number can present infront of them

Now, if we don't want to search anything from our search history then we will enter 0. Again we will have our MAIN MENU.
<img width="1076" height="455" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/411a1859-171a-4751-8323-c7ceef9de98c" />

##DELETE SEARCH HISTORY
Let's search the current weather conditions of few more cities in order to understand this option clearly.
<img width="1062" height="659" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/cfff8ad9-e6fd-4d1d-937f-3d6a25d00a6d" />
<img width="1054" height="495" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/e37a04c5-be02-4705-a464-023f999fcb44" />

Now let's see the search history
<img width="1077" height="307" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/1d2c6404-a754-482d-80ea-8a05e1b8cee0" />







 
 
  

