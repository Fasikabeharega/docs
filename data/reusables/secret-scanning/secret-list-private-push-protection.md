Provider | Supported secret | Secret type
--- | --- | ---
Adafruit IO | Adafruit IO Key | adafruit_io_key
Alibaba Cloud | Alibaba Cloud Access Key ID with Alibaba Cloud Access Key Secret| alibaba_cloud_access_key_id </br>alibaba_cloud_access_key_secret
Amazon | Amazon OAuth Client ID with Amazon OAuth Client Secret | amazon_oauth_client_id </br>amazon_oauth_client_secret
Amazon Web Services (AWS) | Amazon AWS Access Key ID with Amazon AWS Secret Access Key | aws_access_key_id </br>aws_secret_access_key
Amazon Web Services (AWS) | Amazon AWS Session Token with Amazon AWS Temporary Access Key ID and Amazon AWS Secret Access Key | aws_session_token </br>aws_temporary_access_key_id </br>aws_secret_access_key
Asana | Asana {% data variables.product.pat_generic_title_case %} | asana_personal_access_token
Atlassian | Bitbucket Server {% data variables.product.pat_generic_title_case %} | bitbucket_server_personal_access_token
Azure | Azure Active Directory Application Secret | azure_active_directory_application_secret
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
Azure | Azure Batch Key Identifiable | azure_batch_key_identifiable{% endif %}
Azure | Azure Cache for Redis Access Key | azure_cache_for_redis_access_key
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
Azure | Azure CosmosDB Key Identifiable | azure_cosmosdb_key_identifiable{% endif %}
Azure | Azure DevOps {% data variables.product.pat_generic_title_case %} | azure_devops_personal_access_token
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
Azure | Azure ML Studio (classic) Web Service Key | azure_ml_web_service_classic_identifiable_key{% endif %}
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
Azure | Azure Search Admin Key | azure_search_admin_key
Azure | Azure Search Query Key | azure_search_query_key{% endif %}
{%- ifversion fpt or ghec or ghes > 3.6 or ghae > 3.6 %}
Azure | Azure Storage Account Key | azure_storage_account_key{% endif %}
Checkout.com | Checkout.com Production Secret Key | checkout_production_secret_key
{%- ifversion fpt or ghec or ghes > 3.7 or ghae > 3.7 %}
Chief Tools | Chief Tools Token | chief_tools_token{% endif %}
Clojars | Clojars Deploy Token | clojars_deploy_token
Databricks | Databricks Access Token | databricks_access_token
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
DevCycle | DevCycle Client API Key | devcycle_client_api_key
DevCycle | DevCycle Server API Key | devcycle_server_api_key
DevCycle | DevCycle Mobile API Key | devcycle_mobile_api_key{% endif %}
DigitalOcean | DigitalOcean {% data variables.product.pat_generic_title_case %} | digitalocean_personal_access_token
DigitalOcean | DigitalOcean OAuth Token | digitalocean_oauth_token
DigitalOcean | DigitalOcean Refresh Token | digitalocean_refresh_token
DigitalOcean | DigitalOcean System Token | digitalocean_system_token
{%- ifversion fpt or ghec or ghes > 3.7 or ghae > 3.7 %}
Discord | Discord API Token V2 | discord_api_token_v2{% endif %}
Discord | Discord Bot Token | discord_bot_token
Doppler | Doppler Personal Token | doppler_personal_token
Doppler | Doppler Service Token | doppler_service_token
Doppler | Doppler CLI Token | doppler_cli_token
Doppler | Doppler SCIM Token | doppler_scim_token
Doppler | Doppler Audit Token | doppler_audit_token
Dropbox | Dropbox Short Lived Access Token | dropbox_short_lived_access_token
Duffel | Duffel Live Access Token | duffel_live_access_token
EasyPost | EasyPost Production API Key | easypost_production_api_key
{%- ifversion fpt or ghec or ghes > 3.7 or ghae > 3.7 %}
Figma | Figma {% data variables.product.pat_generic_title_case %} | figma_pat{% endif %}
Flutterwave | Flutterwave Live API Secret Key | flutterwave_live_api_secret_key
Fullstory | FullStory API Key | fullstory_api_key
GitHub | GitHub {% data variables.product.pat_generic_title_case %} | github_personal_access_token
GitHub | GitHub OAuth Access Token | github_oauth_access_token
GitHub | GitHub Refresh Token | github_refresh_token
GitHub | GitHub App Installation Access Token | github_app_installation_access_token
GitHub | GitHub SSH Private Key | github_ssh_private_key
Google | Google Cloud Storage Service Account Access Key ID with Google Cloud Storage Access Key Secret | google_cloud_storage_service_account_access_key_id </br>google_cloud_storage_access_key_secret
Google | Google Cloud Storage User Access Key ID with Google Cloud Storage Access Key Secret | google_cloud_storage_user_access_key_id </br>google_cloud_storage_access_key_secret
Google | Google OAuth Client ID with Google OAuth Client Secret | google_oauth_client_id </br>google_oauth_client_secret
Grafana | Grafana API Key | grafana_api_key
{%- ifversion fpt or ghec or ghes > 3.7 or ghae > 3.7 %}
Grafana | Grafana Cloud API Key | grafana_cloud_api_key
Grafana | Grafana Cloud API Token | grafana_cloud_api_token
Grafana | Grafana Project API Key | grafana_project_api_key
Grafana | Grafana Project Service Account Token | grafana_project_service_account_token{% endif %}
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
HashiCorp | HashiCorp Vault Batch Token (v1.10.0+) | hashicorp_vault_batch_token
HashiCorp | HashiCorp Vault Root Service Token (v1.10.0+) | hashicorp_vault_root_service_token
HashiCorp | HashiCorp Vault Service Token (v1.10.0+) | hashicorp_vault_service_token{% endif %}
Hubspot | Hubspot API Key | hubspot_api_key
{%- ifversion fpt or ghec or ghes > 3.7 or ghae > 3.7 %}
Hubspot | Hubspot API Personal Access Key | hubspot_api_personal_access_key{% endif %}
Intercom | Intercom Access Token | intercom_access_token
{%- ifversion fpt or ghec or ghes > 3.6 or ghae > 3.6 %}
JFrog | JFrog Platform Access Token | jfrog_platform_access_token
JFrog | JFrog Platform API Key | jfrog_platform_api_key{% endif %}
Ionic | Ionic {% data variables.product.pat_generic_title_case %} | ionic_personal_access_token
Ionic | Ionic Refresh Token | ionic_refresh_token
Linear | Linear API Key | linear_api_key
Linear | Linear OAuth Access Token | linear_oauth_access_token
{%- ifversion fpt or ghec or ghes > 3.8 or ghae > 3.8 %}
LogicMonitor | LogicMonitor Bearer Token | logicmonitor_bearer_token
LogicMonitor | LogicMonitor LMV1 Access Key | logicmonitor_lmv1_access_key{% endif %}
Midtrans | Midtrans Production Server Key | midtrans_production_server_key
New Relic | New Relic Personal API Key | new_relic_personal_api_key
New Relic | New Relic REST API Key | new_relic_rest_api_key
New Relic | New Relic Insights Query Key | new_relic_insights_query_key
npm | npm Access Token | npm_access_token
NuGet | NuGet API Key | nuget_api_key
Onfido | Onfido Live API Token | onfido_live_api_token
OpenAI | OpenAI API Key | openai_api_key
PlanetScale | PlanetScale Database Password | planetscale_database_password
PlanetScale | PlanetScale OAuth Token | planetscale_oauth_token
PlanetScale | PlanetScale Service Token | planetscale_service_token
Postman | Postman API Key | postman_api_key
{%- ifversion fpt or ghec or ghes > 3.9 or ghae > 3.9 %}
Postman | Postman Collection Key | postman_collection_key{% endif %}
{%- ifversion fpt or ghec or ghes > 3.6 or ghae > 3.6 %}
Prefect | Prefect Server API Key | prefect_server_api_key
Prefect | Prefect User API Key | prefect_user_api_key{% endif %}
Proctorio | Proctorio Secret Key | proctorio_secret_key
{%- ifversion fpt or ghec or ghes > 3.6 or ghae > 3.6 %}
ReadMe | ReadMe API Access Key | readmeio_api_access_token{% endif %}
{%- ifversion fpt or ghec or ghes > 3.5 or ghae > 3.5 %}
redirect.pizza | redirect.pizza API Token | redirect_pizza_api_token{% endif %}
Samsara | Samsara API Token | samsara_api_token
Samsara | Samsara OAuth Access Token | samsara_oauth_access_token
SendGrid | SendGrid API Key | sendgrid_api_key
Sendinblue | Sendinblue API Key | sendinblue_api_key
Sendinblue | Sendinblue SMTP Key | sendinblue_smtp_key
Shippo | Shippo Live API Token | shippo_live_api_token
Shopify | Shopify App Shared Secret | shopify_app_shared_secret
Shopify | Shopify Access Token | shopify_access_token
Slack | Slack API Token | slack_api_token
Stripe | Stripe Live API Secret Key | stripe_api_key
{%- ifversion fpt or ghec or ghes > 3.7 or ghae > 3.7 %}
Telnyx | Telnyx API V2 Key | telnyx_api_v2_key{% endif %}
Tencent Cloud | Tencent Cloud Secret ID | tencent_cloud_secret_id
Typeform | Typeform {% data variables.product.pat_generic_title_case %} | typeform_personal_access_token
{%- ifversion fpt or ghec or ghes > 3.6 or ghae > 3.6 %}
Uniwise | WISEflow API Key | wiseflow_api_key{% endif %}
WorkOS | WorkOS Production API Key | workos_production_api_key
{%- ifversion fpt or ghec or ghes > 3.6 or ghae > 3.6 %}
Zuplo | Zuplo Consumer API Key | zuplo_consumer_api_key{% endif %}
