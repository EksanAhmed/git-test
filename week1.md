**1.What is a Full Stack Web Developer?**
***Summary:*** 
Full Stack Developer means a person who has the knowledge of the 3-tier Architecture. In short we can say 
someone who is has both front end and backend knowledges.

3--tier Architecture consists of three layers. They are :
    1.Presentation Layer.
    2.Business Logic Layer
    3.Data Access Layer.

**Presentation Laye**r: It is basically the UI/UX design of a website. How should the website look in the browser 
and how can user interact with the website it is maintained in this layer. The Front End Developers handles this
layer. they need to have knowledge about 

    * HTML * CSS & * JavaScript

**Business Logic Layer**: It is basically the connecting part between the Presentation layer and data accessing layer.
It is part of the backend development where knowledge about any server side language(python,ruby,node.js etc) is required to 
communicate with the database to collect and send information to the database. Sending the response of a request from the database is 
done in this layer.

**Data Access Layer**: It is mainly the Database where everything is stored. Data is collected and stored in this layer.It is also
a part of backend developer jobs to have knowledge of database related things like( MongoDB, SQL , ORM).

So in a nutshell Full Stack Developer has both the frontend and backend knowledge. Full Stack developer builds a full website from scratch 
both the  front end part and the backend part.

**Git**:
software that enables us to manage source code.it helps us to store our code and handle any changes in the code.
checking git version: (git --version)
configuring username and email:
    git config --global user.name "Eksan Ahmed"
    git config --global user.email  eksanemon@gmail.com
to verify config success:
    git config --list

**Initializing current folder as a git repository** :
    git init (master)

**current status of the folder:**
    git status

**adding file to git repository**:
    git add . (all the files will be added to repository)

**to commit**:
    git commit -m "message"

**brief log of all the commits:**
    git log --oneline
    git log (for details)

**going back to previous version**:
    git checkout (commit identifier number) filename(like->index.html)

**to reset early things** : (unstaged changes)
    git reset HEAD filename(index.html)
    git checkout -- filename (restores the deleted things)

**Online Git Repository**:
**to connect with the online repositor**y:
    git remote add origin <"repository url">

**pushing to online repository**:
    git push -u origin master

**how to clone online repository in local computer**:
    git clone <repository url>

**Initializing package.json** :
    npm init 

**installing npm module**:
    npm install lite-server --save-dev 