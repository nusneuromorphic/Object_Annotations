# Object_Annotations
This repository contains object annotations for various recordings from the Event Camera Dataset from iniLabs: http://rpg.ifi.uzh.ch/davis_data.html

Ground Truth Format

The format of the text files is as follows.

    DATASETFILENAME_OBJECT.txt: One bounding box location per line (timestamp x y width height)

The 'dynamic_translation', 'dynamic_rotation' and 'dynamic_6dof' recordings from the event camera dataset were used to annotate  five objects in the office scene namely, the head of a person in the recording ('HEAD'), a static drone lying on a table ('DRONE'), a stack of books ('BOOKS'), a computer monitor ('MONITOR') and a drinking cup ('CUP'). 

If you use these annotatations, cite the paper below:

“Long-term Object Tracking with a Moving Event Camera”, Bharath Ramesh, Zhang Shihao, Jonathan Lee Wei, Zhi Gao, Garrick Orchard and Xiang Cheng, British Machine Vision Conference (BMVC 2018) .

