# CGI Polymer Codelab

This tutorial is aimed at developers who are familiar with HTML, CSS and 
JavaScript and would like to start working with Polymer. The Tutorial takes
the form of a Codelab app that you can download and install. While talking 
you though the various aspects of Polymer, we provide the opportunity to 
update the app itself, so that you can see what the effect is.  

To work with the Codelab we have to install some tools. This might take 
15 mins. Git uses port 443, so make sure your not behind a firewall.
From the command prompt:

#### Git

See if you have Git installed already: `git --version`. If not, you can install 
it from here: [Git install](https://git-scm.com/download/win).

#### Nodejs

See if you have Nodejs installed already: `npm --version`. If not, you can install 
it from here: [Nodejs install](https://nodejs.org/en/).

You may have to restart your command prompt for the global installs to tale effect.

#### Bower

See if you have Bower installed already: `bower --version`. If not, you can install 
it by executing this command:
 
    npm install -g bower

#### Polymer CLI

See if you have the Polymer CLI installed already: `polymer --version`. If not, you can install 
it by executing this command:
 
    npm install -g polymer-cli

#### Clone the Codelab app

Execute this command to install the app: 

    git clone https://github.com/CGIGroup/polymer-codelab.git

#### Start the app

Now we can start the Codelab app: 

    cd polymer-codelab
    polymer serve

Open it in your browser:  [http://127.0.0.1:8080](http://127.0.0.1:8080) 
(your Polymer server might be running on a different port)
