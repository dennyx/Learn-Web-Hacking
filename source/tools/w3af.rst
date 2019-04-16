w3af
================================

Install 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. code-block:: shell
    git clone https://github.com/andresriancho/w3af.git sqlmap
    apt-get install libxml2-dev libxslt-dev zlib1g-dev npm libegl1-mesa libegl1-mesa-dev
    npm i -g npm
    npm config set registry https://registry.npm.taobao.org --global
    npm config set disturl https://npm.taobao.org/dist --global
    npm config get registry
    ./w3af_gui
    sh /tmp/w3af_dependency_install.sh
    wget http://ftp.de.debian.org/debian/pool/main/i/icu/libicu57_57.1-6+deb9u2_amd64.deb
    wget http://ftp.br.debian.org/debian/pool/main/p/pywebkitgtk/python-webkit_1.1.8-3_amd64.deb
    wget http://ftp.br.debian.org/debian/pool/main/w/webkitgtk/libjavascriptcoregtk-1.0-0_2.4.11-3_amd64.deb
    wget http://ftp.br.debian.org/debian/pool/main/p/python-support/python-support_1.0.15_all.deb
    wget http://ftp.br.debian.org/debian/pool/main/w/webkitgtk/libwebkitgtk-1.0-0_2.4.11-3_amd64.deb
    dpkg -i libicu57_57.1-6+deb9u2_amd64.deb
    dpkg -i libjavascriptcoregtk-1.0-0_2.4.11-3_amd64.deb
    dpkg -i python-support_1.0.15_all.deb
    dpkg -i libwebkitgtk-1.0-0_2.4.11-3_amd64.deb
    apt-get install libpango1.0-dev
    apt --fix-broken install
    dpkg -i python-webkit_1.1.8-3_amd64.deb

Usage
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
