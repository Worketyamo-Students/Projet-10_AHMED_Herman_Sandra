# Projet 10:




<div class="hero">
        <div class="container">
            <div class="clock">
                <span id="hrs">00</span>
                <span>:</span>
                <span id="min">00</span>
                <span>:</span>
                <span id="sec">00</span>

            </div>
        </div>
    </div>
    <script>
        var hrs = document.getElementById ("hrs");
var min = document.getElementById ("min");
var sec = document.getElementById ("sec");

setInterval(()=>{
    var currentTime = new Date();
    hrs.innerHTML = currentTime.getHours();
    min.innerHTML = currentTime.getMinutes();
    sec.innerHTML = currentTime.getSeconds();
},1000)
