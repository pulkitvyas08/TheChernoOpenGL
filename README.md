# Repo containing episode wise codes for The Cherno's OpenGL Series

Known issues (or differences from the series/my mistakes) - 
1. Vertex buffer in the series has the name "position" while in my codes it is written as "positions"
2. Header file for the renderer i.e. "Renderer.h" is, in my code, mistyped as "Renderder.h" for reasons beyond my understanding
3. In one of the commits, parameter "float deltaTime" of the OnUpdate() function in the Test.h file is mistyped as "delatTime". Just that one commit.
4. Some code for episode 25 might be overriden by code of episode 26 as I forgot to commit changes for episode 25
5. Final Output of commit for episode 25 and 26 displays two ImGui windows "debug" and "test". Embarrassing mistake. Might correct it later
6. I've put code for episode 27 on hold for now
7. Ok. This one is just unbelievable. I forgot to delete all the precompiled header and other stuff used by VS. Files like ipch and all. Everything got uploaded in every previous commit and because of that the size of all commits till "episode 25 & 26" way too much. Going to add all those files to .gitignore from now
  
Be careful with the above while referencing/copying my code
