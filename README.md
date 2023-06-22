### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Pasha8Dev/react-portfolio.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your name in `.env.development`
   ```js
   REACT_APP_NAME=<your_name>
   ```
4. Add your markdown pages in `public/pages`
5. Add your routes in `src/app/pages/page.ts`, make sure the names of pages are consistent with markdown files.
    ```ts
    export const pages = [
      { index: 0, name: 'overview.md', route: '/overview' },
      { index: 1, name: 'skills.md', route: '/skills' },
      { index: 2, name: 'experience.md', route: '/experience' },
      { index: 3, name: 'education.md', route: '/education' },
      { index: 4, name: 'projects.md', route: '/projects' },  
      { index: 5, name: 'certificates.md', route: '/certificates' },
      { index: 6, name: 'accomplishments.md', route: '/accomplishments' },
    ];
    ```
6. Add your social links in `src/app/pages/link.tsx`, which will appear in both sidebar and homepage.
    ```ts
    export const links = [
      {
        index: 0,
        title: "Find me on Github",
        href: "https://github.com/noworneverev",
        icon: <FaGithub />,
      },
    ];
    ```
7. Runs the app in the development mode
   ```sh
   npm start
   ```   
8. Deploy your own portfolio,  
   - modify homepage property in `package.json` 
   ```
   "homepage": "https://{username}.github.io/{repo-name}"
   ```
   > \* For a [project site](https://pages.github.com/#project-site), that's the format. For a [user site](https://pages.github.com/#user-site), the format is: `https://{username}.github.io`. You can read more about the `homepage` property in the ["GitHub Pages" section](https://create-react-app.dev/docs/deployment/#github-pages) of the `create-react-app` documentation.   
  


   - modify Google Analytic measurement id in `.env.production`
   ```
   REACT_APP_NAME=<your_name>
   REACT_APP_MEASUREMENT_ID=<your_measurement_id>   
   ```

### Alternative Deployment
```
docker-compose up
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Demonstration

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Features

- Powered by markdown
- Extended markdown syntax supported
  - Syntax highlight
  - Alert
- Dark mode and light mode available
- Closable tabs
- Collapsible explorer
- Responsive web design
- Google Analytics supported
- Auto-deploy to gh-pages with github actions ready

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Pasha&Dev - tomjerry950710@gmail.com


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
