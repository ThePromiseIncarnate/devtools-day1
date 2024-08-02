![Lighthouse](/img/lighthouse.png)
- Lighthouse
    - No areas with low scores
    - Performance Diagnotics: Minify JavaScript, Serve static assets with an efficient cache policy 2 resources found, Eliminate render-blocking resources, Reduce unused JavaScript
    - Accessibility: Background and foreground colors do not have a sufficient contrast ratio

![Performance](/img/performance.png)
- Performance
 - Long Task when loading Introductions page, likely due to the Bootstrap Cards and loading images
 - Long Task when loading Eidolon page, likely due to Bootstrap list
 - LOTS of Long Tasks involved with the Tarot Card functions, should probably have removed all those debug console.logs

 ![Networking](/img/networking.png)
- Networking
 - No issues 

 My website seems to be problem-free for the most part. I primarily just need to fix the colors of my site by forgoing Bootstrap on the text and making it a brighter green and clean up my Javascript to reduce the "long tasks". 