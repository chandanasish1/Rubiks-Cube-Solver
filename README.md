# rubikscube-solver
## Working Example

For this example, the solver uses the IDA* (Iterative Deepening A*) algorithm with a corner pattern database for efficient solving. The program automatically:
1. Takes a scrambled Rubik's cube as input
2. Processes it using the pattern database
3. Finds an optimal or near-optimal solution
4. Displays the sequence of moves to solve the cube

The output is shown below:-

```text
chand@chand-laptop:~/ResumeProjects/Rubiks-Cube-Solver/build$ ./rubiks_cube_solver
Rubik's Cube:

       W B R
       Y W O
       Y G B

R G R  W O R  Y G W  B W G
Y G W  O R O  B B B  O O O
W W R  W R G  Y B B  R G O

       B Y O
       R Y Y
       G G Y

R D' D F B2 R U2 R B F' B2 R' L2
Rubik's Cube:

       W W W
       W W W
       W W W

G G G  R R R  B B B  O O O
G G G  R R R  B B B  O O O
G G G  R R R  B B B  O O O

       Y Y Y
       Y Y Y
       Y Y Y

L2 R F B R' U2 R' F' B2 R'
```