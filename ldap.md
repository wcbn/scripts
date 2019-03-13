Query all members of a group e.g. rfaa-mod

    ldapsearch -x -W -v -H ldaps://ldap.umich.edu:636 -b 'dc=umich,dc=edu' "(&(objectClass=umichGroup)(umichGroupEmail=rfaa-mod))" 
