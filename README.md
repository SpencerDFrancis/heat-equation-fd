# Heat Equation Solver
This code generates solutions to the 1D and 2D heat equations given an initial condition in rectalinear coordinates.

## How to use this code
To use this code, create an initial condition in the form of a .csv file in rectalinear coordinates; the simplest way to construct this is as an Excel file. There are two baseline initial conditions provided:
1. A one-dimensional rod with fixed temperature at each end
2. A two-dimensional plate with fixed temperature at each edge

These may be modified or replaced. The notebook demarcates cells which require user input or adjustment with the & character. The code automatically checks the CFL condition based on the timestep and spacial resolution provided, and will warn the user if proceeding with an unstable setup.

*This project was intially created as a part of a graduate computational physics course taught by Prof. Loukas Gouskos at Brown University.*
