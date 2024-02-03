# HTML-Working-with-Graphics-and-Images
Images
eg <!-- <img src="image.jpg" alt="brown dog" width="400" height="300"> -->
The interesting part is that every image must have these four characteristics. 

The source attribute (SRC), which instructs the browser which image file to load first, is what we have. 
The image's text description is then provided by the alt attribute (ALT). 
The width and height properties are the last ones that control the image's size. All four of these qualities should therefore be present in every image.

The image URL is pasted into the source, and the image loads. Add an ALT attribute to replace the image when it's not visible. Make the ALT text interesting, describing a shiny black dog with pensive eyes. Use humor or poetic language, or leave it blank if there's nothing significant to convey.

The image's dimensions in pixels, 400 pixels wide and 300 pixels tall, can be verified in a program like Photoshop. The width and height attributes should be included, with numerical values sufficing.

Note:In HTML, the order of attributes within an element can be adjusted according to the user's preference, regardless of whether height or width is specified first.

The width and height attributes are necessary for images to be displayed on a page, as the browser determines how to display the image by downloading and analyzing its characteristics. The exact dimensions of each image help the browser calculate the layout, preventing page shifting during loading. This helps improve the reading experience by ensuring the correct dimensions are included in the image.

Image Formates
The image file is crucial for webpages, requiring a web browser-friendly format. New formats aim to balance small file sizes with visually stunning images, ensuring fast downloads and minimizing data usage. Each format uses unique compression techniques to achieve the highest quality with the smallest possible size.

Four common web file formats exist, each with unique strengths and weaknesses in compressing images.

GIFs compress large, color-saturated illustrations but lack 256-color support for photographs, resulting in pixelated images and jagged edges between transparent and solid parts.

SVGs are vector files suitable for logos, icons, and illustrations, with instructions for drawing rather than individual pixels. They can be scaled without loss of quality and can be exported from programs like Illustrator or Sketch.

JPGs are commonly used for compressing images, but web sites should avoid using large, half-compressed JPGs. To further compress, reduce color information and find the right balance between quality and file size.

Responsive Images
CSS provides a solution for displaying images in various sizes, but challenges arise when dealing with high-resolution images with large data files.

To improve image quality, reduce the size of images by reducing colored data and compressing them. This works well for smaller screens but may result in low-quality images on big desktops. Alternatively, keep images small for web designs.

HTML enables the creation of multiple image files, which are then downloaded by the browser, operating system, and device hardware capabilities, considering network speed.

To load an image on a webpage, use an image element with a source attribute, ALT text, width, and height. To support different screen densities, create multiple copies of an image with different resolutions and inform the browser about these options. The device can choose which image to use based on factors like screen density, network connection, and user settings.

The text demonstrates how to display a photo at different widths using HTML code. The code includes the source attribute, ALT text, width, and height. To provide options, a source set attribute is added, listing images with URLs and resolutions. This technique is ideal for handling different image sizes for retina and high DPI screens.

Responsive Pictures
The source set in the sizes attribute can offer multiple image files to the browser, allowing it to decide which one to load and display. However, replacing low-resolution files with high-resolution ones is not possible.

To display a photo on different screens, use the picture element instead of the image element. Use the image element with its ALT text and URL to ensure compatibility with outdated browsers. Wrap the image element with the picture element, and list alternative options using the source element. Create two source elements for each option.

The first source element points to a cropped mobile image file, 320 pixels wide, for smaller screen sizes. The second source element uses a media query to specify the image for larger screens, loading the landscape version when 600 pixels wide.The first source element points to a cropped mobile image file, 320 pixels wide, for smaller screen sizes. The second source element uses a media query to specify the image for larger screens, loading the landscape version when 600 pixels wide.

The "source set" attribute is used in the source element, similar to the image element. Techniques like picture, source, and source set are used, with multiple file options. Browser switches between files based on viewport size and retina screen, switching cropped to wide versions when needed.

Note:In a web browsing scenario, users only download the appropriate image file, reducing unnecessary downloads when viewing a web page on a single screen with a fixed viewport size.

The primary goal of using HTML techniques is to optimize web images by delivering the smallest possible file size while maintaining the beauty of the images.

Figcaption and Figures
The text explains how to add an image to a web page and how to match a caption to that image, focusing on figures.

To create a visually appealing dog image, use the figcaption element to wrap the text and designate it as a caption. Place the image and caption together in a figure element, providing more information about the content and connecting it to search engines and AI. These elements are useful for visual illustrations and concept demonstrations.


