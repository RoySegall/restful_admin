restful_admin
=============

Restful admin is a basic idea that will help you manage through a single controll panel. Each Drupal installation
will have a restful plugin. The restful plugin will write the restul admin dashboard as an authorized entity to 
invoke actions. Action such as:
* Manage entitites
* Get the watchdog records
* Log in as a specific user

Each user in the dashboard will have permission that he can act upon each installation:
On one site user can delete user but in another he can only edit comments.

The restful admin will also provide a fluid restful. Fluid restful is a way to create your restful plugins through api:
* Create restful callbacks
* Expose fields in a desirable way
* Create callbacks for those via the UI
* Define rate limits from UI
* Get stats for each restful plugin
