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
2. Now return to the main page of your GitHub repository. Click into the "**\_data**" folder and click on the pets.csv file to open it. Notice that the file names in the "image" column correspond to image filenames in the "images" folder. 

pets.csv is a _metadata file_--a file with additional information (data) about the image file that it refers to. In this case, each row in the csv (spreadsheet) contains information about the pet in the image, including its owner and location.

3. Find Loulou's row and explore the data in it. What is the incorrect information that is causing Loulou's pin to not appear in France as it's supposed to?

## Step 5. Fix errors in your metadata file

1. Download pets.csv to your desktop. One way to do this is to open pets.csv within GitHub and click on the "Raw" tab in the top right hand corner. Your url will now show something similar to https://raw.githubusercontent.com/learn-static/foundations-3-data/main/_data/pets.csv (except with your username instead of learn-static). The main pane of the browser window will now show the data in a plain text format, as comma separated values.
