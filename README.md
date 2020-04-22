# Flex Box :

Dedicated to my Father Late Shri Vegi.Ramachandraprakash 
@author: vegi.Harendranath B.tech,M.tech, PHD..(CSE)
         UI Lead ,A senior softwareEngineer

Flex Box is :=>
->It is a new css3 layout Model.
->It is 1 dimensional 
-> 1 Dimensional --> Items Flow(or Flex) in one direction at a Time
-> FlexBox focuses on the sizing, Distribution and Alignment.
   of Elements inside of a 1Single Parent Element.
-> Flex Box solves some Layout Problems(Vertical Alignment,columnLayouts Etc)
   No need to use Floats,Table,Positioning or box model Hacks.
How does it work?
It Has 1 parent Element: and this Element is referred to as FlexContainer
Flex container can be any element in the HTML.

The Child Elements are called as FlexItems.
Flex Items can go N number of different Directions, they are not like 
only go either Left or Right .

It has a Main axis ,where it will  be starting from the left hand side of the Flex
container and point to the RIGHT.

As told Above it is 1 Dimensional Means it flows(or Flex) in 1 Direction only
so All the FlexItems will start from Left and pointing towards Right in FlexContainer

Left to Right -->MainAxis------>FlexItem1 FlexItem  < FlexITEM   FLEX ITEM-----------FlexContainer-------------->

MainStart---------------MainEnd
<-----------MainAxis---------->       

So Here the point where FLexItem starts Flexing(Flowing) is called MainStart
and opposite that is called MainEnd.

MainStart is at the VeryLeft of the FlexContainer and
MainEnd   is at the VeryRight of the FlexContainer.

From MainStart --> to MainEnd is total called as MainSize.

CROSSAXIS:

Perpendicular to MainAxis is the CrossAxis
CrossAxis Has CrossStart and CrossEnd.

MainStart             MainSize                   MainEnd
^======================================================^
  |   crossstart
c |  ^
R |  |
o |  |                                          MainAxis( Left to Right )
s |  |crossAxis(top to Bottom) --------------------------------------->
s |  |
i |  |
z |  |
E |  | crossEnd
========================================================

As Like  Parallel ------- Main Size same like that Perpendicular  also 
has  CrossSize







