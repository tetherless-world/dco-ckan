# dco-ckan
DCO CKAN Installation

To get the styling to show up need to do the following
 % paster --plugin=ckan minify ckan/public/base -c development.ini
 % paster --plugin=ckan less -c development.ini
 % service apache2 restart
