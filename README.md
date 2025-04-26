# cop3502-lab-05-connect-four-solved
**TO GET THIS SOLUTION VISIT:** [COP3502 Lab 05:Connect-Four Solved](https://www.ankitcodinghub.com/product/cop3502-lab-05connect-four-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;33488&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3502 Lab 05:Connect-Four Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
Overview:

This lab is designed to introduce students to 2-D arrays by recreating one of everyone’s favorite childhood games: Connect-Four. You will loop through arrays, and manipulate them. Your end product should be robust enough to not have a single ArrayIndexOutOfBounds Exception!

Specification:

You will first start by asking the user for what they wish the height and length of the board to be:

What would you like the height of the board to be? 4

What would you like the length of the board to be? 5

Then you will print the empty board:

———

———

———

———

And tell the players what their tokens are:

Player 1: x

Player 2: o

The players will take turns placing their tokens by choosing columns…

Player 1: Which column would you like to choose? 0

—–

—–

—–

x—-

Player 2: Which column would you like to choose? 3

—–

—–

—–

x –o-

…until one of them wins!

Player 1: Which column would you like to choose? 0

x —-

x —-

x -o–

x o x o o

Player 1 won the game!

Or until there is a tie!

Player 2: Which column would you like to choose? 2

o x o x o

x o o x x

x o o o x

x o x o x

Draw. Nobody wins.

Elements in the array should be accessible via row-major indexing (board[row][column]). In addition, the data should be stored so that row zero is the bottom of the board, i.e.:

Row 3&nbsp; x—-

Row 2 x—-

Row 1 x-o–

Row 0 x o x o o

Make sure you test this along the way! Otherwise, your method tests in ZyBooks will fail!

Assumptions:

Students can assume that:

-the user will choose for the board dimensions to be 4×4 or greater.

-the user will input a valid column number (from 0 to length-1).

-the column that the user chooses to place their token into has space (it is not filled already by other tokens).

-players can only win vertically or horizontally, but not diagonally.

Required Methods

public staticvoidprintBoard(char[][]a<wbr>rray)This will print the board.public staticvoidinitializeBoard(char<wbr>[][]array)This will set each spot in the array to “-”.

public staticintinsertChip(char[][]ar<wbr>ray, int col, charchipType)Places the token in the column that the user has chosen. Will find the next available spot in that column if there are already tokens there. The row that the token is placed in is returned.

public staticbooleancheckIfWinner(cha<wbr>r[][] array, int col, int row, charchipType) After a token is added, checks whether thetoken in this location, of the specified chip type, creates four in a row.Will return true if someone won, and falseotherwise.

Hint: Implement the methods in this order.

Submission

NOTE: Your output must match the example output *exactly*. If it does not, you will not receive full credit for your submission! Files:ConnectFour.javaMethod:S<wbr>ubmit on ZyLabs

Sample Output What would you like the height of the board to be? 4

What would you like the length of the board to be? 5

—–

—–

—–

—–

Player 1: x

Player 2: o

Player 1: Which column would you like to choose? 0

—–

—–

—–

x—-

Player 2: Which column would you like to choose? 3

—–

—–

—–

x–o-

Player 1: Which column would you like to choose? 0

—–

—–

x —-

x–o-

Player 2: Which column would you like to choose? 1

—–

—–

x —-

x o-o-

Player 1: Which column would you like to choose? 0

—–

x —-

x —-

x o-o-

Player 2: Which column would you like to choose? 4

—–

x—-

x—-

x o-oo

Player 1: Which column would you like to choose? 2

—–

x —-

x —-

x o x o o

Player 2: Which column would you like to choose? 2

—–

x—-

x-o–

x o x o o

Player 1: Which column would you like to choose? 0

x —-

x —-

x -o —

x o x o o

Player 1 won the game!

Process finished with exit code 0
