"""

Author: Undariya Purevdorj
Due Date: 07/06/2022 - Extension - 09/06/2022
Title: Short Story: The Adventure of The Farmer
Assignment: Final assignment - Create and Animate a Short Story

"""


from graphics import*

#TITLE FRAME

#Establish the screen window and set the background day time colour
titleWindow = GraphWin ("Title Window", 600, 500)
titleWindow.setBackground("black")

#Display of the title
titleStory = "The Adventure of The Farmer"
titleDisplay = Text(Point(300, 280), titleStory)
titleDisplay.setTextColor("white")
titleDisplay.setSize(20)
titleDisplay.setFace("helvetica")
titleDisplay.draw(titleWindow)

time.sleep(1) #pause

#Display of the sub-title 
titleStory2 = "A Short Story by Undariya P."
subTitleDisplay = Text(Point(300, 340), titleStory2)
subTitleDisplay.setTextColor("white")
subTitleDisplay.setSize(15)
subTitleDisplay.setFace("helvetica")
subTitleDisplay.draw(titleWindow)    

time.sleep(2) #pause

#Erase the titles
titleDisplay.undraw()
subTitleDisplay.undraw()

#Close the title window 
titleWindow.close()







#PRE-STORY FRAME -> REFERENCE TO PICTURE PROGRAM ASSIGNMENT

#Establish the screen window and set the background colour
earlyStory = GraphWin ("Pre-story introduction", 600, 500)
earlyStory.setBackground("black")

#Display of the title
display1 = "Let's begin."
messageOne = Text(Point(300, 280), display1)
messageOne.setTextColor("white")
messageOne.setSize(20)
messageOne.setFace("helvetica")
messageOne.draw(earlyStory)

time.sleep(1) #pause

#Display of the sub-title
display2 = "Earlier in the story..."
messageTwo = Text(Point(300, 340), display2)
messageTwo.setTextColor("white")
messageTwo.setSize(20)
messageTwo.setFace("helvetica")
messageTwo.draw(earlyStory)    

time.sleep(2) #pause

#Erase the titles
messageOne.undraw()
messageTwo.undraw()



#THE PRE-STORY BEGINS:

#Change the background to sky blue 
earlyStory.setBackground(color_rgb(135, 206, 250))

#Establish the main ground of the window -> the field
field = Rectangle (Point(0, 460), Point(600, 500))
field.setFill(color_rgb(0, 100, 0))
field.draw(earlyStory)

#Set up the 2 mountains behind the cows
#1)set up the taller mountain
bigMountain = Polygon (Point(400, 40), Point(590, 460), Point(225, 460))
bigMountain.setFill(color_rgb(34, 139, 34))
bigMountain.setOutline("black")
bigMountain.draw(earlyStory)

#2)set up the smaller mountain
smallMountain = Polygon (Point(235, 135), Point(70, 460), Point(400, 460)) 
smallMountain.setFill(color_rgb(34, 139, 34))
smallMountain.setOutline("black")
smallMountain.draw(earlyStory) 

#set up the sun
sun = Circle(Point(95, 115), 60)
sun.setFill(color_rgb(255, 255, 0))
sun.setOutline("black")
sun.draw(earlyStory)

#Set up the tree in the middle
#1) set up the trunk
treeTrunk = Rectangle (Point(245, 350),Point(260, 460))
treeTrunk.setFill(color_rgb(139, 69, 19))
treeTrunk.draw(earlyStory)

#2) set up the branches and leaves
treeBranch1 = Circle (Point(250, 340), 30)
treeBranch1.setFill(color_rgb(0, 100, 0))
treeBranch1.setOutline(color_rgb(0, 100, 0))
treeBranch1.draw(earlyStory)

treeBranch2 = Circle (Point(230, 380), 30)
treeBranch2.setFill(color_rgb(0, 100, 0))
treeBranch2.setOutline(color_rgb(0, 100, 0))
treeBranch2.draw(earlyStory)

treeBranch3 = Circle (Point(270, 380), 30)
treeBranch3.setFill(color_rgb(0, 100, 0))
treeBranch3.setOutline(color_rgb(0, 100, 0))
treeBranch3.draw(earlyStory)

#Draw the bigger cow (the protagonist)
#1) draw the body
cowBody = Rectangle (Point(365,330), Point(510,420))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(earlyStory)

#2) draw the head
cowHead = Rectangle (Point(305, 340), Point(365, 400))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(earlyStory)

#3) draw the legs
cowLeg1 = Rectangle (Point(495, 460), Point(510, 420))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(earlyStory)

cowLeg2 = Rectangle (Point(465, 460), Point(480, 420))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(earlyStory)

cowLeg3 = Rectangle (Point(395, 460), Point(410, 420))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(earlyStory)

cowLeg4 = Rectangle (Point(365, 460), Point(380, 420))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(earlyStory)

#4) draw the ears
cowEar1 = Rectangle (Point(305, 340), Point(312, 330))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(earlyStory)

cowEar2 = Rectangle (Point(355, 340), Point(362, 330))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(earlyStory)

#5) draw the black spots
cowSpot1 = Circle (Point(480, 390), 20)
cowSpot1.setFill("black")
cowSpot1.draw(earlyStory)

cowSpot2 = Circle (Point(435, 355), 20)
cowSpot2.setFill("black")
cowSpot2.draw(earlyStory)

cowSpot3 = Circle (Point(395, 390), 20)
cowSpot3.setFill("black")
cowSpot3.draw(earlyStory)

#Draw the smaller cow
#1) draw the body
smallCowBody = Rectangle (Point(150, 420), Point(50, 370))
smallCowBody.setFill(color_rgb(205, 133, 63))
smallCowBody.setOutline("black")
smallCowBody.draw(earlyStory)

#2) draw the head
smallCowHead = Rectangle (Point(150, 415), Point(190, 375))
smallCowHead.setFill("white")
smallCowHead.setOutline("black")
smallCowHead.draw(earlyStory)

#3) draw the legs
smallCowLeg1 = Rectangle (Point(150, 420), Point(140, 460))
smallCowLeg1.setFill("white")
smallCowLeg1.setOutline("black")
smallCowLeg1.draw(earlyStory)

smallCowLeg2 = Rectangle (Point(50, 420), Point(60, 460))
smallCowLeg2.setFill("white")
smallCowLeg2.setOutline("black")
smallCowLeg2.draw(earlyStory)

smallCowLeg3 = Rectangle (Point(70, 420), Point(80, 460))
smallCowLeg3.setFill("white")
smallCowLeg3.setOutline("black")
smallCowLeg3.draw(earlyStory)

smallCowLeg4 = Rectangle (Point(130, 420), Point(120, 460))
smallCowLeg4.setFill("white")
smallCowLeg4.setOutline("black")
smallCowLeg4.draw(earlyStory)

#4) draw the ears
smallCowEar1 = Rectangle (Point(150, 375), Point(157, 365))
smallCowEar1.setFill(color_rgb(205, 133, 63))
smallCowEar1.setOutline("black")
smallCowEar1.draw(earlyStory)

smallCowEar2 = Rectangle (Point(180, 375), Point(187, 365))
smallCowEar2.setFill(color_rgb(205, 133, 63))
smallCowEar2.setOutline("black")
smallCowEar2.draw(earlyStory)

#5) draw the black spots
smallCowSpot1 = Circle (Point(130, 405), 11)
smallCowSpot1.setFill("white")
smallCowSpot1.draw(earlyStory)

smallCowSpot2 = Circle (Point(100, 385), 11)
smallCowSpot2.setFill("white")
smallCowSpot2.draw(earlyStory)

smallCowSpot3 = Circle (Point(70, 405), 11)
smallCowSpot3.setFill("white")
smallCowSpot3.draw(earlyStory)

#Set up the spaceship
#1) Establish the lightbeam
lightBeam = Polygon (Point(630, 170), Point(770, 170), Point(820, 460), Point(570, 460))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(earlyStory)

#2) set up the main body of the spaceship
spaceShip = Oval (Point(600, 150), Point(800, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(earlyStory)

#3) set up the window of the spaceship
window = Oval (Point(670, 160), Point(720, 180))
window.setFill(color_rgb(224, 255, 255))
window.setOutline("black")
window.draw(earlyStory)

#spaceship comes in and invades the big cow (mother cow)
while True:
    spaceShip.move(-2, 0)
    window.move(-2, 0)
    lightBeam.move(-2, 0)
    update(30) #30 FPS

    #when the spaceship is right above the cow
    if spaceShip.getCenter().getX() == 410:
        break

#Make the big cow reappear in front of the lightbeam
#Draw the bigger cow (the protagonist)
#1) draw the body
cowBody = Rectangle (Point(365, 330), Point(510, 420))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(earlyStory)

#2) draw the head
cowHead = Rectangle (Point(305, 340), Point(365, 400))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(earlyStory)

#3) draw the legs
cowLeg1 = Rectangle (Point(495,460), Point(510, 420))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(earlyStory)

cowLeg2 = Rectangle (Point(465, 460), Point(480, 420))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(earlyStory)

cowLeg3 = Rectangle (Point(395, 460), Point(410, 420))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(earlyStory)

cowLeg4 = Rectangle (Point(365, 460), Point(380, 420))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(earlyStory)

#4) draw the ears
cowEar1 = Rectangle (Point(305, 340), Point(312, 330))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(earlyStory)

cowEar2 = Rectangle (Point(355, 340), Point(362, 330))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(earlyStory)

#5) draw the black spots
cowSpot1 = Circle (Point(480, 390), 20)
cowSpot1.setFill("black")
cowSpot1.draw(earlyStory)

cowSpot2 = Circle (Point(435, 355), 20)
cowSpot2.setFill("black")
cowSpot2.draw(earlyStory)

cowSpot3 = Circle (Point(395, 390), 20)
cowSpot3.setFill("black")
cowSpot3.draw(earlyStory)                

#The bigger cow moves up and gets invaded by the spaceship
for i in range(0, 260): #move all the big cow components UP
    cowBody.move(0, -0.5)
    cowHead.move(0, -0.5)
    cowLeg1.move(0, -0.5)
    cowLeg2.move(0, -0.5)
    cowLeg3.move(0, -0.5)
    cowLeg4.move(0, -0.5)
    cowEar1.move(0, -0.5)
    cowEar2.move(0, -0.5)
    cowSpot1.move(0, -0.5)
    cowSpot2.move(0, -0.5)
    cowSpot3.move(0, -0.5)

    #when the cow is right below the spaceship, where the invasion occurs.
    if cowBody.getCenter().getY() == 260: #make the big cow disappear
        cowHead.undraw()
        cowBody.undraw()
        cowLeg1.undraw()
        cowLeg2.undraw()
        cowLeg3.undraw()
        cowLeg4.undraw()
        cowEar1.undraw()
        cowEar2.undraw()
        cowSpot1.undraw()
        cowSpot2.undraw()
        cowSpot3.undraw()

#spaceship goes away (with the cow)
for i in range(0, 70):
    spaceShip.move(5, 0)
    window.move(5, 0)
    lightBeam.move(5, 0)
    update(15) #15 FPS

#Close the frame and proceed to the next one
earlyStory.close()








#CURRENT STORY FRAME INTRODUCTION

#Establish the screen window and set the background colour
currentStory = GraphWin ("Real Story Introduction", 600, 500)
currentStory.setBackground("black")

#Display of the title
displayTxt = "Let the REAL story begin..."
nowMessage = Text(Point(300, 280), displayTxt)
nowMessage.setTextColor("white")
nowMessage.setSize(20)
nowMessage.setFace("helvetica")
nowMessage.draw(currentStory)

time.sleep(4) #pause

#Erase the messages
nowMessage.undraw()
currentStory.close()







#ADDITIONAL FRAME -> ENTRY BOX USER INPUT (used TKINTER)

#Set up the import feature (tkinter)
import tkinter as tk
from tkinter import simpledialog

#Establish the entry user input box -> farmer shirt colour selection 
userInput = simpledialog.askstring(title="Entry User Input Box 1",
                                  prompt="Please select a colour for the farmer's shirt. Please choose between red, yellow, blue, green, or cyan.")

#Display the chosen colour on the SHELL window
print("Your chosen colour for the farmer's shirt is", userInput + ".")









#FIRST FRAME

#Establish the first screen window and change the window's background to blue (sky)
windowOne = GraphWin ("Short story: Frame 1", 600, 500)
windowOne.setBackground(color_rgb(135, 206, 250))

#Establish the main ground of the window -> the field
greenField = Rectangle (Point(0, 460), Point(600, 500))
greenField.setFill(color_rgb(0, 100, 0))
greenField.draw(windowOne)

#Set up the 2 mountains behind the cows:
#1)set up the taller mountain
bigMountain = Polygon (Point(400, 40), Point(590, 460), Point(225, 460))
bigMountain.setFill(color_rgb(34, 139, 34))
bigMountain.setOutline("black")
bigMountain.draw(windowOne)

#2)set up the smaller mountain
smallMountain = Polygon (Point(235, 135), Point(70, 460), Point(400, 460)) 
smallMountain.setFill(color_rgb(34, 139, 34))
smallMountain.setOutline("black")
smallMountain.draw(windowOne) 

#Set up the sun
sun = Circle(Point(95, 115), 60)
sun.setFill(color_rgb(255, 255, 0))
sun.setOutline("black")
sun.draw(windowOne)

#Set up the tree in the middle:
#1) set up the trunk
treeTrunk = Rectangle (Point(245, 350),Point(260, 460))
treeTrunk.setFill(color_rgb(139, 69, 19))
treeTrunk.draw(windowOne)

#2) set up the branches and leaves
treeBranch1 = Circle (Point(250, 340), 30)
treeBranch1.setFill(color_rgb(0, 100, 0))
treeBranch1.setOutline(color_rgb(0, 100, 0))
treeBranch1.draw(windowOne)

treeBranch2 = Circle (Point(230, 380), 30)
treeBranch2.setFill(color_rgb(0, 100, 0))
treeBranch2.setOutline(color_rgb(0, 100, 0))
treeBranch2.draw(windowOne)
    
treeBranch3 = Circle (Point(270, 380), 30)
treeBranch3.setFill(color_rgb(0, 100, 0))
treeBranch3.setOutline(color_rgb(0, 100, 0))
treeBranch3.draw(windowOne)
    
#Draw the bigger cow (the protagonist):
#1) draw the body
cowBody = Rectangle (Point(365,330), Point(510,420))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(windowOne)

#2) draw the head
cowHead = Rectangle (Point(305, 340), Point(365, 400))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowOne)

#3) draw the legs
cowLeg1 = Rectangle (Point(495, 460), Point(510, 420))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowOne)

cowLeg2 = Rectangle (Point(465, 460), Point(480, 420))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(windowOne)

cowLeg3 = Rectangle (Point(395, 460), Point(410, 420))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowOne)
    
cowLeg4 = Rectangle (Point(365, 460), Point(380, 420))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(windowOne)

#4) draw the ears
cowEar1 = Rectangle (Point(305, 340), Point(312, 330))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(windowOne)

cowEar2 = Rectangle (Point(355, 340), Point(362, 330))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(windowOne)

#5) draw the black spots
cowSpot1 = Circle (Point(480, 390), 20)
cowSpot1.setFill("black")
cowSpot1.draw(windowOne)

cowSpot2 = Circle (Point(435, 355), 20)
cowSpot2.setFill("black")
cowSpot2.draw(windowOne)

cowSpot3 = Circle (Point(395, 390), 20)
cowSpot3.setFill("black")
cowSpot3.draw(windowOne)
    
#Draw the smaller cow:
#1) draw the body
smallCowBody = Rectangle (Point(150, 420), Point(50, 370))
smallCowBody.setFill(color_rgb(205, 133, 63))
smallCowBody.setOutline("black")
smallCowBody.draw(windowOne)

#2) draw the head
smallCowHead = Rectangle (Point(150, 415), Point(190, 375))
smallCowHead.setFill("white")
smallCowHead.setOutline("black")
smallCowHead.draw(windowOne)

#3) draw the legs
smallCowLeg1 = Rectangle (Point(150, 420), Point(140, 460))
smallCowLeg1.setFill("white")
smallCowLeg1.setOutline("black")
smallCowLeg1.draw(windowOne)

smallCowLeg2 = Rectangle (Point(50, 420), Point(60, 460))
smallCowLeg2.setFill("white")
smallCowLeg2.setOutline("black")
smallCowLeg2.draw(windowOne)

smallCowLeg3 = Rectangle (Point(70, 420), Point(80, 460))
smallCowLeg3.setFill("white")
smallCowLeg3.setOutline("black")
smallCowLeg3.draw(windowOne)

smallCowLeg4 = Rectangle (Point(130, 420), Point(120, 460))
smallCowLeg4.setFill("white")
smallCowLeg4.setOutline("black")
smallCowLeg4.draw(windowOne)

#4) draw the ears
smallCowEar1 = Rectangle (Point(150, 375), Point(157, 365))
smallCowEar1.setFill(color_rgb(205, 133, 63))
smallCowEar1.setOutline("black")
smallCowEar1.draw(windowOne)

smallCowEar2 = Rectangle (Point(180, 375), Point(187, 365))
smallCowEar2.setFill(color_rgb(205, 133, 63))
smallCowEar2.setOutline("black")
smallCowEar2.draw(windowOne)

#5) draw the black spots
smallCowSpot1 = Circle (Point(130, 405), 11)
smallCowSpot1.setFill("white")
smallCowSpot1.draw(windowOne)

smallCowSpot2 = Circle (Point(100, 385), 11)
smallCowSpot2.setFill("white")
smallCowSpot2.draw(windowOne)

smallCowSpot3 = Circle (Point(70, 405), 11)
smallCowSpot3.setFill("white")
smallCowSpot3.draw(windowOne)

#Set up the farmer
#1) set up the first part of the hat
topHat = Circle (Point(545, 240), 40)
topHat.setFill(color_rgb(218,165,32))
topHat.setOutline("black")
topHat.draw(windowOne)
    
