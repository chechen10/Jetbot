## Jetbot

![image](https://github.com/chechen10/Jetbot/assets/161907227/08a84a50-6346-45b6-a485-f770add6699b)

JetBot, which is an open-source robot based on NVIDIA
Jetson Nano. JetBot includes a set of Jupyter notebooks which cover basic robotics concepts like
programatic motor control, to more advanced topics like training a custom AI for avoiding collisions.

You can find the detail, codes and other necessary things in JETBOT folder

# 1. Strategy to win each race
   
 Strategies for winning manually controlled jetbots
      It took us 1 minute and 25 seconds to complete the race. Our strategy to win the game is to change the way we control the jetbot. We chose to use an Xbox controller to control the jetbot. We changed the original code so that it could control the jetbot from two joysticks to two triggers to control forward and backward, and added two buttons to control the left and right directions. We also let a team member who is good at controller operation to complete this race. Secondly, on the straight part of the track, let the jet robot pass as fast as possible. In the curved section, our speed will be appropriately reduced to avoid collision with obstacles on the track.

  Strategies to Win Automatic Controlled Racing
In the Road Following part, we take as many pictures as possible of the road that the jetbot is going to pass through, and use the jetbot's camera to make the jetbot better identify the route it is going to take and avoid invalid turns and leaving the track. After many tests on the track, we have improved the speed of the jetbot on the track so that the jetbot can drive smoothly and continuously automatically on the track.

# 2. Results of two tasks
The link below is the first part of the competition video
  Manually controlling the jetbot -----Race Time 1:23
      
       https://www.youtube.com/watch?v=5xvlz55M-xw
In the manual control of the jetbot, what we did well was to complete it in a very short time without hitting obstacles and the two tires did not leave the track at the same time. What we didn't do well was not being consistent in the turns.

The link below is the second part of the video 
  Automatic controlled racing  -----Race Time 3:56
      
       https://www.youtube.com/watch?v=p94XSGbaJH0
In the autonomous driving part of the jetbot, the jetbot did not collide with obstacles and the two tires did not leave the track at the same time. It was able to recognize the traffic lights well and make corresponding stop or forward instructions. What we did not do well is that due to network delays, jetbot will experience delayed response in some places.

# 3. If we can do over
In this jetbot project, we only turned on the fan on the jetbot through code at the end. If we had the opportunity to redo this jetbot project, we would turn on the fan at the beginning of running the jetbot to cool the power supply on the jetbot, instead of spending a long time naturally cooling it to avoid overheating the power supply and causing problems with the driving path of the jetbot.
We also spent too much time on the wrong path during the modeling process. This needs to be avoided by starting over.
