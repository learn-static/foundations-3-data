## Step 1. Copy this GitHub Repository

Copy code from another repository into your own and start editing it.

1. Make sure you're logged into your account on [GitHub](https://github.com)
2. Scroll to the top of the [foundations-0-github](https://github.com/learn-static/foundations-0-github) repository and click the green "Use This Template" button (appears on the right side above the code area)
4. This brings you to a "Create a new repository" form. Follow these steps:
    1. In the **Repository name** text box, give your repository the name `data-foundations`. If you'd like to create your own name for the repository, be sure to use a lowercase name without spaces or odd characters. Dashes (`-`) or underscores (`_`) are okay.
    2. In the **Description** text box, add `A place to learn metadata basics`.
    3. Select the option for "**Public**" repository.
    4. Leave the "Include all branches" option **Unchecked**!
    5. Click on the green button "**Create repository from template**". This will take you to your new repository.

!["Create a new repository"](https://github.com/learn-static/foundations-3-data/blob/main/images/new-repo.png)


## Step 2. Activate GitHub Pages

1. On your project repository's home page, click the "Settings" button (appears on the right along the tabs above the code area).
2. On "**Settings**" page: click "**Pages**" in the left side menu.
3. On the "**Pages**" page: in the "**Source**" section, change the dropdown button from "none" to "main" (leave the folder option as "/root"), then click the "**Save**" button. 

Once saved, the page will refresh with an alert providing the URL where your site will appear. 
It will take a few minutes for the build to happen and your site to go live--so wait it out! 

Meanwhile, you might want to copy the URL to display on your home page:

1. Copy the provided URL.
2. Go to repository's GitHub Pages home page.
3. On right side of the code area, look for "**About**" section and click on the cog icon to edit. 
4. In the "**About**" box, paste in your URL, then click "**Save**". This will make it easy to access the site in the future!

## Step 3. Explore your website

1. Navigate to the GithHub Pages website you just activated, and explore it! Your site should have two pages: a homepage with pictures of cute pets, and a "**Map**" page that you can access from the menu at the top of the homepage.
2. Where is Loulou, Flaubert's parrot, shown on your map? Oh no! It looks like her pin is not in Paris. To discover how your website is built, and how to fix this error, go to the next step.

## Step 4. Explore how your repository uses metadata to create your website

1. From the main page of your GitHub repository, click into the "**images**" folder, and notice that the jpg files that create the images of the pets on your website are all in this folder. Click on loulou.jpg to confirm it's the same image that you see in Loulou's profile on your website's home page. 
2. Now return to the main page of your GitHub repository. Click into the "**\_data**" folder and click on the **pets.csv** file to open it. Notice that GitHub has formatted the information that appears as a table or spreadsheet: the first row represents the names or titles of the columns of data below them. Note that the file names in the **image** column correspond to image filenames in the "**images**" folder. 

**pets.csv** is a _metadata file_--a file with additional information (data) about the image file that it refers to. In this case, each row in the csv (spreadsheet) contains information about the pet in the image, including its owner and location.

3. Find Loulou's row and explore the data in it. What is the incorrect information that is causing Loulou's pin to not appear in France as it's supposed to?

## Step 5. Import your metadata file into Google Sheets for editing

While you can edit one or two simple values directly in the GitHub browser window, for any edits beyond changing one or two cells you will need to download your metadata file (**pets.csv**), edit it in a spreadsheet editing program, and re-upload your metadata file to your GitHub repository. Let's start with the first step:

1. Download **pets.csv** to your desktop. One way to do this is to open **pets.csv** within GitHub and click on the "Raw" tab in the top right hand corner. The url you have navigated to will be something similar to https://raw.githubusercontent.com/learn-static/foundations-3-data/main/_data/pets.csv (but with your GitHub username replacing learn-static). 

The main pane of the browser window will now show the data in a plain text format (text without formatting). The value of each cell (box) in what GitHub displayed as a table or spreadsheet is in fact a bit of text, and individual cells are separated by a comma. This plain text, comma separated format is the true csv--the table you saw GitHub create is an interpretation or visualization of that underlying document. 

2. While on the page with your raw csv, choose the "**File**" dropdown from your browser menu. Select "**Save Page As**" and save **pets.csv** to somehwere on your computer where you can find it again.
3. Next, open Google Sheets and upload **pets.csv**. Alternatively, you can open **pets.csv** in LibreOffice, an open source alternative to Excel.

Technical note: please _don't_ open your csv file with Excel. Although Excel is a powerful program in many ways, it does not support UTF-8 encoding, and will make your csv file unusable.

Alternative way to import your csv. Take advantage of Google Sheets' powerful import capabilities:

1. Open **pets.csv** within GitHub and click on the "Raw" tab in the top right hand corner. The url you have navigated to will be something similar to https://raw.githubusercontent.com/learn-static/foundations-3-data/main/_data/pets.csv (but with your GitHub username replacing learn-static). Copy this url to your clipboard.
2. Open a new, blank Google Sheet. In cell A1, enter the `IMPORTDATA` command to tell Google to import the data direcly from this GitHub url. Like other commands in Excel or Google Sheets, the command begins with an `=` to tell Google you are entering a formula, and the command is followed by information explaining what you want the command to do in parentheses. As [Google's official IMPORTDATA documentation](https://support.google.com/docs/answer/3093335?hl=en) explains, your url should be in parentheses, in the form =IMPORTDATA("www.yoururl.com").
3. As soon as you enter this command in full, the spreadsheet should populate with your **pets.csv** data. Name your document "pets" by typing "pets" in the box labled "Untitled Spreadsheet" in the top left hand corner of your Google Sheet.

## Step 6. Explore Google Sheets' powerful editing capabilities


