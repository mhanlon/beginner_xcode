# Adding an Image

Next we're going to add an image to our project and add a new view to our application that will display an image.

1. Go back to Xcode. Select the Assets.xcassets items in the Project Navigator. This is where our project's images are stored and we're going to drag an image into this item from the Finder.
2. In the Finder, pick an image you want to add to the project and drag it into the Assets.xcassets editor.![](/en/assets/Sushi11.png)Now that we've added our image we can add it to our view.
3. Select the Main.storyboard in the Project Navigator.
4. We will first delete our old View. Like before in the document outline, highlight the View and press the delete key.
5. In the Utilities pane on the right, there is a section at the bottom. The third icon is for the Object Library, which is where we can find an Image View to add to our view. Start typing 'image' into the search bar at the bottom of the pane to filter objects down to our image view.![](/en/assets/Sushi10.png)
6. Drag the Image View over to our View Controller. If you hold the Image View over the View Controller it will resize itself to fill the entire controller.![](/en/assets/ImageViewDrag.png)
7. Drop the Image View on the controller. The Utilities pane will change to reflect the properties on the Image View. Select the Image dropdown menu item and select the name of the image you dragged in in step 2.![](/en/assets/Sushi12.png)
8. We don't want our image to be squashed or out of proportion, so change the Content Mode to Aspect Fit.
9. Now if we press the Run button to build and run our project we will see our image displayed in our app.![](/en/assets/Sushi14.png)

