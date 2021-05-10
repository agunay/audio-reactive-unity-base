# To clone the repository for the first time 
1. Open 'Terminal'
2. Use the command `cd <path_to_the_directory_to_contain_the_project>`
3. On GitHub, click on the green dropdown button with the text Code. Ensure SSH is selected. Copy the line. Go back to your terminal and type `git clone <paste_the_copied_line_from_github>` - if this step is successful you cloned the project successfully. You can confirm by typing `ls` in the terminal.

Alternatively you can just get it as an archived file but I suggest above steps, so you can easily pull the changes if I make further updates.

# To open in Unity
1. Open Unity Hub
2. Click on Add and locate your project. I used Unity version 2019.4.21f1 (LTS)

# To pull the latest changes to the repository
1. On your Terminal, type `cd <path_to_the_project>`.
2. `git pull origin main`

# Klak Examples
These are located under Assets/Klak/Examples/SampleScenes

# LASP
This package is imported through scopedRegisteries - this means you won't see the package under Assets (e.g. like Klak). You can confirm it's installed through Window -> Package Manager. Examples are located under `Assets/LASP/Assets`

# KlakLasp
This package isn't maintained anymore I'm afraid so I haven't add it to this project, this will not work properly. Kejiro says you don't need it, see: https://github.com/keijiro/KlakLasp/issues/5
