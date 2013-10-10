Updating Images Workflow (for githubber)
========================================

![](https://raw.github.com/AmericanRedCross/Guides/master/TranslationWorkflow_LearnOSM/img/inkscapelogo.png) [ Inkscape](http://inkscape.org/) is an Open Source vector graphics editor. Its many features and streamlined interface make it a useful tool. Download and install the program to follow along with this workflow. However, if you are familiar with a different graphics editor you can use your it and your own methods in the Editing the Image section of this workflow. 

*Note: Some images may require new screen-grabs. This workflow covers currently the basic process of replacing a text box.*


Getting Ready
-------------

+ Find an image you want to translate/edit. 
+ There is specific markdown syntax for images. In the **0200-12-29-start-osm.md** chapter the third section is **NAVIGATE THE MAP** and includes an image with text. The position in the chapter text where the image appears is marked with the following code:

```
    ![Mouse navigation][]
```  

+ At the end of the file, the location and file name of the image is contained in the following code:  

```
    [Mouse navigation]: {{site.baseurl}}/images/xx/en_beg_02_start-osm_image02_mouse-navigation.png
```  

+ __Note__: you should have copied and renamed the 'images/en' folder as well as updated the paths within the chapters as part of the 'Preparing the Folders and Files' step in the [githubber workflow](githubberWorkflow.md)
+ Open the **learnosm/images/xx** folder on your computer (the copy you created and renamed) and find the image file you want to edit. 
	- To edit the **Mouse navigation** image you would find the **en_beg_02_start-osm_image02_mouse-navigation** file. 
+ Rename the image file. Replace 'en' with the two letter code for the new language.		


Editing the Image
-----------------

+ Open Inkscape and then open the image file. Choose to **embed** the image.
+ From the **View** menu dropdown select **Zoom** and then **Drawing** to zoom to the image.

![](https://raw.github.com/AmericanRedCross/Guides/master/TranslationWorkflow_LearnOSM/img/inkscape_zoom.png)

+ Cover up the English text.
	- Select the **Create rectangles and squares (F4)** tool from the sidebar or by using the keyboard shortcut.
	- Draw a rectangle over the English text.
	- From the **Object** menu dropdown select **Fill and Stroke...**
	- In the options box that opens change the R, G, and B values to 255 (for white) and make sure the opacity is set to 100%. Close the options box.

![](https://raw.github.com/AmericanRedCross/Guides/master/TranslationWorkflow_LearnOSM/img/inkscape_rectangle.png)

+ Add translated text.
	- Select the **Create and edit text objects (F8)** tool from the sidebar or by using the keyboard shortcut.
	- Left-click-hold and drag to create a box the size of the entire text area.
	- Type the translation.
	- Press **ctrl + a** to select all the text.
	- From the top bar change the font size up or down so that all fits but it is as large as possible. 
+ Save the edits.
	- From the **File** dropdown select **Export Bitmap...**
	- A menu box will popup.
	- Under **Export area** click the **Drawing** option.
	- For **Filename** browes to the same file you opened.
	- Click **Export**. The program will warn you that the file already exists. Make sure the file name in the warning is the one you are translating. Click **Replace**.
	- Close the **Export Bitmap** menu box.
+ Check your image.

![](https://raw.github.com/AmericanRedCross/Guides/master/TranslationWorkflow_LearnOSM/img/xx_beg_ch2_image02.png)

Update the Code for the Chapter
-------------------------------

+ Open the chapter file in a text editor for code. Go to the end of the file and find the location and file name of the image.
+ Change the file name to match the translated image.
+ For example, from this:

```
    [Mouse navigation]: {{site.baseurl}}/images/xx/en_beg_ch2_image02.png
```

to this:

```
    [Mouse navigation]: {{site.baseurl}}/images/xx/xx_beg_ch2_image02.png
```
