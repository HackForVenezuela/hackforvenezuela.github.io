# HackForVenezuela Website

## Description
This website serves as an online presence for HackForVenezuela events. See below for instructions on how to edit or contribute to the page.

#

## TL;DR for the experienced
1. Fork this repo from HackForVenezuela/hackforvenezuela.github.io
2. Make changes on gh-pages branch
3. Submit pull request to merge into base fork's gh-pages branch
4. If hotfixing, contact an admin to have changes pushed to master immediately

## Cloning
**Do not clone the repo directly!**
1. On the repo's main page, click the `fork` button at the top right of the screen.
2. Select your username from the list of organizations if prompted
    - This will create a copy of the repository on your account that you can work off of
3. Now, you can clone your copy of the repository using the following command:
    - ```git clone https://github.com/<your_username>/hackforvenezuela.github.io.git```
    - (You can also clone via ssh if you have that set up)

## Making changes
Ensure that you make all changes on the `gh-pages` branch of your fork! If using GitHub Pages to preview your changes, you can view any pushed changes live at:
```https://<your_username>.github.io/hackforvenezuela.github.io```

For help using git, checkout the official GitHub guides at https://guides.github.com/

## Submitting changes for review
1. On your forked branch, click the `New Pull Request` button
2. Ensure that the **base fork** is *HackForVenezuela/hackforvenezuela.github.io* and the **base branch** is *gh-pages*.
3. Ensure that the **head fork** is *<your_username>/hackforvenezuela.github.io* and that the **compare branch** is *gh-pages*
4. Enter a summary of your changes and select `Create Pull Request`

Your changes will be reviewed by a page admin. Some fixes may be requested before your changes are merged and published.

## Submitting hotfixes
If you need to quickly submit a hotfix, follow the process for submitting changes for review and contact a page admin to have your changes approved and published. This should be used sparingly for fixing accidental misinformation or serious typos.

#

## Moderators: Publishing Changes
1. Merge PR from user fork into HackForVenezuela/hackforvenezuela.github.io
2. Create a PR to merge gh-pages branch into master branch
    - *Note:* master should never be merged back into gh-pages, as this will copy the CNAME file and could cause a collision or temporary outage.
3. Assign another moderator to the PR to review and merge changes.
    - If reviewing and merging changes, use the `files` tab on the pull request page to view changes, and use the "create review" dropdown to approve/deny changes. Once approved by one person other than the author, the "Merge Pull Request" button will unlock

## Admins: Publishing Hotfixes
If this is a hotfix, tag the PR with the "hotfix" tag and check the "Use admin privileges to merge" box when merging pull request. *Note that this will bypass all checks, and changes will go live immidiately*
