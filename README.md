Typescript, Tailwind, and HTML Template
This project is a template for building web applications using Typescript, Tailwind CSS, and HTML. It provides a structured setup for development and production builds.

Installation
Clone the repository:

git clone [https://github.com/your-username/type-tailwind.git](https://github.com/Abduljebar49/typescript-tailwind-template.git)
Navigate to the project directory:

cd typescript-tailwind-template
Install dependencies using npm:

npm install
How to Use
Adding JavaScript from the Dist Folder
After making changes to your Typescript files (src/*.ts), build the project to generate JavaScript files in the dist folder:

npm run dev
This command compiles Typescript files using tsc, copies the compiled JavaScript files from src to dist, and watches for changes to Tailwind CSS (src/main.css) to rebuild the Tailwind styles.

Running the Development Server
To start a development server:

npm start
This will serve the files from the dist folder and watch for changes, automatically reloading the browser.

Project Structure
src/: Contains Typescript (*.ts) and CSS (main.css) source files.
dist/: Generated output directory where compiled JavaScript and processed CSS are placed.
tsconfig.json: Configuration file for Typescript compilation.
package.json: Includes project metadata, dependencies, and build scripts.
Dependencies
Typescript: Adds static typing to JavaScript.
Tailwind CSS: Utility-first CSS framework.
Autoprefixer: Adds vendor prefixes to CSS rules.
PostCSS: CSS post-processing tool.
ts-node: TypeScript execution and REPL for Node.js.
 
