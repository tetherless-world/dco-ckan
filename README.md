# dco-ckan
DCO CKAN Installation

To get the styling to show up need to do the following

1. paster --plugin=ckan minify ckan/public/base -c development.ini
1. paster --plugin=ckan less -c development.ini
1. service apache2 restart
