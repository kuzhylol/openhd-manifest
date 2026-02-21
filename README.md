# openhd-manifest

# Install repo
    mkdir -p ~/bin
    curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo
    export PATH=~/bin:$PATH

# Initialize the workspace
    mkdir openhd
    cd openhd
    repo init -u git@github.com:kuzhylol/openhd-manifest.git -b main -m openhd.xml

# Sync all projects
    repo sync
