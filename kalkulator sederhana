<html>
    <head>
       <title>Kalkulator</title>
    <style>
    .container {
    Width: 700px;
    margin: 0 auto;
    padding: 70px;
    background-color: #f2f2f2;
    border-radius: 5px;
	background: Gold
    }
    input[type="button"]{
        width: 20%;
		margin-bottom: 5px;
        padding: 10px;
        font-size: 16px;
		background: grey
	}
    input[type="text"]{
        width: 81.5%;
        padding: 10px;
        font-size: 16px;
        margin-bottom: 10px;
        text-align: right;
		background: white
    }
    </style>
    </head>
    <body>
        <div class="container">
            <input type="text" id="result" readonly>
            <input type="button" value="1" onclick="appendNumber(1)">
            <input type="button" value="2" onclick="appendNumber(2)">
            <input type="button" value="3" onclick="appendNumber(3)">
            <input type="button" value="+" onclick="appendOperator('+')">
            <input type="button" value="4" onclick="appendNumber(4)">
            <input type="button" value="5" onclick="appendNumber(5)">
            <input type="button" value="6" onclick="appendNumber(6)">
            <input type="button" value="-" onclick="appendOperator('-')">
            <input type="button" value="7" onclick="appendNumber(7)">
            <input type="button" value="8" onclick="appendNumber(8)">
            <input type="button" value="9" onclick="appendNumber(9)">
            <input type="button" value="X" onclick="appendOperator('*')">
            <input type="button" value="0" onclick="appendNumber(0)">
            <input type="button" value="," onclick="appendDecimal()">
            <input type="button" value="=" onclick="calculate()">
            <input type="button" value=":" onclick="appendOperator('/')">
            <input type="button" value="clear" onclick="clearResult()">
            <input type="button" value="Delete" onclick="deleteLastCharacter()">
        </div>

        <script>
            function
            appendNumber(number){
                document.getElementById("result").value+=number;
            }
            function
            appendOperator(operator){
                document.getElementById("result").value+=operator;
            }
            function
            appendDecimal(){
                var curentResult=document.getElementById("result").value;
                if (curentResult.indexOf(".")===-1){
                    document.getElementById("result").value+=",";
                }
            }
            function
            clearResult(){
                document.getElementById("result").value="";
            }
            function 
            calculate(){
                var result=eval(document.getElementById("result").value);
                document.getElementById("result").value=result;
            }
            function
            deleteLastCharacter(){
                var curentResult=document.getElementById("result").value;
                    document.getElementById("result").value=curentResult.slice(0,-1);
                }
            </script>


    </body>
    </html>
