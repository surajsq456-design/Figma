# Ex08 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="homepage">
        <div class="rectangle"></div>
        <img class="img" src="img/rectangle-2.svg" />
        <img class="element-tvtdkkfk-sm" src="img/1600w-tvtdkkfk-sm-1.png" />
        <div class="text-wrapper">REGISTER</div>
        <div class="DETAILS">&nbsp;&nbsp; DETAILS</div>
        <img class="screenshot" src="img/screenshot-2025-12-28-212124-1.png" />
      </div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.frame {
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  display: flex;
}

.frame .homepage {
  width: 393px;
  height: 852px;
  position: relative;
  background-color: #ffbaba;
}

.frame .rectangle {
  position: absolute;
  top: 579px;
  left: 69px;
  width: 270px;
  height: 74px;
  background-color: #ad5300;
  box-shadow: inset 20px 20px 20px #00000040;
}

.frame .img {
  position: absolute;
  top: 704px;
  left: 65px;
  width: 278px;
  height: 81px;
}

.frame .element-tvtdkkfk-sm {
  position: absolute;
  top: 222px;
  left: 82px;
  width: 250px;
  height: 250px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 592px;
  left: 109px;
  width: 230px;
  font-family: "Joti One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .DETAILS {
  position: absolute;
  top: 723px;
  left: 82px;
  width: 257px;
  font-family: "Joti One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .screenshot {
  position: absolute;
  top: 74px;
  left: 95px;
  width: 218px;
  height: 97px;
  aspect-ratio: 2.24;
  object-fit: cover;
}

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <p class="strong-team-spirit">
        Strong Team Spirit: They consistently showcase great teamwork and determination in competitions, as noted in
        their posts.<br /><br /><br />Hosting Sports Events: SEC serves as an Anna University Sports Coordinator for
        Zone-II, hosting events like the Zone-II Sports General Body Meeting.<br /><br /><br />National Sports Fest: The
        college organizes large-scale events like the SEC National Sports Fest (SECNSF) for various schools, fostering
        sports culture.
      </p>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffbaba;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  display: flex;
}

.android-medium .strong-team-spirit {
  margin-top: 24px;
  width: 334px;
  height: 66px;
  margin-left: 23px;
  text-shadow: 50px 30px 30px #00000040;
  -webkit-text-stroke: 1px #000000;
  font-family: "Joti One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <p class="football-is-one-of">
        <span class="text-wrapper"
          >&nbsp;&nbsp; . Football is one of the most popular and loved sports in the world. It is played between two
          teams, each trying to score goals by kicking the ball into the opponent&#39;s goalpost.<br />
          <br />&nbsp;&nbsp;&nbsp;&nbsp;. The game of football helps players stay physically fit and active. It improves
          stamina, strength, balance, and coordination. Football also teaches important values such as teamwork,
          discipline, leadership, and sportsmanship.<br /><br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </span>
        <span class="span">thankyou.........</span>
      </p>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  background-color: #ffbaba;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  display: flex;
  justify-content: center;
}

.android-medium .football-is-one-of {
  margin-top: 63.5px;
  width: 268.21px;
  height: 319.99px;
  margin-left: -44.0px;
  transform: rotate(0.22deg);
  text-shadow: 50px 30px 30px #00000040;
  font-family: "Joti One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper {
  font-family: "Joti One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
}

.android-medium .span {
  font-family: "Italianno-Regular", Helvetica;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-28 210321.png>)
![alt text](<Screenshot 2025-12-28 210308.png>)
![alt text](<Screenshot 2025-12-28 212253.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
