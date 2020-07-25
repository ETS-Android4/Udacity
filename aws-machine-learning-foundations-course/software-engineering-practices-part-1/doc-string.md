Docstrings
-Docstring, or documentation strings, are valuable pieces of documentation that explain the functionality of any function or module in your code. Ideally, each of your functions should always have a docstring.
-Docstrings are surrounded by triple quotes. The first line of the docstring is a brief explanation of the function's purpose. 
-One line docstring
```
def population_density(population, land_area):
    """Calculate the population density of an area."""
    return population / land_area
```
-Multi line docstring
```
def population_density(population, land_area):
    """Calculate the population density of an area.

    Args:
    population: int. The population of the area
    land_area: int or float. This function is unit-agnostic, if you pass in values in terms of square km or square miles the function will return a density in those units.

    Returns:
    population_density: population/land_area. The population density of a 
    particular area.
    """
    return population / land_area
```