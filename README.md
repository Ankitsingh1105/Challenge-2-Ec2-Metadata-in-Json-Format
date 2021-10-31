# Ec2-Metadata-in-Json-Format

## Before you begin:
Make Sure the script have permission to execute.
Ec2 instance has active internet connection and there are no rules to deny connection to http://169.254.169.254.

## Description
The script provides the metadata of an ec2 instance on the ec2 server. The script also allows for a particular data key to be retrieved individually 
It provides the output in json format.

## How to Run the script
Run the script in default mode i.e without passing any arguments and then select from the list of choices to get your required metadata.
Run the script with the predefined arguments to get the desired output. For example use the argument scriptname.sh --all to see complete metadata of that ec2 instance.
Please use --help to see complete list of arguments. 
