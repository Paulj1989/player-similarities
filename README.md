# Player Roles/Types & Similarities

Using FB Ref player data to measure player roles/types and identify similar players within positions, using clustering and nearest neighbors algorithms.

## Contents

- [Requirements](#requirements)
- [Project Plans](#project-plans)
  - [TODOs](#todos)
    - [Feature Selection](#feature-selection)
    - [Clustering](#clustering)
    - [Similarities](#similarities)
- [License](#license)
- [Contact](#contact)

## Requirements

This project is managed in a virtual environment, using pipenv. All packages and their dependencies can be found in Pipfile and Pipfile.lock. To create a pipenv environment and install all the packages needed to run the code in this repository, run the following in a terminal:

````bash
# install pipenv
pip install pipenv

# navigate to the repository directory
cd ~/path/to/player-similarity-clusters

# install virtual environment and dependencies
pipenv install
````

The packages required are:

- pandas
- ipykernel
- matplotlib
- yellowbrick
- scikit-learn

## Project Plans

This project is still in development.

### TODOs

#### Clustering

- [ ] Consider lasso & weighted k-means feature selection
- [ ] Look at clustering for defenders & goalkeepers
- [ ] Think about features needed for goalkeepers

#### Nearest Neighbors

- [ ] Stop the output pulling the target player when identifying similar players

## License

The data for this project is provided by FB Ref and the code used to train the clustering and the nearest neighbors algorithms is licensed under the [MIT license](LICENSE.md).

## Contact

If you have any questions or comments, feel free to contact [me](https://github.com/paulj1989) by [email](mailto:paul@paulrjohnson.net), on [Twitter](https://twitter.com/paul_johnson89), or in the [repository discussions](https://github.com/Paulj1989/player-similarity-clusters/discussions).
