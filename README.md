# Ex09 Event Registration Web Application
## Date:20.12.2024

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
Home Page 

<div class="frame-1">
  <img
    class="screenshot-2024-12-18-104845-1"
    src="screenshot-2024-12-18-104845-10.png"
  />
  <img class="logo-1" src="logo-10.png" />
  <div class="hostel-fest-events">HOSTEL FEST EVENTS</div>
  <img class="rectangle-1" src="rectangle-10.svg" />
  <div class="frame-2">
    <div class="register">Register</div>
  </div>
  <div class="login">login</div>
</div>

.frame-1,
.frame-1 * {
  box-sizing: border-box;
}
.frame-1 {
  background: #ffffff;
  height: 521px;
  position: relative;
  overflow: hidden;
}
.screenshot-2024-12-18-104845-1 {
  width: 679px;
  height: 521px;
  position: absolute;
  left: -200px;
  top: 0px;
  object-fit: cover;
}
.logo-1 {
  width: 343px;
  height: 52px;
  position: absolute;
  left: 7px;
  top: 8px;
  object-fit: cover;
}
.hostel-fest-events {
  color: rgba(8, 250, 149, 0.99);
  text-align: left;
  font-family: "InriaSans-BoldItalic", sans-serif;
  font-size: 32px;
  font-weight: 700;
  font-style: italic;
  position: absolute;
  left: 20px;
  top: 60px;
  width: 330px;
  height: 71px;
}
.rectangle-1 {
  width: 147px;
  height: 29px;
  position: absolute;
  left: 82px;
  top: 272px;
  overflow: visible;
}
.frame-2 {
  background: rgba(209, 14, 248, 0.9);
  width: 145px;
  height: 31px;
  position: absolute;
  left: 84px;
  top: 324px;
  overflow: hidden;
}
.register {
  color: #000000;
  text-align: left;
  font-family: "AllertaStencil-Regular", sans-serif;
  font-size: 24px;
  font-weight: 400;
  position: absolute;
  left: 26px;
  top: 1px;
  width: 106px;
}
.login {
  color: #260606;
  text-align: left;
  font-family: "Alatsi-Regular", sans-serif;
  font-size: 24px;
  font-weight: 400;
  position: absolute;
  left: 124px;
  top: 269px;
  width: 67px;
  height: 31px;
}
page 2

<div class="frame-3">
  <img
    class="screenshot-2024-12-18-104756-1"
    src="screenshot-2024-12-18-104756-10.png"
  />
  <div class="frame-4">
    <div class="events">EVENTS</div>
  </div>
  <div class="frame-5">
    <div
      class="dance-solo-singing-solo-dance-fashion-walk-instruction-music-singing-dj-song"
    >
      <span>
        <span
          class="dance-solo-singing-solo-dance-fashion-walk-instruction-music-singing-dj-song-span"
        >
          DANCE
          <br />
          <br />
          SOLO SINGING
          <br />
          <br />
          SOLO DANCE
          <br />
          <br />
          FASHION WALK
          <br />
          <br />
          INSTRUCTION MUSIC
          <br />
          <br />
          SINGING
          <br />
          <br />
          DJ SONG...............
          <br />
        </span>
        <span
          class="dance-solo-singing-solo-dance-fashion-walk-instruction-music-singing-dj-song-span2"
        >
          <br />
        </span>
      </span>
    </div>
    <img class="star-1" src="star-10.svg" />
  </div>
</div>

