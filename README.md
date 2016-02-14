Huai Chun Shih 					(Sitting in) BU-ID:U28471189

#1.An overall description
This poject detects hands and how many fingers there.

step1.Find contours by skin color first, and than select contours that has big area.
step2.Find convex and defects by the function: convexityDefects(contours[i], hullsI[i], defects[i]) 
step3.Select the defects having proper depths to put rectangle.
step4.Indicates the unmber of fingers by valid_defects_number +1.

#2.How the graphics respond to different hand shapes and/or gestures
it shows the text and a rectangle to indicate the hands on screen.

#3.Interesting and fun aspects of the graphics display
All of them are fun.
It is hard to distinguish hands, faces and white-yellow background.
When hands contacts a face, it is hard to distinguish too.
I may need one more week.