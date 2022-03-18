- 👋 Hi, I’m @Alimo-ras
- 👀 I’m interested in Django, Vue, Quasar
- 🌱 I’m currently learning Django, Vue, Quasar
- 💞️ I’m looking to collaborate on projects that use Django, Vue, Quasar
- 📫 You can reach me  <a href="mailto:someone@example.com">Send email</a> 


<!DOCTYPE html>
<html>
<style>
    #myProgress {
        width: 100%;
        background-color: #ddd;
    }

    #myBar {
        width: 10%;
        height: 30px;
        background-color: #04AA6D;
        text-align: center;
        line-height: 30px;
        color: white;
    }

    .center {

        top: 50%;
        width: 100%;
        text-align: center;
        font-size: 18px;
    }
</style>

<body>

    <h1>My discrete Journey to learn and code </h1>

    <div id="myProgress">
        <div id="myBar">10%</div>

    </div>
    <h3 id=name></h3>

    <br>
    <button id="button" class="center" onclick="move()">Start</button>

    <script>
        var i = 0;
        document.getElementById("name").innerHTML =
            `<font size=4 color=blue>\
	<b>♥ Have Ideas</b>\
</font>\<br>
<b>♥ like computers</b>\
<br>
<font size=4 color=green>\
<b>♥ like apps and Coding</b>\</font>
<br>	<p> &#9661 Start Learnig &#9661   </p>`
            ;

        function move() {
            console.log(i)
            if (i == 0) {
                i = 1;
                var elem = document.getElementById("myBar");
                var width = 10;
                var id = setInterval(frame, 40);

                function frame() {
                    if (width >= 100) {
                        clearInterval(id);
                        i = 0;
                    } else if (width <= 20) {
                        width++;
                        elem.style.width = width + "%";
                        elem.innerHTML = width + "%";
                        if (width >= 14) {

                            var name = 'ali';
                            document.getElementById("name").innerHTML = `
                                <h3>Starting to learn </h3>
                             <font size=4 color=green>\
                                    <b>♣ I tried to learn django with:</b>\
                                </font>\<br>
                                <font size=4 >\
                                    <ul>♦ <a style="color: black" target="_blank"  href="https://www.youtube.com/watch?v=qgGIqRFvFFk&list=PL6gx4Cwl9DGBlmzzFcLgDhKTTfNLfX1IK">thenewboston youtube channel</a></ul>
                                    
                                </font>
                                <font size=4 >\<ul>♦ Book: django-beginners-learn-web-development-2-1 </ul></font>
                                <font size=4 color=blue>\
                                    <b>♣ Familiarize with HTML, CSS, Javascripts through:</b>\
                                </font>\<br>
                                <font size=4 >\
                                    <ul>♦ Mainly <a style="color: black" target="_blank"  href="https://www.w3schools.com/">W3Schools.com!</a></ul>
                                    
                                </font>`
                                ;
                            document.getElementById("button").innerHTML = "Go on"

                            i = 2;

                        }

                    }
                }
            } else if (i == 2) {

                var elem = document.getElementById("myBar");
                var width = 21;
                var id = setInterval(frame, 40);

                function frame() {
                    if (width >= 100) {
                        clearInterval(id);
                        i = 0;
                    } else if (width <= 40) {
                        width++;
                        elem.style.width = width + "%";
                        elem.innerHTML = width + "%";
                        if (width >= 25) {

                            var name = 'ali';
                            document.getElementById("name").innerHTML = `
                                <h3>Starting to learn </h3>
                             <font size=4 color=green>\
                                    <b>♣ I tried to learn django withsdfsdf:</b>\
                                </font>\<br>
                                <font size=4 >\
                                    <ul>♦ <a style="color: black" target="_blank"  href="https://www.youtube.com/watch?v=qgGIqRFvFFk&list=PL6gx4Cwl9DGBlmzzFcLgDhKTTfNLfX1IK">thenewboston youtube channel</a></ul>
                                    
                                </font>
                                <font size=4 >\<ul>♦ Book: django-beginners-learn-web-development-2-1 </ul></font>
                                <font size=4 color=blue>\
                                    <b>♣ Familiarize with HTML, CSS, Javascripts through:</b>\
                                </font>\<br>
                                <font size=4 >\
                                    <ul>♦ Mainly <a style="color: black" target="_blank"  href="https://www.w3schools.com/">W3Schools.com!</a></ul>
                                    
                                </font>`
                                ;
                            document.getElementById("button").innerHTML = "Go on"

                        }

                    }
                }
            }
        }
    </script>

</body>

</html>



<!---
Alimo-ras/Alimo-ras is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
