# How-To-Install-Qt-in-Ubuntu

# Install Qt Creator
sudo apt-get install build-essential
sudo apt-get install qtcreator
sudo apt-get install qt5-default

# Install documentation and examples

If Qt Creator is installed thanks to the Ubuntu Sofware Center or thanks to the synaptic package manager, documentation for Qt Creator is not installed. Hitting the F1 key will show you the following message : “No documentation available”. This can easily be solved by installing the Qt documentation:

sudo apt-get install qt5-doc

And eventually:

sudo apt-get install qt5-doc-html qtbase5-doc-html

If examples are still missing:

sudo apt-get install qtbase5-examples

Restart Qt Creator to make the documentation available.
