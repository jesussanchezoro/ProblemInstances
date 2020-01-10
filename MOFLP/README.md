# Description of MOFLP files

## Instances
- The instance files are stored in the `instance` folder
- File format:
  - The first line contains four integers, which corresponds to `m n p r`
  - The next `m` lines contains information about the candidate location to host a facility:
    - Each line is conformed with two floats that identifies the x and y coordinates
  - The next `n` lines contains information about the demand points:
    - Each line is conformed with two floats that identifies the x and y coordinates and an integer that represents the weight of the demand point (1 in all the examples)

## Efficient fronts
- The efficient fronts obtained by our algorithm are stored in the `pareto_front` folder
- File format:
  - Each line represents the three objective function of the point (PMP, MCLP, PCP)
