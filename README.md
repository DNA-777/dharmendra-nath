# dharmendra-nath
html blog page 
<!DOCTYPE html>
<html>
  <head>
    <title>Walk through your first HTML page </title>
    <!-- <link rel="stylesheet" type="text/css" href="dna.css"> -->
   </head>
  <body>
    
    <img src="\online web dev\project photos\coding.png"> 

  <div><a href="blog.codingninjas.in">blog.codingninjas.in</a></div>

           <p>Coding Ninja Offical Blog</p>

    <img src="\online web dev\project photos\coding 2.png"> 

        <h1> A step-by-step walk through of your first HTML page</h1>

    <img src="\online web dev\project photos\coding 3.png"> 

      <div> 

          <p>HTML is short for HyperText Markup Language.Basically, it’s the “code” behind every webpage – even this one. If you’re just beginning to learn HTML, let us tell you that it’s a fairly easy task. HTML, without styling, can’t do anything more than setting a layout, drawing a table, or creating frames – but it is handy as it helps you structure the content correctly, which is important when you sit down to add style to your HTML.
         </p>

      </div>

      <img src="\online web dev\project photos\coding 4.jpeg" width="800"> 

      <div> 
        <p>
        However simple this might seem, it is a mighty useful tool when it comes to full-fledged web development. Various tools easily eliminate the HTML coding from your work process – but if you want to be in full control of your web-page, you’ll need to have some command over HTML.
        </p> 

        <p>
        Through this article, we aim to give you the essential HTML building blocks that’ll help you get up and running. Reading this, you’ll be able to understand an HTML source code and even modify it for your own good!
        </p>
      </div>

        <h2>Step One - TAGS</h2>

      <img src="\online web dev\project photos\coding 5.png" width="700"> 

       <div>
        Tags are what you’ll see the most when you look at any HTML source code. A tag can ideally be seen as a wrapper to any item on your HTML document. Tags tell what magic is to be done on the content enclosed by them.
        <br>
        <br>

      <ol type=""> Let’s look at two types of tags:
        <br>

      <li>  &lt;tag-example-1&gt;I need a closign tag&lt;tag-example-1&gt;</li>
      <li> &lt;tag-example-2/&gt;I don't need a cloding tag.</li>

      </ol>
    

       <p> In the first example, the sentence is wrapped by two tags. The first one is called the opening tag and the second one is called the closing tag. Everything in between is affected by the properties of the tag. Very commonly used examples of such tags are <html>, <head>, <body>, &lt;strong&gt;, etc.

       </p>

       <p>
        The second example tags about loner tags – as in, they don’t need a closing tag to function. Although it’s not required, these type of tags are often written as <tag/> to make the debugging of code easier. Common examples of such tags are &lt;hr/&gt; – used for horizontal line, &lt;br/&gt; – to break the line, etc.</p>
      </div>


     <div>  
      <h2>Step Two – HTML, HEAD, and BODY: The three pillars of your document<h2> 
     </div>

      <img src="C:\online web dev\project photos\coding 6.jpg" width="770"> 

       <div>
        <p>
       
       <ul> These tags are essential for any HTML document. They parcel out the significant parts of your HTML code.
        <br>
        <br>

        <li>&lt;BODY&gt; &lt;/BODY&gt; is placed below your &lt;HEAD&gt; tag, and everything that you want to be displayed on your screen comes under this tag. Text, images, links, and pretty much anything you can see in your browser live inside this tag.</li>
       
       <li> &lt;HTML&gt; &lt;/HTML&gt; wraps your entire code. Everything else in your HTML document needs to come inside these tags.</li>
       
       <li>
        &lt;HEAD&gt; &lt;/HEAD&gt; includes things like title, styles, and scripts. Head is usually present at the top (hah!), just inside the &lt;/HTML&gt; tag.</li>
      </ul>
      </p>
      </div>

       <div>
        <h2> Step three – A few tags that’ll make your page pretty</h2>
      </div>

       <p> Now that you know how to set up the skeleton of your document, let’s proceed with the things that will go inside your &lt;BODY&gt; tag and do some magic!</p>

       <ul> Some basic text formatting tags:
        
        <br>

        <li> &lt;b&gt; &lt;/b&gt; makes your text look <b>bold</b></li>
        <li> &lt;i&gt; &lt;/i/&gt;> makes you write in <i>cursive</i></li>
        <li>&lt;u&gt; &lt;/u&gt;<u> underlines</u> what you just wrote</li>
      
       <br>
             For example, this piece of code
        </ul>

        <hr>

      <div>

<code>
        &lt;html&gt;
        <br>
        <br>

         &nbsp; &lt;head&gt; &lt;/head&gt;
          <br>
          <br>

        &nbsp;  &lt;body&gt;
          <br>
          <br>

        &nbsp;&nbsp;    &lt;i&gt; I am italics!  &lt;/i&gt;  &lt;br/&gt;
            <br>
       &nbsp;&nbsp;    &lt;b&gt; I am bold!  &lt;/b&gt;  &lt;br/&gt;
            <br>
        &nbsp;&nbsp;   &lt;u&gt;And me, well, I'm underlined!  &lt;/u&gt; &lt;br/&gt; 
            <br>
            <br>

       &nbsp;  &lt;/body&gt;
          <br>
          <br>

        &lt;/html&gt;
      </code>