#2) set up the head
farmerHead = Circle (Point(547, 270), 50 )
farmerHead.setFill(color_rgb(250,235,215))
farmerHead.setOutline("black")
farmerHead.draw(windowOne)

#3) set up the second part of the hat
bottomHat = Oval(Point(460, 221), Point(625, 255))
bottomHat.setFill(color_rgb(184,134,11))
bottomHat.setOutline("black")
bottomHat.draw(windowOne)

#4) set up the chest/shirt
farmerShirt = Rectangle (Point(525, 320), Point(570, 410))
farmerShirt.setOutline("black")
farmerShirt.draw(windowOne)

#Farmer's shirt colour is selected by the user 
if userInput == "red":
    farmerShirt.setFill("red")

elif userInput == "green":
    farmerShirt.setFill("green")

elif userInput == "yellow":
    farmerShirt.setFill("yellow")

elif userInput == "cyan":
    farmerShirt.setFill("cyan")

elif userInput == "blue":
    farmerShirt.setFill("blue")

#5) set up the legs
farmerLegOne = Rectangle (Point(525, 410), Point(540, 460))
farmerLegOne.setFill(color_rgb(0, 0, 128))
farmerLegOne.setOutline("black")
farmerLegOne.draw(windowOne)

farmerLegTwo = Rectangle (Point(555, 410), Point(570, 460))
farmerLegTwo.setFill(color_rgb(0, 0, 128))
farmerLegTwo.setOutline("black")
farmerLegTwo.draw(windowOne)

#6) set up the arms
farmerArmOne = Rectangle (Point(510, 320), Point(525, 390))
farmerArmOne.setFill(color_rgb(250, 235, 215))
farmerArmOne.setOutline("black")
farmerArmOne.draw(windowOne)

farmerArmTwo = Rectangle (Point (570, 320), Point(585, 390))
farmerArmTwo.setFill(color_rgb(250, 235, 215))
farmerArmTwo.setOutline("black")
farmerArmTwo.draw(windowOne)
    
#7) set up the eyes
farmerEyeOne = Rectangle (Point(535, 265), Point(515, 280))
farmerEyeOne.setFill("white")
farmerEyeOne.setOutline("black")
farmerEyeOne.draw(windowOne)

farmerEyeTwo = Rectangle (Point(575, 265), Point(555, 280))
farmerEyeTwo.setFill("white")
farmerEyeTwo.setOutline("black")
farmerEyeTwo.draw(windowOne)

#the pupils 
farmerEye1Pupil = Circle (Point(518, 273), 2) 
farmerEye1Pupil.setFill("black")
farmerEye1Pupil.draw(windowOne)

farmerEye2Pupil = Circle (Point(558, 273), 2)
farmerEye2Pupil.setFill("black")
farmerEye2Pupil.draw(windowOne)

#8) Set up the mouth(s):
#closed mouth 
farmerMouthOne = Line (Point(535, 300), Point(550, 300))
farmerMouthOne.setFill("white")
farmerMouthOne.setOutline("black")
farmerMouthOne.draw(windowOne)

#open mouth -> later used in the animation
farmerMouthTwo = Oval (Point (535 ,290), Point(550, 305))
farmerMouthTwo.setFill(color_rgb(255,160,122))
farmerMouthTwo.setOutline("black")

#Animation begins:
#1) Once the farmer is set up, he comes in to the frame from the right
for i in range(0, 1):

    time.sleep(1) #pause

    #the farmer must stop behind the big cow 
    topHat.move(-5,0)
    farmerHead.move(-5,0)
    bottomHat.move(-5, 0)
    farmerShirt.move(-5,0)
    farmerLegOne.move(-5,0)
    farmerLegTwo.move(-5,0)
    farmerArmOne.move(-5,0)
    farmerArmTwo.move(-5,0)
    farmerEyeOne.move(-5,0)
    farmerEyeTwo.move(-5,0)
    farmerEye1Pupil.move(-5,0)
    farmerEye2Pupil.move(-5,0)
    farmerMouthOne.move(-5,0)
    update (10) #10 FPS

    #2) The farmer's messages animation:
    
    time.sleep(1)#pause
        
    #The text bubble to display the farmer's message:
    #the bottom triangle 
    indicationShape = Polygon (Point(400, 230), Point(400, 190), Point(480, 270))
    indicationShape.setFill("white")
    indicationShape.draw(windowOne)

    #the bubble
    bubbleText = Circle (Point(400, 180), 75)
    bubbleText.setFill("white")
    bubbleText.setOutline("black")
    bubbleText.draw(windowOne)

    #The texts that are going to be displayed
    farmerFirstMessage = "Hm... this is not my cow."
    farmerSecondMessage = "Where is my real cow?"
    farmerThirdMessage = "Oh no..."
    farmerFourthMessage = "The spaceship took it."
    farmerFifthMessage = "I have to get my cow back!"
        
    #Farmer's messages
    #1) text 
    farmerTxtOne = Text (Point(405, 190), farmerFirstMessage)
    farmerTxtOne.setTextColor("black")
    farmerTxtOne.setSize(9)
    farmerTxtOne.setFace("helvetica")
    farmerTxtOne.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtOne.undraw() #first text goes away

    #2) text
    farmerTxtTwo = Text (Point(405, 190), farmerSecondMessage)
    farmerTxtTwo.setTextColor("black")
    farmerTxtTwo.setSize(10)
    farmerTxtTwo.setFace("helvetica")
    farmerTxtTwo.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtTwo.undraw()#second text goes away

    #3) text
    #The farmer is shocked -> opens mouth
    time.sleep(1) #pause
    farmerMouthOne.undraw()
        
    time.sleep(0.8)#pause
    farmerMouthTwo.draw(windowOne) #farmer's mouth opens

    farmerTxtThree = Text (Point(405, 190), farmerThirdMessage)
    farmerTxtThree.setTextColor("black")
    farmerTxtThree.setSize(10)
    farmerTxtThree.setFace("helvetica")
    farmerTxtThree.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtThree.undraw()#third text goes away

    #4) text
    farmerTxtFour = Text (Point(405, 190), farmerFourthMessage)
    farmerTxtFour.setTextColor("black")
    farmerTxtFour.setSize(10)
    farmerTxtFour.setFace("helvetica")
    farmerTxtFour.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtFour.undraw()#fourth text goes away

    #5) text
    farmerTxtFive = Text (Point(405, 190), farmerFifthMessage)
    farmerTxtFive.setTextColor("black")
    farmerTxtFive.setSize(8)
    farmerTxtFive.setFace("helvetica")
    farmerTxtFive.draw(windowOne)

    time.sleep(1)#pause
    farmerTxtFive.undraw()#fifth text goes away

    #bubble text disappears
    time.sleep(0.5)
    bubbleText.undraw()
    indicationShape.undraw()

    #farmer leaves to get his cow back
    topHat.move(5, 0)
    farmerHead.move(5, 0)
    bottomHat.move(5, 0)
    farmerShirt.move(5, 0)
    farmerLegOne.move(5, 0)
    farmerLegTwo.move(5, 0)
    farmerArmOne.move(5, 0)
    farmerArmTwo.move(5, 0)
    farmerEyeOne.move(5, 0)
    farmerEyeTwo.move(5, 0)
    farmerEye1Pupil.move(5, 0)
    farmerEye2Pupil.move(5, 0)
    farmerMouthTwo.move(5, 0)
    update (10) #10 FPS
        
#Keyboard input feature from user - Small Cow Animation:

#Display the instructions -> move the small cow right or left using specific keys.

#Display Text Instructions
displayText = "Please press 'a' to move the small cow left and 'd' to move it right"
bottomDisplay = Text(Point(300, 470), displayText)
bottomDisplay.setTextColor("white")
bottomDisplay.setSize(12)
bottomDisplay.setFace("helvetica")
bottomDisplay.setStyle("bold")
bottomDisplay.draw(windowOne)

time.sleep(3) #pause

displayText2 = "You are only allowed maximum TEN 'a' and 'b' clicks."
bottomDisplay2 = Text(Point(300, 490), displayText2)
bottomDisplay2.setTextColor("white")
bottomDisplay2.setSize(10)
bottomDisplay2.setFace("helvetica")
bottomDisplay2.draw(windowOne)

#keyboard controlled animation  loop (from user)
for i in range(0, 10):
    key = windowOne.getKey()
    print(key)

    #the small cow moves left feature
    if key == "a": #move all components left
        smallCowHead.move(-10, 0)
        smallCowBody.move(-10, 0)
        smallCowLeg1.move(-10, 0)
        smallCowLeg2.move(-10, 0)
        smallCowLeg3.move(-10, 0)
        smallCowLeg4.move(-10, 0)
        smallCowEar1.move(-10, 0)
        smallCowEar2.move(-10, 0)
        smallCowSpot1.move(-10, 0)
        smallCowSpot2.move(-10, 0)
        smallCowSpot3.move(-10, 0)
            
    #the small cow moves right feature
    elif key == "d": #move all components right
        smallCowHead.move(10, 0)
        smallCowBody.move(10, 0)
        smallCowLeg1.move(10, 0)
        smallCowLeg2.move(10, 0)
        smallCowLeg3.move(10, 0)
        smallCowLeg4.move(10, 0)
        smallCowEar1.move(10, 0)
        smallCowEar2.move(10, 0)
        smallCowSpot1.move(10, 0)
        smallCowSpot2.move(10, 0)
        smallCowSpot3.move(10, 0)

#Remove the keyboard control feature instruction display
time.sleep(1) #pause
bottomDisplay.undraw()
bottomDisplay2.undraw()

time.sleep(2) #pause

#User Instruction -> Transition to the next frame
instructionText = "This frame is over, please proceed to the next frame by clicking anywhere on the frame!"
nextFrame = Text(Point(300, 480), instructionText)
nextFrame.setTextColor("white")
nextFrame.setSize(11)
nextFrame.setFace("helvetica")
nextFrame.draw(windowOne) 
   
#user mouse click -> transition to the next frame
windowOne.getMouse() #user clicks anywhere with the mouse
windowOne.close()#frame closes








#ADDITIONAL FRAME -> ENTRY BOX USER INPUT (used TKINTER)

#Set up the import feature
import tkinter as tk
from tkinter import simpledialog

#Establish the entry user input box -> truck colour selection 
userInput2 = simpledialog.askstring(title="Entry User Input Box 2",
                                  prompt="Please select a colour for the farmer's truck. Please choose between white, grey, green3, or red4.")








#SECOND FRAME

#Display the chosen colour 
print("Your chosen colour for the truck is", userInput2 + ".")

#Establish the screen window and set the background day time colour
windowTwo = GraphWin ("Short story: Frame 2", 600, 500)
windowTwo.setBackground(color_rgb(135, 206, 250))

#Set up the green field 
greenField = Rectangle (Point(0, 290), Point(600, 500))
greenField.setFill(color_rgb(34, 139, 34))
greenField.setOutline("black")
greenField.draw(windowTwo)

#Set up the mountains
mountainOne = Polygon (Point(400, 290), Point(550, 50), Point(700, 290))
mountainOne.setFill(color_rgb(144, 238, 144))
mountainOne.setOutline("black")
mountainOne.draw(windowTwo)

mountainTwo = Polygon (Point(200, 290), Point(340, 50), Point(500, 290))
mountainTwo.setFill(color_rgb(144, 238, 144))
mountainTwo.setOutline("black")
mountainTwo.draw(windowTwo)

mountainThree = Polygon (Point(0, 290), Point(140, 50), Point(320, 290))
mountainThree.setFill(color_rgb(144, 238, 144))
mountainThree.setOutline("black")
mountainThree.draw(windowTwo)

#Set up the houses:
#1) 1st house
#the main building
houseOne = Rectangle (Point(40, 180), Point(160, 290))
houseOne.setFill(color_rgb(238, 232, 170))
houseOne.setOutline("black")
houseOne.draw(windowTwo)

#the roof
houseOneRoof = Polygon (Point(100, 130), Point(160, 180), Point(40, 180))
houseOneRoof.setFill(color_rgb(184,134,11))
houseOneRoof.setOutline("black")
houseOneRoof.draw(windowTwo)
    
#the door
houseOneDoor = Rectangle (Point(65, 230), Point(135, 290))
houseOneDoor.setFill(color_rgb(184, 134, 11))
houseOneDoor.setOutline("black")
houseOneDoor.draw(windowTwo)

houseTwoHandle = Circle(Point(73, 270), 3)
houseTwoHandle.setFill("black")
houseTwoHandle.draw(windowTwo)

#2) 2nd house
#the main building
houseTwo = Rectangle (Point(200, 180), Point(320, 290))
houseTwo.setFill(color_rgb(238, 232, 170))
houseTwo.setOutline("black")
houseTwo.draw(windowTwo)

#the roof
houseTwoRoof = Polygon (Point(260, 130), Point(320, 180), Point(200, 180))
houseTwoRoof.setFill(color_rgb(184, 134, 11))
houseTwoRoof.setOutline("black")
houseTwoRoof.draw(windowTwo)

#the door
houseTwoDoor = Rectangle (Point(225, 230), Point(295, 290))
houseTwoDoor.setFill(color_rgb(184, 134, 11))
houseTwoDoor.setOutline("black")
houseTwoDoor.draw(windowTwo)

houseTwoHandle = Circle(Point(233, 270), 3)
houseTwoHandle.setFill("black")
houseTwoHandle.draw(windowTwo)
                            
#3) 3rd house
houseThird= Rectangle (Point(520, 180), Point(625, 290))
houseThird.setFill(color_rgb(238, 232, 170))
houseThird.setOutline("black")
houseThird.draw(windowTwo)

houseThirdRoof = Polygon (Point(600, 130), Point(650, 180), Point(520, 180))
houseThirdRoof.setFill(color_rgb(184, 134, 11))
houseThirdRoof.setOutline("black")
houseThirdRoof.draw(windowTwo)

houseThirdDoor = Rectangle (Point(545, 230), Point(645, 290))
houseThirdDoor.setFill(color_rgb(184, 134, 11))
houseThirdDoor.setOutline("black")
houseThirdDoor.draw(windowTwo)

houseThirdHandle = Circle(Point(553, 270), 3)
houseThirdHandle.setFill("black")
houseThirdHandle.draw(windowTwo)


#Set up the road:
#grey part
greyRoad = Rectangle (Point(0, 340), Point(600, 460))
greyRoad.setFill(color_rgb(169, 169, 169))
greyRoad.setOutline("black")
greyRoad.draw(windowTwo)

#yellow lines
yellowLineOne = Rectangle (Point(-20, 395), Point(20, 405)) 
yellowLineOne.setFill("yellow")
yellowLineOne.draw(windowTwo)

yellowLineTwo = Rectangle (Point(60, 395), Point(100, 405)) 
yellowLineTwo.setFill("yellow")
yellowLineTwo.draw(windowTwo)

yellowLineThree = Rectangle (Point(140, 395), Point(180, 405)) 
yellowLineThree.setFill("yellow")
yellowLineThree.draw(windowTwo)

yellowLineFour = Rectangle (Point(220, 395), Point(260, 405)) 
yellowLineFour.setFill("yellow")
yellowLineFour.draw(windowTwo)

yellowLineFive = Rectangle (Point(300, 395), Point(340, 405)) 
yellowLineFive.setFill("yellow")
yellowLineFive.draw(windowTwo)

yellowLineSix = Rectangle (Point(380, 395), Point(420, 405)) 
yellowLineSix.setFill("yellow")
yellowLineSix.draw(windowTwo)

yellowLineSeven = Rectangle (Point(460, 395), Point(500, 405)) 
yellowLineSeven.setFill("yellow")
yellowLineSeven.draw(windowTwo)

yellowLineEight = Rectangle (Point(540, 395), Point(580, 405)) 
yellowLineEight.setFill("yellow")
yellowLineEight.draw(windowTwo)

yellowLineNine = Rectangle (Point(620, 395), Point(660, 405)) 
yellowLineNine.setFill("yellow")
yellowLineNine.draw(windowTwo)

#Set up the sun
brightSun = Circle (Point(60, 60), 40)
brightSun.setFill(color_rgb(255, 255, 0))
brightSun.setOutline("black")
brightSun.draw(windowTwo)

#Set up the farmer's truck:
#1) the main body
carBody = Rectangle (Point(-200, 320), Point(-70, 395))
carBody.setOutline("black")
carBody.draw(windowTwo)

#2) the front body
carFront = Rectangle (Point(-70, 340), Point(-10, 395))
carFront.setOutline("black")
carFront.draw(windowTwo)

#Truck's colour is selected/decided by the user
if userInput2 == "white":
    carBody.setFill("white")
    carFront.setFill("white")

elif userInput2 == "grey":
    carBody.setFill("grey")
    carFront.setFill("grey")

elif userInput2 == "green3":
    carBody.setFill("green3")
    carFront.setFill("green3")

elif userInput2 == "red4":
    carBody.setFill("red4")
    carFront.setFill("red4")
            

#3) the front window
carFrontWindow = Rectangle (Point(-55, 350), Point(-10, 380))
carFrontWindow.setFill(color_rgb(230, 230, 250))
carFrontWindow.draw(windowTwo)
    
#4) the wheels
# wheel 1
carWheelOne = Circle (Point(-175, 393), 23)
carWheelOne.setFill("black")
carWheelOne.setOutline("black")
carWheelOne.draw(windowTwo)

carWheelOneMetal = Circle (Point(-175, 393), 13)
carWheelOneMetal.setFill(color_rgb(211, 211, 211))
carWheelOneMetal.setOutline("white")
carWheelOneMetal.draw(windowTwo)

# wheel 2
carWheelTwo = Circle (Point(-100, 393), 23)
carWheelTwo.setFill("black")
carWheelTwo.setOutline('black')
carWheelTwo.draw(windowTwo)

