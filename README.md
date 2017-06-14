# screen
# create a screen
screen -S name

# resume a screen

screen -r name

# list all the screen  
screen -ls

# go back to the attached screen after reconnect to the server

screen -D -r name  

# PYTHON Simple http server

python -m SimpleHTTPServer 8000
