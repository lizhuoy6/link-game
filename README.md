# link-game

Team Member A 
Zhuoying Li
1004021202
zhuoying.li@mail.utoronto.ca

Team Member B 
Bolun Liu
1004701799
bolun.liu@mail.utoronto.ca

Team Member C
Xiangjun Wang
1005362475
xiangjun.wang@mail.utoronto.ca 

Team Member D
Weihong Kuang
1006428670
kayley.kuang@mail.utoronto.ca


In this week, we considered the prototype of our program and implemented the displaying of beginning of the game.

We are planing to implement a link game using a 4x4 matrix, this matrix is consisted with several characters. While playing the game, players can select two same and "connected" characters to be cleared, thus to get scores.

Characters in the matrix can be 'A', 'B', 'C', 'D' and 'E', we use random in python to generate a 4x4 matrix. random.random() function can return a number in range of [0, 1), times by 4 we get a number in range of [0, 5), using this number as the index to select a character in list ['A', 'B', 'C', 'D', 'E']. By doing this for 16 times, we get 16 characters, then they are arranged as a 4x4 matrix.

While the game running, we plan to use a while loop to refresh the displaying. os.system('cls') is used to clear the screen.
