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