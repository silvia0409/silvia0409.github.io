<!DOCTYPE html>
<!-- saved from url=(0035)https://binta-tech.github.io/corgi/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <link rel="stylesheet" href="./front page_files/styles.css">
        
    </head> 
    <body>
        <div class="container">
            <div>
                <h1 class="header_text">Would you be my Valentine Mackenzie &lt;3?</h1>
            </div>
            <div class="gif_container">
                <img src="./front page_files/giphy.gif" alt="Cute animated illustration">
            </div>
            <div class="buttons">
                <button class="btn" id="yesButton" onclick="nextPage()">YES!!</button>
                <button class="btn" id="noButton" onmouseover="moveButton()" style="left: 549.824px; top: 133.776px;">No, I'm a bum</button>
                <script>
                    function nextPage() {
                        window.location.href = "yes.html";
                    }
                    
                    function moveButton() {
                        var x = Math.random() * (window.innerWidth - document.getElementById('noButton').offsetWidth);
                        var y = Math.random() * (window.innerHeight - document.getElementById('noButton').offsetHeight);
                        document.getElementById('noButton').style.left = `${x}px`;
                        document.getElementById('noButton').style.top = `${y}px`;
                    }
                </script> 
            </div>
        </div>
       
     
</body></html>