</div>
        <hr>


       <div> 

        Should produce something like this on your browser: Don’t fret too much about the &lt;br/&gt;. It’s just for breaking the line so that you can start from the next line. Enter key does little when it comes to changing lines in your HTML document.

      </div>
      <br>

    <div>    
      <img src="C:\online web dev\project photos\coding 7.png" width="870">
    </div>
     

     <ul>  <b>Tags to help you structure your content:</b>
      <br>

        <li> &lt;br/&gt; breaks the line, making you continue to the next line</li>
        <li> &lt;p&gt; stands for paragraph. It divides your content into paragraphs</li>
</ul>

    <div>  <i>  Note: you need to use these tags as space and enter keys do very little when it comes to formatting content inside an HTML document.</i></div>

        <div>
         <h4>Heading Tags:<h4>
         </div>

        HTML provides you with six tags, from &lt;H1&gt; &lt;/H1&gt; to &lt;H6&gt; &lt;/H6&gt; to help you create different sized headers quickly.


      <img src="\online web dev\project photos\coding 8.png" width="570" > 

        <h4>Inserting an Image:</h4>

        All that’s good, but what fun without images on the webpage? Don’t worry, &lt;IMG/&gt; to the rescue! The image tag has a mandatory attribute called “source”. Basically, it tells the browser where it should look for the image. The syntax goes something like:
        <br>
        <br>

       <code><i>< img src = “path_to_your_image” /></i></code> 

       <br>
       <br>

        Furthermore, it also has attributes like height and width that let you specify the height and width you want your image to take.

        <h4>Lists:</h4>

        HTML has two types of lists – ordered and unordered. Each item of your list has to be enclosed in a tag. The syntax for creating a list is fairly simple.
        <br>

       <ul> Suppose you want to create a list like: 

      <li>  Item 1</li>
      <li>  Item 2</li>
       <li> Item 3</li>

</ul>
        The following code will easily do the job for you:
        <hr>
<code>
        &lt;ul&gt;
           <br>
            &nbsp; &lt;li> Item 1 &lt;/li&gt;

           <br>
            &nbsp; &lt;li> Item 2 &lt;/li&gt;

           <br>

            &nbsp; &lt;li> Item 3 &lt;/li&gt;
           <br>
        &lt;/ul&gt;
</code>

        <hr>
         <br>
          <br>

        This, by the way, was an example of an unordered list. For an ordered list, all you need to do is replace &lt;ul&gt; with &lt;ol&gt; and &lt;/ul&gt; with &lt;/ol&gt;.
      
        <br>
       <br>
       Let’s see what the following code does: 
       <hr>
<code>
        &lt;html &gt;
        <br>
        <br>

         &nbsp; &lt; head &gt;  &lt;/head &gt;
          <br>
        <br>
 

         &nbsp; &lt;body &gt;
          <br>
        <br>
 

                 &nbsp; &nbsp;&lt;ul &gt;
              <br>
                   &nbsp;&nbsp;&nbsp;&nbsp;&lt;li &gt; I am unordered list's item 1!  &lt;/li &gt;
                <br>
                   &nbsp;&nbsp;&nbsp;&nbsp;&lt;li &gt; I am unordered list's item 2!  &lt;/li &gt;
                <br> 
                   &nbsp;&nbsp;&nbsp;&nbsp;&lt;li &gt; I am unordered list's item 3!  &lt;/li &gt;
                <br> 
                   &nbsp;&nbsp;&nbsp;&nbsp;&lt;li &gt; I am unordered list's item 4!  &lt;/li &gt;
                <br> 
                &nbsp; &nbsp;&lt;/ul &gt;
             <br>

                &nbsp; &nbsp;&lt;ol&gt;  
             <br>  
                  &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;  I am ordered list's item 1! &lt;/li&gt; 
               <br> 
                  &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt; I am ordered list's item 2! &lt;/li&gt;
               <br> 
                  &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt; I am ordered list's item 3! &lt;/li&gt; 
               <br>  
                  &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;  I am ordered list's item 4! &lt;/li&gt;
              <br>  
               
               &nbsp; &nbsp; &lt;/ol&gt;
              <br>

          &lt;/body&gt; 
          <br>
          <br>

        &lt;/html&gt; 
      </code>

     

      <hr>
      <br>
      <hr>

      <br>

      <img src="\online web dev\project photos\coding 9.png" width="700"> 



       <div> 
       All of these tags, when arranged coherently, will provide you with a simple webpage consisting of images, headings, and lists. Further, there are various tags that HTML supports, and we thoroughly recommend you to check them out and play with them!
     </div>

        <h3>In Conclusion </h3>

        <div>You now know enough to skim through and understand any part of an HTML code. We request you to go ahead and try skimming through the source code of any website (you’ll find some tags you don’t know, but that’s how you learn!). Oh, and welcome to the world of web development. With HTML under your belt, your next stop should be making your page look beautiful using CSS.<div>
          <br>
          <br>

        Let us know if you had any problems in the article, and don’t forget to have a look at a source code or two!
        -->

        <br>
        <br>

        
  </body>
</html>

