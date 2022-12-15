# Naas Templates [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
(aka the "awesome-notebooks") 


## What is Naas ?

Naas is an all-in-one data platform that enable anyone with minimal technical knowledge to turn <a href="https://jupyter.org" target="_blank">Jupyter Notebooks</a> into powerful automation, analytical and AI data products thanks to <a href="https://docs.naas.ai/" target="_blank">low-code formulas</a> and microservices.<br>

The platform is based on 3 low-code layers:<br>
- **😎 Templates**: enable anyone to use data engines on all kind of subjects in minutes.
- **🏎 Drivers**: connectors to facilitate access to tools, and complex libraries (database, API, ML algorithm...)
- **🪐 Features**: production microservices on top of Jupyter like scheduling, asset sharing, notifications and more.<br>

Naas Cloud is free to use with 100 credits/month.<br>
<a href="https://www.naas.ai/free-forever" target="_blank">Open your account</a><br>

[>> More information](https://docs.naas.ai/)


## What is the objective of this repository ?

The objective of this repository is to create the largest catalog of production-ready Jupyter Notebooks templates. With those templates, it becomes easy to create data products (analytical dashboards, automation/AI engines and more). Check out the [data-product-template](https://github.com/jupyter-naas/data-product-template) repository to learn more.<br>
The repository is organized by source/tools for easy discovery. You can also use our ["Google-like" search](http://search.live.kn.naas.ai/) to find templates by keywords<br>

To ensure the quality of the templates, we have defined a framework. Each notebook shall be organized with the following sections:  
- **Naas logo**
- **# Title**: "Tool - Action of the notebook", as h1 (an "Open in Naas" button will be automatically added by the CI/CD when a notebook is merged to the master branch)
- **Tags**: hastags of the topics the notebook is about, as text
- **Author**: name and social profile link of the author(s), as text
- **Description**: a one-liner explaining the benefits of the notebooks for the user, as text
- **## Input**: list of all the variables, credentials, that needs to be setup, as h2
- **## Model**: list the functions applied to the data, as h2
- **## Output**: list the assets to be used by the user and its distribution channels if any, as h2


## How to contribute ?

### Pre-requisites:
- Open free account on [Naas Cloud](https://www.naas.ai/free-forever) so we can test the templates in a similar environment 
- Register to the [Contributor Program](https://form.typeform.com/to/jdls9qZf?typeform-source=www.naas.ai) so we can add you to team of contributors in the Naas GitHub organization 
- Join our [Slack Community](https://join.slack.com/t/naas-club/shared_invite/zt-1970s5rie-dXXkigAdEJYc~LPdQIEaLA) so you can present yourself and #chat with us

### Step by step process:

- **Step 1**: Find or propose an issue you want to work on
  - The Backlog of the [Product Roadmap](https://github.com/orgs/jupyter-naas/projects/10) is where we put all the priorities
  - The [Issues](https://github.com/jupyter-naas/awesome-notebooks/issues) section is where we gather all the needs 
- **Step 2**: Prepare the issue before you start working on it
  - Make sure the description is clear
  - Tag yourself in Assignees section
  - Change the status to 'In Progress' in Projects section/Community Roadmap
  - Create a branch in Development section 
- **Step 3**: Clone the awesome-notebooks repository on your Naas Cloud account and switch to the branch you created
- **Step 4**: Create folder named with the source tool (if it's not already created)
- **Step 5**: Copy/Paste template.ipynb at the root of the folder inside the folder you are working on, and start working on your notebook
- **Step 6**: Once you are happy with the result, commit to the branch by using Git extension or command line (make sure you use a GitHub personal access token and not password, otherwise it wont work)
- **Step 7**: Open a Pull Request and add a member of the core team as Reviewer ([Florent](https://github.com/FlorentLvr),[Maxime](https://github.com/Dr0p42) or [Jeremy](https://github.com/jravenel))
- **Step 8**: Change status of this Issue to “Review” in Projects section and comment the Pull Request with a brief on what you have done
- **Step 9**: Expect a feedback and merge in the next 48h-72h
- **Step 10**: Once merged, promote your work on LinkedIn, Twitter and other social media channels! (Optional, but people need to know you are awesome 😉)

[>> More information](https://docs.naas.ai/contributing-to-naas)


## Support on social media
We are committed to sharing templates and giving shout outs to the contributors on our social media platforms, you can support us on:
- [Twitter](https://twitter.com/JupyterNaas) for fast updates<br>
- [LinkedIn](https://www.linkedin.com/company/naas-ai/) for more elaborated posts and articles<br>
- [Youtube](https://www.youtube.com/channel/UCKKG5hzjXXU_rRdHHWQ8JHQ/videos) for demos and tutorials<br>

# Template analytics

![Templates_monthly](https://public.naas.ai/bWV0cmljcy00MG5hYXMtMkVhaQ==/asset/09d0bd9ed8ac2479a2a4f05e60c74d101d140ffdfacd9b0ac7bbb4e53966.png)

# Templates list


## AWS
* [Daily biling notification to slack](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AWS/AWS_Daily_biling_notification_to_slack.ipynb)
* [Get files from S3 bucket](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AWS/AWS_Get_files_from_S3_bucket.ipynb)
* [Read dataframe from S3](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AWS/AWS_Read_dataframe_from_S3.ipynb)
* [Send dataframe to S3](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AWS/AWS_Send_dataframe_to_S3.ipynb)
* [Upload file to S3 bucket](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AWS/AWS_Upload_file_to_S3_bucket.ipynb)

## AbstractAPI
* [Abstractapi Get IP Geolocation](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AbstractAPI/Abstractapi_Get_IP_Geolocation.ipynb)

## Affinity
* [Sync with Notion database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Affinity/Affinity_Sync_with_Notion_database.ipynb)

## Airtable
* [Delete data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Airtable/Airtable_Delete_data.ipynb)
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Airtable/Airtable_Get_data.ipynb)
* [Insert data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Airtable/Airtable_Insert_data.ipynb)
* [Search data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Airtable/Airtable_Search_data.ipynb)

## AlphaVantage
* [Get balance sheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AlphaVantage/AlphaVantage_Get_balance_sheet.ipynb)
* [Get cashflow statement](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AlphaVantage/AlphaVantage_Get_cashflow_statement.ipynb)
* [Get company overview](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AlphaVantage/AlphaVantage_Get_company_overview.ipynb)
* [Get income statement](https://github.com/jupyter-naas/awesome-notebooks/tree/master/AlphaVantage/AlphaVantage_Get_income_statement.ipynb)

## Bazimo
* [Get export Actifs](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Bazimo/Bazimo_Get_export_Actifs.ipynb)
* [Get export Baux](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Bazimo/Bazimo_Get_export_Baux.ipynb)
* [Get export Factures](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Bazimo/Bazimo_Get_export_Factures.ipynb)
* [Get export Locataires](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Bazimo/Bazimo_Get_export_Locataires.ipynb)
* [Get export Lots](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Bazimo/Bazimo_Get_export_Lots.ipynb)

## BigQuery
* [Create table from csv](https://github.com/jupyter-naas/awesome-notebooks/tree/master/BigQuery/BigQuery_Create_table_from_csv.ipynb)
* [Read Table](https://github.com/jupyter-naas/awesome-notebooks/tree/master/BigQuery/BigQuery_Read_Table.ipynb)

## Boursorama
* [Get CDS](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Boursorama/Boursorama_Get_CDS.ipynb)

## Bubble
* [Send data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Bubble/Bubble_Send_data.ipynb)

## CCXT
* [Calculate Support and Resistance](https://github.com/jupyter-naas/awesome-notebooks/tree/master/CCXT/CCXT_Calculate_Support_and_Resistance.ipynb)
* [Predict Bitcoin from Binance](https://github.com/jupyter-naas/awesome-notebooks/tree/master/CCXT/CCXT_Predict_Bitcoin_from_Binance.ipynb)

## CSV
* [Read file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/CSV/CSV_Read_file.ipynb)
* [Save file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/CSV/CSV_Save_file.ipynb)

## Canny
* [Create](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Canny/Canny_Create.ipynb)
* [Github issue update](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Canny/Canny_Github_issue_update.ipynb)
* [Read](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Canny/Canny_Read.ipynb)

## Celestrak
* [Satellites over time](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Celestrak/Celestrak_Satellites_over_time.ipynb)

## Cityfalcon
* [Get data from API](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Cityfalcon/Cityfalcon_Get_data_from_API.ipynb)

## Cloud Mercato
* [Compare VM pricing](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Cloud%20Mercato/Cloud_Mercato_Compare_VM_pricing.ipynb)

## D-Tale
* [Visualize dataframe](https://github.com/jupyter-naas/awesome-notebooks/tree/master/D-Tale/D-Tale_Visualize_dataframe.ipynb)

## Dash
* [Create Datatable With Dropdown](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Create_Datatable_With_Dropdown.ipynb)
* [Create Dropdown Callback](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Create_Dropdown_Callback.ipynb)
* [Create Dropdown with multiples output callbacks](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Create_Dropdown_with_multiples_output_callbacks.ipynb)
* [Create Navbar](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Create_Navbar.ipynb)
* [Create Navbar board](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Create_Navbar_Dashboard.ipynb)
* [Create Navbar Search](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Create_Navbar_Search.ipynb)
* [Deploy app in Naas](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Deploy_app_in_Naas.ipynb)
* [LinkedIn posts metrics dashboard](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_LinkedIn_posts_metrics_dashboard.ipynb)
* [Plotly Dynamic Link](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Plotly_Dynamic_Link.ipynb)
* [Upload mutiples CSV Excel](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dash/Dash_Upload_mutiples_CSV_Excel.ipynb)

## Dask
* [Parallelize operations on multiple csvs](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Dask/Dask_parallelize_operations_on_multiple_csvs.ipynb)

## Data.gouv.fr
* [COVID19 -  FR - Entrées et sorties par région pour 1 million d'hab.](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Data.gouv.fr/COVID19%20-%20%20FR%20-%20Entr%C3%A9es%20et%20sorties%20par%20r%C3%A9gion%20pour%201%20million%20d%27hab..ipynb)
* [Récupération données légales entreprise](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Data.gouv.fr/Data.gouv.fr_R%C3%A9cup%C3%A9ration_donn%C3%A9es_l%C3%A9gales_entreprise.ipynb)

## Draft Kings
* [Get MLB Moneylines](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Draft%20Kings/Draft_Kings_Get_MLB_Moneylines.ipynb)
* [Get NBA Moneylines](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Draft%20Kings/Draft_Kings_Get_NBA_Moneylines.ipynb)

## EM-DAT
* [Natural disasters](https://github.com/jupyter-naas/awesome-notebooks/tree/master/EM-DAT/EM-DAT_natural_disasters.ipynb)

## Elasticsearch
* [Connect to server](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Elasticsearch/Elasticsearch_Connect_to_server.ipynb)

## Excel
* [Consolidate files](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Excel/Excel_Consolidate_files.ipynb)
* [Custom sheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Excel/Excel_Custom_sheet.ipynb)
* [Get dynamic active range](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Excel/Excel_Get_dynamic_active_range.ipynb)
* [Read file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Excel/Excel_Read_file.ipynb)
* [Save file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Excel/Excel_Save_file.ipynb)

## FAO
* [Consumer price indice](https://github.com/jupyter-naas/awesome-notebooks/tree/master/FAO/FAO_Consumer_price_indice.ipynb)

## FEC
* [Creer un dashboard PowerBI](https://github.com/jupyter-naas/awesome-notebooks/tree/master/FEC/FEC_Creer_un_dashboard_PowerBI.ipynb)

## FTP
* [S Connect](https://github.com/jupyter-naas/awesome-notebooks/tree/master/FTP/FTPS_Connect.ipynb)
* [Connect](https://github.com/jupyter-naas/awesome-notebooks/tree/master/FTP/FTP_Connect.ipynb)
* [Get file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/FTP/FTP_Get_file.ipynb)
* [Send file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/FTP/FTP_Send_file.ipynb)

## Faker
* [Anonymize Address from dataframe](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Faker/Faker_Anonymize_Address_from_dataframe.ipynb)
* [Anonymize Personal Names from dataframe](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Faker/Faker_Anonymize_Personal_Names_from_dataframe.ipynb)

## GitHub
* [Add new issues as page in Notion database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Add_new_issues_as_page_in_Notion_database.ipynb)
* [Add new member to team](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Add_new_member_to_team.ipynb)
* [Clone repository](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Clone_repository.ipynb)
* [Close issue](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Close_issue.ipynb)
* [Create issue](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Create_issue.ipynb)
* [Create repository on personal account](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Create_repository_on_personal_account.ipynb)
* [Download file from url](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Download_file_from_url.ipynb)
* [Get active projects](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_active_projects.ipynb)
* [Get commits ranking from repository](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_commits_ranking_from_repository.ipynb)
* [Get issues from repo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_issues_from_repo.ipynb)
* [Get most starred repos](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_most_starred_repos.ipynb)
* [Get profile from user](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_profile_from_user.ipynb)
* [Get profiles from teams](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_profiles_from_teams.ipynb)
* [Get pull requests from repository](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_pull_requests_from_repository.ipynb)
* [Get stargazers from repository](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_stargazers_from_repository.ipynb)
* [Get weekly commits from repository](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Get_weekly_commits_from_repository.ipynb)
* [Peform basic actions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Peform_basic_actions.ipynb)
* [Read issue](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Read_issue.ipynb)
* [Remove member from team](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Remove_member_from_team.ipynb)
* [Track issues on projects](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Track_issues_on_projects.ipynb)
* [Track notebooks created over time](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/GitHub_Track_notebooks_created_over_time.ipynb)
* [Github Create Repo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/Github_Create_Repo.ipynb)
* [Github Create newsletter based on repository activity](https://github.com/jupyter-naas/awesome-notebooks/tree/master/GitHub/Github_Create_newsletter_based_on_repository_activity.ipynb)

## Gmail
* [Automate response from keywords in mailbox](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Gmail/Gmail_Automate_response_from_keywords_in_mailbox.ipynb)
* [Clean mailbox](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Gmail/Gmail_Clean_mailbox.ipynb)
* [Read mailbox](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Gmail/Gmail_Read_mailbox.ipynb)
* [Schedule mailbox cleaning](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Gmail/Gmail_Schedule_mailbox_cleaning.ipynb)
* [Send emails from Gsheet classic](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Gmail/Gmail_Send_emails_from_Gsheet_classic.ipynb)
* [Send emails from Gsheet specific](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Gmail/Gmail_Send_emails_from_Gsheet_specific.ipynb)

## Google Analytics
* [Follow average session duration daily](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_average_session_duration_daily.ipynb)
* [Follow number of new visitors daily](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_daily.ipynb)
* [Follow number of new visitors hourly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_hourly.ipynb)
* [Follow number of new visitors monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_monthly.ipynb)
* [Follow number of new visitors weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_new_visitors_weekly.ipynb)
* [Follow number of sessions daily](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_daily.ipynb)
* [Follow number of sessions hourly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_hourly.ipynb)
* [Follow number of sessions monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_monthly.ipynb)
* [Follow number of sessions weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_sessions_weekly.ipynb)
* [Follow number of visitors daily](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_daily.ipynb)
* [Follow number of visitors hourly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_hourly.ipynb)
* [Follow number of visitors monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_monthly.ipynb)
* [Follow number of visitors weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Follow_number_of_visitors_weekly.ipynb)
* [Get bounce rate](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Get_bounce_rate.ipynb)
* [Get pageview ranking](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Get_pageview_ranking.ipynb)
* [Get stats per country](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Get_stats_per_country.ipynb)
* [Get time on landing page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Get_time_on_landing_page.ipynb)
* [Get unique visitors](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Get_unique_visitors.ipynb)
* [Get unique visitors by country](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Get_unique_visitors_by_country.ipynb)
* [Send visitors traffic graph and trends prediction to Slack channel](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Analytics/Google_Analytics_Send_visitors_traffic_graph_and_trends_prediction_to_Slack_channel.ipynb)

## Google Drive
* [Download file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Drive/Google_Drive_Download_file.ipynb)

## Google Search
* [Get LinkedIn company url from name](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Search/Google_Search_Get_LinkedIn_company_url_from_name.ipynb)
* [Get LinkedIn profile url from name](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Search/Google_Search_Get_LinkedIn_profile_url_from_name.ipynb)
* [Perform search](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Search/Google_Search_Perform_search.ipynb)

## Google Sheets
* [Add items to Notion databases from new rows in](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Add_items_to_Notion_databases_from_new_rows_in_Google_Sheets.ipynb)
* [Add new github member to team from spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Add_new_github_member_to_team_from_spreadsheet.ipynb)
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Get_data.ipynb)
* [Send LinkedIn invitations from spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Send_LinkedIn_invitations_from_spreadsheet.ipynb)
* [Send data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Send_data.ipynb)
* [Send data to MongoDB](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Send_data_to_MongoDB.ipynb)
* [Send emails from sheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Google%20Sheets/Google_Sheets_Send_emails_from_sheet.ipynb)

## HTML
* [Create a website](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HTML/HTML_Create_a_website.ipynb)

## Healthchecks
* [Perfom basic actions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Healthchecks/Healthchecks_Perfom_basic_actions.ipynb)

## HubSpot
* [Associate contact to deal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Associate_contact_to_deal.ipynb)
* [Create Task](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Create_Task.ipynb)
* [Create contact](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Create_contact.ipynb)
* [Create contact from LinkedIn profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Create_contact_from_LinkedIn_profile.ipynb)
* [Create contacts from linkedin post likes](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Create_contacts_from_linkedin_post_likes.ipynb)
* [Create deal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Create_deal.ipynb)
* [Create note](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Create_note.ipynb)
* [Delete Task](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Delete_Task.ipynb)
* [Delete contact](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Delete_contact.ipynb)
* [Delete deal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Delete_deal.ipynb)
* [Delete note](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Delete_note.ipynb)
* [Get Task](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_Task.ipynb)
* [Get all contacts](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_all_contacts.ipynb)
* [Get all deals](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_all_deals.ipynb)
* [Get all pipelines and dealstages](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_all_pipelines_and_dealstages.ipynb)
* [Get contact from URL](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_contact_from_URL.ipynb)
* [Get contact from email](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_contact_from_email.ipynb)
* [Get contact from id](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_contact_from_id.ipynb)
* [Get contacts associated to deal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_contacts_associated_to_deal.ipynb)
* [Get deal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_deal.ipynb)
* [Get notes from contact](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Get_notes_from_contact.ipynb)
* [Send LinkedIn invitations from contacts](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Send_LinkedIn_invitations_from_contacts.ipynb)
* [Send closed deals weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Send_closed_deals_weekly.ipynb)
* [Send contacts to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Send_contacts_to_gsheet.ipynb)
* [Send deals to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Send_deals_to_gsheet.ipynb)
* [Send new deals created weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Send_new_deals_created_weekly.ipynb)
* [Send sales brief](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Send_sales_brief.ipynb)
* [Update Task](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Update_Task.ipynb)
* [Update contact](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Update_contact.ipynb)
* [Update deal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Update_deal.ipynb)
* [Update followers from linkedin](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Update_followers_from_linkedin.ipynb)
* [Update jobtitle country industry from linkedin](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Update_jobtitle_country_industry_from_linkedin.ipynb)
* [Update linkedinbio from google](https://github.com/jupyter-naas/awesome-notebooks/tree/master/HubSpot/HubSpot_Update_linkedinbio_from_google.ipynb)

## Hugging Face
* [Ask boolean question to T5](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Hugging%20Face/Hugging_Face_Ask_boolean_question_to_T5.ipynb)
* [Naas drivers integration](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Hugging%20Face/Hugging_Face_Naas_drivers_integration.ipynb)
* [Question Answering from PDF](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Hugging%20Face/Hugging_Face_Question_Answering_from_PDF.ipynb)

## IFTTT
* [Post on Twitter](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IFTTT/IFTTT_Post_on_Twitter.ipynb)
* [Trigger workflow](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IFTTT/IFTTT_Trigger_workflow.ipynb)

## IMDB
* [Top  Movie](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IMDB/Top_IMDB_Movie.ipynb)

## INPI
* [Download PDF recap](https://github.com/jupyter-naas/awesome-notebooks/tree/master/INPI/INPI_Download_PDF_recap.ipynb)

## IPyWidgets
* [Create button](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IPyWidgets/IPyWidgets_Create_button.ipynb)
* [Create input text and submit button](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IPyWidgets/IPyWidgets_Create_input_text_and_submit_button.ipynb)
* [Setup naas secret](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IPyWidgets/IPyWidgets_Setup_naas_secret.ipynb)

## IUCN
* [Extinct species](https://github.com/jupyter-naas/awesome-notebooks/tree/master/IUCN/IUCN_Extinct_species.ipynb)

## Insee
* [Download PDF recap](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Insee/Insee_Download_PDF_recap.ipynb)

## Instagram
* [Get stats from posts](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Instagram/Instagram_Get_stats_from_posts.ipynb)
* [Post image and caption](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Instagram/Instagram_Post_image_and_caption.ipynb)

## Integromat
* [Trigger workflow](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Integromat/Integromat_Trigger_workflow.ipynb)

## Johns Hopkins
* [Covid19 Active Cases](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Johns%20Hopkins/Johns_Hopkins_Covid19_Active_Cases.ipynb)
* [Get Covid19 data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Johns%20Hopkins/Johns_Hopkins_Get_Covid19_data.ipynb)

## Jupyter Notebooks
* [Add cells in notebook json](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Add_cells_in_notebook_json.ipynb)
* [Add tags in cells](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Add_tags_in_cells.ipynb)
* [Count code characters](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Count_code_characters.ipynb)
* [Count code lines](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Count_code_lines.ipynb)
* [Get installs](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Get_installs.ipynb)
* [Get libraries](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Get_libraries.ipynb)
* [Read file json](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Read_file_json.ipynb)
* [Save file ipynb](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter%20Notebooks/Jupyter_Notebooks_Save_file_ipynb.ipynb)

## Jupyter
* [Get server uptime](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter/Jupyter_Get_server_uptime.ipynb)
* [Get user information](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter/Jupyter_Get_user_information.ipynb)
* [Get user session](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter/Jupyter_Get_user_session.ipynb)
* [Get user terminal](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter/Jupyter_Get_user_terminal.ipynb)
* [Restart server](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Jupyter/Jupyter_Restart_server.ipynb)

## Kaggle
* [Download Data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Kaggle/Kaggle_Download_Data.ipynb)

## Knative
* [Create command file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Knative/Knative_Create_command_file.ipynb)

## LeFigaro
* [House Price analysis](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LeFigaro/LeFigaro_House_Price_analysis.ipynb)

## LinkedIn
* [Accept all invitations and send first message](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Accept_all_invitations_and_send_first_message.ipynb)
* [Accept invitation received](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Accept_invitation_received.ipynb)
* [Create posts metrics dashboard](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Create_posts_metrics_dashboard.ipynb)
* [Extract content world cloud](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Extract_content_world_cloud.ipynb)
* [Follow company followers](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_company_followers.ipynb)
* [Follow connections from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_connections_from_profile.ipynb)
* [Follow content comments monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_comments_monthly.ipynb)
* [Follow content comments weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_comments_weekly.ipynb)
* [Follow content engagements monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_engagements_monthly.ipynb)
* [Follow content engagements weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_engagements_weekly.ipynb)
* [Follow content frequency](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_frequency.ipynb)
* [Follow content likes monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_likes_monthly.ipynb)
* [Follow content likes weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_likes_weekly.ipynb)
* [Follow content published by weekdays by months](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_published_by_weekdays_by_months.ipynb)
* [Follow content published monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_published_monthly.ipynb)
* [Follow content published weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_published_weekly.ipynb)
* [Follow content views by weekdays by hours](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_views_by_weekdays_by_hours.ipynb)
* [Follow content views monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_views_monthly.ipynb)
* [Follow content views weekly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_content_views_weekly.ipynb)
* [Follow number of connections monthly](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Follow_number_of_connections_monthly.ipynb)
* [Generate leads from posts](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Generate_leads_from_posts.ipynb)
* [Get age and gender from profile picture](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_age_and_gender_from_profile_picture.ipynb)
* [Get comments from post](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_comments_from_post.ipynb)
* [Get company followers](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_company_followers.ipynb)
* [Get company posts stats](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_company_posts_stats.ipynb)
* [Get connections from network](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_connections_from_network.ipynb)
* [Get contact from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_contact_from_profile.ipynb)
* [Get conversations](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_conversations.ipynb)
* [Get followers from network](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_followers_from_network.ipynb)
* [Get guests from event](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_guests_from_event.ipynb)
* [Get identity from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_identity_from_profile.ipynb)
* [Get info from company](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_info_from_company.ipynb)
* [Get invitations received](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_invitations_received.ipynb)
* [Get invitations sent](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_invitations_sent.ipynb)
* [Get likes from post](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_likes_from_post.ipynb)
* [Get messages from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_messages_from_profile.ipynb)
* [Get network from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_network_from_profile.ipynb)
* [Get polls from post](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_polls_from_post.ipynb)
* [Get posts engagements](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_posts_engagements.ipynb)
* [Get profile information](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_profile_information.ipynb)
* [Get profile posts stats](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_profile_posts_stats.ipynb)
* [Get resume from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_resume_from_profile.ipynb)
* [Get sentiment emotion irony offensiveness from comments](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_sentiment_emotion_irony_offensiveness_from_comments.ipynb)
* [Get stats from post](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Get_stats_from_post.ipynb)
* [Ignore invitation received](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Ignore_invitation_received.ipynb)
* [Send comments from post to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_comments_from_post_to_gsheet.ipynb)
* [Send company followers to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_company_followers_to_Google_Sheets.ipynb)
* [Send connections from network to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_connections_from_network_to_gsheet.ipynb)
* [Send event invitations post engagements](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_event_invitations_post_engagements.ipynb)
* [Send followers demographic data to a Google Sheets spreadsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_followers_demographic_data_to_a_Google_Sheets_spreadsheet.ipynb)
* [Send invitation to company followers](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_invitation_to_company_followers.ipynb)
* [Send invitation to profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_invitation_to_profile.ipynb)
* [Send invitation to profile from post likes](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_invitation_to_profile_from_post_likes.ipynb)
* [Send invitations to post commenters](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_invitations_to_post_commenters.ipynb)
* [Send likes from post to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_likes_from_post_to_gsheet.ipynb)
* [Send message to new connections](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_message_to_new_connections.ipynb)
* [Send message to profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_message_to_profile.ipynb)
* [Send message to profile from post likes](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_message_to_profile_from_post_likes.ipynb)
* [Send posts feed to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_posts_feed_to_gsheet.ipynb)
* [Send profile followers by email](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_profile_followers_by_email.ipynb)
* [Send weekly post engagement metrics by email](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Send_weekly_post_engagement_metrics_by_email.ipynb)
* [Update metrics from company posts in Notion content calendar](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Update_metrics_from_company_posts_in_Notion_content_calendar.ipynb)
* [Update metrics from posts in Notion content calendar](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Update_metrics_from_posts_in_Notion_content_calendar.ipynb)
* [Withdraw pending profile invitations](https://github.com/jupyter-naas/awesome-notebooks/tree/master/LinkedIn/LinkedIn_Withdraw_pending_profile_invitations.ipynb)

## Matplotlib
* [Create Waterfall chart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Matplotlib/Matplotlib_Create_Waterfall_chart.ipynb)

## Metrics Store
* [Content creation Track connections](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Metrics%20Store/Content_creation_Track_connections.ipynb)

## Microsoft Teams
* [Send message](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Microsoft%20Teams/Microsoft_Teams_Send_message.ipynb)

## Microsoft Word
* [Convert to HMTL](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Microsoft%20Word/Microsoft_Word_Convert_to_HMTL.ipynb)

## MongoDB
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/MongoDB/MongoDB_Get_data.ipynb)
* [Send data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/MongoDB/MongoDB_Send_data.ipynb)
* [Send data to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/tree/master/MongoDB/MongoDB_Send_data_to_Google_Sheets.ipynb)

## MySQL
* [Query database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/MySQL/MySQL_Query_database.ipynb)

## NASA
* [Artic sea ice](https://github.com/jupyter-naas/awesome-notebooks/tree/master/NASA/NASA_Artic_sea_ice.ipynb)
* [Global temperature](https://github.com/jupyter-naas/awesome-notebooks/tree/master/NASA/NASA_Global_temperature.ipynb)
* [Sea level](https://github.com/jupyter-naas/awesome-notebooks/tree/master/NASA/NASA_Sea_level.ipynb)

## Naas Auth
* [Bearer validate](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas%20Auth/Naas_Auth_bearer_validate.ipynb)
* [Connect](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas%20Auth/Naas_Auth_connect.ipynb)
* [Users me](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas%20Auth/Naas_Auth_users_me.ipynb)

## Naas Dashboard
* [Financial Consolidation](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas%20Dashboard/Naas_Dashboard_Financial_Consolidation.ipynb)
* [Revenue Cogs by Segment](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas%20Dashboard/Naas_Dashboard_Revenue_Cogs_by_Segment.ipynb)
* [Social Media KPIs ScoreCard](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas%20Dashboard/Naas_Dashboard_Social_Media_KPIs_ScoreCard.ipynb)

## Naas
* [Asset demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Asset_demo.ipynb)
* [Automate GitHub Auth](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Automate_GitHub_Auth.ipynb)
* [Configure Github with ssh](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Configure_Github_with_ssh.ipynb)
* [Credits Get Balance](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Credits_Get_Balance.ipynb)
* [Dependency demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Dependency_demo.ipynb)
* [Doc demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Doc_demo.ipynb)
* [Download Content Engine](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Download_Content_Engine.ipynb)
* [Emailbuilder demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Emailbuilder_demo.ipynb)
* [Get Transactions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Get_Transactions.ipynb)
* [Get help](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Get_help.ipynb)
* [Get number of downloads naas drivers package](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Get_number_of_downloads_naas_drivers_package.ipynb)
* [Get number of downloads naas package](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Get_number_of_downloads_naas_package.ipynb)
* [Get total downloads naas libraries](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Get_total_downloads_naas_libraries.ipynb)
* [NLP Examples](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_NLP_Examples.ipynb)
* [Notification demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Notification_demo.ipynb)
* [Remove Scheduler Outputs](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Remove_Scheduler_Outputs.ipynb)
* [Reset Instance](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Reset_Instance.ipynb)
* [Scheduler demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Scheduler_demo.ipynb)
* [Secret demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Secret_demo.ipynb)
* [Set timezone](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Set_timezone.ipynb)
* [Use SSH tunnel to reach network protected resources](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Use_SSH_tunnel_to_reach_network_protected_resources.ipynb)
* [Webhook demo](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Naas/Naas_Webhook_demo.ipynb)

## Neo
* [Get currencies live prices](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Neo/Neo_Get_currencies_live_prices.ipynb)

## Newsapi
* [Get data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Newsapi/Newsapi_Get_data.ipynb)
* [Run sentiment analysis](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Newsapi/Newsapi_Run_sentiment_analysis.ipynb)
* [Send emails briefs](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Newsapi/Newsapi_Send_emails_briefs.ipynb)

## Notion
* [Add cover image to page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Add_cover_image_to_page.ipynb)
* [Add icon image to page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Add_icon_image_to_page.ipynb)
* [Add image to page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Add_image_to_page.ipynb)
* [Add new github member to team from database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Add_new_github_member_to_team_from_database.ipynb)
* [Add paragraph with link in page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Add_paragraph_with_link_in_page.ipynb)
* [Automate transcript generation from recording link in page property](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Automate_transcript_generation_from_recording_link_in_page_property.ipynb)
* [Create page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Create_page.ipynb)
* [Delete blocks from page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Delete_blocks_from_page.ipynb)
* [Delete page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Delete_page.ipynb)
* [Duplicate page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Duplicate_page.ipynb)
* [Explore API](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Explore_API.ipynb)
* [Generate Google Sheets rows for new items in  database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Generate_Google_Sheets_rows_for_new_items_in_Notion_database.ipynb)
* [Get blocks from page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Get_blocks_from_page.ipynb)
* [Get database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Get_database.ipynb)
* [Get page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Get_page.ipynb)
* [Get users](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Get_users.ipynb)
* [Send LinkedIn invitations from database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Send_LinkedIn_invitations_from_database.ipynb)
* [Send Slack Messages For New  Database Items](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Send_Slack_Messages_For_New_Notion_Database_Items.ipynb)
* [Sent Gmail On New Item](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Sent_Gmail_On_New_Item.ipynb)
* [Update page](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Update_page.ipynb)
* [Update pages from database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Notion/Notion_Update_pages_from_database.ipynb)

## OpenPIV
* [Openpiv-python-template](https://github.com/jupyter-naas/awesome-notebooks/tree/master/OpenPIV/openpiv-python-template.ipynb)

## OpenWeatherMap
* [Get City Weather](https://github.com/jupyter-naas/awesome-notebooks/tree/master/OpenWeatherMap/OpenWeatherMap_Get_City_Weather.ipynb)
* [Get City temperature weather-type wind-speed](https://github.com/jupyter-naas/awesome-notebooks/tree/master/OpenWeatherMap/OpenWeatherMap_Get_City_temperature_weather-type_wind-speed.ipynb)
* [Send daily email with predictions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/OpenWeatherMap/OpenWeatherMap_Send_daily_email_with_predictions.ipynb)

## OwnCloud
* [Download file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/OwnCloud/OwnCloud_Download_file.ipynb)
* [Upload file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/OwnCloud/OwnCloud_Upload_file.ipynb)

## PDF
* [Extract Text from](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PDF/PDF_Extract_Text_from_PDF.ipynb)
* [Merge multiple  documents](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PDF/PDF_Merge_multiple_PDF_documents.ipynb)
* [Transform to MP3](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PDF/PDF_Transform_to_MP3.ipynb)

## Pandas
* [Check Columns type](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Check_Columns_type.ipynb)
* [Convert datetime series](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Convert_datetime_series.ipynb)
* [Create Pivot Table](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Create_Pivot_Table.ipynb)
* [Create dataframe from dict](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Create_dataframe_from_dict.ipynb)
* [Drop Columns](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Drop_Columns.ipynb)
* [Drop First column](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Drop_First_column.ipynb)
* [Fill emtpy values](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Fill_emtpy_values.ipynb)
* [Format number to string](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Format_number_to_string.ipynb)
* [Groupby and Aggregate](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Groupby_and_Aggregate.ipynb)
* [ISO Date Conversion](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_ISO_Date_Conversion.ipynb)
* [Keep Columns](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Keep_Columns.ipynb)
* [Merge Dataframes](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Merge_Dataframes.ipynb)
* [Pivot rows to columns](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Pivot_rows_to_columns.ipynb)
* [Rename Columns](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Rename_Columns.ipynb)
* [Transform dataframe to dict](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pandas/Pandas_Transform_dataframe_to_dict.ipynb)

## Pillow
* [Add data to image](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pillow/Pillow_Add_data_to_image.ipynb)
* [Create indicator](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pillow/Pillow_Create_indicator.ipynb)
* [Create new image](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pillow/Pillow_Create_new_image.ipynb)
* [Generate A Certificate Template](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pillow/Pillow_Generate_A_Certificate_Template.ipynb)

## Pipedrive
* [Get contact](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pipedrive/Pipedrive_Get_contact.ipynb)

## Plaid
* [Get accounts](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plaid/Plaid_Get_accounts.ipynb)
* [Get transactions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plaid/Plaid_Get_transactions.ipynb)

## Plotly
* [Create Barline chart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Barline_chart.ipynb)
* [Create Bubblechart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Bubblechart.ipynb)
* [Create Candlestick](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Candlestick.ipynb)
* [Create Gantt chart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Gantt_chart.ipynb)
* [Create Heatmap](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Heatmap.ipynb)
* [Create Horizontal Barchart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Horizontal_Barchart.ipynb)
* [Create Leaderboard](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Leaderboard.ipynb)
* [Create Leaderboard stacked](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Leaderboard_stacked.ipynb)
* [Create Linechart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Linechart.ipynb)
* [Create Mapchart world](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Mapchart_world.ipynb)
* [Create Vertical Barchart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Vertical_Barchart.ipynb)
* [Create Vertical Barchart group](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Vertical_Barchart_group.ipynb)
* [Create Vertical Barchart stacked](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Vertical_Barchart_stacked.ipynb)
* [Create Waterfall chart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Plotly/Plotly_Create_Waterfall_chart.ipynb)

## PostgresSQL
* [Get data from database](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PostgresSQL/PostgresSQL_Get_data_from_database.ipynb)

## PowerPoint
* [Add Slide With Image](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PowerPoint/PowerPoint_Add_Slide_With_Image.ipynb)
* [Add Slide With Textbox](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PowerPoint/PowerPoint_Add_Slide_With_Textbox.ipynb)
* [Add Slide With Title Subtitle](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PowerPoint/PowerPoint_Add_Slide_With_Title_Subtitle.ipynb)
* [Add title + line in presentation](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PowerPoint/PowerPoint_Add_title_%2B_line_in_presentation.ipynb)
* [Create Presentation](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PowerPoint/PowerPoint_Create_Presentation.ipynb)
* [Set portrait format](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PowerPoint/PowerPoint_Set_portrait_format.ipynb)

## PyCaret
* [Automl classification](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PyCaret/PyCaret_automl_classification.ipynb)
* [Automl regression](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PyCaret/PyCaret_automl_regression.ipynb)

## PyPI
* [- Get number of downloads any package](https://github.com/jupyter-naas/awesome-notebooks/tree/master/PyPI/PyPI%20-%20Get_number_of_downloads_any_package.ipynb)

## Python
* [Consolidate Excel files](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Consolidate_Excel_files.ipynb)
* [Convert CSV to Excel](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Convert_CSV_to_Excel.ipynb)
* [Convert PNG Images To JPG](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Convert_PNG_Images_To_JPG.ipynb)
* [Copy files and subdir from directory to another directory](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Copy_files_and_subdir_from_directory_to_another_directory.ipynb.ipynb)
* [Create Strong Random Password](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Create_Strong_Random_Password.ipynb)
* [Create dataframe from lists](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Create_dataframe_from_lists.ipynb)
* [Create dict from lists](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Create_dict_from_lists.ipynb)
* [Create directory](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Create_directory.ipynb)
* [Download Image from URL](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Download_Image_from_URL.ipynb)
* [Download PDF from URL](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Download_PDF_from_URL.ipynb)
* [Find Phone Number in string](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Find_Phone_Number_in_string.ipynb)
* [Get Word Definition and Translation](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Get_Word_Definition_and_Translation.ipynb)
* [Get all files from directory](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Get_all_files_from_directory.ipynb)
* [Locate Addresses](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Locate_Addresses.ipynb)
* [Locate Coordinates](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Locate_Coordinates.ipynb)
* [Looping Over Dataframe](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Looping_Over_Dataframe.ipynb)
* [Match pattern with regular expressions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Match_pattern_with_regular_expressions.ipynb)
* [Organize Directories based on file types](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Organize_Directories_based_on_file_types.ipynb)
* [Rename file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Rename_file.ipynb)
* [Using datetime library](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Python/Python_Using_datetime_library.ipynb)

## Pyvis
* [Create a network visualization](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Pyvis/Pyvis_Create_a_network_visualization.ipynb)

## Qonto
* [Get cash position trend](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_cash_position_trend.ipynb)
* [Get organizations](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_organizations.ipynb)
* [Get positions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_positions.ipynb)
* [Get statement](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_statement.ipynb)
* [Get statement barline](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_statement_barline.ipynb)
* [Get statement ranking by category](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_statement_ranking_by_category.ipynb)
* [Get statement summary by operation type](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_statement_summary_by_operation_type.ipynb)
* [Get transactions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Get_transactions.ipynb)
* [Releve de compte augmente](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Qonto/Qonto_Releve_de_compte_augmente.ipynb)

## Quandl
* [Get data from API](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Quandl/Quandl_Get_data_from_API.ipynb)
* [Get data from CSV](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Quandl/Quandl_Get_data_from_CSV.ipynb)

## Reddit
* [Get Hot Posts From Subreddit](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Reddit/Reddit_Get_Hot_Posts_From_Subreddit.ipynb)

## Redshift
* [Connect with SQL Magic and IAM Credentials](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Redshift/Redshift_Connect_with_SQL_Magic_and_IAM_Credentials.ipynb)

## Remoteok
* [Get jobs from categories](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Remoteok/Remoteok_Get_jobs_from_categories.ipynb)
* [Post daily jobs on slack](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Remoteok/Remoteok_Post_daily_jobs_on_slack.ipynb)

## Remotive
* [Get categories from job](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Remotive/Remotive_Get_categories_from_job.ipynb)
* [Get jobs from categories](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Remotive/Remotive_Get_jobs_from_categories.ipynb)
* [Post daily jobs on slack](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Remotive/Remotive_Post_daily_jobs_on_slack.ipynb)
* [Send jobs to gsheet](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Remotive/Remotive_Send_jobs_to_gsheet.ipynb)

## SAP-HANA
* [Query data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/SAP-HANA/SAP-HANA_Query_data.ipynb)

## SendGrid
* [Get all messages](https://github.com/jupyter-naas/awesome-notebooks/tree/master/SendGrid/SendGrid_Get_all_messages.ipynb)
* [Send message](https://github.com/jupyter-naas/awesome-notebooks/tree/master/SendGrid/SendGrid_Send_message.ipynb)

## Sendinblue
* [Get no of emails opened](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Sendinblue/Sendinblue_Get_no_of_emails_opened.ipynb)
* [Get no of emails sent](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Sendinblue/Sendinblue_Get_no_of_emails_sent.ipynb)
* [Get no of spam reports](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Sendinblue/Sendinblue_Get_no_of_spam_reports.ipynb)
* [Get no of undelivered emails](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Sendinblue/Sendinblue_Get_no_of_undelivered_emails.ipynb)

## SharePoint
* [Get file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/SharePoint/SharePoint_Get_file.ipynb)
* [List folder](https://github.com/jupyter-naas/awesome-notebooks/tree/master/SharePoint/SharePoint_List_folder.ipynb)
* [Upload file](https://github.com/jupyter-naas/awesome-notebooks/tree/master/SharePoint/SharePoint_Upload_file.ipynb)

## Slack
* [Add new user to Google Sheets](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Slack/Slack_Add_new_user_to_Google_Sheets.ipynb)
* [Follow number of users in workspace](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Slack/Slack_Follow_number_of_users_in_workspace.ipynb)
* [Send message](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Slack/Slack_Send_message.ipynb)

## Snowflake
* [Basics and data querying](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Snowflake/Snowflake_Basics_and_data_querying.ipynb)
* [Ingest csv data from local stage](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Snowflake/Snowflake_Ingest_csv_data_from_local_stage.ipynb)
* [Ingest data from AWS external stages](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Snowflake/Snowflake_Ingest_data_from_AWS_external_stages.ipynb)
* [Ingest json data from local stage](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Snowflake/Snowflake_Ingest_json_data_from_local_stage.ipynb)

## Societe.com
* [Get company details](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Societe.com/Societe.com_Get_company_details.ipynb)
* [Get verif.com](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Societe.com/Societe.com_Get_verif.com.ipynb)

## Spotify
* [Create Radar Chart to analyze Playlist](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Spotify/Spotify_Create_Radar_Chart_to_analyze_Playlist.ipynb)

## Streamlit
* [Create prediction app](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Streamlit/Streamlit_Create_prediction_app.ipynb)

## Stripe
* [Get balances](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Stripe/Stripe_Get_balances.ipynb)
* [Get charges](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Stripe/Stripe_Get_charges.ipynb)
* [Get customers](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Stripe/Stripe_Get_customers.ipynb)

## Telegram
* [Create crypto sentiment bot](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Telegram/Telegram_Create_crypto_sentiment_bot.ipynb)

## Text
* [Reformat  Without Spaces](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Text/Text_Reformat_Text_Without_Spaces.ipynb)

## Thinkific
* [Get users](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Thinkific/Thinkific_Get_users.ipynb)
* [Send users](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Thinkific/Thinkific_Send_users.ipynb)

## TikTok
* [Get user stats](https://github.com/jupyter-naas/awesome-notebooks/tree/master/TikTok/TikTok_Get_user_stats.ipynb)
* [Get videos stats](https://github.com/jupyter-naas/awesome-notebooks/tree/master/TikTok/TikTok_Get_videos_stats.ipynb)

## Trello
* [Get board data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Trello/Trello_Get_board_data.ipynb)

## Twilio
* [Make Call](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twilio/Twilio_Make_Call.ipynb)
* [Send SMS](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twilio/Twilio_Send_SMS.ipynb)

## Twitter
* [Get posts stats](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Get_posts_stats.ipynb)
* [Get tweets from search](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Get_tweets_from_search.ipynb)
* [Get tweets stats from profile](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Get_tweets_stats_from_profile.ipynb)
* [Get user data](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Get_user_data.ipynb)
* [Post text and image](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Post_text_and_image.ipynb)
* [Schedule posts](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Schedule_posts.ipynb)
* [Send posts stats to Notion](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Twitter/Twitter_Send_posts_stats_to_Notion.ipynb)

## Typeform
* [Log New  Entries In Notion Databases](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Typeform/Typeform_Log_New_Typeform_Entries_In_Notion_Databases.ipynb)

## US Bureau of Labor Statistics
* [Follow CPI](https://github.com/jupyter-naas/awesome-notebooks/tree/master/US%20Bureau%20of%20Labor%20Statistics/US_Bureau_of_Labor_Statistics_Follow_CPI.ipynb)

## Vizzu
* [Create interactive data story](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Vizzu/Vizzu_Create_interactive_data_story.ipynb)

## WSR
* [WHI Create indicator](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WSR/WHI_Create_indicator.ipynb)
* [Get daily Covid19 active cases trend JHU](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WSR/WSR_Get_daily_Covid19_active_cases_trend_JHU.ipynb)
* [Get daily Covid19 active cases worldmap JHU](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WSR/WSR_Get_daily_Covid19_active_cases_worldmap_JHU.ipynb)

## WindsorAI
* [Create Dash app to query AP](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WindsorAI/WindsorAI_Create_Dash_app_to_query_AP.ipynb)

## WorldBank
* [GDP contributors](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_GDP_contributors.ipynb)
* [GDP per capita and growth](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_GDP_per_capita_and_growth.ipynb)
* [GDP per country and evolution](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_GDP_per_country_and_evolution.ipynb)
* [Gini index](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_Gini_index.ipynb)
* [Most populated countries](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_Most_populated_countries.ipynb)
* [Richest countries top10](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_Richest_countries_top10.ipynb)
* [World employment by sector](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_World_employment_by_sector.ipynb)
* [World population and density](https://github.com/jupyter-naas/awesome-notebooks/tree/master/WorldBank/WorldBank_World_population_and_density.ipynb)

## Worldometer
* [World population evolution and projections](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Worldometer/Worldometer_World_population_evolution_and_projections.ipynb)

## XGBoost
* [Binary classification example with hyper-parameters optimization](https://github.com/jupyter-naas/awesome-notebooks/tree/master/XGBoost/XGBoost_Binary_classification_example_with_hyper-parameters_optimization.ipynb)

## XML
* [Transform sitemap to dataframe](https://github.com/jupyter-naas/awesome-notebooks/tree/master/XML/XML_Transform_sitemap_to_dataframe.ipynb)

## YahooFinance
* [Candlestick chart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Candlestick_chart.ipynb)
* [Cryptocurrencies heatmap correlation graph](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Cryptocurrencies_heatmap_correlation_graph.ipynb)
* [Display chart from ticker](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Display_chart_from_ticker.ipynb)
* [Find the stock with closest performance using KNN](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Find_the_stock_with_closest_performance_using_KNN.ipynb)
* [Get Brent Crude Oil trend and predictions](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Get_Brent_Crude_Oil_trend_and_predictions.ipynb)
* [Get Stock Update](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Get_Stock_Update.ipynb)
* [Get USDEUR data and chart](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Get_USDEUR_data_and_chart.ipynb)
* [Get data from ticker](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Get_data_from_ticker.ipynb)
* [Send daily prediction to Email](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Send_daily_prediction_to_Email.ipynb)
* [Send daily prediction to Notion](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Send_daily_prediction_to_Notion.ipynb)
* [Send daily prediction to Slack](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YahooFinance/YahooFinance_Send_daily_prediction_to_Slack.ipynb)

## YouTube
* [Download video](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Download_video.ipynb)
* [Extract and summarize transcript](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Extract_and_summarize_transcript.ipynb)
* [Extract transcript from video](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Extract_transcript_from_video.ipynb)
* [Get statistics from channel](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Get_statistics_from_channel.ipynb)
* [Get statistics from video](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Get_statistics_from_video.ipynb)
* [Get uploads from channel](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Get_uploads_from_channel.ipynb)
* [Send track to Spotify](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Send_track_to_Spotify.ipynb)
* [Send video stats to Notion](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Send_video_stats_to_Notion.ipynb)
* [Summarize video](https://github.com/jupyter-naas/awesome-notebooks/tree/master/YouTube/YouTube_Summarize_video.ipynb)

## ZIP
* [Extract files](https://github.com/jupyter-naas/awesome-notebooks/tree/master/ZIP/ZIP_Extract_files.ipynb)

## Zapier
* [Trigger workflow](https://github.com/jupyter-naas/awesome-notebooks/tree/master/Zapier/Zapier_Trigger_workflow.ipynb)

## spaCy
* [SpaCy Build a sentiment analysis model using Twitter](https://github.com/jupyter-naas/awesome-notebooks/tree/master/spaCy/SpaCy_Build_a_sentiment_analysis_model_using_Twitter.ipynb)



<br/>

Contact us on support@naas.ai if you need any help or join our [Slack community](https://join.slack.com/t/naas-club/shared_invite/zt-1970s5rie-dXXkigAdEJYc~LPdQIEaLA)
