# Data-Analytics-and-Visualization-Case-Study
<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
    html,
    body,
    h1,
    h2,
    h3,
    h4 {
        font-family: "Lato", sans-serif
    }

    .mySlides {
        display: none
    }

    .w3-tag,
    .fa {
        cursor: pointer
    }

    .w3-tag {
        height: 15px;
        width: 15px;
        padding: 0;
        margin-top: 6px
    }
</style>

<body>

    <!-- Links (sit on top) -->
    <div class="w3-top">
        <div class="w3-row w3-large w3-light-grey">
            <div class="w3-col s3">
                <a href="#" class="w3-button w3-block">Home</a>
            </div>
            <div class="w3-col s3">
                <a href="#plans" class="w3-button w3-block">Plans</a>
            </div>
            <div class="w3-col s3">
                <a href="#about" class="w3-button w3-block">About</a>
            </div>
            <div class="w3-col s3">
                <a href="#contact" class="w3-button w3-block">Contact</a>
            </div>
        </div>
    </div>

    <!-- Content -->
    <div class="w3-content" style="max-width:1100px;margin-top:80px;margin-bottom:80px">

        <div class="w3-panel">
            <h1><b>Number of new family planning acceptors by type, Malaysia, 2000 - 2017</b></h1>
            <p>Family planning benefits: Improving the quality of life of women, couples and children. Helping women plan and distance
            pregnancy for better maternal and child health. In this case tudy, we want to study on how many people practices family planning and which
        method they usually use.</p>
        </div>

        <!-- Slideshow -->
        <div class="w3-container">
            <div class='tableauPlaceholder' id='viz1644043550083' style='position: relative'><object class='tableauViz'
                    style='display:none;'>
                    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
                    <param name='embed_code_version' value='3' />
                    <param name='site_root' value='' />
                    <param name='name' value='NumberofnewfamilyplanningacceptorsbytypeMalaysia2000-2017&#47;Dashboard1' />
                    <param name='tabs' value='no' />
                    <param name='toolbar' value='yes' />
                    <param name='animate_transition' value='yes' />
                    <param name='display_static_image' value='yes' />
                    <param name='display_spinner' value='yes' />
                    <param name='display_overlay' value='yes' />
                    <param name='display_count' value='yes' />
                    <param name='language' value='en-US' />
                </object></div>
            <script type='text/javascript'>                
             var divElement = document.getElementById('viz1644043550083'); 
             var vizElement = divElement.getElementsByTagName('object')[0];
              if (divElement.offsetWidth > 800) { 
                  vizElement.style.width = '1250px'; 
                  vizElement.style.height = '887px'; } 
              else if (
                  divElement.offsetWidth > 500) { 
                  vizElement.style.width = '1250px'; 
                  vizElement.style.height = '887px'; }
              else { 
                  vizElement.style.width = '100%'; 
                  vizElement.style.height = '1227px'; } 
            var scriptElement = document.createElement('script'); 
            scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
            vizElement.parentNode.insertBefore(scriptElement, vizElement);              
                  </script>
        </div>

        <!-- Grid -->
        <div class="w3-row w3-container">
            <div class="w3-center w3-padding-64">
                <span class="w3-xlarge w3-bottombar w3-border-dark-grey w3-padding-16">General View of Methods Preference</span>
            </div>
            <div class="w3-panel">
                <p>Looking at the trend in Methods Preferences show in Bubble Graph above. We can see that pills are highly demand 
                    for family planning followed by Injection and Condoms. We can see the usage of pills always high with average of 50000
                    to 60000. The trend for pills are increasing but a bit flop in 2011 and 2012. Followed up by injection, the demand are 
                    constantly increasing year by year until 2011 where there are drastically increase of demand towards injection.
                    From the charts, we can see that couples are more comfortable with pills due to it is easy to use compared to condoms.
                    Eventhough, pills come with the side effects, the user seems aware and able to bear the consequences. There also a proof that
                    pills are more effective compared to condoms. 
                </p>
            </div>
            <div class="w3-col l3 m6 w3-light-grey w3-container w3-padding-16">
                <h3>Pill</h3>
                <p>From the graph, we can see that a lot of family or couples in Malaysia more using pills with total of 967428 users since 2000-2017. </p>
            </div>

            <div class="w3-col l3 m6 w3-grey w3-container w3-padding-16">
                <h3>Injection</h3>
                <p>From the graph, we can see that injection is second high choice for family or couples in Malaysia with total of 273808 users since
                2000-2017.</p>
            </div>

            <div class="w3-col l3 m6 w3-dark-grey w3-container w3-padding-16">
                <h3>Condoms</h3>
                <p>From the graph, Condoms is third high choice for family or couples in Malaysia with total of 157885 users since
                2000-2017.</p>
            </div>

            <div class="w3-col l3 m6 w3-black w3-container w3-padding-16">
                <h3>Intra Uterine Device</h3>
                <p>Intra Uterine Device is the forth methods with total of count 52198 since 2000-2017.</p>
            </div>
        </div>

        <!-- Grid -->
      

        <!-- Grid -->
        

        <!-- Contact -->
        <div class="w3-center w3-padding-64" id="contact">
            <span class="w3-xlarge w3-bottombar w3-border-dark-grey w3-padding-16">Contact Us</span>
        </div>

        <form class="w3-container" action="/action_page.php" target="_blank">
            <div class="w3-section">
                <label>Name</label>
                <input class="w3-input w3-border w3-hover-border-black" style="width:100%;" type="text" name="Name"
                    required>
            </div>
            <div class="w3-section">
                <label>Email</label>
                <input class="w3-input w3-border w3-hover-border-black" style="width:100%;" type="text" name="Email"
                    required>
            </div>
            <div class="w3-section">
                <label>Subject</label>
                <input class="w3-input w3-border w3-hover-border-black" style="width:100%;" name="Subject" required>
            </div>
            <div class="w3-section">
                <label>Message</label>
                <input class="w3-input w3-border w3-hover-border-black" style="width:100%;" name="Message" required>
            </div>
            <button type="submit" class="w3-button w3-block w3-black">Send</button>
        </form>

    </div>

    <!-- Footer -->

    <footer class="w3-container w3-padding-32 w3-light-grey w3-center">
        <h4>Footer</h4>
        <a href="#" class="w3-button w3-black w3-margin"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
        <div class="w3-xlarge w3-section">
            <i class="fa fa-facebook-official w3-hover-opacity"></i>
            <i class="fa fa-instagram w3-hover-opacity"></i>
            <i class="fa fa-snapchat w3-hover-opacity"></i>
            <i class="fa fa-pinterest-p w3-hover-opacity"></i>
            <i class="fa fa-twitter w3-hover-opacity"></i>
            <i class="fa fa-linkedin w3-hover-opacity"></i>
        </div>
        <p>Powered by <a href="http://khaidirkhaizuki.blogspot.com/" title="Khaidir Khaizuki" target="_blank"
                class="w3-hover-text-green">Khaidir Khaizuki</a></p>
    </footer>


    <script>
        // Slideshow
        var slideIndex = 1;
        showDivs(slideIndex);

        function plusDivs(n) {
            showDivs(slideIndex += n);
        }

        function currentDiv(n) {
            showDivs(slideIndex = n);
        }

        function showDivs(n) {
            var i;
            var x = document.getElementsByClassName("mySlides");
            var dots = document.getElementsByClassName("demodots");
            if (n > x.length) { slideIndex = 1 }
            if (n < 1) { slideIndex = x.length };
            for (i = 0; i < x.length; i++) {
                x[i].style.display = "none";
            }
            for (i = 0; i < dots.length; i++) {
                dots[i].className = dots[i].className.replace(" w3-white", "");
            }
            x[slideIndex - 1].style.display = "block";
            dots[slideIndex - 1].className += " w3-white";
        }
    </script>

</body>

</html>
