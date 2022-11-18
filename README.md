# problemNSolutions
list of problems and there solutions that occurs while developing 

# Vue filters 
using Vue filters inside funcitons

## solution : 
        this.$options.filters.capitalize(this.word);
        link 
        https://stackoverflow.com/questions/33639312/in-vue-js-call-a-filter-from-a-method-inside-the-vue-instance

 
## deployment  

        php artisan down 

        composer install --no-dev --no-interaction --prefer-dist --optimize-autoloader
        
        php artisan clear-compiled
        
        php artisan optimize 
        
        php artisan migrate --force  
        
        php artisan up
=======


#Your requirements could not be resolved to an installable set of packages" error?
## solution :
        sudo apt-get install php8.0-curl php8.0-gd php8.0-xsl php8.0-dom
        https://stackoverflow.com/questions/29318709/how-can-i-resolve-your-requirements-could-not-be-resolved-to-an-installable-set


# laravel sanctom error = message : "CSRF token mismatch."
## solution for this
         If u are trying it on localhost, so u can try this one: (.env) settings: SESSION_DOMAIN=localhost SANCTUM_STATEFUL_DOMAINS=localhost
         
>>>>>>> parent of 0259568 (Update README.md)
