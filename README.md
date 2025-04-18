# Documentation for Modifying the Website

## Website Editting

**If you are unfamiliar with coding:**
* Follow **How To's** below and edit the corresponding files on Github directly.

**If you have experience with coding:**
* Follow instructions on [this page](https://wowchemy.com/docs/install-locally/) to install hugo and dependencies
* cd into a directory you want to have the file in
* git clone https://github.com/UofTActuarial/UofTActuarial.github.io.git
* cd into the UofTActuarial.github.io folder
* `hugo server` which allows you to view changes on the localhost first.
* Check it is up and running at localhost:1313
  *  If you encounter the error `hugo academic failed to extract shortcode: template for shortcode "callout" not found`, do:
      ~~~
      hugo mod clean
      hugo mod get -u ./...
      ~~~
* Install the text editor of your choice
* Create branch for the repository and open the branch in vs code
* Page about website structure: https://wowchemy.com/docs/get-started/

## How To's

### Edit Personal Profiles:

* Personal profiles are located in content\authors.
* To create a new profile:
  * Copy the Profile-Template folder, paste and rename it as your Firstname-Lastname.
* Once your profile folder is created, change the _index.md file in your folder.  In particular, fill in the following fields (please refer to the markdown file for field descriptions):
  * title - required
  * weight - required, for correct ordering
  * authors - required
  * names - required
  * role - required
  * interests - optional
  * education - optional
  * social - recommended
  * user_groups - required
  * A short bio and Email at the end of the file.
* To include a profile picture, place your photo in your profile folder and rename it as avatar.
  * Since avatars are set to display as circle and center, make sure your face is relatively centered in your photo; crop first if necessary.

### Edit List of Publications:

**If you are unfamiliar with coding:**

* All publications are stored in publications.bib located at the root folder.
* To add a publication, input the reference in bibtex into publications.bib.
  * Modify the title if necessary, e.g. citations downloaded from ASTIN have the whole title capitalized.
  * Inclusion of the abstract is encouraged - it will be displayed on the publication's individual page.
* Contact the website manager to update the list on the website.

**If you have experienced with coding:**

* Prerequisite:
  * To edit the list of publications, please install and use the [Academic Import](https://github.com/wowchemy/hugo-academic-cli/#usage).  It uses [Python 3.6+](https://realpython.com/installing-python/), so install if it's not already installed.
  * Open your Terminal or Command Prompt app and install the Academic CLI tool: 
    ~~~
    pip3 install -U academic
    ~~~
* All publications are stored in publications.bib located at the root folder.
* To add a publication, input the reference in bibtex into publications.bib.
  * Modify the title if necessary, e.g. citations downloaded from ASTIN have the whole title capitalized.
  * Inclusion of the abstract is encouraged - it will be displayed on the publication's individual page.
* Once publication(s) are added/modified, open your Terminal or Command Prompt app and cd into the UofTActuarial.github.io folder.  Run the following:
  ~~~
  academic import --bibtex publications.bib --overwrite
  ~~~
  A folder for each of your publication will be added under content\publication; the folder name automatically replaces any underscore(_) with hyphen(-).
* To include a pdf of a publication, place the pdf file in the corresponding folder and rename it the same as the folder name.

### Edit List of Softwares:

* Software pages are located in content\software.
* To create a new software page:
  * Copy the template folder, paste and rename it as the package's name.
* Once the package folder is created, change the index.md file in the folder.  In particular, fill in the following fields:
  * title - required
  * summary - required
  * date - required, for the page to show
  * A description at the end of the file.

## More on the Website Design (Skip for Non-website managers)
### Website Structure Overview

* The general file structure looks like this: https://wowchemy.com/docs/get-started/#remove-any-unused-example-pages
* You can figure out which folders correspond to which tabs on the menu by looking at menus.toml under config\_default
  * for example the "People" tab can be accessed via <website url>/People-UofTActuarial and the web code for the content of the page is found under content/People-UofTActuarial
* Individual webpages are built using the index.md or _index.md file in the content folder. There are two types of index file:
  * _index.md: it is a simple functionality that displays the rest of the content from the folder based on the view style chosen. It is flanked by "---" at the start and end of the file. Example:

    ~~~~
    ---
    title: Publications
    # View.
    #   1 = List
    #   2 = Compact
    #   3 = Card
    #   4 = Citation
    view: 1
    # Optional header image (relative to `static/media/` folder).
    header:
      caption: ""
      image: ""
    ---
    ~~~~
  
  * index.md: It is a widget page (A page that will include widgets). The page is flanked by "+++" at the top and bottom. Example:

      ~~~~
      +++
      # People
      type = "widget_page"
      headless = false  # Homepage is headless, other widget pages are not.
      +++
      ~~~~

* Widgets

  Widgets are functions which take in parameters and generate html code accordingly. There are 3 parts to a widget:

  **Widget Call:** This is an .md file in the directory where the widget is being called. E.g. publications.md in the home directory under content. It is flanked by "+++" and contains the name of the widget being called (in the example case pages), provides a series of parameters for the function to work (headless, active, weight, title, subtitle) and widget specific parameters (content.filters, design, design.background, custom css). For examples of the widget call function for each of the different widgets see /themes/academic/exampleSite/content/home and open any of the .md files other than index.

  **Widget Function:** A widget function is called based on the widget parameter in the widget call. The widget is code (Go's html/template and text/template libraries) interspersed with code to build it (you have functionality like if statements, loops, etc, for more info see: https://gohugo.io/templates/introduction/). There are two locations where the widgets are found: /themes/academic/layouts/partials/widgets or any custom widgets are found in layouts/partials/widgets.

  **Widget Data:** The widget may not have anymore data than the parameters provided in the widget call (this is the case for widgets like featurette) or they might link out to get more information (for example the people widget obtains its information by looping through all authors files and filling in the template using the information provided in the author's index file e.g. admin/_index.md)

* Partials

  Widgets are a subset of partials. Partials are html files that contain go code and are used to provide the general structure of the web page, e.g the navbar, the citation views, page footer etc. You can go in and edit them too but I suggest leaving them alone for now.

* Images

  Any image files not associated with authors should go in the static\media file. It can be called in an html image tag using "/media/example.png"

  Author images go in the file associated with the author and must be named avatar.<extension> e.g. avatar.png or avatar.jpg

* CSS

  Like most website there are css files. You can go in and edit them to change the way the page appears. Better practice is to use the file for custom scss located under themes\academic\assests\scss\custom.scss. Be careful overriding anything in here as it can drastically affect the way widgets works.

## Common Error and Mistakes

* Folders **must not** have any spaces. Use web-friendly hyphens instead.
