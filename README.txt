{\rtf1\ansi\ansicpg1252\cocoartf1348\cocoasubrtf170
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red47\green102\blue178;\red255\green255\blue255;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural

\f0\fs24 \cf0 The code is in java and is run in eclipse.  To change between parts 1,2, and 3, there are two global booleans at the top of the RayTracer class.  For part 1 have justWhite = true and noAnti = true.  For part 2 have justWhite = false and noAnti = true.  For part 3 have justWhite = false and noAnti = false.\
\
The Vector class is used for vector calculations, while the Sphere class is mainly used to see if a vector intersects with the sphere.  All other calculations and drawing are done in the RayTracer class.\
\
The only libraries used was the JRE System (that should already be included with eclipse) and JOGL which was installed using following the instructions here: {\field{\*\fldinst{HYPERLINK "https://solarianprogrammer.com/2014/12/08/getting-started-jogl-java-opengl-eclipse/"}}{\fldrslt 
\f1\fs26 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 https://solarianprogrammer.com/2014/12/08/getting-started-jogl-java-opengl-eclipse/}}
\f1\fs26 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\
\cf0 The runtime for when antialiasing is on is about 10 seconds.  Otherwise it takes less than a second.\
\
The generated image should pop up in a java generated window.}