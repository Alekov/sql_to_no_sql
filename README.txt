if error - "Authentication plugin 'caching_sha2_password' cannot be loaded: The specified module could not be found." Do the following:

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'xxx';

Project uses mysql2 adapter.

Ruby - 2.5.5-1-x86