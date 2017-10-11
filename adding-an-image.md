# Adding an Image

Next we're going to add an image to our project and add a new view to our application that will display an image.

1. Go back to Xcode. Select the Assets.xcassets items in the Project Navigator. This is where our project's images are stored and we're going to drag an image into this item from the Finder.
2. In the Finder, pick an image you want to add to the project and drag it into the Assets.xcassets editor.

![](/assets/Sushi11.png)

Now that we've added our image we can add it to our view.

Select the Main.storyboard in the Project Navigator.

We will first delete our old View. Like before in the document outline, highlight the View and press the delete key.

In the Utilities pane on the right, there is a section at the bottom. The third icon is for the Object Library, which is where we can find an Image View to add to our view. Start typing 'image' into the search bar at the bottom of the pane to filter objects down to our image view.

![](/assets/Sushi10.png)

Drag the Image View over to our View Controller. If you hold the Image View over the View Controller it will resize itself to fill the entire controller.

![](/assets/ImageViewDrag.png)

Drop the Image View on the controller. The Utilities pane will change to reflect the properties on the Image View. Select the Image dropdown menu item and select the name of the image you dragged in in step 

