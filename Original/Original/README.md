**This folder**  
**Purpose** - Prepare a similar implementation in julia so that it can be compared with our own  
**File structure** - Everything is declared in the header files (.h). The cpp files then do useful work using those declerations.  
  
**How to set up**
1. Install cLion
2. Run it
3. Select import or open cLion project or whatever makes sense
4. Select Original/Original (.)
5. If you get any errors, google them. If the error in in the form of a hyperlink, 
click it.

**Running the project**  
**neatmain.cpp** is the main file that runs others.
It calls NEAT::load_neat_params() (in neat.cpp) and then a function from experiments.cpp based on the user's choice  
To run, use a .ne file as the parameter. For cMake, the **path** is **../__.ne**      