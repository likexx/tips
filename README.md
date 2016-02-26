# tips
weird undocumented tips for software engineers

1. Non-root user running docker tool on OSX

You'll have eDSRecordNotFound error or something, which means you don't have root permission. You'll have to run this in terminal:

sudo "/Applications/Docker/Docker Quickstart Terminal.app/Contents/Resources/Scripts/start.sh"

or

sudo bash "/Applications/Docker/Docker Quickstart Terminal.app/Contents/Resources/Scripts/start.sh"
