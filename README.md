# hello

## Background
As a software developer, I'm constantly reminded that the industry is in a state of perpetual evolution. To remain relevant, I need to stay up-to-date with the latest technologies, frameworks, and methodologies. This repository, `hello`, serves as a hub for my personal projects and experiments, allowing me to learn, explore, and adapt to the ever-changing landscape of software development. By sharing my journey, I hope to not only improve my own skills but also contribute to the broader community of developers. Through this repository, I aim to showcase my growth, experiment with new ideas, and stay relevant in the industry.

### Why `hello`?
Because what's more original than naming a repository after the most cliché programming phrase of all time?

## Understanding

### Submodules
Each explored technology is housed inside its own Git submodule (e.g. `hello-django`, `hello-react`, etc.). This is mentioned here for my own purposes; for future reference. These submodules don't necessarily relate to each other, although some might, but in most cases don't.

#### Creating submodules
1. Create the submodule either in GitHub or using the GitHub CLI (i.e. `gh repo create ...`).
2. Add each submodule to the `hello` repository using `git submodule add https://github.com/rclgs/hello-submodule.git hello-submodule`.
3. Initialize and update the submodules using `git submodule init` and `git submodule update`.

#### Working with submodules
1. To work on a submodule, navigate into its directory using `cd hello-submodule`.
2. Make changes, commit, and push them to the submodule's repository.
3. To update the submodule in the `hello` repository, use `git submodule update --remote hello-submodule`.
4. To commit the changes in the `hello` repository, use `git add .` and `git commit -m "Updated submodule"`.

#### Adding new submodules
1. Create the submodule either in GitHub or using the GitHub CLI (i.e. `gh repo create ...`).
2. Add each submodule to the `hello` repository using `git submodule add https://github.com/rclgs/hello-new-submodule.git hello-new-submodule`.
3. Initialize and update the submodules using `git submodule init` and `git submodule update`.
 
## Implementation
*This section will be updated as needed.*

## Lessons Learned
*This section will be updated as needed.*

## Deliverables
*This section will be updated as needed.*