carWheelTwoMetal = Circle (Point(-100, 393), 13)
carWheelTwoMetal.setFill(color_rgb(211, 211, 211))
carWheelTwoMetal.setOutline("white")
carWheelTwoMetal.draw(windowTwo)
    
#Set up the Spaceship:
#1) set up the lightbeam
lightBeam = Polygon (Point(-130, 170), Point(-270, 170), Point(-320, 430), Point(-70, 430))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(windowTwo)

#2) set up the main body 
spaceShip = Oval (Point(-100, 150), Point(-300, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(windowTwo)
    
#3) set up the window
spaceShipWindow = Oval (Point(-170, 160), Point(-220, 180))
spaceShipWindow.setFill(color_rgb(224, 255, 255))
spaceShipWindow.setOutline("black")
spaceShipWindow.draw(windowTwo)

#Animation begins:

#The farmer is in the truck and he chases after the spaceship
for i in range(0, 100):
        
    #spaceship moves right - getting chased
    lightBeam.move(15, 0)
    spaceShip.move(15, 0)
    spaceShipWindow.move(15, 0)
    update (15) #15 FPS

for i in range(0, 100):

    #farmer's truck moves right - chases the spaceship
    carBody.move(15, 0)
    carFront.move(15, 0)
    carFrontWindow.move(15, 0)
    carWheelOne.move(15, 0)
    carWheelTwo.move(15, 0)
    carWheelOneMetal.move(15, 0)
    carWheelTwoMetal.move(15, 0)
    update(20) #20 FPS
 


#User Instruction for the next frame's transition
message = "This frame is over, please proceed to the next frame by clicking anywhere on the frame!"
nextFrameTransition = Text(Point(300, 480), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(11)
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowTwo)


windowTwo.getMouse() #clicks with mouse anywhere on the frame
windowTwo.close() #this frame closes













#THIRD FRAME

#set the window screen and background
windowThree = GraphWin("Short story: Frame 3", 600, 500)
windowThree.setBackground(color_rgb(135, 206, 250))

#Set up the green field 
greenField = Rectangle (Point(0, 320), Point(600, 500))
greenField.setFill(color_rgb(34,139,34))
greenField.setOutline("black")
greenField.draw(windowThree)

#Set up the sun
brightSun = Circle (Point(60, 60), 40)
brightSun.setFill(color_rgb(255, 255, 0))
brightSun.setOutline("black")
brightSun.draw(windowThree)

#Set up the mountains
bigMountain = Polygon (Point(180, 320), Point(320, 20), Point(470, 320))
bigMountain.setFill(color_rgb(144,238,144))
bigMountain.setOutline("black")
bigMountain.draw(windowThree)

smallMountain = Polygon (Point(20, 320), Point(160, 80), Point(290, 320))
smallMountain.setFill(color_rgb(144,238,144))
smallMountain.setOutline("black")
smallMountain.draw(windowThree)

#Set up the trees
treeOneTrunk = Rectangle (Point(45, 270), Point(70, 320))
treeOneTrunk.setFill(color_rgb(74, 51, 27))
treeOneTrunk.setOutline("black")
treeOneTrunk.draw(windowThree)

treeOne = Circle (Point(55, 245), 35)
treeOne.setFill(color_rgb(33, 97, 21))
treeOne.setOutline("black")
treeOne.draw(windowThree)

treeTwoTrunk = Rectangle (Point(130, 270), Point(155, 320))
treeTwoTrunk.setFill(color_rgb(74, 51, 27))
treeTwoTrunk.setOutline("black")
treeTwoTrunk.draw(windowThree)

treeTwo = Circle (Point(140, 245), 35)
treeTwo.setFill(color_rgb(33, 97, 21))
treeTwo.setOutline("black")
treeTwo.draw(windowThree)

treeThreeTrunk = Rectangle (Point(210, 270), Point(235, 320))
treeThreeTrunk.setFill(color_rgb(74, 51, 27))
treeThreeTrunk.setOutline("black")
treeThreeTrunk.draw(windowThree)

treeThree = Circle (Point(220, 245), 35)
treeThree.setFill(color_rgb(33, 97, 21))
treeThree.setOutline("black")
treeThree.draw(windowThree)

#Set up the farm house:
#1) the chimney 
yellowChimney = Rectangle (Point(440, 100), Point(490, 320))
yellowChimney.setFill(color_rgb(189, 139, 23))
yellowChimney.setOutline("black")
yellowChimney.draw(windowThree)

#2) the first base
groundBase = Rectangle (Point(415, 220), Point(600, 320)) 
groundBase.setFill(color_rgb(201, 34, 34))
groundBase.setOutline("black")
groundBase.draw(windowThree)

#3) the second level
secondLevel = Rectangle (Point(440, 170), Point(600, 220))
secondLevel.setFill(color_rgb(163, 42, 42))
secondLevel.setOutline("black")
secondLevel.draw(windowThree)

#4) the attic
yellowAttic = Polygon (Point(440, 170), Point(525, 100), Point(600, 170))
yellowAttic.setFill(color_rgb(247, 184, 47))
yellowAttic.setOutline("black")
yellowAttic.draw(windowThree)

#5) the doors
whiteDoorOne = Rectangle (Point(480, 255), Point(525, 320))
whiteDoorOne.setFill("white")
whiteDoorOne.setOutline("black")
whiteDoorOne.draw(windowThree)

whiteDoorTwo = Rectangle (Point(525, 255), Point(570, 320))
whiteDoorTwo.setFill("white")
whiteDoorTwo.setOutline("black")
whiteDoorTwo.draw(windowThree)
    
#Set up the road
greyRoad = Rectangle (Point(0, 350), Point(600, 440))
greyRoad.setFill(color_rgb(169,169,169))
greyRoad.setOutline("black")
greyRoad.draw(windowThree)

yellowLine = Rectangle (Point(0, 390), Point(600, 400))
yellowLine.setFill("yellow")
yellowLine.setOutline("black")
yellowLine.draw(windowThree)
    
#Set up the calf:
#1) draw the body
cowBody = Rectangle (Point(610, 400), Point(710, 460))
cowBody.setFill(color_rgb(184, 134, 11))
cowBody.setOutline("black")
cowBody.draw(windowThree)

#2) draw the head
cowHead = Rectangle (Point(560, 400), Point(610, 450))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowThree)

#3) draw the legs
cowLeg1 = Rectangle (Point(610, 460), Point(625, 490))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowThree)

cowLeg2 = Rectangle (Point(630, 460), Point(645, 490))
cowLeg2.setFill(color_rgb(184, 134, 11))
cowLeg2.setOutline("black")
cowLeg2.draw(windowThree)
    
cowLeg3 = Rectangle (Point(675, 460), Point(690, 490))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowThree)

cowLeg4 = Rectangle (Point(695, 460), Point(710, 490))
cowLeg4.setFill(color_rgb(184, 134, 11))
cowLeg4.setOutline("black")
cowLeg4.draw(windowThree)

#4) draw the ears
cowEar1 = Rectangle (Point(565, 386), Point(575, 400))
cowEar1.setFill(color_rgb(184,134,11))
cowEar1.setOutline("black")
cowEar1.draw(windowThree)

cowEar2 = Rectangle (Point(595, 386), Point(605, 400))
cowEar2.setFill(color_rgb(184,134,11))
cowEar2.setOutline("black")
cowEar2.draw(windowThree)

#5) draw the black spots
cowSpot1 = Circle (Point(630, 420), 12)
cowSpot1.setFill("white")
cowSpot1.draw(windowThree)

cowSpot2 = Circle (Point(680, 440), 12)
cowSpot2.setFill("white")
cowSpot2.draw(windowThree)

#Set up the spaceship:
#1) set up the lightbeam
lightBeam = Polygon (Point(-130, 170), Point(-270, 170), Point(-320, 430), Point(-70, 430))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(windowThree)

#2) set up the main body of the spaceship
spaceShip = Oval (Point(-100, 150), Point(-300, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(windowThree)

#3) set up the window of the spaceship
spaceShipWindow = Oval (Point(-170, 160), Point(-220, 180))
spaceShipWindow.setFill(color_rgb(224, 255, 255))
spaceShipWindow.setOutline("black")
spaceShipWindow.draw(windowThree)

#Animation begins:

#calf animation
for i in range(0, 70):

    #the lost calf stops near the farmhouse
    if cowBody.getCenter().getX() == 460:
        break
    
    #calf moves left
    cowBody.move(-2, 0)
    cowHead.move(-2, 0)
    cowLeg1.move(-2, 0)
    cowLeg2.move(-2, 0)
    cowLeg3.move(-2, 0)
    cowLeg4.move(-2, 0)
    cowEar1.move(-2, 0)
    cowEar2.move(-2, 0)
    cowSpot1.move(-2, 0)
    cowSpot2.move(-2, 0)
    update(20) #20 FPS
    
#spaceship animation 
for i in range(0, 115):

    #the spaceship stops in front of the calf 
    if spaceShip.getCenter().getX() == 415:
        break
    
    #spaceship moves right 
    lightBeam.move(4, 0)
    spaceShip.move(4, 0)
    spaceShipWindow.move(4, 0)
    update (15) #15 FPS

#quick pause
time.sleep(2)

#the mom cow animation
for i in range(0, 1):

    #Set up the mother cow:        
    #1) draw the body
    motherCowBody = Rectangle (Point(190, 180), Point(340, 260))
    motherCowBody.setFill("white")
    motherCowBody.setOutline("black")
    motherCowBody.draw(windowThree)

    #2) draw the head
    motherCowHead = Rectangle (Point(340, 180), Point(400, 230))
    motherCowHead.setFill("white")
    motherCowHead.setOutline("black")
    motherCowHead.draw(windowThree)

    #3) draw the legs
    motherCowLeg1 = Rectangle (Point(190, 260), Point(205, 290))
    motherCowLeg1.setFill("white")
    motherCowLeg1.setOutline("black")
    motherCowLeg1.draw(windowThree)

    motherCowLeg2 = Rectangle (Point(220, 260), Point(235, 290))
    motherCowLeg2.setFill("white")
    motherCowLeg2.setOutline("black")
    motherCowLeg2.draw(windowThree)

    motherCowLeg3 = Rectangle (Point(295, 260), Point(310, 290))
    motherCowLeg3.setFill("white")
    motherCowLeg3.setOutline("black")
    motherCowLeg3.draw(windowThree)

    motherCowLeg4 = Rectangle (Point(325, 260), Point(340, 290))
    motherCowLeg4.setFill("white")
    motherCowLeg4.setOutline("black")
    motherCowLeg4.draw(windowThree)

    #4) draw the ears
    motherCowEar1 = Rectangle (Point(345, 170), Point(355, 180))
    motherCowEar1.setFill(color_rgb(238, 232, 170))
    motherCowEar1.setOutline("black")
    motherCowEar1.draw(windowThree)

    motherCowEar2 = Rectangle (Point(385, 170), Point(395, 180))
    motherCowEar2.setFill(color_rgb(238, 232, 170))
    motherCowEar2.setOutline("black")
    motherCowEar2.draw(windowThree)

    #5) draw the black spots
    motherCowSpot1 = Circle (Point(220, 230), 20)
    motherCowSpot1.setFill("black")
    motherCowSpot1.draw(windowThree)

    motherCowSpot2 = Circle (Point(260, 210), 20)
    motherCowSpot2.setFill("black")
    motherCowSpot2.draw(windowThree)

    motherCowSpot3 = Circle (Point(310, 230), 20)
    motherCowSpot3.setFill("black")
    motherCowSpot3.draw(windowThree)

for i in range(0, 40):
    #the cow is dropped off by the spaceship 
    motherCowBody.move(0, 5)
    motherCowHead.move(0, 5)
    motherCowLeg1.move(0, 5)
    motherCowLeg2.move(0, 5)
    motherCowLeg3.move(0, 5)
    motherCowLeg4.move(0, 5)
    motherCowEar1.move(0, 5)
    motherCowEar2.move(0, 5)
    motherCowSpot1.move(0, 5)
    motherCowSpot2.move(0, 5)
    motherCowSpot3.move(0, 5)
    update(15) #15 FPS

for i in range(0, 1):
    #the bubble text 
    bubbleText2 = Circle (Point(420, 310), 50)
    bubbleText2.setFill("white")
    bubbleText2.setOutline("black")
    bubbleText2.draw(windowThree)

#The text that is going to be displayed
    cowMessage = "Moo!"
    
#mother cow message 
    #1) text 
    cowTxt = Text (Point(420, 315), cowMessage)
    cowTxt.setTextColor("black")
    cowTxt.setSize(9)
    cowTxt.setFace("helvetica")
    cowTxt.draw(windowThree)

    time.sleep(3)#pause
    cowTxt.undraw() #mother cow sound goes away
    bubbleText2.undraw()

#User Instruction for the next frame's transition
message = "This frame is over, please proceed to the next frame by clicking anywhere on the frame!"
nextFrameTransition = Text(Point(300, 10), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(10)
nextFrameTransition.setStyle("bold")
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowThree)

#close the frame 3 and proceed to frame 4
windowThree.getMouse()
windowThree.close() #this frame closes











#FOURTH FRAME

#Display the number of stars for the user
print("You will see 10 twinkling stars.") 

#**note**: counter and accumulator used in fourth frame.
#set the window screen and background
windowFour = GraphWin("Short story: Frame 4", 600, 500)
windowFour.setBackground(color_rgb(135, 206, 250))

#Set up the moon -> later used for animation
halfMoon = Circle(Point(40, 360), 40)
halfMoon.setFill(color_rgb(245, 245, 245))
halfMoon.setOutline("black")
halfMoon.draw(windowFour)

skyCover = Circle(Point(60, 355), 40)
skyCover.setFill(color_rgb(25, 25, 112))
skyCover.setOutline(color_rgb(25, 25, 112))
skyCover.draw(windowFour)

#Set up the green field 
greenField = Rectangle (Point(0, 320), Point(600, 500))
greenField.setFill(color_rgb(34,139,34))
greenField.setOutline("black")
greenField.draw(windowFour)

#Set up the sun
brightSun = Circle (Point(60, 60), 40)
brightSun.setFill(color_rgb(255, 255, 0))
brightSun.setOutline("black")
brightSun.draw(windowFour)

#Set up the mountains
bigMountain = Polygon (Point(180, 320), Point(320, 20), Point(470, 320))
bigMountain.setFill(color_rgb(144,238,144))
bigMountain.setOutline("black")
bigMountain.draw(windowFour)

smallMountain = Polygon (Point(20, 320), Point(160, 80), Point(290, 320))
smallMountain.setFill(color_rgb(144,238,144))
smallMountain.setOutline("black")
smallMountain.draw(windowFour)

#Set up the trees
treeOneTrunk = Rectangle (Point(45, 270), Point(70, 320))
treeOneTrunk.setFill(color_rgb(74, 51, 27))
treeOneTrunk.setOutline("black")
treeOneTrunk.draw(windowFour)

treeOne = Circle (Point(55, 245), 35)
treeOne.setFill(color_rgb(33, 97, 21))
treeOne.setOutline("black")
treeOne.draw(windowFour)

treeTwoTrunk = Rectangle (Point(130, 270), Point(155, 320))
treeTwoTrunk.setFill(color_rgb(74, 51, 27))
treeTwoTrunk.setOutline("black")
treeTwoTrunk.draw(windowFour)

treeTwo = Circle (Point(140, 245), 35)
treeTwo.setFill(color_rgb(33, 97, 21))
treeTwo.setOutline("black")
treeTwo.draw(windowFour)

treeThreeTrunk = Rectangle (Point(210, 270), Point(235, 320))
treeThreeTrunk.setFill(color_rgb(74, 51, 27))
treeThreeTrunk.setOutline("black")
treeThreeTrunk.draw(windowFour)

treeThree = Circle (Point(220, 245), 35)
treeThree.setFill(color_rgb(33, 97, 21))
treeThree.setOutline("black")
treeThree.draw(windowFour)

#Set up the farm house:
#1) the chimney 
yellowChimney = Rectangle (Point(440, 100), Point(490, 320))
yellowChimney.setFill(color_rgb(189, 139, 23))
yellowChimney.setOutline("black")
yellowChimney.draw(windowFour)

#2) the first base
groundBase = Rectangle (Point(415, 220), Point(600, 320)) 
groundBase.setFill(color_rgb(201, 34, 34))
groundBase.setOutline("black")
groundBase.draw(windowFour)

#3) the second level
secondLevel = Rectangle (Point(440, 170), Point(600, 220))
secondLevel.setFill(color_rgb(163, 42, 42))
secondLevel.setOutline("black")
secondLevel.draw(windowFour)

#4) the attic
yellowAttic = Polygon (Point(440, 170), Point(525, 100), Point(600, 170))
yellowAttic.setFill(color_rgb(247, 184, 47))
yellowAttic.setOutline("black")
yellowAttic.draw(windowFour)

#5) the doors
whiteDoorOne = Rectangle (Point(480, 255), Point(525, 320))
whiteDoorOne.setFill("white")
whiteDoorOne.setOutline("black")
whiteDoorOne.draw(windowFour)

whiteDoorTwo = Rectangle (Point(525, 255), Point(570, 320))
whiteDoorTwo.setFill("white")
whiteDoorTwo.setOutline("black")
whiteDoorTwo.draw(windowFour)
    
#Set up the road
greyRoad = Rectangle (Point(0, 350), Point(600, 440))
greyRoad.setFill(color_rgb(169,169,169))
greyRoad.setOutline("black")
greyRoad.draw(windowFour)

yellowLine = Rectangle (Point(0, 390), Point(600, 400))
yellowLine.setFill("yellow")
yellowLine.setOutline("black")
yellowLine.draw(windowFour)

#Set up the farmer's truck:
#1) the main body
carBody = Rectangle (Point(-200, 320), Point(-70, 395))
carBody.setFill("white")
carBody.setOutline("black")
carBody.draw(windowFour)

#2) the front body
carFront = Rectangle (Point(-70, 340), Point(-10, 395))
carFront.setFill("white")
carFront.setOutline("black")
carFront.draw(windowFour)

#3) the front window
carFrontWindow = Rectangle (Point(-55, 350), Point(-10, 380))
carFrontWindow.setFill(color_rgb(230, 230, 250))
carFrontWindow.draw(windowFour)

#4) the wheels
# wheel 1
carWheelOne = Circle (Point(-175, 393), 23)
carWheelOne.setFill("black")
carWheelOne.setOutline("black")
carWheelOne.draw(windowFour)

carWheelOneMetal = Circle (Point(-175, 393), 13)
carWheelOneMetal.setFill(color_rgb(211, 211, 211))
carWheelOneMetal.setOutline("white")
carWheelOneMetal.draw(windowFour)

# wheel 2
carWheelTwo = Circle (Point(-100, 393), 23)
carWheelTwo.setFill("black")
carWheelTwo.setOutline('black')
carWheelTwo.draw(windowFour)

carWheelTwoMetal = Circle (Point(-100, 393), 13)
carWheelTwoMetal.setFill(color_rgb(211, 211, 211))
carWheelTwoMetal.setOutline("white")
carWheelTwoMetal.draw(windowFour)

#Set up the spaceship
#1) Establish the lightbeam
lightBeam = Polygon (Point(160, 170), Point(290, 170), Point(355, 430), Point(118, 430))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(windowFour)

#2) set up the main body of the spaceship
spaceShip = Oval (Point(130, 150), Point(320, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(windowFour)
    
#3) set up the window of the spaceship
window = Oval (Point(200, 160), Point(250, 180))
window.setFill(color_rgb(224, 255, 255))
window.setOutline("black")
window.draw(windowFour)

#Set up the calf:
#1) draw the body
cowBody = Rectangle (Point(410, 400), Point(510, 460))
cowBody.setFill(color_rgb(184, 134, 11))
cowBody.setOutline("black")
cowBody.draw(windowFour)

#2) draw the head
cowHead = Rectangle (Point(360, 400), Point(410, 450))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowFour)

#3) draw the legs
cowLeg1 = Rectangle (Point(410, 460), Point(425, 490))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowFour)

cowLeg2 = Rectangle (Point(430, 460), Point(445, 490))
cowLeg2.setFill(color_rgb(184, 134, 11))
cowLeg2.setOutline("black")
cowLeg2.draw(windowFour)
    
cowLeg3 = Rectangle (Point(475, 460), Point(490, 490))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowFour)

cowLeg4 = Rectangle (Point(495, 460), Point(510, 490))
cowLeg4.setFill(color_rgb(184, 134, 11))
cowLeg4.setOutline("black")
cowLeg4.draw(windowFour)

#4) draw the ears
cowEar1 = Rectangle (Point(365, 386), Point(375, 400))
cowEar1.setFill(color_rgb(184,134,11))
cowEar1.setOutline("black")
cowEar1.draw(windowFour)

cowEar2 = Rectangle (Point(395, 386), Point(405, 400))
cowEar2.setFill(color_rgb(184,134,11))
cowEar2.setOutline("black")
cowEar2.draw(windowFour)

#5) draw the black spots
cowSpot1 = Circle (Point(430, 420), 12)
cowSpot1.setFill("white")
cowSpot1.draw(windowFour)

cowSpot2 = Circle (Point(480, 440), 12)
cowSpot2.setFill("white")
cowSpot2.draw(windowFour)

#Draw the mother cow 
#1) draw the body
cowBody = Rectangle (Point(150, 390), Point(300, 470))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(windowFour)

#2) draw the head
cowHead = Rectangle (Point(300, 390), Point(352, 445))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowFour)

