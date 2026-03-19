# Stress Eating
## Problem
Stress eating is defined as the habit of overeating as a negative response to stress, and can lead to increased BMI or obesity. Past studies regarding stress eating relied on participants' self-reporting, which can lead to bias. Few studies have combined human physiological signals with eating measurements to examine in real time how stress influences eating behaviour.

## Solution
The PhysioHub sensor allows for real-time monitoring of stress-eating metrics such as heart rate and eating gestures. Using this data, we can determine whether the participant was stressed during the experiment and also how many times they reached for food.

## Methods
During the study, 10 participants took part in the experiment. Participants attended one Relax session and one Stress session the day after the Relax session. During both sessions, participants wore a PhysioHub wrist sensor that collected heart rate and eating gesture data. Before both sessions, participants completed a survey that assessed their current hunger level and mood. Then, they sat quietly for 3 minutes to establish a baseline heart rate. After, participants in the Relax session watched a 5-minute nature documentary. Participants in the Stress session completed a 5-minute Paced Auditory Serial Addition Task (PASAT) that has been demonstrated to induce stress in previous studies. After these activities, participants in both sessions engaged in a five-minute free snacking period where they were offered various low and high-calorie foods such as chips, apples, and cashews. Before and after each session, each snack was weighed, and the weight difference allowed us to calculate the amount of calories consumed.

## Results
Heart rate, calorie intake, and number of eating gestures were all confirmed to increase significantly from the Relax session to the Stress session. Mean heart rate increased from 72.1 beats per minute (BPM) during the Relax session to 89.8 BPM during the Stress session, with a p-value of 0.005, indicating that this difference is statistically significant. 
<img width="552" height="743" alt="image" src="https://github.com/user-attachments/assets/e76353b0-d426-4eb4-8b0e-90ffbd819cee" />
This figure compares individual caloric intake during the relaxation and stress phases, with lines connecting each participant’s values. The mean caloric intake in kcals increased from 185.2 kcal during the Relax session to 238.7 kcal during the Stress session, with a p-value < 0.001, indicating this difference is statistically significant.
<img width="554" height="740" alt="image" src="https://github.com/user-attachments/assets/9c6e47fa-24d1-4c60-ba10-748396ba0f60" />
This figure shows the number of eating actions per participant, as detected by the PhysioHub sensor. The mean number of eating actions increased from 48 actions during the Relax session to 66.5 actions during the Stress session, with a p-value of 0.001, indicating this difference is statistically significant.


## Limitations
The first limitation was the small sample size, with 10 participants. There was also no randomization between the sessions, meaning the Stress session always took place after the Relax session. During the second session, participants may have become more familiar with the experiment, altering their behavior. There were also frequent siren noises due to the nearby fire department while conducting the experiment. Finally, the gesture detection from the PhysioHub may have incorrectly detected some eating gestures, and wasn't verified.

## Future Steps
In the future, we can utilize the detected changes in heart rate as well as gesture detection to integrate Just-in-Time Adaptive Intervention (JITAI) for users who struggle with stress eating. Examples of interventions could be a notification or a quick reminder for users to assess their current hunger level and determine if they are eating due to emotional or physical factors.
