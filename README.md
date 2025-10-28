
# Instructions 

## Task 1 - `bears.html`
Edit the `bears.html` document so that each section of the page has the width indicated by the heading and the comments.

Remember that you should use the full screen preview to view your changes. You should only be editing `bears.html`. You can use `index.html` as a reference.

1. First add the appropriate links (in the `<head>`) to the bootstrap stylesheet and the stylesheet that makes the background green.

2. Then add the appropriate class names to the appropriate divs. All of the classes that you will need to use have been used in `index.html` and/or were highlighted in the videos. 

- Remember that one `div` is the `container` for all of the rows.

- All of the columns need to be nested inside of rows.
Nothing needs to be turned in today.
 
If you need help this assignment, this **[video](https://youtu.be/FFaHpsKRx1E)** walks through about 80% of the assignment along with explanations. The last 20% is for you to complete individually.

## Task 2 - `page3.html`

Expand the Website by adding a third html document named `page3.html`.

- Connect `page3` to both the `style.css` and `bootstrap.css`stylesheets with appropriate links in the `head`.
  - This will make the background color green to match and allow you to apply the bootstrap style classes to the third page.

- Set up the third page to have the following layout
  - A heading with centered text.
  - Hyperlinks to all 3 pages: Home, More Bear Info and Page 3.
    - These hyperlinks should also be updated on `bears.html` and `index.html`
  - A row with filler text on the left (50% width) and a 50% width image of a dog on the right (you can download any dog image that you want). The dog image should resize automatically as the size of the screen changes. For more info on how to accomplish that, look at the other images or view the documentation at [Bootstrap image docs](https://getbootstrap.com/docs/5.3/content/images/#responsive-images).
  - A row with 3 equal columns.
    - Each column should have an image of a pig (your choice on the image), and an `h2` that says pigs. 

The 3rd page should look like the mockup below: 
![P3 mockup](/img/p3.png)

For help with adding the 3rd page check out this **[video](https://youtu.be/X0gyLcTT7Bo)**. The video covers about 90% of the task requirements.


## Task 3 - Navbar

Setting Up for a Bootstrap Navbar - 
https://youtu.be/awB3mzsSqgM

Adding the Navbar -
https://youtu.be/P4x8aujxc3Q

Follow along with the videos and use the bootstrap documentation at https://www.getbootstrap.com. Most of what we do will be a copy and paste, but then you need to update the code to link to your specific pages. 

The video will walk you through a navbar on one page. Your job will then be to copy that navbar code to all of your pages in order to create consistent navigation for your users.

## Task 4 - Carousel

Today we will add an image carousel to our practice bootstrap website.

First, watch the video https://youtu.be/oQIN3wZNXOM and follow along to replace the bear image on the home page (`index.html`) with a carousel.

Next, find at least 3 dog images of the same size, download and save them in the `/img` folder of your repository. Be sure to name them with simple names. For help finding images that are the same size watch: https://youtu.be/nTjb_UQa8G8. All image files should end with `.jpg`, `.png` or `.gif` file extensions.

Repeat the process from the first video to change the dog image on `page3.html` into a carousel with at least 3 dog images. If your carousel will not advance, double-check that you added the optional Javascript tag at the bottom of the document (just before the closing body tag). 

    `<!-- Optional JavaScript -->`
    `<script src="js/bootstrap.bundle.js"></script>`