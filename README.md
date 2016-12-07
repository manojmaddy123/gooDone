# Website Performance Optimization portfolio project #

1. In this project two websites are to be optimized for the page speed and the number of frames per second.
2. The first website is a portfolio site where the page speed is to be optimized.
3. The second website is a pizza shop website where the number of frames per second must be approximately equal to 60fps.

## Instructions to open the websites ##

1. Extract the zip file.
2. open the index.html file in the folder after extraction to view the portfolio website.
3. Now go to views folder and open pizza.html file to view the pizza shop website.
4. Paste the URL "https://manojmaddy123.github.io/gooDone/" in "https://developers.google.com/speed/pagespeed/insights/" to check the pagespeed score for mobile and desktop.

## Editing index.html to render the speed of the protfolio site ##

1. The code in the file styles.css is minified by css minifier app and is inlined in the html file.
2. The font family is removed from the inline css code and its corresponding css font link is removed.
3. The analytics.js file is removed from the link and its corresponding functions are removed as it has no effect on building the site.
4. All the images links in the content div are downloaded and are placed in the images folder and the links are mentioned.
5. Since the image files are too large to load, they are compressed and added to the images folder.
6. https://manojmaddy123.github.io/gooDone/
7. The above website is hosted in the github and is tested in the pagespeed insights website for a mobile and desktop score of 94 and 96 respectively.

## Editing the main.js file for the pizza shop website for running in 60fps ##

1. The main.js had a function called randomPizzaContainer that was called multiple times which was responsible for forced synchronous layout.
2. The function was corrected by calling it once and iterating it through a for loop.
3. The images are now compressed and the links are correspondingly given.
4. Now going to tools and rendering by selecting the paint flash and FPS meter, the site is now scrolled up and down to get an 60fps approximately.

## Screenshots Folder added in the Zip file ##
1. The screenshots for the pagespeed score for mobile and desktop versions are added to the folder named screenshots.




