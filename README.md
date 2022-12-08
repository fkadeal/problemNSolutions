# problemNSolutions
list of problems and there solutions that occurs while developing 

# Vue filters 
using Vue filters inside funcitons

## solution : 
        this.$options.filters.capitalize(this.word);
        link 
        https://stackoverflow.com/questions/33639312/in-vue-js-call-a-filter-from-a-method-inside-the-vue-instance


#Your requirements could not be resolved to an installable set of packages" error?
## solution :
        sudo apt-get install php8.0-curl php8.0-gd php8.0-xsl php8.0-dom
        https://stackoverflow.com/questions/29318709/how-can-i-resolve-your-requirements-could-not-be-resolved-to-an-installable-set


# laravel sanctom error = message : "CSRF token mismatch."
## solution for this
         If u are trying it on localhost, so u can try this one: (.env) settings: SESSION_DOMAIN=localhost SANCTUM_STATEFUL_DOMAINS=localhost
         
# laravel error : the redis extention to be enable ,
        ## SOLUTION I GET , IS 
        https://romanmiranda.com/install-php-redis-extension-in-mac-with-homebrew/

        or just run:  pecl install redis
        it works on php 8.0 and using mac 

# Enable TCP/IP Android Debugging 
        ## solution https://ihilalahmadd.medium.com/how-to-debug-android-application-over-wifi-without-usb-cable-d29927891614
        
# error ubuntu not init with systemd: solution is to run Script to enable systemd support on current Ubuntu WSL2
        ## solution https://www.youtube.com/watch?v=oILBqhnyCPA&t=10s
                https://github.com/DamionGans/ubuntu-wsl2-systemd-script
