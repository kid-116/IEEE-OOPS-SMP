# Assignment 1
> Go through the README.md for the submission format

Objective: To create a chess board using OOP.

Instructions:  
* The chess board has to be an object with the following members:  
    * **Attributes:**
        * **board:** An 8x8 matrix representing the board of type **spot** (Go to next instruction for spot class)
    * **Constructor:** *(To be done in future assignments)* Initializes the board with the pawns in appropriate positions.
    * **Behaviours:**
        * **getSpot():** Gets the spot assigned to the given row and column.
        * **getPawn():** Gets the pawn assigned to the given row and column.
        * **setPawn():** Places the given pawn into the spot specified by the coordinates.
        *  **movepawn():** takes 3 arguments - The pawn object, intitial location, final location and moves the pawn accordingly.
        * **isValid():** checks if the move is valid. Validity of a move can be looked up on the net
        * **kill():** takes one argument - the pawn object to be killed. Destroys the object



* Spot object should consist of the following:
    * **Attributes:**
        * **pawn:** pawn object to be placed in the spot
        * **color:** color could be black or white
        * **row:** row number of this spot
        * **column:** column number of this spot
    * **Constructor:** to set the row, column, color and pawn to be placed in the spot(the pawn could be Null)
    * **Behaviours:**
        * **getpawn():** returns the pawn placed in the spot
        * **setpawn():** sets the pawn placed in the spot by taking an argument.
        * **getColor():** returns the color of the spot
        * **setColor():** sets the color of the spot
        * **getRow()**
        * **setRow()**
        * **getColumn()**
        * **setColumn()**

* The attributes should not be accessible from anywhere outside the class definition, only the behaviours should.
        

        