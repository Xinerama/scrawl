# scrawl font
This contains the scrawl font that I love and use

## Usage for terminal
- Clone and copy the scrawl* font files to /usr/lib/kbd/consolefonts/
- Copy the vconsole.conf file to /etc/ 

## Adding to local fonts
- mkdir -p /usr/local/share/fonts/scrawl
- mkfontdir /usr/local/share/fonts/scrawl
- cp -v scrawl*.* /usr/local/share/fonts/scrawl
- sudo chown -R root: /usr/local/share/fonts/scrawl
- sudo chmod 644 /usr/local/share/fonts/scrawl/*
- sudo restorecon -vFr /usr/local/share/fonts/scrawl
- fc-cache -v
