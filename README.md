# Web pages for the SCRIBE project

You can find the website at [https://scribe-project.github.io/](https://scribe-project.github.io/)

The pages are automatically generated from Markdown and data files that you can find in this repository. Please look at the existing data as an example of how to add new information.

Whenever you modify this repository, the web pages will be updated in a few minutes. You can check the status of the generation in Settings/Pages. A blue color corresponds to code with no error, green means the new version has been published.

## To add a publication
- modify the `_data/publist.yml` file following the same format as existing entries.
- if you want the publication to be displayed at the top, choose `highlight: 1`, otherwise `0`
- if you add a figure for the publication, store it in `images/pubpic`, and only use the base name in  `_data/publist.yml`

## To add news
- modify the `_data/news.yml` file following the same format as existing entries.

## To add a member to the team
- modify one of `team_members.yml`, `students.yml`, `international_members.yml`, or `alumni*` under `_data`.
- the corresponding picture must be stored in `images/teampic`
- if you don't have a picture, you can use `bio-photo.jpg` as placeholder.

## To modify the text in any page
- modify the Markdown files under `_pages`
- logotypes are stored under `images/logopic`

## (Advanced) to modify the layout
- look into `_includes`, `_sass` and `_layouts`, bit this is not recommended.

## Custom domain
- if we get a domain from NTNU this can be set in the `CNAME` file
