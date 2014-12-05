Checkers
==============

Complete the following classes to make the checkers program functional:

## Complete the class CheckersMove (CheckersMove.java)
A CheckersMove object represents a move in the game of Checkers. It holds the row and column of the piece that is to be moved and the row and column of the square to which it is to be moved. (This class makes no guarantee that the move is legal.) This class should properly implement **encapsulation and abstraction**.

### Fields
Create 4 integer fields that represent the row & column a piece is being moved from and the row & column a piece is being moved to. 

### Constructor 
Create a single constructor that takes 4 integer parameters (from row, from column, to row & to column) and assigns their values to the class fields from row, from column, to row & to column

### Accessors 
- create an accessor method for each field. They *MUST* be named: **getFromRow**, **getFromCol**, **getToRow** & **getToCol**
- create a boolean accessor, **isJump**, that tests whether this move is a jump.  It is assumed that the move is legal.  In a jump, the piece moves two rows.  (In a regular move, it only moves one row.)

## Complete the class CheckersData (CheckersData.java)
- complete method **pieceAt**: return the contents of the square in the specified row and column.
- compete method **setPieceAt**: set the contents of the square in the specified row and column.
- complete the public method **makeMove**: call this class' private method makeMove(int fromRow, int fromCol, int toRow, int toCol)

