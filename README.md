# egmde-snap

Sample project for snapping up egmde.

## From the snap store

    sudo snap install --classic --beta egmde

## Run as X11 app desktop

    snap run egmde

## Run as desktop session

Log out and select "egmde" session when logging back in.

## Build & install

Check out the code:

    git clone https://github.com/MirServer/egmde-snap.git
    cd egmde-snap

Build and install snap:

    snapcraft 
    snap install --dangerous --classic ./egmde*.snap
