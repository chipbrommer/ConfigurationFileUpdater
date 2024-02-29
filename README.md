# ConfigurationFileUpdater

A simple JSON file updater that will receive a filepath via argument or display the list of pre-declared files for the user to update. 

Utilizing a simple UI and some recursion, the user is prompted with the ability to update information in the json with safety knowing 
inputs will be validated for the appropriate type, preventing any errors. 

Current handled data input 'types'

    - String
    - Boolean
    - Integer
    - Float
    - Object
    - Array

This is a great utility for embedded systems where you want to prevent a user from making costly errors to the format of a configuration file. 