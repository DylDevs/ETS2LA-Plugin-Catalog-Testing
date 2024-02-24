# Demo Repository For ETS2LA Plugin Catalog

## This is the official repository to create your own fork/repo for the Plugin Catalog built into [ETS2LA](https://github.com/Tumppi066/Euro-Truck-Simulator-2-Lane-Assist)

### Here's how you can create a repository of your own:

Forking the Repository:

    Go to the repository URL: TUMPPIS REPO WHEN HE MAKES IT
    Click on the "Fork" button at the top right corner of the page.
    Wait for the forking process to complete. This will create a copy of the repository under your GitHub account.

Adding Your Plugin Files:

    Once the repository is forked, navigate into your forked repository on GitHub.
    You should delete all the current plugins in your fork by deleting the plugins folder.
    Click on the "Add file" dropdown and select "Upload files".
    Upload your /plugins folder that includes all of your plugin folders. Make sure to include all necessary plugin files.
    Once the files are uploaded, click on the "Commit changes" button to commit your changes.

Guide to the plugin_index.json file
This file is a list of plugins and attributes, they include:
- Name | Name of your plugin
- Description | Short description of what your plugin does
- Author | Who made this plugin?
- Version | What is the version? (Every time you change a plugin, you should update its version, this way, the autoupdater works.)
- Path | The path to your plugins folder. For the example ir could be, ```/plugins/YourPluginName```.

It also includes information about your repository for the app to display:
- Name 
- Description
--------------

Editing the index.json File:

    Navigate to the root directory of your forked repository.
    Click on the index.json file to open it.
    Click on the pencil icon to edit the file.
    Update the JSON content with the information about your plugin. Make sure to include the plugin name, description, author, version, compatibility, and path.
    After making the necessary changes, scroll down and click on the "Commit changes" button to save your modifications.

Automated GitHub Action for Creating plugin.zip:

    GitHub Actions can automate the process of creating the main.zip file for your plugin.
    A GitHub Action in your repository will automatically create the main.zip file whenever changes are pushed to the repository.
    GitHub will automatically run the workflow whenever changes are made to the repository.

Creating a Pull Request to the Official Repository:

    After you have committed your changes to your forked repository and pushed them to GitHub, you can submit a pull request to merge your changes into the official repository. This is not manditory, you can keep these plugins on your own repository if you please.
    Go to the official repository URL: PLACEHOLDER.
    Click on the "Pull requests" tab.
    Click on the green "New pull request" button.
    GitHub will prompt you to compare changes.
    GitHub will automatically detect the changes you made in your fork. Review the changes.
    Once you're satisfied, click on the "Create pull request" button.
    Provide a title and description for your pull request, explaining the changes you've made and the purpose of the pull request.
    Finally, click on "Create pull request" to submit your changes for review by the repository maintainers.

------------------
If you need more info about this, you can head over to the wiki page where everything is explained in detail.

[https://wiki.tumppi066.fi/plugins/plugincatalog/](https://wiki.tumppi066.fi/plugins/plugincatalog/)
