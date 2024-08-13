# static-html-template
A template repository to bootstrap simple html content.
It is a GitHub template for HTML pages with a live server and Rollup bundling.


## Features

- HTML, CSS, and JavaScript structure
- Live server for development
- Bundling with Rollup

## Structure
```
├── dist/                  # Output directory for bundled files
├── src/                   # Source directory for HTML, CSS, and JavaScript files
│   ├── css/               # CSS files
│   ├── js/                # JavaScript files
│   └── index.html         # Main HTML file
├── .gitignore             # Git ignore file
├── package.json           # NPM package configuration file
├── rollup.config.js       # Rollup configuration file
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- Node.js installed

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/my-html-template.git
    cd my-html-template
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

### Development

Start the live server and watch for changes:

```sh
npm run dev
```

### Build

Build an bundle:

```sh
npm run build
```
