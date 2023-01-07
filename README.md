# Ubersicht-Kill

This is a product that I collected and edited to suit my simple liking...
Widgets for Übersicht
UPDATE: widgets now live in their own github repo. The old format is still supported, but will be phased out soon.

Got a widget to share? Great, create a github repo for it, then open an issue here and be sure to mention the url. It will get picked up ASAP!

Note:
Since tweaking the look of a widget is fun and easy, the widget gallery is probably the most useful if it serves as starting point instead of being a comprehensive list of all possible widgets. For this reason we try to keep the widget gallery as focused as possible. This means, instead of adding new widgets that are very similar to an existing widget, we try to encourage people to make a pull requests with their improvements (these could be technical improvements or style/design improvements).

Widget format
Your repo should contain at least these three files:

widget.json a widget manifest
<widget-name>.widget.zip a zip archive containing your widget
screenshot.png an image showing your widget in action
It is also advised that you include an unzipped version of your widget, so that people can view the code and/or issue pull requests with improvements.

widget.json
A small manifest file that describes your widget. It should have the following format:

{
  "name": "name of your widget",
  "description": "a short(!) description",
  "author": "your name",
  "email": "your email address"
}
widget-name.widget.zip
This is the actual widget, which is a zipped folder with the name of your widget and a .widget extension. The contents of the folder are usually just the .js or .coffee file with your widget code (you can call it anything you like, but using the name your widget seems like a good choice). If your widget needs any other assets such as images, fonts or even binaries, you can include them here.

![Screenshot 2023-01-07 at 17 47 03](https://user-images.githubusercontent.com/106985465/211143027-6b249ecc-a4b8-4c64-bddf-a8ac1979990b.png)

Support me : PayPal : h281994@gmail.com
