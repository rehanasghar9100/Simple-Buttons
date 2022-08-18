#Simple-Buttons
7 Buttons, 3 right and 3left, middle one will be big. All 6 buttons comes with animation after clicking middle also add onclick event to a specific link on 6 buttons.

<html>
<head>
    <script>
        function enableButton2(){
            document.getElementById("button2").disabled = false;
        }
        function enableButton3(){
        document.getElementById("button3").disabled = false;
        }
        function enableButton4(){
        document.getElementById("button4").disabled = false;
        }
        function enableButton5(){
        document.getElementById("button5").disabled = false;
        }
        function enableButton6(){
        document.getElementById("button6").disabled = false;
        }
        function enableButton7(){
        document.getElementById("button7").disabled = false;
        }
    </script>
    <style> 
  input[type=button], input[type=submit]{
  border: 2px solid #de6553;
  outline: none;
  color: #ffffff;
  padding: 16px 32px;
  text-align: center;
  box-shadow: 0 6px 20px -5px rgba(0,0,0,0.4);
  text-decoration: none;
  display: inline-block;
  font-size: 32px;
  border-radius: 40px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}
</style>
    
    
    
</head>
<body>
    <input type="button" id="button1" value="button 1" onclick="enableButton2(),enableButton3(),enableButton4(),enableButton5(),enableButton6(),enableButton7()" />
    <input type="button" id="button2" value="button 2" disabled onClick="parent.open('https://www.google.com/')" />
    <input type="button" id="button3" value="button 3" disabled onClick="parent.open('https://www.google.com/')"/>
    <input type="button" id="button4" value="button 4" disabled onClick="parent.open('https://www.google.com/')"/>
    <input type="button" id="button5" value="button 5" disabled onClick="parent.open('https://www.google.com/')"/>
    <input type="button" id="button6" value="button 6" disabled onClick="parent.open('https://www.google.com/')"/>
    <input type="button" id="button7" value="button 7" disabled
}
 onClick="parent.open('https://www.google.com/')"/>
    


</body>
</html>
