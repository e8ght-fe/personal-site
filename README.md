# Free Personal Site
So I decided to release the source to my personal sites so it can be easily edited and so people can make their own personal sites for free. I don't intend to screw over any other personal site developers with this release so if you want to buy one check out:<br>
https://ogu.gg/ruub<br>
https://ogu.gg/capo<br>
With that being said feel free to use as you please. However I don't permit use of this source to sell your own personal site development service. If you are going to make a service using these themes then you **must** credit me and be completely transparent about what your service is.

I'd also like to preface this by saying this isn't my best work, I made this original template almost a year ago now and didn't put much thought into it. I **highly** recommend putting in the time to make your own template.

# Preview

<img src="https://file.coffee/u/2O_opOMgxfh778.gif">


# Prerequisites

Basic Knowledge in HTML and CSS are heavily recommended

## Changing the Content of Your Site

### Changing the profile picture
Copy your profile picture of choice into
> --> assets<br>
> -----> imgs

Find the ``img`` tag in the <ins>index.html</ins> file and replace *pfp.jpg* with the name of your image.

### Changing the name
Replace the text in the ``h1`` tag with your name, replace it with your name and in the spans write the parts of your name you want highlighted

### Changing icons
Essentially the same process as changing profile pictures, get your icons (I get mine from icons8 or from the sites branding section), drag them into ``imgs`` folder, reference them using the ``src`` attribute in the img tags.

### Changing scrolling footer
Just change the text lol

## Changing the Styling of Your Site

### Changing the background
Go into 
> --> assets<br>
> -----> css<br>
> ---------> style.css<br>

go to the ``body`` selector and change the ``background`` rule to the hex color of your choice. 

If you'd like an image or GIF background wrap the entire site in a new div and make that div the full size of the document. Then apply the background image using CSS and make sure the ``z-index`` of that is below all of the other elements.

### Changing the font
To change the font go to the ``h1`` selector in the CSS and change the ``font-family`` rule to the font of your choice.
Make sure you have your font imported, see how to import Google fonts here:<br>
https://stackoverflow.com/questions/14676613/how-to-import-google-web-font-in-css-file<br>
and see how to import TTFs/OTFs/etc. here:<br>
https://stackoverflow.com/questions/3245141/using-otf-fonts-on-web-browsers<br>

---

That essentially sums that up, if you have any questions DM me on Discord @ offtop#5704
