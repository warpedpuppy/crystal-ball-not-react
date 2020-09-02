# crystal ball

 ## converted react application to html in order to insert into wordpress

steps for insertion:

1. make an images directory in the same folder as the crystal ball animation file is going to be.   Add the 9 images from the image folder into it.

1. add the code from 'crystal-ball.css' into the css file that applies to the page that the graphic will be on.

1. add the file 'crystal-ball.js' into the same directory as the file that you want the crystal ball animation in.

1. on the page that you want the animation add these two lines of code at the bottom of the page, right below the closing body ( ```</body>``` ) tag:

    ```
    <script src="https://cdnjs.cloudflare.com/ajax/libs/pixi.js/5.3.3/pixi.min.js"></script>
    <script src="crystal-ball.js"></script>
    ```

1. finally, add the following code to where you want the animation to appear:

    ```
    <div id="crystal-ball-unifier">
        <div id="crystal-ball-animated-graphic"></div>
        <img alt="lower-half-of-promo" src='/images/bottom-graphic.png' />
    </div>
    ```