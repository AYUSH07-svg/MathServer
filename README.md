# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
math.html

<!DOCTYPE html>
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Power Calculation (P = I²R)</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body {
    background-color:  #3c00ff;
}
.edge {
    width: 100%;
    padding-top: 250px;
    text-align: center;
}
.box {
    display: inline-block;
    border: thick double rgb(59, 8, 116);
    width: 500px;
    min-height: 300px;
    font-size: 20px;
    background-color: #fefbd8;
}
.formelt {
    color: black;
    text-align: center;
    margin-top: 7px;
    margin-bottom: 6px;
}
h1 {
    color: black;
    padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
    <div class="box">
        <h1>Power Calculation</h1>
        <h3>AYUSH S</h3>
        <form method="POST">
            
            <div class="formelt">
                Current (I): <input type="text" name="current" value="{{current}}"> A<br/>
            </div>
            <div class="formelt">
                Resistance (R): <input type="text" name="resistance" value="{{resistance}}"> Ω<br/>
            </div>
            <div class="formelt">
                <input type="submit" value="Calculate"><br/>
            </div>
            <div class="formelt">
                Power (P): <input type="text" name="power" value="{{power}}"> W<br/>
            </div>
        </form>
    </div>
</div>
</body>
</html>

## SERVER SIDE PROCESSING:
![SERVER SIDE PROCESSING](https://github.com/user-attachments/assets/fbb9aabe-51f9-4a72-9d53-1e0b8258aaf8)


## HOMEPAGE:
![Expt 5 Op](https://github.com/user-attachments/assets/f6927673-6a16-46c6-916f-2d91ee8aa314)


## RESULT:
The program for performing server side processing is completed successfully.
