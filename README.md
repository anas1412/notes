# Notes

This is a personal notes website built with [Hugo](https://gohugo.io/) and the [hugo-book](https://github.com/alex-shpak/hugo-book) theme.

## Getting Started

To get a copy of this project up and running on your local machine for development and testing purposes, follow these steps.

### Prerequisites

Make sure you have [Hugo](https://gohugo.io/getting-started/installing/) installed on your system.

### Installing

1. Clone the repository:
   ```bash
   git clone https://github.com/anas1412/notes.git
   ```
2. Navigate to the project directory:
   ```bash
   cd notes
   ```
3. Start the Hugo server:
   ```bash
   hugo server -minify
   ```

The website will be available at `http://localhost:1313/`.

## Creating a new post

To create a new post, run the following command:

```bash
hugo new docs/new-post-name.md
```

This will create a new file in `content/docs/new-post-name.md`. You can then edit this file to add your content.

## Pushing to GitHub

Once you have created your new post, you can push it to GitHub. This will trigger a GitHub Action that will build the website and deploy it to GitHub Pages.

```bash
git add .
git commit -m "Add new post"
git push origin main
```

Or simply

```bash
git add .; git commit -m "Add new post"; git push origin main
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License - see the [LICENSE](LICENSE) file for details.