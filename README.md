
This is the first step to make [Silex website builder](https://www.silex.me) edit and publish P2P websites with [Beaker browser](https://beakerbrowser.com/)

CloudExplorer features include

* list and browse files and folders
* rename, delete, create files and folders
* upload files
* preview files as thumbnails or in a new tab

Test this online:

* Open [CloudExplorer online demo](https://demo.cloud-explorer.org/ce/cloud-explorer/cloud-explorer.html) in Beaker
* Click on "hyperdrive" service and choose the drive you want to browse

![Screen shot](https://user-images.githubusercontent.com/715377/98023754-ae21ff00-1e07-11eb-8690-5929212af5e7.png)


Or test this as a [Beaker ui front end](https://docs.beakerbrowser.com/developers/frontends-.ui-folder/):

* Clone this repo somewhere on you computer
* Run `npm install` and `npm start`
* Create a new drive from the `ui/` folder of the cloned repo
* Mount this new drive with the name `.ui` in one of your drives
* Display your drive, there will be a "Browse files" button, click it to see your files in CloudExplorer

In this second test, CloudExplorer will browse the files of your open drive instead of letting you choose

