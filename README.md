# Lab: Class 11: Numpy Arrays

## GitHub Pull Requests:
[https://github.com/joseph-zabaleta/chess-board/pull/1}](https://github.com/joseph-zabaleta/chess-board/pull/1)  


## Overview  
This project is about constructing a chess board like its 1980. No prebuilt images just the power of arrays and pixel art.

## Feature Tasks and Requirements  
Your job is to render out chess boards with red and blue queens on them.

Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

- [x] Define a `ChessBoard` class  
  - [x] should have `add_red` method that accepts a row and column as input.  
  - [x] should have `add_blue` method that accepts a row and column as input.  
  - [x] should have `render` method that displays the chress board on screen with red and blue shown in correct locations.  
  - [x] should have `is_under_attack` method that returns boolean if red is under attack by a blue piece horizontally, vertically, or diagonally.  

## User Acceptance Tests 
- [x] Queens on the same row should be "under attack".  
- [x] Queens on the same column should be "under attack".  
- [x] Queens on the same diagonal should be "under attack".  
- [x] Queens with any other coordinates should NOT be "under attack".  

## Dependencies  
- poetry  
- python 3.8.2
- numpy
- matplotlib
- jupyterlab

## Authors  / Collaborators
- Software Developer: Joseph Zabaleta
  - [Official Github](https://github.com/joseph-zabaleta)  

## License  
This project is under the MIT License.

## Acknowledgements / Resources  


## Version History  
- 1.0.0 20200525 1200
    - Initial files created.