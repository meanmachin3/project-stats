# Project Stats

## Table of Contents
+ [About](#about)
+ [Getting Started](#getting_started)
+ [Usage](#usage)
+ [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>
`stats.sh` helps you find most committed file in a git repository. I find this script useful when you are trying to understand someone else's code base. The most committed files generally helps in understanding the core component of project which makes it easier to learn about that system. The final output is in the form of csv and contains information like filename, line of code, number of commit, first commit date, last commit date

## Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

```
bash
```

### Installing

Clone this project

```
git clone https://github.com/meanmachin3/project-stats.git
```

and then, 

```
cd project-stats
```

## Usage <a name = "usage"></a>

```sh
bash stats.sh /rails-project "rb" "haml" "coffee" "scss" > rails_project.csv
```

