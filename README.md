# FMS_Group8_Project_Part_1-2

This is the code of our project(both parts).

## Environment

Python 3.6  (see `requirements.txt`)

# For Part 1

See `Roll_Two_Dice.ipynb`.

### How to run

Run `Roll_Two_Dice.ipynb` step by step.

### Results

The result is saved in `./figure_part_1`.

### Important method and class

| `class Die`                                                  | The class of one die (default sides = 6)                 |
| ------------------------------------------------------------ | -------------------------------------------------------- |
| `roll_n_times(roll_times)`                                   | roll two dice for `roll_times `                          |
| `plot_fX_x(save_figure=True)`                                | plot the CMF of X                                        |
| `plot_relative_frequency_diagram(dict_res, n_trial, save_figure=True)` | plot the diagram of rolling two dice for `n_trial` times |
| `compute_average_sn(list_res)`                               | compute the average of $S_n$                             |
| `compute_variance_sn(list_res)`                              | compute the variance of $S_n$                            |
| `normfun(x, mu, sigma)`                                      | norm function                                            |
| `simulate_m_groups_n_samples`                                | the last simulation                                      |

## For Part 2

See `Least_Squares.ipynb`.

### How to run

Run `Least_Squares.ipynb` step by step.

### Results

The result is saved in `./figure_part_2`.

### Important method and class

| `linear_fit(x, y)`              | $y = a_1x+a_0$                                               |
| ------------------------------- | ------------------------------------------------------------ |
| `quadratic_fit(x, y)`           | $y = a_2x^2+a_1x+a_0$                                        |
| `cubic_fit(x, y)`               | $y = a_3x^3 + a_2x^2+a_1x+a_0$                               |
| `poly_fit(x, y, k)`             | $y = a_kx^k + \ldots + a_2x^2+a_1x+a_0$                      |
| `cos_sin_fit(x, y, k)`          | $y = a_0 + a_1cosx+a_2sinx + \ldots + a_{2k-1}cos(kx) + a_{2k}sin(kx)$ |
| `ln_fit(x, y)`                  | $y = a \ln(x) + b$                                           |
| `plot_poly_fit(x, y, coeff)`    | plot the polynomial with coefficients `coeff`                |
| `plot_cos_sin_fit(x, y, coeff)` | plot the cos&sin with coefficients `coeff`                   |
| `plot_ln_fit(x, y, coeff)`      | plot the $\ln(x)$ with coefficients `coeff`                  |