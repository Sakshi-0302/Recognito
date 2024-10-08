# Recognito
## Description
The **Recognito** web application acts as an **emotion detector**, 
allowing people to identify their emotions by looking at their faces.
               By keeping suspects on this project's radar, the web app will serve 
               as a **truth-finder** and **distinguisher between an object and a face** for the cops. 
               <br>
                Through its monitoring, this project
                will be able to see every emotion the suspect exhibits. Every 
                emotion will be tracked. After 24 hours, the **most noted emotion** 
                will be displayed after this app has been keeping a watchful eye 
                on culprits. <br>
                As an example-if, the most observed emotion is 
                **happiness**, which means the culprit is not hiding anything and 
                is confident that he is not wrong. When most observed emotion 
                turns into **fear**, it likely means he has a secret and is not 
                telling anyone. There is no doubt that these predictions are 
                accurate because a person who is guilty will definitely become 
                nervous, and this nervousness,fear will definitely be evident on 
                his face. 
                <br>It is almost impossible for a detective to constantly watch a 
                criminal and his emotions, but this web app can do as much as it 
                can. In addition, it eliminates the need to hire additional employees
                 for observation. 
## Features
1. It acts as a **distinguisher** between various objects and faces
2. Whenever **object other than a face** is detected in line of sight of a camera, camera screen **automatically gets freezed** and unblocks only after face comes again in line of sight of camera.
3. Whenever there is a face it **detects emotions** and displays it.
4. Most observed emotion is displayed.
5. Other than the emotion of a person, **race** and **gender** is also displayed in result section.


## Steps To Use
1. Click on the Detect button as shown on the homepage.
2. Keep your face in line of sight of camera.
3. As soon as the face gets away from camera and other object appears, camera screen gets blocked automatically.
4. It gets unblock only when face comes again in front of a camera.
5. As per the face emotions, emotions will be displayed of a person.
6. After pressing 'q' twice on the keyboard continuously camera stops and result of most observed emotion and race is displayed.


  
## Calculations/Algorithm
  1. Store each and every occurrence of emotion value into a **map or dictionary**.
  2. **Count** the occurrence of each emotion. 
  3. **Traverse** through the map and find the maximum occurence count emotion.
  4. **Display** the result and proceed the same for race.
## Tech-Stack Used
<ul>
<li>Python</li>
<li>OpenCV Library</li>
<li>Flask</li>
<li>HTML</li>
<li>CSS</li>
<li>Jupyter Notebook</li>
</ul>
  
  
## Future Scope
  1. Recognito can be taken to the **METAVERSE** in a way such that culprits in a cell will feel that Cops are there in front of them in the jail and so culprits will be forced to sit in front of the camera of this Recognito software, and this will ensure that culprits do not act over-smarter and not play any bad tactics . But in reality, no cops will be there around the culprits. Therefore, it is possible through **metaverse** to make policemen available in front of culprits without actually having them in reality.
  2. More advancements can be made in this project in the near future such as it can detect face color, hair color, face shape etc.
  3. Other than this, it can have the capability to detect any unwanted dangerous equipment hided inside the culprits body.
  


