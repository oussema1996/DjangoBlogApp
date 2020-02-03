# DjangoBlogApp
Clone This Project

# in th project repository run 

docker-compose build

docker-compose up -d

##### ps: Wops, at this point did your server crash because it could not find the MySQL database through the hostname ‘db’? Don’t worry, just run docker-compose up -d again until obeys you

# set Database run 

docker-compose run web python manage.py migrate






