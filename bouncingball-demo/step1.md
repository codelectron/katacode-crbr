
You will see the commands execute within the terminal for you, wait till they are complete and the screen is cleared


# Fetch Source
Execute `git clone https://github.com/codelectron/crossbar-examples`{{execute}} to fetch the example source code.

# Fetch Bouncing ball source
Execute `git clone https://github.com/oddjobz/crossbar_ball_demo`{{execute}} to fetch the example source code.

# Start Crossbar.io in Dockers 

Execute `  docker run -d -v  $PWD/crossbar-examples/getting-started:/node -u 0 --rm --name=crossbar -it -p 8080:8080 crossbario/crossbar`{{execute}} to run Crossbar.io in dockers with configuration mounted from getting-started folder.


