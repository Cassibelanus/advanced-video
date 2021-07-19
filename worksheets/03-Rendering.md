# Rendering

## The Deliver Panel

Rendering might seem scary at first, with all the technical information thrown at you when look at the settings. However, there are a few basic ideas that you will need to know, that from there will make understanding the panel and rendering better.

### What is Rendering?
Rendering video (different to rendering 3D Graphics) is the process of encoding images or frames into a single file (MP4, MOV) or multiple files ([Digital Cinema Package (DCP)](../extras/glossary.md)) to be played as a singular film.

---

### Render Settings
Here are the key, basic settings you will need to do some rendering. We will guide you through rendering your trailer anyway, so do not worry if you don't quite understand all of this yet! It is a lot to take in.

Setting | Description
------- | -------
Single Clip | Render the whole timeline or the specific 'In & Out Range'
Individual Clips | Render each clip as a separate file in the timeline

#### Video
Setting | Description
------- | -------
Export Video (Checkbox) | You can only export Audio if unchecked.
Format | How the final video is presented or encoded for viewing (e.g. MP4, MOV, AVI)
Codec | The encoding process. (How it takes the timeline and makes it into a MP4 file, for instance - with magic!).
--- | ---
Resolution | The scale of your image and the number of pixels fitted into the image. (e.g. 1920x1080, has 1,920 pixels across, horizontally and 1,080 pixels going vertically. Multiply them together, you get the total number of pixels in an image). In 1080p the 'p' stands for the way the image is presented on screen; 'p' means 'progressive scan', where the lines of pixels appear on screen in sequential order, contrast to 1080i where the 'i' means it is 'interlaced', where only the odd number lines of pixels appear in sequence and then the even numbers, to get the full image. Don't worry if you don't quite understand all of this, you don't need to know all the details of this to render your film. *You [click here]() if you do want to learn more.*
Frame Rate | The rate the images are displayed at, per second. (24 FPS = 24 images or frames per second)

#### Audio
Setting | Description
------- | -------
Export Audio (Checkbox) | You can only export Video if unchecked.
Codec | How the audio is encoded (processed) - audio is processed separately from video and then pushed together with the video later and made into one file - a mp4, for instance.

#### File
  * Settings for adjusting filenames and other details of the file. We won't go into detail as they aren't too important for this.

---

### How To Render in Resolve
1. **Setting In & Out.** You first need to make sure you have marked on your timeline what to render. Using the grey line above your timeline and adjusting it to where your video extends to.
###### TIP: If you want extra black screen at the end of your video, but you can't seem to move the grey bar any further than your last clip, simply add a clip to the timeline in the 'Edit' panel that is far enough away from your main video. Then, go back to the 'Deliver' panel, and now you can adjust the grey bar to wherever, before the end of that random clip you added (Make sure not to include that random clip!) - this is something I did for the 'Spring' trailer.
2. **Format and Codec.** Set the Format to 'MP4' in the drop-down menu, then select H.264 in the Codec drop-down menu. H.264 is the most commonly used Video codec and will do us just fine.
3. **Resolution and Frame Rate.** Now, the frame rate will differ per each Blender Film, so take a look at the following list of the Blender films with their resolutions and frame rates to see what settings to use:

| Film | Resolution | Frame Rate |
| --- | --- | --- |
| 'Hero' | 1280x536 | 24 |
| 'Spring' | 1280x536 | 24 |
| 'Big Buck Bunny' | 1280x720 | 60 |

4. **Use Optimized Media (Checkbox).** Go under 'Advanced Settings', find the 'Use Optimized Media' setting and make sure it is checked. This is so the footage in the timeline - that has been optimized (to perform better) - will be rendered properly.
5. **Filename and Save Location.** At the top of the Rendering Settings window, type in your desired Filename in the box next to where it says 'Filename' (e.g. livewires-spring-trailer). Then, underneath that box is another box for the Location of where your file will be rendered to, and stored - click the 'Browse' button to right of the box and choose a suitable place on your computer to store your film!
6. **Render!** Click 'Add to Render Queue' and then on the right-side of the screen, in the 'Render Queue', hit 'Start Render'.

Well done! You have made a film in DaVinci Resolve! Now, of course, you've learnt to use DaVinci Resolve with us here at Livewires but... it is important to know that it's not the software that makes you skilfull or your film great, it is your ideas and skill that you bring to the software, and use it as the tool to manufacture your ideas.  

## Challenge

If you've raced ahead and have finished early, or if you're just looking for something video-related to do after Livewires, then have a go at creating a narrative out of free stock-footage from online.
Here are a few useful links to :
- Free, high-quality stock footage - [Pexels.com](https://www.pexels.com/videos/)
- Free Sound Effects and Recordings - [freesound.org](https://freesound.org/)

---

= Find more useful links here, in [Extras](../extras/UsefulLinks.md)

<- Previous Page: [Editing Audio](02-EditingAudio.md)

[X] Home Page: [Livewires Video Production](../README.md)
