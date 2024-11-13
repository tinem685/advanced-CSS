<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced CSS Demo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="parent-container">
        <div class="div static">
            <span>Position: Static</span>
        </div>
        <div class="div relative">
            <span>Position: Relative</span>
        </div>
        <div class="div sticky">
            <span>Position: Sticky</span>
        </div>
        <div class="div absolute">
            <span>Position: Absolute</span>
        </div>
        <div class="div fixed">
            <span>Position: Fixed</span>
        </div>
    </div>
</body>
</html>

<style>
.parent-container {
    position: absolute;
    width: 60vw;
    height: 200vh;
    background-color: grey;
    overflow: auto; 
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: flex-start;
    padding: 20px;
}

.div {
    width: 200px;
    height: 200px;
    margin: 10px;
    position: relative;
    transition: all 0.3s ease-in-out;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 16px;
    text-align: center;
}

.static {
    background-color: #3498db;  
}

.relative {
    background-color: #e74c3c;  
}

.sticky {
    background-color: #2ecc71;  
    position: -webkit-sticky; 
    position: sticky;
}

.absolute {
    background-color: #f39c12;  
}

.fixed {
    background-color: #9b59b6;  
    position: fixed;
    z-index: 10;
}

.div:hover {
    opacity: 0.8;
    border: 3px solid #fff;
}



{
}

.relative {
    position: relative;
    left: 20px;
}

.sticky {
    position: sticky;
    top: 50px;
    right: 0;
}

.absolute {
    position: absolute;
    left: 400px;
    top: 50px;
}

.fixed {
    position: fixed;
    right: 50px;
    bottom: 50px;
}

</style>
