# IBM-Project-7072-1658846694
Smart Solutions For Railways

//......Build a python code, Assume u get temperature and humidity values
(generated with random function to a variable) and write a 
condition to continuously detect alarm in case of high temperature  for this QUESTIONS program AND code below showing. sir could you vefiy sir .......// 


from playsound import playsound
import random

while True:

    temp=random.randint(0,100)
    humidity=random.randint(0,100)
    if(temp > 40)  and (humidity > 50) :
        if(temp > 40):
            print("Temperature is high", temp)
            playsound("sound.mp3")
        elif(humidity>50):
            print("Humidity is high",humidity)
            playsound("sound.mp3")

    else:
        print("Temprature and humidity is normal",temp, humidity)
        