#3) draw the legs
cowLeg1 = Rectangle (Point(150, 470), Point(165, 490))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowFour)

cowLeg2 = Rectangle (Point(180, 470), Point(195, 490))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(windowFour)

cowLeg3 = Rectangle (Point(250, 470), Point(265, 490))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowFour)

cowLeg4 = Rectangle (Point(285, 470), Point(300, 490))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(windowFour)

#4) draw the ears
cowEar1 = Rectangle (Point(300, 380), Point(310, 390))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(windowFour)

cowEar2 = Rectangle (Point(340, 380), Point(350, 390))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(windowFour)

#5) draw the black spots
cowSpot1 = Circle (Point(180, 445), 20)
cowSpot1.setFill("black")
cowSpot1.draw(windowFour)

cowSpot2 = Circle (Point(230, 415), 20)
cowSpot2.setFill("black")
cowSpot2.draw(windowFour)

cowSpot3 = Circle (Point(275, 445), 20)
cowSpot3.setFill("black")
cowSpot3.draw(windowFour)                

#Animation begins:

#Sunset -> sun disappears 
for i in range(0, 200):
    brightSun.move(0, 1)
    brightSun.move(-0.5, 0)
    update(20) #20 FPS

time.sleep(2) #pause

#Night time -> sky turns dark
for i in range(0, 1):
    windowFour.setBackground(color_rgb(25, 25, 112)) #change the background colour

#Set up the stars - projected on the sky
star1 = Polygon(Point(140, 20), Point(150, 10), Point(160, 20), Point(150, 30))
star1.setFill(color_rgb(255, 255, 224))
star1.draw(windowFour)

star2 = Polygon(Point(170, 60), Point(180, 50), Point(190, 60), Point(180,70))
star2.setFill(color_rgb(255, 255, 224))
star2.draw(windowFour)

star3 = Polygon(Point(350, 20), Point(360, 10), Point(370, 20), Point(360, 30))
star3.setFill(color_rgb(255, 255, 224))
star3.draw(windowFour)

star5 = Polygon(Point(470, 80), Point(480, 70), Point(490, 80), Point(480, 90))
star5.setFill(color_rgb(255, 255, 224))

star6 = Polygon(Point(500, 30), Point(510, 20), Point(520, 30), Point(510, 40))
star6.setFill(color_rgb(255, 255, 224))
star6.draw(windowFour)

star7 = Polygon(Point(560, 100), Point(570, 90), Point(580, 100), Point(570, 110))
star7.setFill(color_rgb(255, 255, 224))

star9 = Polygon(Point(250, 100), Point(260, 90), Point(270, 100), Point(260, 110))
star9.setFill(color_rgb(255, 255, 224))
star9.draw(windowFour)

star10 = Polygon(Point(20, 30), Point(30, 20), Point(40, 30), Point(30, 40))
star10.setFill(color_rgb(255, 255, 224))
star10.draw(windowFour)

#Stars twinkle animation
for i in range(0, 100):
  star1.undraw()
  star1.draw(windowFour)
  star2.undraw()
  star2.draw(windowFour)
  star3.undraw()
  star3.draw(windowFour)
  star5.undraw()
  star5.draw(windowFour)
  star6.undraw()
  star6.draw(windowFour)
  star7.undraw()
  star7.draw(windowFour)
  star9.undraw()
  star9.draw(windowFour)
  star10.undraw()
  star10.draw(windowFour)
  update(10) #10 FPS


#Set up the counter and accumulator -> related to the stars:

#10 stars
#Declare and Initialize
counter = 1
sum = 0
numStars = 10

#The accumulator and counter
while counter <= numStars:
  counter = counter + 1 #counter
  sum += 10 #accumulator
    
#Print the results:
print("The sum of all the stars is:", sum)
print("The average of the stars is:", round(sum/counter, 1))

#Display the accumulator/counter result on the window
infoTxt = "10 stars twinkled."

#Display Text
displayInformation = Text (Point(510, 335), infoTxt)
displayInformation.setTextColor("black")
displayInformation.setSize(12)
displayInformation.setStyle("bold")
displayInformation.setFace("helvetica")
displayInformation.draw(windowFour)

time.sleep(4) #pause

#Erase the text
displayInformation.undraw()

#Moon appears 
for i in range(0, 280):
    skyCover.move(0, -1)
    skyCover.move(0.1, 0)
    update(50) #50 FPS

    halfMoon.move(0, -1)
    halfMoon.move(0.1, 0)
    update(50) #50 FPS        


#Farmer's truck comes from the right
for i in range(0, 40):

  #User selected truck colour - fill in before animation
  if userInput2 == "white":
    carBody.setFill("white")
    carFront.setFill("white")

  elif userInput2 == "grey":
    carBody.setFill("grey")
    carFront.setFill("grey")

  elif userInput2 == "green3":
    carBody.setFill("green3")
    carFront.setFill("green3")

  elif userInput2 == "red4":
    carBody.setFill("red4")
    carFront.setFill("red4")

    #truck moves
    carBody.move(6, 0)
    carFront.move(6, 0)
    carFrontWindow.move(6, 0)
    carWheelOne.move(6, 0)
    carWheelTwo.move(6, 0)
    carWheelOneMetal.move(6, 0)
    carWheelTwoMetal.move(6, 0)
    update(10) #10 FPS

#pause
time.sleep(2)

#The farmer goes out of the truck 
for i in range(0, 1):
    #Set up the farmer
    #1) set up the first part of the hat
    topHat = Circle (Point(100, 260), 30)
    topHat.setFill(color_rgb(218,165,32))
    topHat.setOutline("black")
    topHat.draw(windowFour)

    #4) set up the chest/shirt
    farmerShirt = Rectangle (Point(80, 310), Point(120, 420))
    farmerShirt.setOutline("black")

    #user colour selection 
    if userInput == "red":
        farmerShirt.setFill("red")

    elif userInput == "green":
        farmerShirt.setFill("green")

    elif userInput == "yellow":
        farmerShirt.setFill("yellow")

    elif userInput == "cyan":
        farmerShirt.setFill("cyan")

    elif userInput == "blue":
        farmerShirt.setFill("blue")

    farmerShirt.draw(windowFour)
        
    #2) Set up the head
    farmerHead = Circle (Point(100, 295), 40 )
    farmerHead.setFill(color_rgb(250,235,215))
    farmerHead.setOutline("black")
    farmerHead.draw(windowFour)

    #3) set up the second part of the hat
    bottomHat = Oval(Point(35, 250), Point(160, 270))
    bottomHat.setFill(color_rgb(184,134,11))
    bottomHat.setOutline("black")
    bottomHat.draw(windowFour)

    #5) set up the legs
    farmerLegOne = Rectangle (Point(80, 420), Point(95, 480))
    farmerLegOne.setFill(color_rgb(0, 0, 128))
    farmerLegOne.setOutline("black")
    farmerLegOne.draw(windowFour)

    farmerLegTwo = Rectangle (Point(105, 420), Point(120, 480))
    farmerLegTwo.setFill(color_rgb(0, 0, 128))
    farmerLegTwo.setOutline("black")
    farmerLegTwo.draw(windowFour)

    #6) set up the arms
    farmerArmOne = Rectangle (Point(70, 330), Point(80, 410))
    farmerArmOne.setFill(color_rgb(250, 235, 215))
    farmerArmOne.setOutline("black")
    farmerArmOne.draw(windowFour)

    farmerArmTwo = Rectangle (Point (120, 330), Point(130, 410))
    farmerArmTwo.setFill(color_rgb(250, 235, 215))
    farmerArmTwo.setOutline("black")
    farmerArmTwo.draw(windowFour)
        
    #7) set up the eyes
    farmerEyeOne = Rectangle (Point(75, 280), Point(95, 300))
    farmerEyeOne.setFill("white")
    farmerEyeOne.setOutline("black")
    farmerEyeOne.draw(windowFour)

    farmerEyeTwo = Rectangle (Point(110, 280), Point(130, 300))
    farmerEyeTwo.setFill("white")
    farmerEyeTwo.setOutline("black")
    farmerEyeTwo.draw(windowFour)

    #the pupils 
    farmerEye1Pupil = Circle (Point(90, 292), 2) 
    farmerEye1Pupil.setFill("black")
    farmerEye1Pupil.draw(windowFour)

    farmerEye2Pupil = Circle (Point(125, 292), 2)
    farmerEye2Pupil.setFill("black")
    farmerEye2Pupil.draw(windowFour)

for i in range(0, 1):
    #8) Set up the mouth:
    #closed mouth 
    farmerMouthOne = Line (Point(95, 315), Point(110, 315))
    farmerMouthOne.setFill("white")
    farmerMouthOne.setOutline("black")
    farmerMouthOne.draw(windowFour)

    time.sleep(2)

    farmerMouthOne.undraw()

#farmer's surprised expression
for i in range(0, 1):

    totalSize = 9
    farmerHappy = Circle (Point(100, 320), totalSize)
    farmerHappy.setFill(color_rgb(255,160,122))
    farmerHappy.setOutline("black")
    farmerHappy.draw(windowFour)

    #the bubble
    bubbleText = Circle (Point(130, 170), 75)
    bubbleText.setFill("white")
    bubbleText.setOutline("black")
    bubbleText.draw(windowFour)

    #The texts that are going to be displayed
    textOne = "Oh... my little Joey..."
    textTwo = "You were here this whole time!"
    textThree = "Yay! We found you and your mom."
    textFour = "Thank you aliens."
        
    #Farmer's messages
    #1) text 
    firstMessage = Text (Point(130, 170), textOne)
    firstMessage.setTextColor("black")
    firstMessage.setSize(9)
    firstMessage.setFace("helvetica")
    firstMessage.draw(windowFour)

    time.sleep(2)#pause
    firstMessage.undraw() #first text goes away
    farmerHappy.undraw()

#farmer thanks the spaceship:
for i in range(0, 1):
    totalSize = 6 #the radius
    farmerHappy2 = Circle (Point(100, 320), totalSize)
    farmerHappy2.setFill(color_rgb(255,160,122))
    farmerHappy2.setOutline("black")
    farmerHappy2.draw(windowFour)

    #2) text
    secondMessage = Text (Point(130, 170), textTwo)
    secondMessage.setTextColor("black")
    secondMessage.setSize(8)
    secondMessage.setFace("helvetica")
    secondMessage.draw(windowFour)

    time.sleep(3)#pause
    secondMessage.undraw()#second text goes away

    #3) text
    thirdMessage = Text (Point(130, 170), textThree)
    thirdMessage.setTextColor("black")
    thirdMessage.setSize(6)
    thirdMessage.setFace("helvetica")
    thirdMessage.setStyle("bold")
    thirdMessage.draw(windowFour)

    time.sleep(3)#pause
    thirdMessage.undraw()#third text goes away

    #4) text
    fourthMessage = Text (Point(130, 170), textFour)
    fourthMessage.setTextColor("black")
    fourthMessage.setSize(10)
    fourthMessage.setFace("helvetica")
    fourthMessage.draw(windowFour)

    time.sleep(2)#pause
    fourthMessage.undraw()#fourth text goes away

    #bubble text disappears
    time.sleep(0.5)
    bubbleText.undraw()

#After the farmer shows appreciation, the spaceship goes away. 
for i in range(0, 80):
  
    #spaceship animation 
    spaceShip.move(7, 0)
    window.move(7, 0)
    lightBeam.move(7, 0)
    update(10) #10 FPS


#User Instruction for the next frame's transition
message = "This frame is over, please proceed to the next one by clicking anywhere on the frame!"
nextFrameTransition = Text(Point(300, 10), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(11)
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowFour)


windowFour.getMouse() #user clicks anywhere with the mouse on the window
windowFour.close() #the last frame closes




  








#FINAL AND LAST FRAME
  
#set up the screen window 
windowFive = GraphWin("Short story: Final Frame", 600, 500)
windowFive.setBackground("black")

#set up the messages that are going to be displayed
displayText0 = "The End."
displayText1 = "Thank you for watching."
displayText2 = "Moral of the short story:"
displayText3 = "Never assume something."

#ending display
endDisplay = Text(Point(300, 290), displayText0)
endDisplay.setTextColor("white")
endDisplay.setSize(19)
endDisplay.setFace("helvetica")
endDisplay.setStyle("bold")
endDisplay.draw(windowFive)

time.sleep(1) #pause

endDisplay.undraw()

#thank the audience
thankDisplay = Text(Point(300, 290), displayText1)
thankDisplay.setTextColor("white")
thankDisplay.setSize(19)
thankDisplay.setFace("helvetica")
thankDisplay.setStyle("bold")
thankDisplay.draw(windowFive)

time.sleep(2) #pause

thankDisplay.undraw()

#moral of the story
moralDisplay = Text(Point(300, 290), displayText2)
moralDisplay.setTextColor("white")
moralDisplay.setSize(18)
moralDisplay.setFace("helvetica")
moralDisplay.setStyle("bold")
moralDisplay.draw(windowFive)

time.sleep (2) # pause

#moral quote
realMoralDisplay = Text(Point(300, 370), displayText3)
realMoralDisplay.setTextColor("white")
realMoralDisplay.setSize(20)
realMoralDisplay.setFace("helvetica")
realMoralDisplay.setStyle("italic")
realMoralDisplay.draw(windowFive)

#image (gif) feature display
alienImage = Image(Point(300, 180), "alienPicture.gif")
alienImage.draw(windowFive)

#pause
time.sleep(3)

#User Instruction for the next frame's transition
message = "This frame is over, please click anywhere on the frame to restart the story."
nextFrameTransition = Text(Point(300, 480), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(11)
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowFive)


windowFive.getMouse() #user clicks anywhere on the frame with the mouse to close and restart the story 
windowFive.close() #the fifth frame closes (of this round)

















#THE STORY RESTARTS


#TITLE FRAME

#Establish the screen window and set the background day time colour
titleWindow = GraphWin ("Title Window", 600, 500)
titleWindow.setBackground("black")

#Display of the title
titleStory = "The Adventure of The Farmer"
titleDisplay = Text(Point(300, 280), titleStory)
titleDisplay.setTextColor("white")
titleDisplay.setSize(20)
titleDisplay.setFace("helvetica")
titleDisplay.draw(titleWindow)

time.sleep(1) #pause

