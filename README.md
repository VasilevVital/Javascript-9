<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <meta http-equiv="Content-type" content="text/html;charset=UTF-8" />
    <link href="styles.css" rel="stylesheet" type="text/css" />
        <script type="text/javascript" src="teichroeb.js"></script>
                <form class="calcForm" name="calculator">
                     <input type="text" class="calcDisplay" id="display" />
                     <div class="calcRow">
                             <input type="button" class="calcButton" value="+" onclick="setOperation('add')" />
                     </div>
                     <div class="calcRow">
                             <input type="button" class="calcButton" value="four" onclick="numInput('4')" />
                             <input type="button" class="calcButton" value="five" onclick="numInput('5')" />
                             <input type="button" class="calcButton" value="six" onclick="numInput('6')" />
                             <input type="button" class="calcButton" value="-" onclick="setOperation('subtract')" />
                     </div>
                     <div class="calcRow">
                             <input type="button" class="calcButton" value="one" onclick="numInput('1')" />
                             <input type="button" class="calcButton" value="two" onclick="numInput('2')" />
                             <input type="button" class="calcButton" value="three" onclick="numInput('3')" />
                             <input type="button" class="calcButton" value="x" onclick="setOperation('multiply')" />
                     </div>
                     <div class="calcRow">
                             <input type="button" class="calcButton" value="0" onclick="numInput('0')" />
                             <input type="button" class="calcButton" value="C" onclick="clearDisplay()" />
                             <input type="button" class="calcButton" value="=" onclick="calculate()" />
                     </div>
             </form>
</head>

<body>
<p>Words into numbers</p>
</body>

</html>
