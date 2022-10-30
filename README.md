Summary:
Phylotrees was piece of software designed by UVic students Nabil Nazri and Mattias Park. The software, which runs on python and utilizes libraries such as Tkinter (to build a GUI), and Biopython (to Graphically present phylogenetic trees), was aimed at teaching and helping individuals -- primarily students -- solve genetic multiple sequencne alignments. This was a last-year special-option course research project. The job was to pick a topic and explore solutions or investigate a question. We decided to build a Multiple Sequence Alignment tool because there is a lack of teaching resources online for the layments computer science student when it comes to computational biology.


IMPORTANT Disclaimer:
1-
The UPGMA algoritm 100% works for all inputs. 
The GUI example though is only optimized for the presentation example. E.g the highlighted values and descriptions in the GUI. 
The graphic phylogenetic tree presentation is accurate because it uses biopython.

2-
The neighbor joining algorithm works for all inputs.
The GUI example though is only optimized for the presentation example. E.g the highlighted values and descriptions in the GUI. 
The graphic phylogenetic tree presentation is not accurate because it was never ported 100% by the preseentation date to use a rooted tree presentation. neighbor joined trees are usually unrooted.


The Video Presentation + Instructions to Run:
https://drive.google.com/file/d/1cScnkeiHjp30FR-zMcvX-D_ktTfWmZLK/view?usp=sharing

Instructions:
1) Go to V4 or V5 Directory
2) Run e.g phyloTreesV4.py or phyloTreesV5.py file
3) Delete any and all output files after done using tool


The Research Report:
https://docs.google.com/document/d/1xhVP52scvCidJxUQFbUWD1wTbqoxrWKnoy6eEmm0EwE/edit?usp=sharing

Rough Rough Rough Planning Examples:
https://docs.google.com/document/d/1mJhWyzTgLAe2e1yvas1c4oGi-D_qrmUvZ85XisgJbgI/edit?usp=sharing


What we built:
1) The GUI
2) The UPGMA algorithm implementation
3) The tool's logic and design


What was borrowed (other people's work and significant libraries used):


1) Biopython
https://biopython.org/

2) Tkinter
https://docs.python.org/3/library/tkinter.html

3) The neighbor joining implementation
https://github.com/sness/courses/blob/master/neighbour-joining.py

Other dependencies (Use pip to install them):
- pydot
- graphviz
- pillow
- etc.


Main Menu:
![Menu](https://github.com/Nabildexter/CSC482B)/MainMenuSample.jpg?raw=true)

Sample Input:
![Input](https://github.com/Nabildexter/CSC482B)/MainMenuOptions.jpg?raw=true)
![Input](https://github.com/Nabildexter/CSC482B)/ChooseInput.jpg?raw=true)
![Input](https://github.com/Nabildexter/CSC482B)/SampleInput.jpg?raw=true)


Sample Outputs:
![Output](https://github.com/Nabildexter/CSC482B)/Output1.jpg?raw=true)
![Output](https://github.com/Nabildexter/CSC482B)/Output2.jpg?raw=true)