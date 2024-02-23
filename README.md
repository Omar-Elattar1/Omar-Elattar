<!DOCTYPE html>
<html>
    <head>
       <!--title is the name of the website-->
        <title>
            Omar Elattar
        </title>
        <!--meta : charset is languages of the website and descreption is to describe ur web-->
        <meta http-equiv="X-UA-Compatible" content = "IE=edge">
        <meta name = "viewport" content="width=device-width, initial-scale=1.0">
        <meta charset="8">
        <meta description="I am Omar Yasser Elattar from Egypt studies in Millenium language school " >
        <style>

        </style>
        <link rel="stylesheet" href="omar.css">
    </head>
    <body>
        <!-- 
            semantic elements
            <header>
                <main>
                    <section>
         -->
        <header>
                <h1>Omar Elattar</h1>
                   <!-- 
               images
           src = source
           alt = alternative    
            -->
            <img src="./photo.jpg" width="150px" Height="150px"alt="photo 1">
            <!-- 
                AUDIO & VIDEO
                <audio src="./     .mp3" type=audio/mpeg controls> </audio>
                <video src="./      .mp4" type=video/mp4 width=" px" height=" px" controls loop autoplay></video>
             -->
           <!--
               b = bold
               u = underline
               i = icalic
               hr = horizontal line
           -->
           <p><u>Iam</u> <b> <span style="color:brown;"> Omar Yasser Elattar</span></b> <br>
             <u>Studies</u> in <span style="color:red;"><b>M.L.S</b></span></b><br> 
             <u>works</u> in <span style="color:orange;">video montage
            </span> and <span style="color:blue"><b>photoshop</b></span> <br> 
            <u>writes</u> <span style="color: chartreuse;">Podcasts</span>
               </p>
        </header>
             <hr>
             <main>
                <section id="contact us">
                    <!-- 
                        div
                    -->
                    <body>
                       <div>
                       <h4>Contact me</h4>
                          <!-- 
                        FORM
                        <form>
                        </form>
                     -->
                     <form action = "https://formsubmit.co/omarelattar308@gmail.com" method = post>
                        <div id = name></div>
                        <input type = text placeholder = Name required>
                        <br><br>
                        <div id = Email></div>
                        <input type = text placeholder = Email required>
                        <br><br>
                        <div id = password></div>
                        <input type = password placeholder = Password required>
                       <br><br>
                       <div id = message></div>
                        <textarea name ="Message" Cols ="30" rows = "10" placeholder="Message" ></textarea>
                        <br>  
                        <body>
                         <p>
                          <h4>
                            Gendre
                          </h4>
                          </p>
                        </body>  
                        <br>
                        <input type = radio name = gendre>
                        <label>Male</label>
                        <br><br>
                        <input type = radio name = gendre >
                        <label>Female</label>
                        <br><br>
                        <body>
                            <body>
                                <p>
                                    <h4>Country</h4>
                                </p>
                            </body>
                        <select>
                          <option value = "1" selected >Egypt</option>
                          <option value = "1">Qutar</option>
                          <option value = "1">Suadi Arabia</option>
                          <option value = "1">Morocco</option>
                          </select>
                        <p>
                        <h4>
                            I can help you with
                        </h4>
                        </p>
                        </body>
                        <input type = checkbox name = work >
                        <label>Podcast</label>
                        <br><br>
                        <input type =checkbox name = work >
                        <label>Photo Graphic Designing </label>
                        <br><br>
                        <input type =checkbox name = work >
                        <label>Video montage</label>
                        <br><br>
                        <input type =checkbox name = work >
                        <label>Sponser</label>
                        <br><br>
                        <input type = submit >
                 </form>
                 <hr>
                       <p><b>Phone number</b> : +201027795920 
                       <br> <b>Tlegram</b> : </p>
                        <a href="https://www.facebook.com/profile.php?id=100051007188187">facebook</a>
                        <br>
                        <a href="https://www.instagram.com/invites/contact/?i=19g9l84b0qlru&utm_content=jk06eyb">Instgram</a>
                        <br>
                        <a href="https://www.tiktok.com/@o_el3attar?is_from_webapp=1&sender_device=pc">Tiktok</a>
                        <br>
                        <a href="mailto:omarelattar308@gmail.com">Gmail</a>
                       </body>
                       </div>
                    </section>
                    <hr>
                    <body>
                        <section id="About me">
                            <h3>About me</h3>
                   <!-- 
                    Lists
                    ordered lists = ol
                    *unordered lists* = ul
                    -->
                    <body>
                        <p>
                         <h4>
                            My skills
                         </h4>
                        </p>
                    </body>
                    <ul>
                        <li>programing</li>
                        <ul>
                        <li>Html</li>
                        <li>Css</li>
                        <li>python</li>
                        </ul>
                        <li>Montage</li>
                        <li>Designing</li>
                        <li>writing</li>
                        <li>studies psychology</li>
                    </ul>
                        </section>
               <!-- 
                   Table
                   Thead
                   Tbody
                   Tfoot
                   tr = table row
                   td = table data
                   border
                -->
                <table border="1" width = 30%>
                    <thead>
                        <tr>
                            <td>name</td>
                            <td>Grade</td>
                            <td>Total</td>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>
                                Omar
                            </td>
                            <td>Prep. 3</td>
                            <td>97.5%</td>
                        </tr>
                        <tr>
                            <td>Yasser</td>
                            <td>Prep. 3</td>
                            <td>-------</td>
                        </tr>
                    </tbody>
                    <tfoot>
                        <tr>
                            <td colspan="2">Total</td>
                            <td>-------</td>
                        </tr>
                    </tfoot>
                </table>
            </main>
            </body>
            <hr>
            <body>
            <footer>
                    <p>
                        all rights are preserved &copy;
                    </p>
                </body>
            </footer>
        </html>
