#Axelerant Site API Key Drupal 8 module.

  *Introduction
  *Requirements
  *Installation
  *Configuration
  *Resources Used
  *Time taken
  *Author


INTRODUCTION
----------------------

Drupal 8 module provides a url to get Json representation of a page type node.


REQUIRMENTS
----------------------

No specific requirement.


INSTALLATION
----------------------

1. Install as you would  normally install a Druapl contributed module. 
* Visit: https://www.drupal.org/docs/8/extending-drupal-8/installing-drupal-8-modules
for further informtaion.


CONFIGURATION
----------------------

1. Go to Administrator > Configuration > System > Basic site settings.
or visit '/admin/config/system/site-information'.

2. In the SITE DETAILS section add 'Site API Key'.

3. Configure permissions at /admin/people/permissions under 
'Axelerant Site API Key Custom Module'.

3. Access the json representation of respective page type node by visiting the 
url '/page_json/{site_api_key}/{node_id}'.


RESOURCES USED
----------------------

https://api.drupal.org/api/drupal/core%21lib%21Drupal%21Core%21Form%21form.api.php/function/hook_form_FORM_ID_alter/8.2.x
https://www.drupal.org/node/2407153
https://api.drupal.org/api/drupal/core!includes!bootstrap.inc/function/drupal_set_message/8.2.x
https://www.drupal.org/docs/8/api/routing-system/structure-of-routes
https://www.drupal.org/docs/8/api/routing-system/using-parameters-in-routes
https://api.drupal.org/api/drupal/vendor%21symfony%21http-foundation%21JsonResponse.php/class/JsonResponse/8.2.x


TIME TAKEN
----------------------

It took 3 Hours to build this module.


AUTHORS
----------------------

Akansha Saxena
Twitter - @saxenaakansa30
Github - https://github.com/saxenaakansha30/
Drupal Profile - https://www.drupal.org/u/saxenaakansha30gmailcom