#Display of the sub-title 
titleStory2 = "A Short Story by Undariya P."
subTitleDisplay = Text(Point(300, 340), titleStory2)
subTitleDisplay.setTextColor("white")
subTitleDisplay.setSize(15)
subTitleDisplay.setFace("helvetica")
subTitleDisplay.draw(titleWindow)    

time.sleep(2) #pause

#Erase the titles
titleDisplay.undraw()
subTitleDisplay.undraw()

#Close the title window 
titleWindow.close()







#PRE-STORY FRAME -> REFERENCE TO PICTURE PROGRAM ASSIGNMENT

#Establish the screen window and set the background colour
earlyStory = GraphWin ("Pre-story introduction", 600, 500)
earlyStory.setBackground("black")

#Display of the title
display1 = "Let's begin."
messageOne = Text(Point(300, 280), display1)
messageOne.setTextColor("white")
messageOne.setSize(20)
messageOne.setFace("helvetica")
messageOne.draw(earlyStory)

time.sleep(1) #pause

#Display of the sub-title
display2 = "Earlier in the story..."
messageTwo = Text(Point(300, 340), display2)
messageTwo.setTextColor("white")
messageTwo.setSize(20)
messageTwo.setFace("helvetica")
messageTwo.draw(earlyStory)    

time.sleep(2) #pause

#Erase the titles
messageOne.undraw()
messageTwo.undraw()



#THE PRE-STORY BEGINS:

#Change the background to sky blue 
earlyStory.setBackground(color_rgb(135, 206, 250))

#Establish the main ground of the window -> the field
field = Rectangle (Point(0, 460), Point(600, 500))
field.setFill(color_rgb(0, 100, 0))
field.draw(earlyStory)

#Set up the 2 mountains behind the cows
#1)set up the taller mountain
bigMountain = Polygon (Point(400, 40), Point(590, 460), Point(225, 460))
bigMountain.setFill(color_rgb(34, 139, 34))
bigMountain.setOutline("black")
bigMountain.draw(earlyStory)

#2)set up the smaller mountain
smallMountain = Polygon (Point(235, 135), Point(70, 460), Point(400, 460)) 
smallMountain.setFill(color_rgb(34, 139, 34))
smallMountain.setOutline("black")
smallMountain.draw(earlyStory) 

#set up the sun
sun = Circle(Point(95, 115), 60)
sun.setFill(color_rgb(255, 255, 0))
sun.setOutline("black")
sun.draw(earlyStory)

#Set up the tree in the middle
#1) set up the trunk
treeTrunk = Rectangle (Point(245, 350),Point(260, 460))
treeTrunk.setFill(color_rgb(139, 69, 19))
treeTrunk.draw(earlyStory)

#2) set up the branches and leaves
treeBranch1 = Circle (Point(250, 340), 30)
treeBranch1.setFill(color_rgb(0, 100, 0))
treeBranch1.setOutline(color_rgb(0, 100, 0))
treeBranch1.draw(earlyStory)

treeBranch2 = Circle (Point(230, 380), 30)
treeBranch2.setFill(color_rgb(0, 100, 0))
treeBranch2.setOutline(color_rgb(0, 100, 0))
treeBranch2.draw(earlyStory)

treeBranch3 = Circle (Point(270, 380), 30)
treeBranch3.setFill(color_rgb(0, 100, 0))
treeBranch3.setOutline(color_rgb(0, 100, 0))
treeBranch3.draw(earlyStory)

#Draw the bigger cow (the protagonist)
#1) draw the body
cowBody = Rectangle (Point(365,330), Point(510,420))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(earlyStory)

#2) draw the head
cowHead = Rectangle (Point(305, 340), Point(365, 400))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(earlyStory)

#3) draw the legs
cowLeg1 = Rectangle (Point(495, 460), Point(510, 420))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(earlyStory)

cowLeg2 = Rectangle (Point(465, 460), Point(480, 420))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(earlyStory)

cowLeg3 = Rectangle (Point(395, 460), Point(410, 420))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(earlyStory)

cowLeg4 = Rectangle (Point(365, 460), Point(380, 420))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(earlyStory)

#4) draw the ears
cowEar1 = Rectangle (Point(305, 340), Point(312, 330))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(earlyStory)

cowEar2 = Rectangle (Point(355, 340), Point(362, 330))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(earlyStory)

#5) draw the black spots
cowSpot1 = Circle (Point(480, 390), 20)
cowSpot1.setFill("black")
cowSpot1.draw(earlyStory)

cowSpot2 = Circle (Point(435, 355), 20)
cowSpot2.setFill("black")
cowSpot2.draw(earlyStory)

cowSpot3 = Circle (Point(395, 390), 20)
cowSpot3.setFill("black")
cowSpot3.draw(earlyStory)

#Draw the smaller cow
#1) draw the body
smallCowBody = Rectangle (Point(150, 420), Point(50, 370))
smallCowBody.setFill(color_rgb(205, 133, 63))
smallCowBody.setOutline("black")
smallCowBody.draw(earlyStory)

#2) draw the head
smallCowHead = Rectangle (Point(150, 415), Point(190, 375))
smallCowHead.setFill("white")
smallCowHead.setOutline("black")
smallCowHead.draw(earlyStory)

#3) draw the legs
smallCowLeg1 = Rectangle (Point(150, 420), Point(140, 460))
smallCowLeg1.setFill("white")
smallCowLeg1.setOutline("black")
smallCowLeg1.draw(earlyStory)

smallCowLeg2 = Rectangle (Point(50, 420), Point(60, 460))
smallCowLeg2.setFill("white")
smallCowLeg2.setOutline("black")
smallCowLeg2.draw(earlyStory)

smallCowLeg3 = Rectangle (Point(70, 420), Point(80, 460))
smallCowLeg3.setFill("white")
smallCowLeg3.setOutline("black")
smallCowLeg3.draw(earlyStory)

smallCowLeg4 = Rectangle (Point(130, 420), Point(120, 460))
smallCowLeg4.setFill("white")
smallCowLeg4.setOutline("black")
smallCowLeg4.draw(earlyStory)

#4) draw the ears
smallCowEar1 = Rectangle (Point(150, 375), Point(157, 365))
smallCowEar1.setFill(color_rgb(205, 133, 63))
smallCowEar1.setOutline("black")
smallCowEar1.draw(earlyStory)

smallCowEar2 = Rectangle (Point(180, 375), Point(187, 365))
smallCowEar2.setFill(color_rgb(205, 133, 63))
smallCowEar2.setOutline("black")
smallCowEar2.draw(earlyStory)

#5) draw the black spots
smallCowSpot1 = Circle (Point(130, 405), 11)
smallCowSpot1.setFill("white")
smallCowSpot1.draw(earlyStory)

smallCowSpot2 = Circle (Point(100, 385), 11)
smallCowSpot2.setFill("white")
smallCowSpot2.draw(earlyStory)

smallCowSpot3 = Circle (Point(70, 405), 11)
smallCowSpot3.setFill("white")
smallCowSpot3.draw(earlyStory)

#Set up the spaceship
#1) Establish the lightbeam
lightBeam = Polygon (Point(630, 170), Point(770, 170), Point(820, 460), Point(570, 460))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(earlyStory)

#2) set up the main body of the spaceship
spaceShip = Oval (Point(600, 150), Point(800, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(earlyStory)

#3) set up the window of the spaceship
window = Oval (Point(670, 160), Point(720, 180))
window.setFill(color_rgb(224, 255, 255))
window.setOutline("black")
window.draw(earlyStory)

#spaceship comes in and invades the big cow (mother cow)
while True:
    spaceShip.move(-2, 0)
    window.move(-2, 0)
    lightBeam.move(-2, 0)
    update(30) #30 FPS

    #when the spaceship is right above the cow
    if spaceShip.getCenter().getX() == 410:
        break

#Make the big cow reappear in front of the lightbeam
#Draw the bigger cow (the protagonist)
#1) draw the body
cowBody = Rectangle (Point(365, 330), Point(510, 420))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(earlyStory)

#2) draw the head
cowHead = Rectangle (Point(305, 340), Point(365, 400))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(earlyStory)

#3) draw the legs
cowLeg1 = Rectangle (Point(495,460), Point(510, 420))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(earlyStory)

cowLeg2 = Rectangle (Point(465, 460), Point(480, 420))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(earlyStory)

cowLeg3 = Rectangle (Point(395, 460), Point(410, 420))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(earlyStory)

cowLeg4 = Rectangle (Point(365, 460), Point(380, 420))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(earlyStory)

#4) draw the ears
cowEar1 = Rectangle (Point(305, 340), Point(312, 330))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(earlyStory)

cowEar2 = Rectangle (Point(355, 340), Point(362, 330))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(earlyStory)

#5) draw the black spots
cowSpot1 = Circle (Point(480, 390), 20)
cowSpot1.setFill("black")
cowSpot1.draw(earlyStory)

cowSpot2 = Circle (Point(435, 355), 20)
cowSpot2.setFill("black")
cowSpot2.draw(earlyStory)

cowSpot3 = Circle (Point(395, 390), 20)
cowSpot3.setFill("black")
cowSpot3.draw(earlyStory)                

#The bigger cow moves up and gets invaded by the spaceship
for i in range(0, 260): #move all the big cow components UP
    cowBody.move(0, -0.5)
    cowHead.move(0, -0.5)
    cowLeg1.move(0, -0.5)
    cowLeg2.move(0, -0.5)
    cowLeg3.move(0, -0.5)
    cowLeg4.move(0, -0.5)
    cowEar1.move(0, -0.5)
    cowEar2.move(0, -0.5)
    cowSpot1.move(0, -0.5)
    cowSpot2.move(0, -0.5)
    cowSpot3.move(0, -0.5)

    #when the cow is right below the spaceship, where the invasion occurs.
    if cowBody.getCenter().getY() == 260: #make the big cow disappear
        cowHead.undraw()
        cowBody.undraw()
        cowLeg1.undraw()
        cowLeg2.undraw()
        cowLeg3.undraw()
        cowLeg4.undraw()
        cowEar1.undraw()
        cowEar2.undraw()
        cowSpot1.undraw()
        cowSpot2.undraw()
        cowSpot3.undraw()

#spaceship goes away (with the cow)
for i in range(0, 70):
    spaceShip.move(5, 0)
    window.move(5, 0)
    lightBeam.move(5, 0)
    update(15) #15 FPS

#Close the frame and proceed to the next one
earlyStory.close()








#CURRENT STORY FRAME INTRODUCTION

#Establish the screen window and set the background colour
currentStory = GraphWin ("Real Story Introduction", 600, 500)
currentStory.setBackground("black")

#Display of the title
displayTxt = "Let the REAL story begin..."
nowMessage = Text(Point(300, 280), displayTxt)
nowMessage.setTextColor("white")
nowMessage.setSize(20)
nowMessage.setFace("helvetica")
nowMessage.draw(currentStory)

time.sleep(4) #pause

#Erase the messages
nowMessage.undraw()
currentStory.close()







#ADDITIONAL FRAME -> ENTRY BOX USER INPUT (used TKINTER)

#Set up the import feature (tkinter)
import tkinter as tk
from tkinter import simpledialog

#Establish the entry user input box -> farmer shirt colour selection 
userInput = simpledialog.askstring(title="Entry User Input Box 1",
                                  prompt="Please select a colour for the farmer's shirt. Please choose between red, yellow, blue, green, or cyan.")

#Display the chosen colour on the SHELL window
print("Your chosen colour for the farmer's shirt is", userInput + ".")









#FIRST FRAME

#Establish the first screen window and change the window's background to blue (sky)
windowOne = GraphWin ("Short story: Frame 1", 600, 500)
windowOne.setBackground(color_rgb(135, 206, 250))

#Establish the main ground of the window -> the field
greenField = Rectangle (Point(0, 460), Point(600, 500))
greenField.setFill(color_rgb(0, 100, 0))
greenField.draw(windowOne)

#Set up the 2 mountains behind the cows:
#1)set up the taller mountain
bigMountain = Polygon (Point(400, 40), Point(590, 460), Point(225, 460))
bigMountain.setFill(color_rgb(34, 139, 34))
bigMountain.setOutline("black")
bigMountain.draw(windowOne)

#2)set up the smaller mountain
smallMountain = Polygon (Point(235, 135), Point(70, 460), Point(400, 460)) 
smallMountain.setFill(color_rgb(34, 139, 34))
smallMountain.setOutline("black")
smallMountain.draw(windowOne) 

#Set up the sun
sun = Circle(Point(95, 115), 60)
sun.setFill(color_rgb(255, 255, 0))
sun.setOutline("black")
sun.draw(windowOne)

#Set up the tree in the middle:
#1) set up the trunk
treeTrunk = Rectangle (Point(245, 350),Point(260, 460))
treeTrunk.setFill(color_rgb(139, 69, 19))
treeTrunk.draw(windowOne)

#2) set up the branches and leaves
treeBranch1 = Circle (Point(250, 340), 30)
treeBranch1.setFill(color_rgb(0, 100, 0))
treeBranch1.setOutline(color_rgb(0, 100, 0))
treeBranch1.draw(windowOne)

treeBranch2 = Circle (Point(230, 380), 30)
treeBranch2.setFill(color_rgb(0, 100, 0))
treeBranch2.setOutline(color_rgb(0, 100, 0))
treeBranch2.draw(windowOne)
    
treeBranch3 = Circle (Point(270, 380), 30)
treeBranch3.setFill(color_rgb(0, 100, 0))
treeBranch3.setOutline(color_rgb(0, 100, 0))
treeBranch3.draw(windowOne)
    
#Draw the bigger cow (the protagonist):
#1) draw the body
cowBody = Rectangle (Point(365,330), Point(510,420))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(windowOne)

#2) draw the head
cowHead = Rectangle (Point(305, 340), Point(365, 400))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowOne)

#3) draw the legs
cowLeg1 = Rectangle (Point(495, 460), Point(510, 420))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowOne)

cowLeg2 = Rectangle (Point(465, 460), Point(480, 420))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(windowOne)

cowLeg3 = Rectangle (Point(395, 460), Point(410, 420))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowOne)
    
cowLeg4 = Rectangle (Point(365, 460), Point(380, 420))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(windowOne)

#4) draw the ears
cowEar1 = Rectangle (Point(305, 340), Point(312, 330))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(windowOne)

cowEar2 = Rectangle (Point(355, 340), Point(362, 330))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(windowOne)

#5) draw the black spots
cowSpot1 = Circle (Point(480, 390), 20)
cowSpot1.setFill("black")
cowSpot1.draw(windowOne)

cowSpot2 = Circle (Point(435, 355), 20)
cowSpot2.setFill("black")
cowSpot2.draw(windowOne)

cowSpot3 = Circle (Point(395, 390), 20)
cowSpot3.setFill("black")
cowSpot3.draw(windowOne)
    
#Draw the smaller cow:
#1) draw the body
smallCowBody = Rectangle (Point(150, 420), Point(50, 370))
smallCowBody.setFill(color_rgb(205, 133, 63))
smallCowBody.setOutline("black")
smallCowBody.draw(windowOne)

#2) draw the head
smallCowHead = Rectangle (Point(150, 415), Point(190, 375))
smallCowHead.setFill("white")
smallCowHead.setOutline("black")
smallCowHead.draw(windowOne)

#3) draw the legs
smallCowLeg1 = Rectangle (Point(150, 420), Point(140, 460))
smallCowLeg1.setFill("white")
smallCowLeg1.setOutline("black")
smallCowLeg1.draw(windowOne)

smallCowLeg2 = Rectangle (Point(50, 420), Point(60, 460))
smallCowLeg2.setFill("white")
smallCowLeg2.setOutline("black")
smallCowLeg2.draw(windowOne)

smallCowLeg3 = Rectangle (Point(70, 420), Point(80, 460))
smallCowLeg3.setFill("white")
smallCowLeg3.setOutline("black")
smallCowLeg3.draw(windowOne)

smallCowLeg4 = Rectangle (Point(130, 420), Point(120, 460))
smallCowLeg4.setFill("white")
smallCowLeg4.setOutline("black")
smallCowLeg4.draw(windowOne)

#4) draw the ears
smallCowEar1 = Rectangle (Point(150, 375), Point(157, 365))
smallCowEar1.setFill(color_rgb(205, 133, 63))
smallCowEar1.setOutline("black")
smallCowEar1.draw(windowOne)

smallCowEar2 = Rectangle (Point(180, 375), Point(187, 365))
smallCowEar2.setFill(color_rgb(205, 133, 63))
smallCowEar2.setOutline("black")
smallCowEar2.draw(windowOne)

#5) draw the black spots
smallCowSpot1 = Circle (Point(130, 405), 11)
smallCowSpot1.setFill("white")
smallCowSpot1.draw(windowOne)

smallCowSpot2 = Circle (Point(100, 385), 11)
smallCowSpot2.setFill("white")
smallCowSpot2.draw(windowOne)

smallCowSpot3 = Circle (Point(70, 405), 11)
smallCowSpot3.setFill("white")
smallCowSpot3.draw(windowOne)

#Set up the farmer
#1) set up the first part of the hat
topHat = Circle (Point(545, 240), 40)
topHat.setFill(color_rgb(218,165,32))
topHat.setOutline("black")
topHat.draw(windowOne)
    
#2) set up the head
farmerHead = Circle (Point(547, 270), 50 )
farmerHead.setFill(color_rgb(250,235,215))
farmerHead.setOutline("black")
farmerHead.draw(windowOne)

#3) set up the second part of the hat
bottomHat = Oval(Point(460, 221), Point(625, 255))
bottomHat.setFill(color_rgb(184,134,11))
bottomHat.setOutline("black")
bottomHat.draw(windowOne)

#4) set up the chest/shirt
farmerShirt = Rectangle (Point(525, 320), Point(570, 410))
farmerShirt.setOutline("black")
farmerShirt.draw(windowOne)

