+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Black Nursury Rhyme"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-06-03T14:39:10-07:00 #the date the file was created

    
    shortDescription = "Short film From the Poem 'The Black Nursury Rhyme'"
    projectVideo = "306454058"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "vimeo"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "nursury1.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++
<h3>About:</h3>

<div class="titleline">
<hr>
</div>

<div class="paragraph">
<p>“The Black Nursery Rhyme” is a poem written by Malissia Bordeoaux that speaks about police brutality, social injustices, discrimination and black culture. The video highlights the poem’s imagery of children nursery rhymes and is brought to life by myself and two other creatives. I served as a screen writer for the narrative, and the videographer in charge of capturing b-role of the main character and shots of children imagery.</p>
</div>