## Sustainable Frontend Cheatsheet

### Images

- Images will make a large contribution to the weight of your page. It’s worth considering if you can deliver a good user experience without images, or with only a few images.
- If you have any uncompressed images on your site, compress them.
- Consider replacing pixellated images (.jpg, .png) with vector images (.svg).
- Right-size your images, rather than scaling them up or down using css.
- Read more on using images effectively [here](https://sustainablewebdesign.org/has-the-design-used-imagery-efficiently/).

### Video

- **Note: Because the video header is streaming, changes you make to it won't be immediately visible on the sustainability calculator's score. If you leave the calculator recording, it be contribute to the score increasing over time. However, you can see the full impact of the video if you analyse the website's payload using Lighthouse. You can find out how to do that [here](https://developer.chrome.com/docs/lighthouse/overview/#devtools).**
- Videos will make a large contribution to the weight of your page. It’s worth considering if you can deliver a good user experience without video.
- If you have any uncompressed videos on your site, compress them.
- If you’re hosting high quality videos, consider whether you could host them in lower quality without affecting user experience.

### Animation

- Animated elements will make a medium contributions to the weight of your page. Consider removing them if they’re not making a big impact.

### Fonts

- Font choices can make a large contribution to the weight of your page. The lightest fonts are system fonts- these are fonts which are already present on every users’ machine by default. Examples of system fonts are Helvetica, Arial and Futura. Web fonts like Google Fonts make a page heavier as they have to be fetched. This page uses Montesserat and Bebas Neue.
- If you use Google Fonts, you can reduce the amount your webpage needs to fetch by refining the query you use to fetch them. For instance, in this project we fetch the entire font family for the fonts we are using (see `public/index.html`).

### Icons

- Similarly to web fonts, if you use web icons, they need to be fetched. You can reduce the amount your webpage needs to fetch by refining the query you use to fetch them. For instance, in this project we are fetching a large number of icons (see `public/index.html`).

### Efficiency and Performance

- More sustainable solutions are more efficient solutions. A good way to make your project more sustainable is to look up efficiency strategies for the tech stack that you are using on your project. For instance, you can find documentation on making your React project more efficient [here](https://legacy.reactjs.org/docs/optimizing-performance.html).
- You can get more tips to help you improve the performance of your page using Lighthouse. You can find out how to do that [here](https://developer.chrome.com/docs/lighthouse/overview/#devtools).

### Advanced

- This page is being run using a development configuration and so it has not been configured for efficiency. This site has been built using create-react-app for simplicity. If you would like to have a go at optimising the site configuration, running `npm run eject` in your terminal [will give you access to the project's configuration files](https://create-react-app.dev/docs/available-scripts/). 
- Useful configuration changes you could make are [minification](https://webpack.js.org/guides/production/#minification) and [improved caching](https://developer.chrome.com/docs/lighthouse/performance/uses-long-cache-ttl/?utm_source=lighthouse&utm_medium=devtools).

### The Philosophy of Sustainability Design

Creating a sustainable website is not all about stripping everything out of a website which you can- if you slim a website down without taking account of design and usability few people will use it, and then you’ve simply created waste. Instead, good, sustainable web design is about delivering your website in a way which is lean, and which works well for your users. A good way to find this balance on your own projects is to you use mobile-first development, which forces you to be thoughtful about the elements that you choose to include on a page, and to set yourself [page weight budgets](https://sustainablewebdesign.org/has-the-design-team-set-a-page-weight-budget/) and efficiency targets while designing.

Accessibility is also an important feature of a sustainable front end design, as if users are forced to click around your website in order to find what they are looking for, energy will be being wasted. You can read more about web accessibility [here](https://www.hostinger.co.uk/tutorials/web-accessibility).