# blog_website_task2-bharat-intern
Install Node.js:
Before you can use npm, you need to have Node.js installed on your system. You can download and install it from the official website: Node.js.

Open a Terminal or Command Prompt:
Once Node.js is installed, open a terminal or command prompt on your computer.

Navigate to Your Project Directory:
Use the cd command to navigate to the directory where your Node.js project is located. For example:

bash
Copy code
cd path/to/your/project
Initialize Your Project (if not already done):
If your project doesn't have a package.json file, you can create one by running:

bash
npm init
Follow the prompts to provide information about your project. You can press Enter to accept the default values for most fields.

Install the Node Module:
To install a Node module, you use the npm install command followed by the name of the module. For example, to install a module called example-module, run:

bash
npm install example-module
If you want to save it as a dependency in your package.json file, use the --save flag:

bash
npm install example-module --save
If you are installing a module that you will only use during development (not in production), you can use the --save-dev flag:

bash
npm install example-module --save-dev
Check Your package.json:
After the installation, check your package.json file to make sure the module has been added to the dependencies or devDependencies section, depending on how you installed it.
