#Gallery
Just a simple gallery app written in golang

##dependancies
libvips (for the vipsthumbnail binary)  
golang  
BurntSushi: toml (go get github.com/BurntSushi/toml)  
google maps API key  

##setup
 1 copy config.toml.example to config.toml  
 2 put your gmaps api key into config.toml  
 3 make a directory called 'hikedata'  
 4 in hike data make a directory for each album  
 5 in each album make two directories: 'img', 'pan'  
 6 put images in to the img dir and panoramics into the pan dir  
 7 run `go build server.go`  
 8 run `server`  