# Web pages for the SCRIBE project

The pages are automatically generated from Markdown and data files that you can find in this repository. Please look at the existing data as an example of how to add new information.

## To add a publication
- modify the `_data/publist.yml` file following the same format as existing entries.
- if you want the publication to be displayed at the top, choose `highlight: 1`, otherwise `0`
- if you add a figure for the publication, store it in `images/pubpic`, and only use the base name in  `_data/publist.yml`

## To add news
- modify the `_data/news.yml` file following the same format as existing entries.

## To add a member to the team
- modify one of `team_members.yml`, `students.yml`, `international_members.yml`, or `alumni*` under `_data`.
- the corresponding picture must be stored in `images/teampic`

## To modify the text in any page
- modify the Markdown files under `_pages`
- logotypes are stored under `images/logopic`

## (Advanced) to modify the layout
- look into `_includes`, `_sass` and `_layouts`, bit this is not recommended.
