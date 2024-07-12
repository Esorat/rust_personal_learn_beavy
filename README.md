# Bevy Job System

This project demonstrates a simple entity-component-system (ECS) job system using the Bevy game engine. It includes functionalities to manage people with and without jobs, print their names, and describe their occupations. The main components and systems are as follows:

## Components

1. **Person**: Represents a person entity with a name.
2. **Employed**: Associates a job with a person entity.
3. **Job**: Enum defining different job types (Witch, Botovod, FireGuy).

## Systems

1. **setup**: Initializes the game state by spawning person entities, some of which have jobs.
2. **print_names**: Prints the names of all person entities.
3. **people_with_jobs**: Prints the names of all employed person entities.
4. **people_ready_to_hire**: Prints the names of all unemployed person entities.
5. **person_does_job**: Prints the job description of all employed person entities.

## Getting Started

To run this project, ensure you have Rust and Bevy installed. Clone the repository, navigate to the project directory, and execute the following command:

```sh
cargo run


## Example Output

Name: Alex
Name: Bobba
Name: Puma
Name: Marina
Alex has a job
Bobba has a job
Puma has a job
Marina ready to hire!
Alex is a Botovod.
Bobba is a FireGuy.
Puma is a Witch.

This project serves as a basic introduction to Bevy's ECS pattern, demonstrating how to manage and query components effectively.

