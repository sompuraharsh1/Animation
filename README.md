<!DOCTYPE html>
<html lang="en">
<head>

    <title>Document</title>
    <style type="text/css">
        div{
            height: 200px;
            width: 200px;
            background-color: black;
            animation: square;
            animation-duration: 10s;
            animation-iteration-count: infinite;
            position: relative;
        }

        @keyframes square {
            0%{background-color: blueviolet;left: 0px;top:0px;transform: rotate(0deg);}
            25%{background-color: brown;left: 100px;top: 100px;transform: rotate(90deg);}
            50%{background-color: rgb(28, 108, 179);left: 200px;top:200px;transform:rotate(180deg);}
            75%{background-color: chartreuse;left: 200px;top: 20px;transform: rotate(270deg);}
            100%{background-color: brown;left: 0px;top: 0px;transform: rotate(360deg);}
            
        }

    </style>
</head>
<body>
<div>

