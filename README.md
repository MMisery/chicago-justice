chicago-justice
===============

Crime, Punishment and Discretion in Chicago

## Previewing

You can see the current version of this website here: http://chicago-justice.smartchicagoapps.org/.




## Local Development

### Getting Tarbell
First, make sure you have [Tarbell](http://tarbell.tribapps.com/) installed and setup. 

If it's not already installed, here's the two steps you need to get it:  

    sudo pip install tarbell==0.9b2  
    tarbell configure  

Note: When it asks you, you should set up Google Spreadsheets, but we can laeve Amazoon S3 setup for later.

### Getting the mockup

Clone the repo:  

    git clone git@github.com:bepetersn/chicago-justice.git

Do some setup and launch the Tarbell preview server:  

    cd chicago-justice  
    git submodule update --init  
    tarbell serve  

You should be able to view the results in a browser at `localhost:5000`.
