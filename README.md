# COMP3104_Group41_Assignment

## Group Members

- **Leader:** Diego Tsukayama (101472085) - [GitHub](https://github.com/DiegoHidenori)
- **Member 2:** Liz Cruz (101470163) - [GitHub](https://github.com/qanntu)
- **Member 3:** Kaman Wong (101424041) - [GitHub](https://github.com/KamanWong0317)
- **Member 4:** Naomi Teklu (101441399) - [GitHub](https://github.com/naomitek)
- **Member 5:** Illia Konik () - [GitHub](https://github.com/xxxxxx)
- **Member 6:** Hooman Hafsharnia (101466119) - [GitHub](https://github.com/ItsHooman)

## Project Description

This repository hosts the group assignment for COMP3104 DevOps course, focusing on
collaborative Git workflows, branching strategies, and CI/CD integration.

## Setup Instructions

1. Clone the repository using `git clone https://github.com/YourUsername/COMP3104_Group41_Assignment.git`.
2. Navigate to the repository using `cd COMP3104_Group41_Assignment`.
3. Create and switch to your branch using `git checkout -b STUDENTID-Name`.
4. Install any dependencies as listed.
5. Push the personal branch to GitHub using `git push -u origin STUDENTID-Name`.

## CI/CD Pipeline

The project utilizes GitHub Actions for continuous integration.
The workflow is defined in `.github/workflows/ci.yml`.

## Branching Strategy

- The main branch is the official code for the group.
- Each member has their own branch, which then the changes are merged to the main branch.
  - Create a personal branch with `STUDENTID-NAME` naming convention.
- Regularly pull the main branch to make sure the local main branch is up-to-date.
  - Then switch to personal branch and merge the main branch to it.
- First make changes to the personal branch. Then you can push it to the remote personal branch.
  - Then, switch to the main branch and pull from the remote main branch to stay up-to-date.
  - Then, merge the local personal branch to the local main branch.
  - Finally, push the local main branch to the remote main branch.
