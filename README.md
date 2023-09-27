# Ismail Khan [dot] dev

Welcome to Ismail Khan's personal website! This website showcases my portfolio, blog, and other projects. It's built using Flask, Frozen-Flask, Jinja2, TailwindCSS, and TypeScript.

## Features

-   **Home Page**: An introduction to me and my work.
-   **About Page**: Learn more about my background, skills, and interests.
-   **Projects Page**: Explore the projects I've worked on, complete with descriptions and links.
-   **Blog Page**: Access my blog posts on various topics.
-   **Responsive Design**: The website is responsive and looks great on both desktop and mobile devices.
-   **TailwindCSS Styling**: Stylish and modern UI design using TailwindCSS.
-   **Static Site Generation**: Uses Frozen-Flask to generate static HTML pages for faster loading and deployment.

## Technologies Used

-   **Flask**: A micro web framework for Python used for building web applications.
-   **Frozen-Flask**: Converts Flask web applications into static websites.
-   **Jinja2**: A template engine for Python, used for rendering HTML templates.
-   **TailwindCSS**: A utility-first CSS framework for creating modern and responsive web designs.
-   **JavaScript**: Used for client-side interactivity and dynamic behavior.
-   **GitHub**: Hosting the source code and project repository.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

    ```shell
    git clone https://github.com/yourusername/your-website.git
    ```

2. Navigate to the project directory:

    ```shell
    cd your-website
    ```

3. Create a virtual environment (recommended):

    ```shell
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On macOS and Linux:

        ```shell
        source venv/bin/activate
        ```

    - On Windows (Command Prompt):

        ```shell
        venv\Scripts\activate
        ```

    - On Windows (PowerShell):

        ```shell
        .\venv\Scripts\Activate.ps1
        ```

5. Install the project dependencies:

    ```shell
    pip install -r requirements.txt
    ```

6. Run the Flask development server:

    ```shell
    flask --app app --debug run
    ```

7. Build the tailwindCSS output.css (in another shell, optional):

    ```shell
    npx tailwindcss -i ./static/src/input.css -o ./static/dist/css/output.css --watch
    ```

    The website should be accessible at `http://localhost:5000` in your web browser.

8. Building for Freezer-Flask

    ```shell
     python3 build.py
    ```

## Deployment

This website is deployed with GitHub Pages and CI/CD with GitHub Actions.
