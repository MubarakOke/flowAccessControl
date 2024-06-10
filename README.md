# Register Contract on Flow

Project: Using Structs

## Description

This is a Project Built on Flow, This project explains different level of access for different variables and function in different area

## Getting Started

### Structure
    - Contracts
        This folder contains the `SomeContract.cdc` contract, the contract contains 4 variables readable and settable in different areas, also contains 3 functions callable in different areas 
    - Scripts
        This folder contains `SomeContractScript.cdc` script, which showcase another area scope, for reading and settinf variables and also for calling functions.
        
### Code Walkthrough program
    - Variable a
        - Read Area 1,2,3,4 - Set Area 1,2,3,4
    - Variable b
        - Read Area 1,2,3,4 - Set Area 1
    - Varaiable c
        - Read Area 1,2,3,4 - Set Area 1,2,3,4
    - Varaiable d
        - Read Area 1       - Set Area 1
    - function publicFunc
        - Callable Area 1,2,3,4
    - function privateFunc
        - Callable Area 1,2,3
    - function structFunc
        - Callable Area 1

## Authors

Contributors names and contact info

ex. Okeola Mubarak  
ex. [@Mubie_X](https://twitter.com/mubie_X)


## License

This project is licensed under the MIT License 
