some helpful links with trying to setup Laravel sail on local with docker and wsl ubuntu
and dbeaver on main machine as db client

// this shows command for sail down
https://laracasts.com/discuss/channels/code-review/access-denied-for-user-sail-at-to-database
https://laracasts.com/discuss/channels/devops/laravel-sail-cannot-connect-to-the-database


Note
- in .env file change/add the FORWARD_DB_PORT value to 3307 then in dbeaver connection setting change the port to 3307 

Also Note
- remember that the included files are just references although u included these files yourself (im talking to future me) and is working during the time of this writing on my version(current me which is past), these files may not be compatible with your current Laravel/sail version