#Farmer's shirt colour is selected by the user 
if userInput == "red":
    farmerShirt.setFill("red")

elif userInput == "green":
    farmerShirt.setFill("green")

elif userInput == "yellow":
    farmerShirt.setFill("yellow")

elif userInput == "cyan":
    farmerShirt.setFill("cyan")

elif userInput == "blue":
    farmerShirt.setFill("blue")

#5) set up the legs
farmerLegOne = Rectangle (Point(525, 410), Point(540, 460))
farmerLegOne.setFill(color_rgb(0, 0, 128))
farmerLegOne.setOutline("black")
farmerLegOne.draw(windowOne)

farmerLegTwo = Rectangle (Point(555, 410), Point(570, 460))
farmerLegTwo.setFill(color_rgb(0, 0, 128))
farmerLegTwo.setOutline("black")
farmerLegTwo.draw(windowOne)

#6) set up the arms
farmerArmOne = Rectangle (Point(510, 320), Point(525, 390))
farmerArmOne.setFill(color_rgb(250, 235, 215))
farmerArmOne.setOutline("black")
farmerArmOne.draw(windowOne)

farmerArmTwo = Rectangle (Point (570, 320), Point(585, 390))
farmerArmTwo.setFill(color_rgb(250, 235, 215))
farmerArmTwo.setOutline("black")
farmerArmTwo.draw(windowOne)
    
#7) set up the eyes
farmerEyeOne = Rectangle (Point(535, 265), Point(515, 280))
farmerEyeOne.setFill("white")
farmerEyeOne.setOutline("black")
farmerEyeOne.draw(windowOne)

farmerEyeTwo = Rectangle (Point(575, 265), Point(555, 280))
farmerEyeTwo.setFill("white")
farmerEyeTwo.setOutline("black")
farmerEyeTwo.draw(windowOne)

#the pupils 
farmerEye1Pupil = Circle (Point(518, 273), 2) 
farmerEye1Pupil.setFill("black")
farmerEye1Pupil.draw(windowOne)

farmerEye2Pupil = Circle (Point(558, 273), 2)
farmerEye2Pupil.setFill("black")
farmerEye2Pupil.draw(windowOne)

#8) Set up the mouth(s):
#closed mouth 
farmerMouthOne = Line (Point(535, 300), Point(550, 300))
farmerMouthOne.setFill("white")
farmerMouthOne.setOutline("black")
farmerMouthOne.draw(windowOne)

#open mouth -> later used in the animation
farmerMouthTwo = Oval (Point (535 ,290), Point(550, 305))
farmerMouthTwo.setFill(color_rgb(255,160,122))
farmerMouthTwo.setOutline("black")

#Animation begins:
#1) Once the farmer is set up, he comes in to the frame from the right
for i in range(0, 1):

    time.sleep(1) #pause

    #the farmer must stop behind the big cow 
    topHat.move(-5,0)
    farmerHead.move(-5,0)
    bottomHat.move(-5, 0)
    farmerShirt.move(-5,0)
    farmerLegOne.move(-5,0)
    farmerLegTwo.move(-5,0)
    farmerArmOne.move(-5,0)
    farmerArmTwo.move(-5,0)
    farmerEyeOne.move(-5,0)
    farmerEyeTwo.move(-5,0)
    farmerEye1Pupil.move(-5,0)
    farmerEye2Pupil.move(-5,0)
    farmerMouthOne.move(-5,0)
    update (10) #10 FPS

    #2) The farmer's messages animation:
    
    time.sleep(1)#pause
        
    #The text bubble to display the farmer's message:
    #the bottom triangle 
    indicationShape = Polygon (Point(400, 230), Point(400, 190), Point(480, 270))
    indicationShape.setFill("white")
    indicationShape.draw(windowOne)

    #the bubble
    bubbleText = Circle (Point(400, 180), 75)
    bubbleText.setFill("white")
    bubbleText.setOutline("black")
    bubbleText.draw(windowOne)

    #The texts that are going to be displayed
    farmerFirstMessage = "Hm... this is not my cow."
    farmerSecondMessage = "Where is my real cow?"
    farmerThirdMessage = "Oh no..."
    farmerFourthMessage = "The spaceship took it."
    farmerFifthMessage = "I have to get my cow back!"
        
    #Farmer's messages
    #1) text 
    farmerTxtOne = Text (Point(405, 190), farmerFirstMessage)
    farmerTxtOne.setTextColor("black")
    farmerTxtOne.setSize(9)
    farmerTxtOne.setFace("helvetica")
    farmerTxtOne.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtOne.undraw() #first text goes away

    #2) text
    farmerTxtTwo = Text (Point(405, 190), farmerSecondMessage)
    farmerTxtTwo.setTextColor("black")
    farmerTxtTwo.setSize(10)
    farmerTxtTwo.setFace("helvetica")
    farmerTxtTwo.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtTwo.undraw()#second text goes away

    #3) text
    #The farmer is shocked -> opens mouth
    time.sleep(1) #pause
    farmerMouthOne.undraw()
        
    time.sleep(0.8)#pause
    farmerMouthTwo.draw(windowOne) #farmer's mouth opens

    farmerTxtThree = Text (Point(405, 190), farmerThirdMessage)
    farmerTxtThree.setTextColor("black")
    farmerTxtThree.setSize(10)
    farmerTxtThree.setFace("helvetica")
    farmerTxtThree.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtThree.undraw()#third text goes away

    #4) text
    farmerTxtFour = Text (Point(405, 190), farmerFourthMessage)
    farmerTxtFour.setTextColor("black")
    farmerTxtFour.setSize(10)
    farmerTxtFour.setFace("helvetica")
    farmerTxtFour.draw(windowOne)

    time.sleep(2)#pause
    farmerTxtFour.undraw()#fourth text goes away

    #5) text
    farmerTxtFive = Text (Point(405, 190), farmerFifthMessage)
    farmerTxtFive.setTextColor("black")
    farmerTxtFive.setSize(8)
    farmerTxtFive.setFace("helvetica")
    farmerTxtFive.draw(windowOne)

    time.sleep(1)#pause
    farmerTxtFive.undraw()#fifth text goes away

    #bubble text disappears
    time.sleep(0.5)
    bubbleText.undraw()
    indicationShape.undraw()

    #farmer leaves to get his cow back
    topHat.move(5, 0)
    farmerHead.move(5, 0)
    bottomHat.move(5, 0)
    farmerShirt.move(5, 0)
    farmerLegOne.move(5, 0)
    farmerLegTwo.move(5, 0)
    farmerArmOne.move(5, 0)
    farmerArmTwo.move(5, 0)
    farmerEyeOne.move(5, 0)
    farmerEyeTwo.move(5, 0)
    farmerEye1Pupil.move(5, 0)
    farmerEye2Pupil.move(5, 0)
    farmerMouthTwo.move(5, 0)
    update (10) #10 FPS
        
#Keyboard input feature from user - Small Cow Animation:

#Display the instructions -> move the small cow right or left using specific keys.

#Display Text Instructions
displayText = "Please press 'a' to move the small cow left and 'd' to move it right"
bottomDisplay = Text(Point(300, 470), displayText)
bottomDisplay.setTextColor("white")
bottomDisplay.setSize(12)
bottomDisplay.setFace("helvetica")
bottomDisplay.setStyle("bold")
bottomDisplay.draw(windowOne)

time.sleep(3) #pause

displayText2 = "You are only allowed maximum TEN 'a' and 'b' clicks."
bottomDisplay2 = Text(Point(300, 490), displayText2)
bottomDisplay2.setTextColor("white")
bottomDisplay2.setSize(10)
bottomDisplay2.setFace("helvetica")
bottomDisplay2.draw(windowOne)

#keyboard controlled animation  loop (from user)
for i in range(0, 10):
    key = windowOne.getKey()
    print(key)

    #the small cow moves left feature
    if key == "a": #move all components left
        smallCowHead.move(-10, 0)
        smallCowBody.move(-10, 0)
        smallCowLeg1.move(-10, 0)
        smallCowLeg2.move(-10, 0)
        smallCowLeg3.move(-10, 0)
        smallCowLeg4.move(-10, 0)
        smallCowEar1.move(-10, 0)
        smallCowEar2.move(-10, 0)
        smallCowSpot1.move(-10, 0)
        smallCowSpot2.move(-10, 0)
        smallCowSpot3.move(-10, 0)
            
    #the small cow moves right feature
    elif key == "d": #move all components right
        smallCowHead.move(10, 0)
        smallCowBody.move(10, 0)
        smallCowLeg1.move(10, 0)
        smallCowLeg2.move(10, 0)
        smallCowLeg3.move(10, 0)
        smallCowLeg4.move(10, 0)
        smallCowEar1.move(10, 0)
        smallCowEar2.move(10, 0)
        smallCowSpot1.move(10, 0)
        smallCowSpot2.move(10, 0)
        smallCowSpot3.move(10, 0)

#Remove the keyboard control feature instruction display
time.sleep(1) #pause
bottomDisplay.undraw()
bottomDisplay2.undraw()

time.sleep(2) #pause

#User Instruction -> Transition to the next frame
instructionText = "This frame is over, please proceed to the next frame by clicking anywhere on the frame!"
nextFrame = Text(Point(300, 480), instructionText)
nextFrame.setTextColor("white")
nextFrame.setSize(11)
nextFrame.setFace("helvetica")
nextFrame.draw(windowOne) 
   
#user mouse click -> transition to the next frame
windowOne.getMouse() #user clicks anywhere with the mouse
windowOne.close()#frame closes








#ADDITIONAL FRAME -> ENTRY BOX USER INPUT (used TKINTER)

#Set up the import feature
import tkinter as tk
from tkinter import simpledialog

#Establish the entry user input box -> truck colour selection 
userInput2 = simpledialog.askstring(title="Entry User Input Box 2",
                                  prompt="Please select a colour for the farmer's truck. Please choose between white, grey, green3, or red4.")








#SECOND FRAME

#Display the chosen colour 
print("Your chosen colour for the truck is", userInput2 + ".")

#Establish the screen window and set the background day time colour
windowTwo = GraphWin ("Short story: Frame 2", 600, 500)
windowTwo.setBackground(color_rgb(135, 206, 250))

#Set up the green field 
greenField = Rectangle (Point(0, 290), Point(600, 500))
greenField.setFill(color_rgb(34, 139, 34))
greenField.setOutline("black")
greenField.draw(windowTwo)

#Set up the mountains
mountainOne = Polygon (Point(400, 290), Point(550, 50), Point(700, 290))
mountainOne.setFill(color_rgb(144, 238, 144))
mountainOne.setOutline("black")
mountainOne.draw(windowTwo)

mountainTwo = Polygon (Point(200, 290), Point(340, 50), Point(500, 290))
mountainTwo.setFill(color_rgb(144, 238, 144))
mountainTwo.setOutline("black")
mountainTwo.draw(windowTwo)

mountainThree = Polygon (Point(0, 290), Point(140, 50), Point(320, 290))
mountainThree.setFill(color_rgb(144, 238, 144))
mountainThree.setOutline("black")
mountainThree.draw(windowTwo)

#Set up the houses:
#1) 1st house
#the main building
houseOne = Rectangle (Point(40, 180), Point(160, 290))
houseOne.setFill(color_rgb(238, 232, 170))
houseOne.setOutline("black")
houseOne.draw(windowTwo)

#the roof
houseOneRoof = Polygon (Point(100, 130), Point(160, 180), Point(40, 180))
houseOneRoof.setFill(color_rgb(184,134,11))
houseOneRoof.setOutline("black")
houseOneRoof.draw(windowTwo)
    
#the door
houseOneDoor = Rectangle (Point(65, 230), Point(135, 290))
houseOneDoor.setFill(color_rgb(184, 134, 11))
houseOneDoor.setOutline("black")
houseOneDoor.draw(windowTwo)

houseTwoHandle = Circle(Point(73, 270), 3)
houseTwoHandle.setFill("black")
houseTwoHandle.draw(windowTwo)

#2) 2nd house
#the main building
houseTwo = Rectangle (Point(200, 180), Point(320, 290))
houseTwo.setFill(color_rgb(238, 232, 170))
houseTwo.setOutline("black")
houseTwo.draw(windowTwo)

#the roof
houseTwoRoof = Polygon (Point(260, 130), Point(320, 180), Point(200, 180))
houseTwoRoof.setFill(color_rgb(184, 134, 11))
houseTwoRoof.setOutline("black")
houseTwoRoof.draw(windowTwo)

#the door
houseTwoDoor = Rectangle (Point(225, 230), Point(295, 290))
houseTwoDoor.setFill(color_rgb(184, 134, 11))
houseTwoDoor.setOutline("black")
houseTwoDoor.draw(windowTwo)

houseTwoHandle = Circle(Point(233, 270), 3)
houseTwoHandle.setFill("black")
houseTwoHandle.draw(windowTwo)
                            
#3) 3rd house
houseThird= Rectangle (Point(520, 180), Point(625, 290))
houseThird.setFill(color_rgb(238, 232, 170))
houseThird.setOutline("black")
houseThird.draw(windowTwo)

houseThirdRoof = Polygon (Point(600, 130), Point(650, 180), Point(520, 180))
houseThirdRoof.setFill(color_rgb(184, 134, 11))
houseThirdRoof.setOutline("black")
houseThirdRoof.draw(windowTwo)

houseThirdDoor = Rectangle (Point(545, 230), Point(645, 290))
houseThirdDoor.setFill(color_rgb(184, 134, 11))
houseThirdDoor.setOutline("black")
houseThirdDoor.draw(windowTwo)

houseThirdHandle = Circle(Point(553, 270), 3)
houseThirdHandle.setFill("black")
houseThirdHandle.draw(windowTwo)


#Set up the road:
#grey part
greyRoad = Rectangle (Point(0, 340), Point(600, 460))
greyRoad.setFill(color_rgb(169, 169, 169))
greyRoad.setOutline("black")
greyRoad.draw(windowTwo)

#yellow lines
yellowLineOne = Rectangle (Point(-20, 395), Point(20, 405)) 
yellowLineOne.setFill("yellow")
yellowLineOne.draw(windowTwo)

yellowLineTwo = Rectangle (Point(60, 395), Point(100, 405)) 
yellowLineTwo.setFill("yellow")
yellowLineTwo.draw(windowTwo)

yellowLineThree = Rectangle (Point(140, 395), Point(180, 405)) 
yellowLineThree.setFill("yellow")
yellowLineThree.draw(windowTwo)

yellowLineFour = Rectangle (Point(220, 395), Point(260, 405)) 
yellowLineFour.setFill("yellow")
yellowLineFour.draw(windowTwo)

yellowLineFive = Rectangle (Point(300, 395), Point(340, 405)) 
yellowLineFive.setFill("yellow")
yellowLineFive.draw(windowTwo)

yellowLineSix = Rectangle (Point(380, 395), Point(420, 405)) 
yellowLineSix.setFill("yellow")
yellowLineSix.draw(windowTwo)

yellowLineSeven = Rectangle (Point(460, 395), Point(500, 405)) 
yellowLineSeven.setFill("yellow")
yellowLineSeven.draw(windowTwo)

yellowLineEight = Rectangle (Point(540, 395), Point(580, 405)) 
yellowLineEight.setFill("yellow")
yellowLineEight.draw(windowTwo)

yellowLineNine = Rectangle (Point(620, 395), Point(660, 405)) 
yellowLineNine.setFill("yellow")
yellowLineNine.draw(windowTwo)

#Set up the sun
brightSun = Circle (Point(60, 60), 40)
brightSun.setFill(color_rgb(255, 255, 0))
brightSun.setOutline("black")
brightSun.draw(windowTwo)

#Set up the farmer's truck:
#1) the main body
carBody = Rectangle (Point(-200, 320), Point(-70, 395))
carBody.setOutline("black")
carBody.draw(windowTwo)

#2) the front body
carFront = Rectangle (Point(-70, 340), Point(-10, 395))
carFront.setOutline("black")
carFront.draw(windowTwo)

#Truck's colour is selected/decided by the user
if userInput2 == "white":
    carBody.setFill("white")
    carFront.setFill("white")

elif userInput2 == "grey":
    carBody.setFill("grey")
    carFront.setFill("grey")

elif userInput2 == "green3":
    carBody.setFill("green3")
    carFront.setFill("green3")

elif userInput2 == "red4":
    carBody.setFill("red4")
    carFront.setFill("red4")
            

#3) the front window
carFrontWindow = Rectangle (Point(-55, 350), Point(-10, 380))
carFrontWindow.setFill(color_rgb(230, 230, 250))
carFrontWindow.draw(windowTwo)
    
#4) the wheels
# wheel 1
carWheelOne = Circle (Point(-175, 393), 23)
carWheelOne.setFill("black")
carWheelOne.setOutline("black")
carWheelOne.draw(windowTwo)

carWheelOneMetal = Circle (Point(-175, 393), 13)
carWheelOneMetal.setFill(color_rgb(211, 211, 211))
carWheelOneMetal.setOutline("white")
carWheelOneMetal.draw(windowTwo)

# wheel 2
carWheelTwo = Circle (Point(-100, 393), 23)
carWheelTwo.setFill("black")
carWheelTwo.setOutline('black')
carWheelTwo.draw(windowTwo)

carWheelTwoMetal = Circle (Point(-100, 393), 13)
carWheelTwoMetal.setFill(color_rgb(211, 211, 211))
carWheelTwoMetal.setOutline("white")
carWheelTwoMetal.draw(windowTwo)
    
#Set up the Spaceship:
#1) set up the lightbeam
lightBeam = Polygon (Point(-130, 170), Point(-270, 170), Point(-320, 430), Point(-70, 430))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(windowTwo)

