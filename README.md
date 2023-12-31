This Python package is intended to be used for zero-sum (=antagonistic) matrix game solving and visualization of the solutions. <br>

See [the Jupyter notebook](https://github.com/oscar-foxtrot/antagonistic_game_solver/blob/main/Workflow.ipynb) for examples and illustrations 🎨 <br>

How to install? <br>
**pip install antagonistic_game** <br>

What to include? <br>
from antagonistic_game.matrix_game import nash_equilibrium <br>
from antagonistic_game.matrix_game import visualize <br>

How does it work?
- "nash_equilibrium" function solves the game. Takes a np.ndarray matrix representing the game and returns the game solution as a tuple: game value, first player's optimal strategies and the second player's optimal strategies. <br>
nash_equilibrium(payoff_matrix: np.ndarray) -> Tuple[float, np.ndarray, np.ndarray] <br>
- "visualize" function visualizes solutions. Takes two parameters: the game matrix and a tuple of 2 elements: a numpy array of the first player's strategies and a numpy array of the second player's strategies. <br>
visualize(matrix: np.ndarray, spectrum: Tuple[np.ndarray, np.ndarray]) -> None <br> <br>
Enjoy using ❤️

