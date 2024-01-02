# Ex-08-Book-Cover-Design
# AIM:
Design a book cover page using HTML and CSS.

# PROCEDUCE:
## STEP-1:
Create a new Django project and app.

## STEP-2:
Create a static file directory and mention the changes in settings.

## STEP-3:
Make a new folder templates inside your app and create a html and map them using views and url.

## STEP-4:
Write down the code for book cover using HTML and CSS.

## STEP-5:
Add images and other contents using CSS record a screenshot of it.

# PROGRAM:
```html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
    </head>
    <style>
        body{
    color:rgb(252, 254, 254);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url('https://th.bing.com/th/id/R.671f161d141466cdcf83db28cb0f3a9c?rik=chK%2bVFNfy9d5yQ&riu=http%3a%2f%2fwww.textronic.com%2fblog%2fwp-content%2fuploads%2f2017%2f10%2fJARVIS.png&ehk=ZeD47puFibIuEgnTFLJ0EvR0pvMX2F4jcL4rRn2y4EU%3d&risl=1&pid=ImgRaw&r=0');
    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f8aa03;
}
h4{
    font-size:20px;
    margin:60px;
    bottom-margin-top:10px;
    width:430px;
}
#top{
    border-bottom:2px solid #f8aa03;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f8aa03;
    padding-top:10px;
    width:726px;
}
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  .photo{
    position: relative;
    top: 140px;
    left: 560px;
    width: 50px;
    height: 50px;
    background-size: cover;
}
  #end{
    padding-right:60px;
  }
    </style>
    <body>
        <section class="book">
            <br><br>
        <span id="top">STRAK LTD &nbsp;&nbsp;&nbsp;</span>
            <h1> INTRODUCTION OF ARTIFICIAL INTELLIGENCE </h1>
            <h2>  </h2>
            <h4> Future Of Technologies</h4>
            <h3>PERMIUM EDITION</h3>
            <div class="photo">
                <img src="C:\Users\admin\Downloads\WhatsApp_Image_2023-12-17_at_5.15.25_PM-removebg-preview.png" width="130" height="145"alt="">
            </div>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>SUNIL KUMAR T</span>
                    <span id="end"><U>  2023</u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```

# OUTPUT
![Alt text](<Screenshot 2023-12-17 172226.png>)

 # RESULT

Thus the book-cover-design has been successfully created using HTML and CSS.