#2) set up the main body 
spaceShip = Oval (Point(-100, 150), Point(-300, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(windowTwo)
    
#3) set up the window
spaceShipWindow = Oval (Point(-170, 160), Point(-220, 180))
spaceShipWindow.setFill(color_rgb(224, 255, 255))
spaceShipWindow.setOutline("black")
spaceShipWindow.draw(windowTwo)

#Animation begins:

#The farmer is in the truck and he chases after the spaceship
for i in range(0, 100):
        
    #spaceship moves right - getting chased
    lightBeam.move(15, 0)
    spaceShip.move(15, 0)
    spaceShipWindow.move(15, 0)
    update (15) #15 FPS

for i in range(0, 100):

    #farmer's truck moves right - chases the spaceship
    carBody.move(15, 0)
    carFront.move(15, 0)
    carFrontWindow.move(15, 0)
    carWheelOne.move(15, 0)
    carWheelTwo.move(15, 0)
    carWheelOneMetal.move(15, 0)
    carWheelTwoMetal.move(15, 0)
    update(20) #20 FPS
 


#User Instruction for the next frame's transition
message = "This frame is over, please proceed to the next frame by clicking anywhere on the frame!"
nextFrameTransition = Text(Point(300, 480), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(11)
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowTwo)


windowTwo.getMouse() #clicks with mouse anywhere on the frame
windowTwo.close() #this frame closes













#THIRD FRAME

#set the window screen and background
windowThree = GraphWin("Short story: Frame 3", 600, 500)
windowThree.setBackground(color_rgb(135, 206, 250))

#Set up the green field 
greenField = Rectangle (Point(0, 320), Point(600, 500))
greenField.setFill(color_rgb(34,139,34))
greenField.setOutline("black")
greenField.draw(windowThree)

#Set up the sun
brightSun = Circle (Point(60, 60), 40)
brightSun.setFill(color_rgb(255, 255, 0))
brightSun.setOutline("black")
brightSun.draw(windowThree)

#Set up the mountains
bigMountain = Polygon (Point(180, 320), Point(320, 20), Point(470, 320))
bigMountain.setFill(color_rgb(144,238,144))
bigMountain.setOutline("black")
bigMountain.draw(windowThree)

smallMountain = Polygon (Point(20, 320), Point(160, 80), Point(290, 320))
smallMountain.setFill(color_rgb(144,238,144))
smallMountain.setOutline("black")
smallMountain.draw(windowThree)

#Set up the trees
treeOneTrunk = Rectangle (Point(45, 270), Point(70, 320))
treeOneTrunk.setFill(color_rgb(74, 51, 27))
treeOneTrunk.setOutline("black")
treeOneTrunk.draw(windowThree)

treeOne = Circle (Point(55, 245), 35)
treeOne.setFill(color_rgb(33, 97, 21))
treeOne.setOutline("black")
treeOne.draw(windowThree)

treeTwoTrunk = Rectangle (Point(130, 270), Point(155, 320))
treeTwoTrunk.setFill(color_rgb(74, 51, 27))
treeTwoTrunk.setOutline("black")
treeTwoTrunk.draw(windowThree)

treeTwo = Circle (Point(140, 245), 35)
treeTwo.setFill(color_rgb(33, 97, 21))
treeTwo.setOutline("black")
treeTwo.draw(windowThree)

treeThreeTrunk = Rectangle (Point(210, 270), Point(235, 320))
treeThreeTrunk.setFill(color_rgb(74, 51, 27))
treeThreeTrunk.setOutline("black")
treeThreeTrunk.draw(windowThree)

treeThree = Circle (Point(220, 245), 35)
treeThree.setFill(color_rgb(33, 97, 21))
treeThree.setOutline("black")
treeThree.draw(windowThree)

#Set up the farm house:
#1) the chimney 
yellowChimney = Rectangle (Point(440, 100), Point(490, 320))
yellowChimney.setFill(color_rgb(189, 139, 23))
yellowChimney.setOutline("black")
yellowChimney.draw(windowThree)

#2) the first base
groundBase = Rectangle (Point(415, 220), Point(600, 320)) 
groundBase.setFill(color_rgb(201, 34, 34))
groundBase.setOutline("black")
groundBase.draw(windowThree)

#3) the second level
secondLevel = Rectangle (Point(440, 170), Point(600, 220))
secondLevel.setFill(color_rgb(163, 42, 42))
secondLevel.setOutline("black")
secondLevel.draw(windowThree)

#4) the attic
yellowAttic = Polygon (Point(440, 170), Point(525, 100), Point(600, 170))
yellowAttic.setFill(color_rgb(247, 184, 47))
yellowAttic.setOutline("black")
yellowAttic.draw(windowThree)

#5) the doors
whiteDoorOne = Rectangle (Point(480, 255), Point(525, 320))
whiteDoorOne.setFill("white")
whiteDoorOne.setOutline("black")
whiteDoorOne.draw(windowThree)

whiteDoorTwo = Rectangle (Point(525, 255), Point(570, 320))
whiteDoorTwo.setFill("white")
whiteDoorTwo.setOutline("black")
whiteDoorTwo.draw(windowThree)
    
#Set up the road
greyRoad = Rectangle (Point(0, 350), Point(600, 440))
greyRoad.setFill(color_rgb(169,169,169))
greyRoad.setOutline("black")
greyRoad.draw(windowThree)

yellowLine = Rectangle (Point(0, 390), Point(600, 400))
yellowLine.setFill("yellow")
yellowLine.setOutline("black")
yellowLine.draw(windowThree)
    
#Set up the calf:
#1) draw the body
cowBody = Rectangle (Point(610, 400), Point(710, 460))
cowBody.setFill(color_rgb(184, 134, 11))
cowBody.setOutline("black")
cowBody.draw(windowThree)

#2) draw the head
cowHead = Rectangle (Point(560, 400), Point(610, 450))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowThree)

#3) draw the legs
cowLeg1 = Rectangle (Point(610, 460), Point(625, 490))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowThree)

cowLeg2 = Rectangle (Point(630, 460), Point(645, 490))
cowLeg2.setFill(color_rgb(184, 134, 11))
cowLeg2.setOutline("black")
cowLeg2.draw(windowThree)
    
cowLeg3 = Rectangle (Point(675, 460), Point(690, 490))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowThree)

cowLeg4 = Rectangle (Point(695, 460), Point(710, 490))
cowLeg4.setFill(color_rgb(184, 134, 11))
cowLeg4.setOutline("black")
cowLeg4.draw(windowThree)

#4) draw the ears
cowEar1 = Rectangle (Point(565, 386), Point(575, 400))
cowEar1.setFill(color_rgb(184,134,11))
cowEar1.setOutline("black")
cowEar1.draw(windowThree)

cowEar2 = Rectangle (Point(595, 386), Point(605, 400))
cowEar2.setFill(color_rgb(184,134,11))
cowEar2.setOutline("black")
cowEar2.draw(windowThree)

#5) draw the black spots
cowSpot1 = Circle (Point(630, 420), 12)
cowSpot1.setFill("white")
cowSpot1.draw(windowThree)

cowSpot2 = Circle (Point(680, 440), 12)
cowSpot2.setFill("white")
cowSpot2.draw(windowThree)

#Set up the spaceship:
#1) set up the lightbeam
lightBeam = Polygon (Point(-130, 170), Point(-270, 170), Point(-320, 430), Point(-70, 430))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(windowThree)

#2) set up the main body of the spaceship
spaceShip = Oval (Point(-100, 150), Point(-300, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(windowThree)

#3) set up the window of the spaceship
spaceShipWindow = Oval (Point(-170, 160), Point(-220, 180))
spaceShipWindow.setFill(color_rgb(224, 255, 255))
spaceShipWindow.setOutline("black")
spaceShipWindow.draw(windowThree)

#Animation begins:

#calf animation
for i in range(0, 70):

    #the lost calf stops near the farmhouse
    if cowBody.getCenter().getX() == 460:
        break
    
    #calf moves left
    cowBody.move(-2, 0)
    cowHead.move(-2, 0)
    cowLeg1.move(-2, 0)
    cowLeg2.move(-2, 0)
    cowLeg3.move(-2, 0)
    cowLeg4.move(-2, 0)
    cowEar1.move(-2, 0)
    cowEar2.move(-2, 0)
    cowSpot1.move(-2, 0)
    cowSpot2.move(-2, 0)
    update(20) #20 FPS
    
#spaceship animation 
for i in range(0, 115):

    #the spaceship stops in front of the calf 
    if spaceShip.getCenter().getX() == 415:
        break
    
    #spaceship moves right 
    lightBeam.move(4, 0)
    spaceShip.move(4, 0)
    spaceShipWindow.move(4, 0)
    update (15) #15 FPS

#quick pause
time.sleep(2)

#the mom cow animation
for i in range(0, 1):

    #Set up the mother cow:        
    #1) draw the body
    motherCowBody = Rectangle (Point(190, 180), Point(340, 260))
    motherCowBody.setFill("white")
    motherCowBody.setOutline("black")
    motherCowBody.draw(windowThree)

    #2) draw the head
    motherCowHead = Rectangle (Point(340, 180), Point(400, 230))
    motherCowHead.setFill("white")
    motherCowHead.setOutline("black")
    motherCowHead.draw(windowThree)

    #3) draw the legs
    motherCowLeg1 = Rectangle (Point(190, 260), Point(205, 290))
    motherCowLeg1.setFill("white")
    motherCowLeg1.setOutline("black")
    motherCowLeg1.draw(windowThree)

    motherCowLeg2 = Rectangle (Point(220, 260), Point(235, 290))
    motherCowLeg2.setFill("white")
    motherCowLeg2.setOutline("black")
    motherCowLeg2.draw(windowThree)

    motherCowLeg3 = Rectangle (Point(295, 260), Point(310, 290))
    motherCowLeg3.setFill("white")
    motherCowLeg3.setOutline("black")
    motherCowLeg3.draw(windowThree)

    motherCowLeg4 = Rectangle (Point(325, 260), Point(340, 290))
    motherCowLeg4.setFill("white")
    motherCowLeg4.setOutline("black")
    motherCowLeg4.draw(windowThree)

    #4) draw the ears
    motherCowEar1 = Rectangle (Point(345, 170), Point(355, 180))
    motherCowEar1.setFill(color_rgb(238, 232, 170))
    motherCowEar1.setOutline("black")
    motherCowEar1.draw(windowThree)

    motherCowEar2 = Rectangle (Point(385, 170), Point(395, 180))
    motherCowEar2.setFill(color_rgb(238, 232, 170))
    motherCowEar2.setOutline("black")
    motherCowEar2.draw(windowThree)

    #5) draw the black spots
    motherCowSpot1 = Circle (Point(220, 230), 20)
    motherCowSpot1.setFill("black")
    motherCowSpot1.draw(windowThree)

    motherCowSpot2 = Circle (Point(260, 210), 20)
    motherCowSpot2.setFill("black")
    motherCowSpot2.draw(windowThree)

    motherCowSpot3 = Circle (Point(310, 230), 20)
    motherCowSpot3.setFill("black")
    motherCowSpot3.draw(windowThree)

for i in range(0, 40):
    #the cow is dropped off by the spaceship 
    motherCowBody.move(0, 5)
    motherCowHead.move(0, 5)
    motherCowLeg1.move(0, 5)
    motherCowLeg2.move(0, 5)
    motherCowLeg3.move(0, 5)
    motherCowLeg4.move(0, 5)
    motherCowEar1.move(0, 5)
    motherCowEar2.move(0, 5)
    motherCowSpot1.move(0, 5)
    motherCowSpot2.move(0, 5)
    motherCowSpot3.move(0, 5)
    update(15) #15 FPS

for i in range(0, 1):
    #the bubble text 
    bubbleText2 = Circle (Point(420, 310), 50)
    bubbleText2.setFill("white")
    bubbleText2.setOutline("black")
    bubbleText2.draw(windowThree)

#The text that is going to be displayed
    cowMessage = "Moo!"
    
#mother cow message 
    #1) text 
    cowTxt = Text (Point(420, 315), cowMessage)
    cowTxt.setTextColor("black")
    cowTxt.setSize(9)
    cowTxt.setFace("helvetica")
    cowTxt.draw(windowThree)

    time.sleep(3)#pause
    cowTxt.undraw() #mother cow sound goes away
    bubbleText2.undraw()

#User Instruction for the next frame's transition
message = "This frame is over, please proceed to the next frame by clicking anywhere on the frame!"
nextFrameTransition = Text(Point(300, 10), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(10)
nextFrameTransition.setStyle("bold")
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowThree)

#close the frame 3 and proceed to frame 4
windowThree.getMouse()
windowThree.close() #this frame closes











#FOURTH FRAME

#Display the number of stars for the user
print("You will see 10 twinkling stars.") 

#**note**: counter and accumulator used in fourth frame.
#set the window screen and background
windowFour = GraphWin("Short story: Frame 4", 600, 500)
windowFour.setBackground(color_rgb(135, 206, 250))

#Set up the moon -> later used for animation
halfMoon = Circle(Point(40, 360), 40)
halfMoon.setFill(color_rgb(245, 245, 245))
halfMoon.setOutline("black")
halfMoon.draw(windowFour)

skyCover = Circle(Point(60, 355), 40)
skyCover.setFill(color_rgb(25, 25, 112))
skyCover.setOutline(color_rgb(25, 25, 112))
skyCover.draw(windowFour)

#Set up the green field 
greenField = Rectangle (Point(0, 320), Point(600, 500))
greenField.setFill(color_rgb(34,139,34))
greenField.setOutline("black")
greenField.draw(windowFour)

#Set up the sun
brightSun = Circle (Point(60, 60), 40)
brightSun.setFill(color_rgb(255, 255, 0))
brightSun.setOutline("black")
brightSun.draw(windowFour)

#Set up the mountains
bigMountain = Polygon (Point(180, 320), Point(320, 20), Point(470, 320))
bigMountain.setFill(color_rgb(144,238,144))
bigMountain.setOutline("black")
bigMountain.draw(windowFour)

smallMountain = Polygon (Point(20, 320), Point(160, 80), Point(290, 320))
smallMountain.setFill(color_rgb(144,238,144))
smallMountain.setOutline("black")
smallMountain.draw(windowFour)

#Set up the trees
treeOneTrunk = Rectangle (Point(45, 270), Point(70, 320))
treeOneTrunk.setFill(color_rgb(74, 51, 27))
treeOneTrunk.setOutline("black")
treeOneTrunk.draw(windowFour)

treeOne = Circle (Point(55, 245), 35)
treeOne.setFill(color_rgb(33, 97, 21))
treeOne.setOutline("black")
treeOne.draw(windowFour)

treeTwoTrunk = Rectangle (Point(130, 270), Point(155, 320))
treeTwoTrunk.setFill(color_rgb(74, 51, 27))
treeTwoTrunk.setOutline("black")
treeTwoTrunk.draw(windowFour)

treeTwo = Circle (Point(140, 245), 35)
treeTwo.setFill(color_rgb(33, 97, 21))
treeTwo.setOutline("black")
treeTwo.draw(windowFour)

treeThreeTrunk = Rectangle (Point(210, 270), Point(235, 320))
treeThreeTrunk.setFill(color_rgb(74, 51, 27))
treeThreeTrunk.setOutline("black")
treeThreeTrunk.draw(windowFour)

treeThree = Circle (Point(220, 245), 35)
treeThree.setFill(color_rgb(33, 97, 21))
treeThree.setOutline("black")
treeThree.draw(windowFour)

#Set up the farm house:
#1) the chimney 
yellowChimney = Rectangle (Point(440, 100), Point(490, 320))
yellowChimney.setFill(color_rgb(189, 139, 23))
yellowChimney.setOutline("black")
yellowChimney.draw(windowFour)

#2) the first base
groundBase = Rectangle (Point(415, 220), Point(600, 320)) 
groundBase.setFill(color_rgb(201, 34, 34))
groundBase.setOutline("black")
groundBase.draw(windowFour)

#3) the second level
secondLevel = Rectangle (Point(440, 170), Point(600, 220))
secondLevel.setFill(color_rgb(163, 42, 42))
secondLevel.setOutline("black")
secondLevel.draw(windowFour)

#4) the attic
yellowAttic = Polygon (Point(440, 170), Point(525, 100), Point(600, 170))
yellowAttic.setFill(color_rgb(247, 184, 47))
yellowAttic.setOutline("black")
yellowAttic.draw(windowFour)

#5) the doors
whiteDoorOne = Rectangle (Point(480, 255), Point(525, 320))
whiteDoorOne.setFill("white")
whiteDoorOne.setOutline("black")
whiteDoorOne.draw(windowFour)

whiteDoorTwo = Rectangle (Point(525, 255), Point(570, 320))
whiteDoorTwo.setFill("white")
whiteDoorTwo.setOutline("black")
whiteDoorTwo.draw(windowFour)
    
#Set up the road
greyRoad = Rectangle (Point(0, 350), Point(600, 440))
greyRoad.setFill(color_rgb(169,169,169))
greyRoad.setOutline("black")
greyRoad.draw(windowFour)

yellowLine = Rectangle (Point(0, 390), Point(600, 400))
yellowLine.setFill("yellow")
yellowLine.setOutline("black")
yellowLine.draw(windowFour)

#Set up the farmer's truck:
#1) the main body
carBody = Rectangle (Point(-200, 320), Point(-70, 395))
carBody.setFill("white")
carBody.setOutline("black")
carBody.draw(windowFour)

#2) the front body
carFront = Rectangle (Point(-70, 340), Point(-10, 395))
carFront.setFill("white")
carFront.setOutline("black")
carFront.draw(windowFour)

#3) the front window
carFrontWindow = Rectangle (Point(-55, 350), Point(-10, 380))
carFrontWindow.setFill(color_rgb(230, 230, 250))
carFrontWindow.draw(windowFour)

#4) the wheels
# wheel 1
carWheelOne = Circle (Point(-175, 393), 23)
carWheelOne.setFill("black")
carWheelOne.setOutline("black")
carWheelOne.draw(windowFour)

carWheelOneMetal = Circle (Point(-175, 393), 13)
carWheelOneMetal.setFill(color_rgb(211, 211, 211))
carWheelOneMetal.setOutline("white")
carWheelOneMetal.draw(windowFour)

# wheel 2
carWheelTwo = Circle (Point(-100, 393), 23)
carWheelTwo.setFill("black")
carWheelTwo.setOutline('black')
carWheelTwo.draw(windowFour)

carWheelTwoMetal = Circle (Point(-100, 393), 13)
carWheelTwoMetal.setFill(color_rgb(211, 211, 211))
carWheelTwoMetal.setOutline("white")
carWheelTwoMetal.draw(windowFour)

#Set up the spaceship
#1) Establish the lightbeam
lightBeam = Polygon (Point(160, 170), Point(290, 170), Point(355, 430), Point(118, 430))
lightBeam.setFill(color_rgb(0, 255, 0))
lightBeam.setOutline(color_rgb(152, 251, 152))
lightBeam.draw(windowFour)

#2) set up the main body of the spaceship
spaceShip = Oval (Point(130, 150), Point(320, 190))
spaceShip.setFill(color_rgb(128, 128, 128))
spaceShip.setOutline("black")
spaceShip.draw(windowFour)
    
#3) set up the window of the spaceship
window = Oval (Point(200, 160), Point(250, 180))
window.setFill(color_rgb(224, 255, 255))
window.setOutline("black")
window.draw(windowFour)

#Set up the calf:
#1) draw the body
cowBody = Rectangle (Point(410, 400), Point(510, 460))
cowBody.setFill(color_rgb(184, 134, 11))
cowBody.setOutline("black")
cowBody.draw(windowFour)

#2) draw the head
cowHead = Rectangle (Point(360, 400), Point(410, 450))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowFour)

#3) draw the legs
cowLeg1 = Rectangle (Point(410, 460), Point(425, 490))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowFour)

