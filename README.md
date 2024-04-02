C++ ☀️ Game Text Adventure CONSOLE-MODE
Manual c++ -> https://github.com/fffaraz/awesome-cpp
Need TO install on linux:
❗ Running random scripts off the internet is generally a bad idea!
Install C++ compiler/librarys on linux using a script Script provided by David Croft (Coventry University Tutor)

wget https://git.io/vF0E1 -O - | sudo bash (Script)
sudo apt install ncurses-dev (Curses Library)
sudo apt install sqlite3-dev (SQLite Library)

❗ REMEMBER TO BE ON THE CORRECT FOLDER FRIST 
 Useful Commands:
 Easy compile(load script):
"make"

this load the makefile on the folder
to compile ->
"g++ -std=c++14 main.cpp -lsqlite3 -lncurses -o game"

after -o put the name you want to give to the executable, my case i choose 'game' -l means library to load sqlite3 (database) ncurses( is "canvas"(pointers) for console) execute ->
"./<name inputed after -o>"

If same functions on the game dont work you need to give full permission to the files/folder
"sudo chmod -R 755"

BUGS FOUND
 REAL BUG FROM bind() -> DONT ACCEPT 2 binds() with a Operation (AND,OR,BETWEEN,etc)
 Fast SOLUTION -> Use transform2Quote function (bad pratice!)
 After input a 'possibleRoute' show at position and did press ENTER again
TO DO LIST
Ideia for game-dev
 Use cordenates like [x,y] on the floor and z to indicate the floor ,Player start on 0,0,0 Up and Down (Floors), North(+y) , South(-y) , West(-x) , East(+x) , [-1,-1,z] unvaiable in all floors, when reach [x,y,z] position, that means a room, only on door location is posible to enter and LOOK for items after find n items can go up
 ❗Game Name
 ❗Game History
 Simple Design
 DB Creaction
 DB Items
 Connection to DB
 DB Options SCRUD or CRUD (Search Create Read Update Delete)
 Ranking
 Organize functions , create better algorithm, kinda like MVC design
 addScore(user,score2add)
 upLevel(user,xLevels)
 haveItem(user,item)
 Go back if wanted(Struct algorithm/Menus)
 Player info travel between cpp&&headers
 Game - GAME IDEIA ()
 Game - Children (Floor 3)
 Game - Surgery (Floor 2)
 Game - Psychiatric (Floor 1)
 Game - Lobby (Floor 0)
 Game - After found key do the maze to finish the game
 Game - Algorithm for maze creation (MAYBE, to be diferent each time start an final level)
 Game - Congratz after finish maze with Player Info
 Game - Basement (Floor -1)
 Game - Credit area
 Game - Review all stuff(Check comments on code)
❗ ❗ Important for IPP/Viva 💻

 ⚠️ Flow Diagram(Code)
 ⚠️ ER Diagram(DB)
 Screenshots of runtime game
EXTRA
 Improve Design (COLORS,etc.)
