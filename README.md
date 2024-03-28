# Android Github Workflow And Actions For CI CD 🤖

## Workflows
  A workflow is a configurable automated process that will run one or more jobs. Workflows are defined by a YAML file checked in to your repository and will run when triggered by an event in your repository, or they can be triggered manually, or at a defined schedule.

## Workflow basics
A workflow must contain the following basic components:
  - One or more events that will trigger the workflow.
  - One or more jobs, each of which will execute on a runner machine and run a series of one or more steps.
  - Each step can either run a script that you define or run an action, which is a reusable extension that can simplify your workflow.

![image](https://github.com/SandeepSatpute9271/AndroidCICD/assets/13411996/f8d8fce7-1047-426e-8c8b-03f2129cbea9)

## Steps To Create Workflow
  - create the .github/workflows/ directory to store your workflow files.
  - In the .github/workflows/ directory, create a new file called main.yml.
  - Add a code in main.yml for the following steps
    - Cancel the previous build
    - Lint check
    - Unit test
    - Instrumental Test
    - Generate Build
   
![Screenshot 2024-03-20 095619](https://github.com/SandeepSatpute9271/AndroidCICD/assets/13411996/b88c26b1-5077-49b6-9dd0-4c64ef7bd8ed)

## Artifacts
Artifacts Produced during runtime
![Screenshot 2024-03-20 095652](https://github.com/SandeepSatpute9271/AndroidCICD/assets/13411996/b0138166-da6d-4134-8c3e-6334b1cc8684)




## Thanks For Your Time  🤝

Feel free to for any bugs/improvements.