.frame-3,
.frame-3 * {
  box-sizing: border-box;
}
.frame-3 {
  background: #ffffff;
  height: 521px;
  position: relative;
  overflow: hidden;
}
.screenshot-2024-12-18-104756-1 {
  width: 677px;
  height: 521px;
  position: absolute;
  left: -161px;
  top: 0px;
  object-fit: cover;
}
.frame-4 {
  background: #f8b19a;
  width: 120px;
  height: 32px;
  position: absolute;
  left: 17px;
  top: 14px;
  overflow: hidden;
}
.events {
  color: #000000;
  text-align: left;
  font-family: "IrishGrover-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: -3px;
}
.frame-5 {
  background: linear-gradient(to left, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)),
    linear-gradient(to left, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)),
    linear-gradient(to left, #c9cfcf, #c9cfcf);
  width: 234px;
  height: 331px;
  position: absolute;
  left: 83px;
  top: 80px;
  overflow: hidden;
}
.dance-solo-singing-solo-dance-fashion-walk-instruction-music-singing-dj-song {
  text-align: left;
  font-family: "Akronim-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
  position: absolute;
  left: 41px;
  top: 28px;
  width: 193px;
  height: 303px;
}
.dance-solo-singing-solo-dance-fashion-walk-instruction-music-singing-dj-song-span {
  color: #110117;
  font-family: "Akronim-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
.dance-solo-singing-solo-dance-fashion-walk-instruction-music-singing-dj-song-span2 {
  color: #ffffff;
  font-family: "Akronim-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
.star-1 {
  width: 48px;
  height: 18px;
  position: absolute;
  left: 0px;
  top: 10px;
  overflow: visible;
}

page 3
<div class="frame-6">
  <img
    class="screenshot-2024-12-18-104940-1"
    src="screenshot-2024-12-18-104940-10.png"
  />
  <div class="event-registeration-form">
    EVENT REGISTERATION
    <br />
    <br />
    FORM:
  </div>
  <div class="frame-14">
    <div class="frame-13"></div>
    <div class="fully-name">fully name</div>
  </div>
  <div class="frame-15">
    <div class="gender">Gender</div>
  </div>
  <div class="frame-16">
    <div class="age">Age</div>
  </div>
  <div class="frame-17">
    <div class="registration-number">Registration number</div>
  </div>
  <div class="frame-18">
    <div class="phone-number">Phone number</div>
  </div>
  <div class="frame-19">
    <div class="department">Department</div>
  </div>
  <div class="frame-20">
    <div class="email-id">Email Id</div>
  </div>
  <div class="frame-21">
    <div class="register">Register!</div>
  </div>
  <div class="frame-22">
    <div class="event-to-resiter">Event to Resiter</div>
  </div>
</div>

.frame-6,
.frame-6 * {
  box-sizing: border-box;
}
.frame-6 {
  background: #ffffff;
  width: 316px;
  height: 521px;
  position: relative;
  overflow: hidden;
}
.screenshot-2024-12-18-104940-1 {
  width: 674px;
  height: 526px;
  position: absolute;
  left: -179px;
  top: -5px;
  object-fit: cover;
}
.event-registeration-form {
  color: #ffffff;
  text-align: left;
  font-family: "IrishGrover-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
  position: absolute;
  left: 8px;
  top: 6px;
}
.frame-14 {
  background: #ffffff;
  width: 218px;
  height: 27px;
  position: absolute;
  left: 44px;
  top: 93px;
  overflow: hidden;
}
.frame-13 {
  width: 4px;
  height: 2px;
  position: absolute;
  left: 17px;
  top: 0px;
  overflow: hidden;
}
.fully-name {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 15px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: 0px;
}
.frame-15 {
  background: #ffffff;
  width: 164px;
  height: 24px;
  position: absolute;
  left: 44px;
  top: 131px;
  overflow: hidden;
}
.gender {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: 0px;
}
.frame-16 {
  background: #ffffff;
  width: 137px;
  height: 26px;
  position: absolute;
  left: 44px;
  top: 170px;
  overflow: hidden;
}
.age {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: 0px;
}
.frame-17 {
  background: #ffffff;
  width: 198px;
  height: 28px;
  position: absolute;
  left: 44px;
  top: 212px;
  overflow: hidden;
}
.registration-number {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 3px;
  top: 4px;
}
.frame-18 {
  background: #ffffff;
  width: 196px;
  height: 25px;
  position: absolute;
  left: 44px;
  top: 255px;
  overflow: hidden;
}
.phone-number {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 4px;
  top: 3px;
}
.frame-19 {
  background: #ffffff;
  width: 225px;
  height: 27px;
  position: absolute;
  left: 45px;
  top: 301px;
  overflow: hidden;
}
.department {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: 4px;
}
.frame-20 {
  background: #ffffff;
  width: 209px;
  height: 29px;
  position: absolute;
  left: 44px;
  top: 349px;
  overflow: hidden;
}
.email-id {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: 5px;
}
.frame-21 {
  background: rgba(8, 250, 149, 0.99);
  width: 119px;
  height: 27px;
  position: absolute;
  left: 187px;
  top: 456px;
  overflow: hidden;
}
.register {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 23px;
  top: 4px;
}
.frame-22 {
  background: #ffffff;
  width: 206px;
  height: 31px;
  position: absolute;
  left: 47px;
  top: 394px;
  overflow: hidden;
}
.event-to-resiter {
  color: #000000;
  text-align: left;
  font-family: "InriaSerif-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 5px;
  top: 7px;
  width: 117px;
  height: 18px;
}

<div class="frame-23">
  <img
    class="screenshot-2024-12-20-190227-1"
    src="screenshot-2024-12-20-190227-10.png"
  />
  <div class="thank-you">
    thank
    <br />
    you......
  </div>
  <div class="frame-24">
    <div class="we-all-are-eagerly-waiting-for-you-participation-in-event">
      <span>
        <span
          class="we-all-are-eagerly-waiting-for-you-participation-in-event-span"
        >
          we all are eagerly
          <br />
          waiting....
          <br />
          for you participation in Event!!
        </span>
        <span
          class="we-all-are-eagerly-waiting-for-you-participation-in-event-span2"
        >
          <br />
          <br />
        </span>
      </span>
    </div>
  </div>
  <div class="frame-25"></div>
  <div class="frame-26">
    <div class="contact-us-email-id-festevent-gmail-com-phone-no-9789007934">
      Contact us:
      <br />
      Email id:
      <br />
      Festevent@gmail.com
      <br />
      Phone no:
      <br />
      9789007934
    </div>
  </div>
</div>
.frame-23,
.frame-23 * {
  box-sizing: border-box;
}
.frame-23 {
  background: #ffffff;
  height: 503px;
  position: relative;
  overflow: hidden;
}
.screenshot-2024-12-20-190227-1 {
  width: 323px;
  height: 503px;
  position: absolute;
  left: 0px;
  top: 0px;
  object-fit: cover;
}
.thank-you {
  color: #ffffff;
  text-align: left;
  font-family: "Kablammo-Splat", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 85px;
  top: 24px;
}
.frame-24 {
  width: 228px;
  height: 128px;
  position: absolute;
  left: 31px;
  top: 133px;
  overflow: hidden;
}
.we-all-are-eagerly-waiting-for-you-participation-in-event {
  text-align: left;
  font-family: "KaushanScript-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
  position: absolute;
  left: 0px;
  top: 11px;
  width: 206px;
  height: 128px;
}
.we-all-are-eagerly-waiting-for-you-participation-in-event-span {
  color: #000000;
  font-family: "KaushanScript-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
.we-all-are-eagerly-waiting-for-you-participation-in-event-span2 {
  color: #ffffff;
  font-family: "KaushanScript-Regular", sans-serif;
  font-size: 20px;
  font-weight: 400;
}
.frame-25 {
  width: 139px;
  height: 126px;
  position: absolute;
  left: 173px;
  top: 353px;
  overflow: hidden;
}
.frame-26 {
  background: rgba(255, 255, 255, 0.38);
  width: 204px;
  height: 125px;
  position: absolute;
  left: 106px;
  top: 317px;
  overflow: hidden;
}
.contact-us-email-id-festevent-gmail-com-phone-no-9789007934 {
  color: #110117;
  text-align: left;
  font-family: "Kavoon-Regular", sans-serif;
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  left: 6px;
  top: 4px;
}
```

## OUTPUT:
![alt text](<Screenshot 2024-12-20 192515.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
