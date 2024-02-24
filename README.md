# ETS2LA extra plugins.

## This is the official repository to create your own fork/repo for the Plugin Catalog built into [ETS2LA](https://github.com/Tumppi066/Euro-Truck-Simulator-2-Lane-Assist)

### Here's how you can create a repository of your own:

### Forking the Repository:
1. Go to the repository URL: https://github.com/Tumppi066/ETS2LA-Extra-Plugins
2. Click on the "Fork" button at the top right corner of the page.
3. Wait for the forking process to complete. This will create a copy of the repository under your GitHub account.
4. Go to the "Actions" tab and mae sure that they are turned on. This will ensure that zip files can be created automatically.

### Adding Your Plugin Files:
1. Once the repository is forked, navigate into your forked repository on GitHub.
2. You should delete all the current plugins in your fork by deleting the plugins folder.
3. Click on the "Add file" dropdown and select "Upload files".
4. Upload your /plugins folder that includes all of your plugin folders. Make sure to include all necessary plugin files.
5. Once the files are uploaded, click on the "Commit changes" button to commit your changes.

### Guide to the plugin_index.json file.

This file is a list of plugins and attributes, they include:
- **Name** | Name of your plugin
- **Description** | Short description of what your plugin does
- **Author** | Who made this plugin?
- **Version** | What is the version? (Every time you change a plugin, you should update its version, this way, the autoupdater works.)
- **Path** | The path to your plugins folder. For the example ir could be, ```/plugins/YourPluginName```.

It also includes information about your repository for the app to display:
- **Name** 
- **Description**

### Editing the index.json File:
1. Navigate to the root directory of your forked repository.
2. Click on the index.json file to open it.
3. Click on the pencil icon to edit the file.
4. Update the JSON content with the information about your plugin. Make sure to include the plugin name, description, author, version, compatibility, and path.
5. After making the necessary changes, scroll down and click on the "Commit changes" button to save your modifications.

### Automated GitHub Action for Creating plugin.zip:
1. GitHub Actions can automate the process of creating the main.zip file for your plugin.
2. A GitHub Action in your repository will automatically create the main.zip file whenever changes are pushed to the repository.
3. GitHub will automatically run the workflow whenever changes are made to the repository.

### Creating a Pull Request to the Official Repository:
1. After you have committed your changes to your forked repository and pushed them to GitHub, you can submit a pull request to merge your changes into the official repository. This is not manditory, you can keep these plugins on your own repository if you please.
2. Go to the official repository URL: https://github.com/Tumppi066/ETS2LA-Extra-Plugins
3. Click on the "Pull requests" tab.
4. Click on the green "New pull request" button.
5. GitHub will prompt you to compare changes.
6. GitHub will automatically detect the changes you made in your fork. Review the changes.
7. Once you're satisfied, click on the "Create pull request" button.
8. Provide a title and description for your pull request, explaining the changes you've made and the purpose of the pull request.
9. Finally, click on "Create pull request" to submit your changes for review by the repository maintainers.

If you need more info about this, you can head over to the wiki page where everything is explained in detail.

[https://wiki.tumppi066.fi/plugins/plugincatalog/](https://wiki.tumppi066.fi/plugins/plugincatalog/)
