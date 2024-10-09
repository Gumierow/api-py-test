# Description

It's a trained model using Python and Machine Learning libraries that recommends movies to users. The model will rate previously user's experience based on `duration`, `director`, `gender` and `media_type`.

The application must be built using Python (if necessary Flask to build an API Rest), simple datasets and machine learning/AI libraries. 
SHOULD follow a code architeture that keeps SOLID principles working and scripts organized.
Uses GitFlow correctly


# Git PR's pattern

- To open PR's, ALWAYS open two:
    - The first one is pointing to `develop`. Follow: `[develop] - <what-you-done>`
    - The seconde one is pointing to `main`. Follow: `[main] - <what-you-done>`.

    -> Code review will be make in develop one, passes, and if tests passes, accept PR to main branch.

- Keep branch names short as possible and objective names. For example, to create initial setup, the branch should be named as `1-initial-setup`