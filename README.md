# Chapter-1-Lab-5b
Lab Goal :   This lab was designed to teach you more object oriented programming and how to write a very simple game.

Lab Description :   Complete the code for the Grid class located in Grid.java.  Test Grid using the GridTester.java file.  Grid will store Drawable references.  Drawable is an abstract class used to make game pieces for games like TicTacToe and Checkers.  

Files Needed ::
Locatable.java
Drawable.java
Nameable.java
Piece.java
Grid.java
GridTester.java



public class Grid
{
   private Drawable[][] grid;
	
   public Grid()
   {
      setSize(0,0);
   }

   public Grid(int rows, int cols)
   {
      
   }

   public void setSize(int rows, int cols)
   {
      
   }

   public void setSpot(int row,int col, Drawable val){
      
   }
	
   public Drawable getSpot(int row, int col){
      return grid[row][col];
   }
	
   public int getNumRows() {
      return 0;
   }
	
   public int getNumCols(){
      return o;
   }

   public boolean drawGrid(Graphics window){
      boolean full=true;
		
      //for loop for row
      for(int r=0;r<grid.length;r++)
      {
         //for loop for col
         for(int c=0;c<grid[r].length;c++)
         {
            
 	    //get current Drawable

	    //if it is not null
		//draw it

            //if it is null mark full as false
	  }
      }
      return full;
   }
	
   //toString
}

Sample Output ( GridTester.java )
2
2
5 5 5 5 red checker java.awt.Color[r=0,g=0,b=255] null
null null

5 5 5 5 red checker java.awt.Color[r=0,g=0,b=255] null
null 100 100 5 5 black bishop java.awt.Color[r=0,g=0,b=255]

5 5 5 5 red checker java.awt.Color[r=0,g=0,b=255] null
null 200 200 20 20 bishop java.awt.Color[r=255,g=255,b=255]


