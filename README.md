## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Pyraegea/pyraegea.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Pyraegea/pyraegea.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Local Development Setup

#### Prerequisites

- Docker and Docker Compose must be installed on your machine.

#### Setup and Running Locally

1. **Clone the Repository** (if you haven't already):  
   ```sh
   git clone https://github.com/Pyraegea/pyraegea.github.io.git
   cd pyraegea.github.io
   ```

2. **Build and Start the Docker Environment:**  
   Run the following command in the root directory of this project:
   ```sh
   docker-compose up --build
   ```
   This command builds the Docker image and starts the Jekyll server inside a Docker container. It may take a few minutes the first time.

3. **Access Your Site:**  
   Once the server is running, open your web browser and visit http://localhost:4000 to view your Jekyll site. Changes you make to the project files will automatically update and reflect in the browser.
   
4. **Stopping the Server:**  
   When you're done developing, you can stop the Docker container with:
   ```sh
   docker-compose down
   ```


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
