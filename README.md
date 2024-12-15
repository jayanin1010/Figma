# Ex09 Event Registration Web Application
# Date:25/11/24
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

# HOME PAGE

    <div class="i-phone-14-plus-1">
    <img class="sec-logo-01-as-1" src="sec-logo-01-as-10.png" />
    <div class="rectangle-1"></div>
    <div class="login">LOGIN</div>
    <div class="rectangle-2"></div>
    <img class="images-1" src="images-10.png" />
    <div class="register">REGISTER</div>
    </div>


    .i-phone-14-plus-1,
    .i-phone-14-plus-1 * {
    box-sizing: border-box;
    }
    .i-phone-14-plus-1 {
    background: #75fff4;
    height: 926px;
    position: relative;
    overflow: hidden;
    }
    .sec-logo-01-as-1 {
    width: 399px;
    height: 83px;
    position: absolute;
    left: 18px;
    top: 10px;
    object-fit: cover;
    }
    .rectangle-1 {
    background: #f6f02a;
    width: 203px;
    height: 56px;
    position: absolute;
    left: 112px;
    top: 707px;
    }
    .login {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 727px;
    width: 141px;
    height: 36px;
    }
    .rectangle-2 {
    background: #f6f02a;
    width: 203px;
    height: 56px;
    position: absolute;
    left: 112px;
    top: 594px;
    }
    .images-1 {
    width: 224px;
    height: 224px;
    position: absolute;
    left: 102px;
    top: 264px;
    object-fit: cover;
    }
    .register {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 613px;
    width: 141px;
    height: 37px;
    }


# EVENTS PAGE


    <div class="i-phone-14-plus-2">
    <div class="sports-day-events">SPORTS DAY EVENTS</div>
    <div class="rectangle-3"></div>
    <div class="cricket">CRICKET</div>
    <div class="rectangle-4"></div>
    <div class="rectangle-6"></div>
    <div class="rectangle-7"></div>
    <div class="rectangle-5"></div>
    <div class="badminton">BADMINTON</div>
    <div class="volleyball">VOLLEYBALL</div>
    <div class="_100-m">100M</div>
    <div class="_200-m">200M</div>
    </div>


    .i-phone-14-plus-2,
    .i-phone-14-plus-2 * {
    box-sizing: border-box;
    }
    .i-phone-14-plus-2 {
    background: rgba(255, 117, 161, 0.37);
    border-style: solid;
    border-color: #000000;
    border-width: 1px;
    height: 926px;
    position: relative;
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
    overflow: hidden;
    }
    .sports-day-events {
    color: #4310d9;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 90px;
    top: 140px;
    width: 330px;
    height: 130px;
    }
    .rectangle-3 {
    background: #fc56ae;
    width: 250px;
    height: 60px;
    position: absolute;
    left: 89px;
    top: 285px;
    }
    .cricket {
    color: #faf3f3;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 147px;
    top: 300px;
    width: 295px;
    height: 50px;
    }
    .rectangle-4 {
    background: #fc56ae;
    width: 250px;
    height: 60px;
    position: absolute;
    left: 89px;
    top: 403px;
    }
    .rectangle-6 {
    background: #fc56ae;
    width: 250px;
    height: 60px;
    position: absolute;
    left: 90px;
    top: 640px;
    }
    .rectangle-7 {
    background: #fc56ae;
    width: 250px;
    height: 60px;
    position: absolute;
    left: 90px;
    top: 750px;
    }
    .rectangle-5 {
    background: #fc56ae;
    width: 250px;
    height: 60px;
    position: absolute;
    left: 89px;
    top: 520px;
    }
    .badminton {
    color: #faf3f3;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 130px;
    top: 420px;
    width: 295px;
    height: 50px;
    }
    .volleyball {
    color: #faf3f3;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 130px;
    top: 535px;
    width: 295px;
    height: 50px;
    }
    ._100-m {
    color: #faf3f3;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 170px;
    top: 653px;
    width: 295px;
    height: 50px;
    }
    ._200-m {
    color: #faf3f3;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 170px;
    top: 768px;
    width: 295px;
    height: 50px;
    }


