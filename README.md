# Travel-Journal-using-React.
my travel journal A travel journal, also called road journal, is a record made by a traveller, sometimes in diary form, of the traveler's experiences, written during the course of the journey and later made with React.JS


Installation Information
Fork this repository to your own account.

Clone the Forked repository:

git clone https://github.com/BaburshahSayer/Travel-Journal-using-React..git
After cloning, now run cd aop-application-boards-system and get into your newly cloned local repository/folder.

Download and install Node.js from Nodejs. The suggested version to install is 14.16.x LTS.

Install the latest NPM:

npm install --global npm@latest
To install Composer globally, download the installer from https://getcomposer.org/download/ Verify that Composer in successfully installed, and version of installed Composer will appear:

composer --version
Install Composer dependencies.

composer install
Install NPM dependencies.

npm install
The below command will compile all the assets(sass, js, media) to public folder:

npm run dev
Copy .env.example file and create duplicate. Use cp command for Linux or Max user.

cp .env.example .env
Create a table in MySQL database and fill the database details DB_DATABASE in .env file.

The below command will create tables into database using Laravel migration and seeder.

php artisan migrate:fresh --seed
Generate your application encryption key:

php artisan key:generate
Start the localhost server:

    php artisan serve
You can now visit the app in your browser by visiting http://127.0.0.1:8000.

Good Practices
Before doing fetching any records from upstream or pushing, always check if you are in the right branch. You can see what branch you are in by running the following command: git branch

Before doing any new work, always run git fetch upstream and then git merge upstream/master on the master branch. If you are not in the master branch, simply run get checkout master first to make sure you are in the master branch.

Keep every commit and its message meaningful and relevant.

Keep your PR titles meaningful and relevant.

Always include ifix- before your branch names. That’s our common pattern. i there is issue and fix is the fix you are providing.
