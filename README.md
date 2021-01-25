# frontend-code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
.smart-green {
    margin-left: auto;
    margin-right: auto;

    max-width: 500px;
    background: #F8F8F8;
    padding: 30px 30px 20px 30px;
    font: 12px Arial,  Helvetica, sans-serif ;
    color: #666666;
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;    
}
.smart-green h1{
    font: 24px "Trebuchet MS", Arial, helvetica, sans-serif;
    padding: 20px 0px 20px 40px;
    display:block ;
    margin: -30px -30px 10px -30px ;
    color: #FFF;
    background: #9DC45F ;
    text-shadow: 1px 1px 1px #949494 ;
    border-radius:5px 5px 0px 0px ;
    -webkit-border-radius: 5px 5px 0px 0px;
    -moz-border-radius:5px 5px 0px 0px ;
    border-bottom: 1px solid #89AF4C ; 
}
.smart-green h1>span{
    display: block;
    font-size: 11px ;
    color: #FFF;
}

.smart-green label{
    display: block;
    margin: 0px 0px 5px;
}
.smart-green label>span{
    float: left;
    margin-top: 10px;
    color: #5E5E5E;
}
.smart-green input[type="text"], .smart-green input[type="email"], .smart-green textarea, .smart-greens select{
    color: #555 ;
    height: 30px;
    line-height:15px;
    width: 100%;
    padding:0px 0px 0px 10px;
    margin-top: 2px;
    border:1px solid #E5E5E5;
    background: #FBFBFB;
    outline: 0;
    -webkit-box-shadow: inset 1px 1px 2px rgba(238, 238, 238, 0.2);
    box-shadow: inset 1px 1px 2px rgba(238, 238, 238, 0.2);
    font: normal 14px/14px Arial, Helvetica, sans-serif;
}
.smart-green textarea{
    height: 100px;
    padding-top: 10px;
}
.smart-green select{
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    text-indent: 0.01px;
    text-overflow: '';
    width:100%;
    height:30px;
}
.smart-green .button{
    background-color: #9DC45F;
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-border-radius: 5px;
    border: none;
    padding: 10px 25px 10px 25px;
    color: #FFF;
    text-shadow: 1px 1px 1px #80A24A;
}
.smart-green .button:hover{
    background-color: #80A24A;
}
    </style>
</head>
<body>

    <form action="" method="post" class="smart-green">
        <h1>Contact Form
            <span>Please fill all the texts in the fields.</span>
        </h1>
        <label>
            <span>Your Name :</span>
            <input id="name" type="text" name="name" placeholder="Your Full Name" />  
        </label>
        
        <label>
            <span>Your Name :</span>
            <input id="email" type="email" name="email" placeholder="Valid Email Address" />  
        </label>
        <label>
            <span>Message :</span>
            <textarea id="message" name="message" placeholder="Your Message to us"></textarea>
        </label>
        <label>
            <span>Subject :</span><select name="selection">
            <option value="Job Inquiry">Job Inquiry</option>
            <option value="Genral Question">Genral Question</option>
            </select>
        </label>
        <label>
            <span> </span>
            <input type="button" class="button" value="send" />
        </label>
    </form>
</body>
</html>
