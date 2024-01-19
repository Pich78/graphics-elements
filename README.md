# graphics-elements
Collection of basic drawing elements

In CSS, `.rectangle.contour` and `.rectangle .contour` are used to select elements for styling, but they target different elements.

- `.rectangle.contour`: This is a **compound selector** that targets elements that have **both** `rectangle` and `contour` classes. For example, in `<div class="rectangle contour">`, this selector would apply.

- `.rectangle .contour`: This is a **descendant selector** that targets elements with the `contour` class that are **descendants** of elements with the `rectangle` class. For example, in `<div class="rectangle"><span class="contour"></span></div>`, this selector would apply to the `span` element.

So, the main difference is that `.rectangle.contour` looks for elements that have both classes, while `.rectangle .contour` looks for `contour` elements within `rectangle` elements.


(1) Hough transformation vs Contour detection for Rectangle recognition .... https://stackoverflow.com/questions/10260519/hough-transformation-vs-contour-detection-for-rectangle-recognition-with-perspec.
(2) python - Find contour of rectangle in object - Stack Overflow. https://stackoverflow.com/questions/54508006/find-contour-of-rectangle-in-object.
(3) Drawing a rectangle around all contours in OpenCV Python. https://stackoverflow.com/questions/40203932/drawing-a-rectangle-around-all-contours-in-opencv-python.
(4) border-radius - CSS : Feuilles de style en cascade | MDN - MDN Web Docs. https://developer.mozilla.org/fr/docs/Web/CSS/border-radius.
(5) OpenCV: Contour Features. https://docs.opencv.org/3.4/dd/d49/tutorial_py_contour_features.html.
(6) undefined. http://www.imagemagick.org/discourse-server/viewtopic.php?f=1&t=14491&start=9.
