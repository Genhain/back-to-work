# Getting Started

Hi Ben. Find below a list of tasks which will give you the necessary skills in order to get back into a work enviroment.

For each task please fork the repo, create a branch (E.g. task/one), code, create a pull request. I'll then review the code and asked for any changes.

## Tasks

### Recreate NSNotificationCentre
Please recreate the NSNotificationCentre and NSNotification functionality. You should write tests which show the class is functioning how it should

### Creating a background downloader
Create a set of classes which will allow the background downloading of HTML files from a given URL.

#### UI

* UITextField to enter URL
* UIButton to start the download -> Added the download into the UITableView
* UITableView which holds all of the downloads which have been started/completed (UI layout will follow)
* If a download is currently in progress the user should be able to click a 'cancel' button on the cell and thus cancel the download
* UILabel (Inside the cell) to display to display the total size (if avalible) and how far we are through the download

#### Flow

* User should enter a url
* User should click start
* An entery will be added into the UITableView
* User can click 'cancel' -> UITableView will say 'Cancelled' and the download will be cancelled
* Download will finished and say 'completed', Cell can then be clicked and will show a new ViewController with the HTML inside a UITextView
