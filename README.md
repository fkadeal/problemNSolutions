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
# Install composer dependencies
composer install --no-dev --no-interaction --prefer-dist --optimize-autoloader

# Clear the old cache
php artisan clear-compiled

# Recreate cache
php artisan optimize 

# Run database migrations
php artisan migrate --force  
# Exit maintenance mode
php artisan up