
# Fountain OOO Reliving

This challenge is based on John Conway's Game of Life. Specifically, using the CPU created by the Quest for Tetris guys at https://github.com/QuestForTetris.  They discuss and describe the CPU they created to implement the Tetris Game in Game of Life at https://github.com/QuestForTetris/tetris-writeup.

This is a pure reversing challenge, as a result, by changing the appropiate cells in the CPU it would run and the flag would be in the RAM portion of the device.

The supplied file, can be loaded and run in Golly, a game of life simulator https://sourceforge.net/projects/golly/

![Fountain Zoom](https://github.com/o-o-overflow/dc2020q-fountain-ooo-reliving-public/raw/master/fountain-zoom.png)

So the simple computer that runs 60ish assembly commands, is comprised of nearly 20 billion individual cells.  However, using the abstracted VarLife rules from the Quest for Tetris developers the same computer is reduced to 800k cells.

![Fountain Zoom Varlife](https://github.com/o-o-overflow/dc2020q-fountain-ooo-reliving-public/raw/master/fountain-varlife-zoom.png)
