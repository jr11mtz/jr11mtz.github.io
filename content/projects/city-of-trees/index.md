+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    
    title = "City of Trees"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-21T10:51:18-07:00 #the date the file was created

    
    shortDescription = "City of Trees Artists Interview Photographs"
    projectVideo = ""
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = ""
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "cot3.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++
<div class="row"> 
  <div class="column">
  <img src="cot4.jpg" style="width:100%">
  <img src="cot1.jpg" style="width:100%">
</div>
 
  <div class="column">
  <img src="cot2.jpg" style="width:100%">
  <img src="cot5.jpg" style="width:100%">
</div>

<div class="column">
  <img src="cot3.jpg" style="width:100%">
  <img src="cot6.jpg" style="width:100%">
</div>
</div>

 <h3>About:</h3>

<div class="titleline">
<hr>
</div>

 <div class="paragraph">
    <p>City of Trees is a music festival based in Sacramento, CA presented by the radio station, Alt 94.7. During the festival, I served as a photographer for various artists including Bastille, Odesza, Chvrches, and more. I captured moments from their interview with on-air talents, and shot the meet and greet photos with the artists and the listeners after their interview.</p>
</div>
