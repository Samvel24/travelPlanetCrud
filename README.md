# Travel reservation management system
 
version: v1.1.2
 
Travel reservation management system (Sistema adminsitrador de reservas de viajes usando las tecnologias Laravel y Auth0)
 
 
### SET UP
* Requirements (Already covered with Docker deployment)
	1. Apache/2.4.27 or greater.
	2. MySQL 5.7 or greater.
	3. PHP/7.2.24 or greater.
  
* App Configuration
    1. Add host `travel-planet-crud.localhost`,
        	see [Edit hosts](https://dinahosting.com/ayuda/como-modificar-el-fichero-hosts).        	
    2. Create `.env` file from `.env.example` and set it.
	3. Give Folder permissions:	
	    ```
	    sudo chown -R $USER:www-data storage;
        chmod -R 775 storage;
        sudo chown -R $USER:www-data bootstrap/cache;
        chmod -R 775 bootstrap/cache;
	    ```
    4. Set `APP_KEY=base64:7XouBv3l67xQR3hT+/1d78P1c+wqNOAjOHIhfd1/hAU=` at `.env`.
	5. Run `composer install`.
	6. Run `php artisan storage:link`. 
	7. Run `php artisan migrate`. 	

* Browse at [travel-planet-crud.localhost](http://travel-planet-crud.localhost).
 
* Login at [travel-planet-crud.localhost/login](http://travel-planet-crud.localhost/login).
 
### CONTRIBUTION: Guidelines & Documentation
* Git :
    [Gitflow](http://nvie.com/posts/a-successful-git-branching-model).
* Back End:
    [Laravel 6.x](https://laravel.com/docs/6.x),
* Front End:
    [Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction),
 
***

2021 [Samuel Ramirez](https://github.com/Samvel24/)