# REGISTRATION FORM PAGE

    <div class="i-phone-14-plus-3">
    <div class="rectangle-1"></div>
    <div class="register">REGISTER</div>
    <div class="rectangle-8"></div>
    <div class="full-name">FULL NAME</div>
    <div class="rectangle-9"></div>
    <div class="rectangle-10"></div>
    <div class="rectangle-11"></div>
    <div class="rectangle-12"></div>
    <div class="register-no">REGISTER NO</div>
    <div class="event">EVENT</div>
    <div class="department">DEPARTMENT</div>
    <div class="gender">GENDER</div>
    <div class="registration-form">REGISTRATION FORM</div>
    </div>


    .i-phone-14-plus-3,
    .i-phone-14-plus-3 * {
    box-sizing: border-box;
    }
    .i-phone-14-plus-3 {
    background: #eba4a4;
    height: 926px;
    position: relative;
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
    overflow: hidden;
    }
    .rectangle-1 {
    background: #f6f02a;
    width: 203px;
    height: 56px;
    position: absolute;
    left: 112px;
    top: 761px;
    }
    .register {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 15px;
    font-weight: 700;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 780px;
    width: 141px;
    height: 37px;
    }
    .rectangle-8 {
    background: #d9d9d9;
    width: 285px;
    height: 46px;
    position: absolute;
    left: 72px;
    top: 189px;
    }
    .full-name {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 15px;
    font-weight: 700;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 203px;
    width: 141px;
    height: 37px;
    }
    .rectangle-9 {
    background: #d9d9d9;
    width: 285px;
    height: 46px;
    position: absolute;
    left: 72px;
    top: 281px;
    }
    .rectangle-10 {
    background: #d9d9d9;
    width: 285px;
    height: 46px;
    position: absolute;
    left: 72px;
    top: 373px;
    }
    .rectangle-11 {
    background: #d9d9d9;
    width: 285px;
    height: 46px;
    position: absolute;
    left: 71px;
    top: 557px;
    }
    .rectangle-12 {
    background: #d9d9d9;
    width: 285px;
    height: 46px;
    position: absolute;
    left: 72px;
    top: 463px;
    }
    .register-no {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 15px;
    font-weight: 700;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 476px;
    width: 141px;
    height: 37px;
    }
    .event {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 15px;
    font-weight: 700;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 571px;
    width: 141px;
    height: 37px;
    }
    .department {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 15px;
    font-weight: 700;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 385px;
    width: 141px;
    height: 37px;
    }
    .gender {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 15px;
    font-weight: 700;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 295px;
    width: 141px;
    height: 37px;
    }
    .registration-form {
    color: #faf3f3;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 85px;
    top: 76px;
    width: 295px;
    height: 50px;
    }


# CONTACT PAGE

    <div class="i-phone-14-plus-4">
    <div class="ellipse-1"></div>
    <div class="thank-you">THANK YOU!!!</div>
    <div class="contact-us">CONTACT US</div>
    <div class="ph-no-9888765342-email-sec-events-gmail-com">
        PH NO: 9888765342
        <br />
        <br />
        EMAIL: sec.events@gmail.com
    </div>
    <img class="sec-logo-01-as-2" src="sec-logo-01-as-20.png" />
    </div>


    .i-phone-14-plus-4,
    .i-phone-14-plus-4 * {
    box-sizing: border-box;
    }
    .i-phone-14-plus-4 {
    background: #eba4a4;
    height: 926px;
    position: relative;
    overflow: hidden;
    }
    .ellipse-1 {
    background: #fffd89;
    border-radius: 50%;
    width: 319px;
    height: 303px;
    position: absolute;
    left: 63px;
    top: 285px;
    }
    .thank-you {
    color: #000000;
    text-align: left;
    font-family: "Inter-Bold", sans-serif;
    font-size: 24px;
    font-weight: 700;
    position: absolute;
    left: 138px;
    top: 427px;
    width: 217px;
    height: 103px;
    }
    .contact-us {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 15px;
    font-weight: 400;
    position: absolute;
    left: calc(50% - 123px);
    top: 746px;
    width: 141px;
    height: 37px;
    }
    .ph-no-9888765342-email-sec-events-gmail-com {
    color: #fa4d53;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 20px;
    font-weight: 400;
    position: absolute;
    left: 50%;
    translate: -50%;
    top: 783px;
    width: 250px;
    height: 87px;
    }
    .sec-logo-01-as-2 {
    width: 417px;
    height: 75px;
    position: absolute;
    left: 5px;
    top: 28px;
    object-fit: cover;
    }



# OUTPUT:

![alt text](<Screenshot 2024-12-15 193854.png>)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
