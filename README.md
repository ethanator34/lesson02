<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Selector Basics</title>
    <link
      rel="stylesheet"
      href="http://fonts.googleapis.com/css?family=Varela+Round"
    />
    <style>
      body {
        background-color: rgb(50,122,167);
        padding: 0 20px 20px 20px;/*p0-0-20-20-20*/
        margin: 0;/*m0*/
      }
      p{
        color: rgba(255,255,255,0.6);/*0.6 is for 60% opaque*/
        font-size: 1em;/*fz1em*/
        font-family: "Varela Round", Arial, Helvetica, sans-serif;
      }
      h1, h2, h3 {
        color: rgb(255,255,255);
        font-family: Arial, "Palatino Linotype", Times, serif;
        /*border-block-start: 2px solid --rgb(87,185,178);*/
        border-bottom: 2px solid rgb(87,185,178);
        padding-top: 10px;
        padding-bottom: 5px;
      }
      h1{
        font-size: 2em;
      }
      #logo{
        font-family: Baskerville, Palatino, sans-serif;
        font-size: 2em;
        color: rgba(255,255,255,0.8);
        font-style: italic;
        text-align: center;
        margin-bottom: 30px;
        background-color: rgb(191,91,116);
        border-radius: 0 0 10px 10px;/*bdrs0-0-10-10*/
        padding: 10px;
      }
      .note{
        color: #000;
        border: 2px solid #fff;
        background-color: rgb(69,189,102);
        margin-top: 25px;
        margin-bottom: 35px;
        padding: 20px;
      }
      .note strong{
        color: #fc6512;
      }
      article{
        max-width: 760px;/*maw760*/
        margin: 0 auto;
      }
      h1+p{
        color: rgb(255,255,255);
        font-size: 1.2m;
        line-height: 140%;
      }
      a[href^="/en-US/docs/Glossary/CSS"]{
        color: rgb(0,255,0);
      }
      .italics{
        font-style: italic;
      }
      .uniqueheading{
        font-style: bold, underline;
        font-size: 400%;
        color: rgb(175,255,175,0.5);
      }
    </style>
  </head>
  <body>
    <header><div id="logo">CSS: The Missing Manual</div></header>

    <article>
      <!-- The article element is intended to present an independent entry that could stand on its own. -->
      <h1>The Amazing World of CSS</h1>
      <p>
        <strong><a href="/en-US/docs/Glossary/CSS">CSS</a></strong> (Cascading
        Style Sheets) allows you to create great-looking web pages. Cascading
        Style Sheets (CSS) is a style sheet language used for describing the
        presentation of a document written in a markup language such as HTML.
        CSS is a cornerstone technology of the World Wide Web, alongside HTML
        and JavaScript.
      </p>
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
        illo inventore veritatis et quasi architecto beatae vitae dicta sunt
        explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut
        odit aut fugit, sed quia consequuntur magni dolores eos qui ratione
        voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum
        quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam
        eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat
        voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam
        corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?
        Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse
        quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo
        voluptas nulla pariatur?
      </p>
      <p class="note"> 
        <strong>NOTE:</strong> Ut enim ad minima veniam, quis nostrum
        exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea
        commodi consequatur?
      </p>

      <h2>Who Knew CSS Had Such Power?</h2>
      <p>
        Separation of formatting and content also makes it feasible to present
        the same markup page in different styles for different rendering
        methods, such as on-screen, in print, by voice (via speech-based browser
        or screen reader), and on Braille-based tactile devices. CSS also has
        rules for alternate formatting if the content is accessed on a mobile
        device.
      </p>
      <p class="note">
        <strong>NOTE:</strong> Ut enim ad minima veniam, quis nostrum
        exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea
        commodi consequatur?
      </p>

      <h3 class="uniqueheading">Not Me!</h3>
      <p>
        This assignment has helped me navigate the ins and outs of HTML and CSS a lot. 
        I am not exactly comfortable wile doing this assignment, but I have been able
        to retain at least ome information from the tutorial and I can complete the 
        assignment with no help from the internet so far. The emmet cheat sheet seems 
        to be very helpful, I might use that for future endeavors.
      </p>

      <h3 class="italics">Me Neither!</h3>
      <p>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
        illo inventore veritatis et quasi architecto beatae vitae dicta sunt
        explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut
        odit aut fugit, sed quia consequuntur magni dolores eos qui ratione
        voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum
        quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam
        eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat
        voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam
        corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?
        Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse
        quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo
        voluptas nulla pariatur?
      </p>
    </article>
  </body>
</html>
