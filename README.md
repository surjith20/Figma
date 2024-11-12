# Ex09 Event Registration Web Application
## Date:12:11:2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
/* Home Page */

position: relative;
width: 360px;
height: 640px;

background: linear-gradient(0deg, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0.2)), #FFFFFF;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);


/* Affiliated to Anna University */

position: absolute;
width: 321px;
height: 34px;
left: calc(50% - 321px/2 + 0.5px);
top: calc(50% - 34px/2 - 66px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B3F0A;

mix-blend-mode: normal;


/* NIRF Ranked Autonomous Institiution */

position: absolute;
width: 228px;
height: 48px;
left: calc(50% - 228px/2);
top: calc(50% - 48px/2 + 5px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #2B3F0A;

mix-blend-mode: normal;


/* Line 1 */

position: absolute;
width: 360px;
height: 0px;
left: 0px;
top: 67px;

border: 4px solid #0090CF;


/* Saveetha Logo 1 */

box-sizing: border-box;

position: absolute;
width: 95px;
height: 87px;
left: calc(50% - 95px/2 + 0.5px);
top: calc(50% - 87px/2 - 174.5px);

background: url(Saveetha Logo.png);


/* Rectangle 1 */

position: absolute;
width: 148px;
height: 35px;
left: calc(50% - 148px/2);
top: calc(50% - 35px/2 + 122.5px);

background: rgba(32, 63, 152, 0.83);


/* LOGIN */

position: absolute;
width: 125px;
height: 20px;
left: calc(50% - 125px/2 + 0.5px);
top: calc(50% - 20px/2 + 120px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #000000;



/* image 1 */

position: absolute;
width: 321px;
height: 48.28px;
left: 20px;
top: 8px;

background: url(image.png);


/* © Since 2001 */

position: absolute;
width: 136px;
height: 14px;
left: 113px;
top: 619px;

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 17px;
text-align: center;

color: rgba(0, 0, 0, 0.59);

/* Login Page */

position: relative;
width: 360px;
height: 640px;

background: #FFFFFF;


/* Line 2 */

position: absolute;
width: 360px;
height: 0px;
left: 1px;
top: 68px;

border: 4px solid #279DD9;


/* Saveetha Logo 2 */

position: absolute;
width: 95px;
height: 87px;
left: calc(50% - 95px/2 - 0.5px);
top: calc(50% - 87px/2 - 173.5px);

background: url(Saveetha Logo.png);


/* Username */

position: absolute;
width: 123px;
height: 25px;
left: 14px;
top: 258px;

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #B412B8;



/* Password */

position: absolute;
width: 123px;
height: 25px;
left: 14px;
top: 318px;

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #B412B8;



/* Rectangle 2 */

position: absolute;
width: 187px;
height: 30px;
left: 154px;
top: 258px;

background: rgba(32, 63, 152, 0.83);


/* Rectangle 3 */

position: absolute;
width: 187px;
height: 30px;
left: 154px;
top: 312px;

background: rgba(32, 63, 152, 0.83);


/* Rectangle 3 */

position: absolute;
width: 148px;
height: 35px;
left: calc(50% - 148px/2 + 1px);
top: calc(50% - 35px/2 + 117.5px);

background: #D9D9D9;


/* Rectangle 4 */

position: absolute;
width: 148px;
height: 35px;
left: calc(50% - 148px/2 + 1px);
top: calc(50% - 35px/2 + 117.5px);

background: rgba(32, 63, 152, 0.83);


/* LOGIN */

position: absolute;
width: 125px;
height: 20px;
left: calc(50% - 125px/2 + 1.5px);
top: calc(50% - 20px/2 + 115px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #000000;



/* image 2 */

position: absolute;
width: 321px;
height: 48.28px;
left: 19px;
top: 10px;

background: url(image.png);


/* © Since 2001 */

position: absolute;
width: 136px;
height: 14px;
left: 114px;
top: 617px;

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 17px;
text-align: center;

color: rgba(0, 0, 0, 0.59);

/* SEC Page */

position: relative;
width: 360px;
height: 640px;

background: #FFFFFF;


/* Line 3 */

position: absolute;
width: 360px;
height: 0px;
left: calc(50% - 360px/2);
top: calc(50% - 0px/2 - 252px);

border: 4px solid #0196D4;


/* Saveetha Logo 3 */

position: absolute;
width: 95px;
height: 87px;
left: calc(50% - 95px/2 - 1.5px);
top: calc(50% - 87px/2 - 173.5px);

background: url(Saveetha Logo.png);


/* Rectangle 5 */

position: absolute;
width: 218px;
height: 52px;
left: calc(50% - 218px/2);
top: calc(50% - 52px/2 - 53px);

background: rgba(32, 63, 152, 0.83);


/* Timetable */

position: absolute;
width: 203px;
height: 24px;
left: calc(50% - 203px/2 - 1.5px);
top: calc(50% - 24px/2 - 53px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
/* identical to box height */
text-align: center;

color: #000000;



/* Monday */

position: absolute;
width: 127px;
height: 25px;
left: calc(50% - 127px/2 + 0.5px);
top: calc(50% - 25px/2 + 12.5px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* Tuesdaty */

position: absolute;
width: 98px;
height: 26px;
right: 130px;
top: calc(50% - 26px/2 + 50px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* Wednesday */

position: absolute;
width: 198px;
height: 25px;
left: calc(50% - 198px/2 + 1px);
top: calc(50% - 25px/2 + 87.5px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* Thursday */

position: absolute;
width: 212px;
height: 27px;
left: calc(50% - 212px/2);
top: calc(50% - 27px/2 + 125.5px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* Friday */

position: absolute;
width: 119px;
height: 25px;
left: calc(50% - 119px/2 + 0.5px);
top: calc(50% - 25px/2 + 163.5px);

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #62260C;



/* image 2 */

position: absolute;
width: 321px;
height: 48.28px;
left: 20px;
top: 8px;

background: url(image.png);


/* © Since 2001 */

position: absolute;
width: 136px;
height: 14px;
left: 113px;
top: 612px;

font-family: 'Luxurious Roman';
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 17px;
text-align: center;

color: rgba(0, 0, 0, 0.59);


```

## OUTPUT:
![image](https://github.com/user-attachments/assets/0fdac160-53d0-4c61-9538-cb6ff3e82867)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