cowLeg2 = Rectangle (Point(430, 460), Point(445, 490))
cowLeg2.setFill(color_rgb(184, 134, 11))
cowLeg2.setOutline("black")
cowLeg2.draw(windowFour)
    
cowLeg3 = Rectangle (Point(475, 460), Point(490, 490))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowFour)

cowLeg4 = Rectangle (Point(495, 460), Point(510, 490))
cowLeg4.setFill(color_rgb(184, 134, 11))
cowLeg4.setOutline("black")
cowLeg4.draw(windowFour)

#4) draw the ears
cowEar1 = Rectangle (Point(365, 386), Point(375, 400))
cowEar1.setFill(color_rgb(184,134,11))
cowEar1.setOutline("black")
cowEar1.draw(windowFour)

cowEar2 = Rectangle (Point(395, 386), Point(405, 400))
cowEar2.setFill(color_rgb(184,134,11))
cowEar2.setOutline("black")
cowEar2.draw(windowFour)

#5) draw the black spots
cowSpot1 = Circle (Point(430, 420), 12)
cowSpot1.setFill("white")
cowSpot1.draw(windowFour)

cowSpot2 = Circle (Point(480, 440), 12)
cowSpot2.setFill("white")
cowSpot2.draw(windowFour)

#Draw the mother cow 
#1) draw the body
cowBody = Rectangle (Point(150, 390), Point(300, 470))
cowBody.setFill("white")
cowBody.setOutline("black")
cowBody.draw(windowFour)

#2) draw the head
cowHead = Rectangle (Point(300, 390), Point(352, 445))
cowHead.setFill("white")
cowHead.setOutline("black")
cowHead.draw(windowFour)

#3) draw the legs
cowLeg1 = Rectangle (Point(150, 470), Point(165, 490))
cowLeg1.setFill("white")
cowLeg1.setOutline("black")
cowLeg1.draw(windowFour)

cowLeg2 = Rectangle (Point(180, 470), Point(195, 490))
cowLeg2.setFill("white")
cowLeg2.setOutline("black")
cowLeg2.draw(windowFour)

cowLeg3 = Rectangle (Point(250, 470), Point(265, 490))
cowLeg3.setFill("white")
cowLeg3.setOutline("black")
cowLeg3.draw(windowFour)

cowLeg4 = Rectangle (Point(285, 470), Point(300, 490))
cowLeg4.setFill("white")
cowLeg4.setOutline("black")
cowLeg4.draw(windowFour)

#4) draw the ears
cowEar1 = Rectangle (Point(300, 380), Point(310, 390))
cowEar1.setFill(color_rgb(238, 232, 170))
cowEar1.setOutline("black")
cowEar1.draw(windowFour)

cowEar2 = Rectangle (Point(340, 380), Point(350, 390))
cowEar2.setFill(color_rgb(238, 232, 170))
cowEar2.setOutline("black")
cowEar2.draw(windowFour)

#5) draw the black spots
cowSpot1 = Circle (Point(180, 445), 20)
cowSpot1.setFill("black")
cowSpot1.draw(windowFour)

cowSpot2 = Circle (Point(230, 415), 20)
cowSpot2.setFill("black")
cowSpot2.draw(windowFour)

cowSpot3 = Circle (Point(275, 445), 20)
cowSpot3.setFill("black")
cowSpot3.draw(windowFour)                

#Animation begins:

#Sunset -> sun disappears 
for i in range(0, 200):
    brightSun.move(0, 1)
    brightSun.move(-0.5, 0)
    update(20) #20 FPS

time.sleep(2) #pause

#Night time -> sky turns dark
for i in range(0, 1):
    windowFour.setBackground(color_rgb(25, 25, 112)) #change the background colour

#Set up the stars - projected on the sky
star1 = Polygon(Point(140, 20), Point(150, 10), Point(160, 20), Point(150, 30))
star1.setFill(color_rgb(255, 255, 224))
star1.draw(windowFour)

star2 = Polygon(Point(170, 60), Point(180, 50), Point(190, 60), Point(180,70))
star2.setFill(color_rgb(255, 255, 224))
star2.draw(windowFour)

star3 = Polygon(Point(350, 20), Point(360, 10), Point(370, 20), Point(360, 30))
star3.setFill(color_rgb(255, 255, 224))
star3.draw(windowFour)

star5 = Polygon(Point(470, 80), Point(480, 70), Point(490, 80), Point(480, 90))
star5.setFill(color_rgb(255, 255, 224))

star6 = Polygon(Point(500, 30), Point(510, 20), Point(520, 30), Point(510, 40))
star6.setFill(color_rgb(255, 255, 224))
star6.draw(windowFour)

star7 = Polygon(Point(560, 100), Point(570, 90), Point(580, 100), Point(570, 110))
star7.setFill(color_rgb(255, 255, 224))

star9 = Polygon(Point(250, 100), Point(260, 90), Point(270, 100), Point(260, 110))
star9.setFill(color_rgb(255, 255, 224))
star9.draw(windowFour)

star10 = Polygon(Point(20, 30), Point(30, 20), Point(40, 30), Point(30, 40))
star10.setFill(color_rgb(255, 255, 224))
star10.draw(windowFour)

#Stars twinkle animation
for i in range(0, 100):
  star1.undraw()
  star1.draw(windowFour)
  star2.undraw()
  star2.draw(windowFour)
  star3.undraw()
  star3.draw(windowFour)
  star5.undraw()
  star5.draw(windowFour)
  star6.undraw()
  star6.draw(windowFour)
  star7.undraw()
  star7.draw(windowFour)
  star9.undraw()
  star9.draw(windowFour)
  star10.undraw()
  star10.draw(windowFour)
  update(10) #10 FPS


#Set up the counter and accumulator -> related to the stars:

#10 stars
#Declare and Initialize
counter = 1
sum = 0
numStars = 10

#The accumulator and counter
while counter <= numStars:
  counter = counter + 1 #counter
  sum += 10 #accumulator
    
#Print the results:
print("The sum of all the stars is:", sum)
print("The average of the stars is:", round(sum/counter, 1))

#Display the accumulator/counter result on the window
infoTxt = "10 stars twinkled."

#Display Text
displayInformation = Text (Point(510, 335), infoTxt)
displayInformation.setTextColor("black")
displayInformation.setSize(12)
displayInformation.setStyle("bold")
displayInformation.setFace("helvetica")
displayInformation.draw(windowFour)

time.sleep(4) #pause

#Erase the text
displayInformation.undraw()

#Moon appears 
for i in range(0, 280):
    skyCover.move(0, -1)
    skyCover.move(0.1, 0)
    update(50) #50 FPS

    halfMoon.move(0, -1)
    halfMoon.move(0.1, 0)
    update(50) #50 FPS        


#Farmer's truck comes from the right
for i in range(0, 40):

  #User selected truck colour - fill in before animation
  if userInput2 == "white":
    carBody.setFill("white")
    carFront.setFill("white")

  elif userInput2 == "grey":
    carBody.setFill("grey")
    carFront.setFill("grey")

  elif userInput2 == "green3":
    carBody.setFill("green3")
    carFront.setFill("green3")

  elif userInput2 == "red4":
    carBody.setFill("red4")
    carFront.setFill("red4")

    #truck moves
    carBody.move(6, 0)
    carFront.move(6, 0)
    carFrontWindow.move(6, 0)
    carWheelOne.move(6, 0)
    carWheelTwo.move(6, 0)
    carWheelOneMetal.move(6, 0)
    carWheelTwoMetal.move(6, 0)
    update(10) #10 FPS

#pause
time.sleep(2)

#The farmer goes out of the truck 
for i in range(0, 1):
    #Set up the farmer
    #1) set up the first part of the hat
    topHat = Circle (Point(100, 260), 30)
    topHat.setFill(color_rgb(218,165,32))
    topHat.setOutline("black")
    topHat.draw(windowFour)

    #4) set up the chest/shirt
    farmerShirt = Rectangle (Point(80, 310), Point(120, 420))
    farmerShirt.setOutline("black")

    #user colour selection 
    if userInput == "red":
        farmerShirt.setFill("red")

    elif userInput == "green":
        farmerShirt.setFill("green")

    elif userInput == "yellow":
        farmerShirt.setFill("yellow")

    elif userInput == "cyan":
        farmerShirt.setFill("cyan")

    elif userInput == "blue":
        farmerShirt.setFill("blue")

    farmerShirt.draw(windowFour)
        
    #2) Set up the head
    farmerHead = Circle (Point(100, 295), 40 )
    farmerHead.setFill(color_rgb(250,235,215))
    farmerHead.setOutline("black")
    farmerHead.draw(windowFour)

    #3) set up the second part of the hat
    bottomHat = Oval(Point(35, 250), Point(160, 270))
    bottomHat.setFill(color_rgb(184,134,11))
    bottomHat.setOutline("black")
    bottomHat.draw(windowFour)

    #5) set up the legs
    farmerLegOne = Rectangle (Point(80, 420), Point(95, 480))
    farmerLegOne.setFill(color_rgb(0, 0, 128))
    farmerLegOne.setOutline("black")
    farmerLegOne.draw(windowFour)

    farmerLegTwo = Rectangle (Point(105, 420), Point(120, 480))
    farmerLegTwo.setFill(color_rgb(0, 0, 128))
    farmerLegTwo.setOutline("black")
    farmerLegTwo.draw(windowFour)

    #6) set up the arms
    farmerArmOne = Rectangle (Point(70, 330), Point(80, 410))
    farmerArmOne.setFill(color_rgb(250, 235, 215))
    farmerArmOne.setOutline("black")
    farmerArmOne.draw(windowFour)

    farmerArmTwo = Rectangle (Point (120, 330), Point(130, 410))
    farmerArmTwo.setFill(color_rgb(250, 235, 215))
    farmerArmTwo.setOutline("black")
    farmerArmTwo.draw(windowFour)
        
    #7) set up the eyes
    farmerEyeOne = Rectangle (Point(75, 280), Point(95, 300))
    farmerEyeOne.setFill("white")
    farmerEyeOne.setOutline("black")
    farmerEyeOne.draw(windowFour)

    farmerEyeTwo = Rectangle (Point(110, 280), Point(130, 300))
    farmerEyeTwo.setFill("white")
    farmerEyeTwo.setOutline("black")
    farmerEyeTwo.draw(windowFour)

    #the pupils 
    farmerEye1Pupil = Circle (Point(90, 292), 2) 
    farmerEye1Pupil.setFill("black")
    farmerEye1Pupil.draw(windowFour)

    farmerEye2Pupil = Circle (Point(125, 292), 2)
    farmerEye2Pupil.setFill("black")
    farmerEye2Pupil.draw(windowFour)

for i in range(0, 1):
    #8) Set up the mouth:
    #closed mouth 
    farmerMouthOne = Line (Point(95, 315), Point(110, 315))
    farmerMouthOne.setFill("white")
    farmerMouthOne.setOutline("black")
    farmerMouthOne.draw(windowFour)

    time.sleep(2)

    farmerMouthOne.undraw()

#farmer's surprised expression
for i in range(0, 1):

    totalSize = 9
    farmerHappy = Circle (Point(100, 320), totalSize)
    farmerHappy.setFill(color_rgb(255,160,122))
    farmerHappy.setOutline("black")
    farmerHappy.draw(windowFour)

    #the bubble
    bubbleText = Circle (Point(130, 170), 75)
    bubbleText.setFill("white")
    bubbleText.setOutline("black")
    bubbleText.draw(windowFour)

    #The texts that are going to be displayed
    textOne = "Oh... my little Joey..."
    textTwo = "You were here this whole time!"
    textThree = "Yay! We found you and your mom."
    textFour = "Thank you aliens."
        
    #Farmer's messages
    #1) text 
    firstMessage = Text (Point(130, 170), textOne)
    firstMessage.setTextColor("black")
    firstMessage.setSize(9)
    firstMessage.setFace("helvetica")
    firstMessage.draw(windowFour)

    time.sleep(2)#pause
    firstMessage.undraw() #first text goes away
    farmerHappy.undraw()

#farmer thanks the spaceship:
for i in range(0, 1):
    totalSize = 6 #the radius
    farmerHappy2 = Circle (Point(100, 320), totalSize)
    farmerHappy2.setFill(color_rgb(255,160,122))
    farmerHappy2.setOutline("black")
    farmerHappy2.draw(windowFour)

    #2) text
    secondMessage = Text (Point(130, 170), textTwo)
    secondMessage.setTextColor("black")
    secondMessage.setSize(8)
    secondMessage.setFace("helvetica")
    secondMessage.draw(windowFour)

    time.sleep(3)#pause
    secondMessage.undraw()#second text goes away

    #3) text
    thirdMessage = Text (Point(130, 170), textThree)
    thirdMessage.setTextColor("black")
    thirdMessage.setSize(6)
    thirdMessage.setFace("helvetica")
    thirdMessage.setStyle("bold")
    thirdMessage.draw(windowFour)

    time.sleep(3)#pause
    thirdMessage.undraw()#third text goes away

    #4) text
    fourthMessage = Text (Point(130, 170), textFour)
    fourthMessage.setTextColor("black")
    fourthMessage.setSize(10)
    fourthMessage.setFace("helvetica")
    fourthMessage.draw(windowFour)

    time.sleep(2)#pause
    fourthMessage.undraw()#fourth text goes away

    #bubble text disappears
    time.sleep(0.5)
    bubbleText.undraw()

#After the farmer shows appreciation, the spaceship goes away. 
for i in range(0, 80):
  
    #spaceship animation 
    spaceShip.move(7, 0)
    window.move(7, 0)
    lightBeam.move(7, 0)
    update(10) #10 FPS


#User Instruction for the next frame's transition
message = "This frame is over, please proceed to the next one by clicking anywhere on the frame!"
nextFrameTransition = Text(Point(300, 10), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(11)
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowFour)


windowFour.getMouse() #user clicks anywhere with the mouse on the window
windowFour.close() #the last frame closes




  








#FINAL AND LAST FRAME
  
#set up the screen window 
windowFive = GraphWin("Short story: Final Frame", 600, 500)
windowFive.setBackground("black")

#set up the messages that are going to be displayed
displayText0 = "The End."
displayText1 = "Thank you for watching."
displayText2 = "Moral of the short story:"
displayText3 = "Never assume something."

#ending display
endDisplay = Text(Point(300, 290), displayText0)
endDisplay.setTextColor("white")
endDisplay.setSize(19)
endDisplay.setFace("helvetica")
endDisplay.setStyle("bold")
endDisplay.draw(windowFive)

time.sleep(1) #pause

endDisplay.undraw()

#thank the audience
thankDisplay = Text(Point(300, 290), displayText1)
thankDisplay.setTextColor("white")
thankDisplay.setSize(19)
thankDisplay.setFace("helvetica")
thankDisplay.setStyle("bold")
thankDisplay.draw(windowFive)

time.sleep(2) #pause

thankDisplay.undraw()

#moral of the story
moralDisplay = Text(Point(300, 290), displayText2)
moralDisplay.setTextColor("white")
moralDisplay.setSize(18)
moralDisplay.setFace("helvetica")
moralDisplay.setStyle("bold")
moralDisplay.draw(windowFive)

time.sleep (2) # pause

#moral quote
realMoralDisplay = Text(Point(300, 370), displayText3)
realMoralDisplay.setTextColor("white")
realMoralDisplay.setSize(20)
realMoralDisplay.setFace("helvetica")
realMoralDisplay.setStyle("italic")
realMoralDisplay.draw(windowFive)

#image (gif) feature display
alienImage = Image(Point(300, 180), "alienPicture.gif")
alienImage.draw(windowFive)

#pause
time.sleep(3)

#User Instruction for the next frame's transition
message = "This frame is over, please click anywhere on the frame to exit."
nextFrameTransition = Text(Point(300, 480), message)
nextFrameTransition.setTextColor("white")
nextFrameTransition.setSize(11)
nextFrameTransition.setFace("helvetica")
nextFrameTransition.draw(windowFive)


windowFive.getMouse() #user clicks anywhere on the frame with the mouse to close and restart the story 
windowFive.close() #the last frame closes




