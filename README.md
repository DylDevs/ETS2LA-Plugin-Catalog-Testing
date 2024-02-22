# Demo Repository For App Store

## This is the official repository to create your own fork/repo for the App Store built into [ETS2LA](https://github.com/Tumppi066/Euro-Truck-Simulator-2-Lane-Assist)

### Here's how you can create a repository of your own::

Forking the Repository:

    Go to the repository URL: https://github.com/Cloud-121/testapprepo.
    Click on the "Fork" button at the top right corner of the page.
    Wait for the forking process to complete. This will create a copy of the repository under your GitHub account.

Adding Your Plugin Files:

    Once the repository is forked, navigate into your forked repository on GitHub.
    Click on the "Add file" dropdown and select "Upload files".
    Upload all the files related to your plugin into the /plugins/{Name of plugin} directory. Make sure to include all necessary plugin files.
    Once the files are uploaded, click on the "Commit changes" button to commit your changes.

Editing the index.json File:

    Navigate to the root directory of your forked repository.
    Click on the index.json file to open it.
    Click on the pencil icon to edit the file.
    Update the JSON content with the information about your plugin. Make sure to include the plugin name, description, author, version, compatibility, and path.
    After making the necessary changes, scroll down and click on the "Commit changes" button to save your modifications.

Automated GitHub Action for Creating main.zip:

    GitHub Actions can automate the process of creating the main.zip file for your plugin.
    A GitHub Action in your repository will automatically create the main.zip file whenever changes are pushed to the repository.
    GitHub will automatically run the workflow whenever changes are made to the repository.
