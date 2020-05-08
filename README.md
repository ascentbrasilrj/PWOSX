


	Mac OS X Server
	Perfect World Server
	Build PWServer 0.1.0



[Command List]

[Install xCode]
$ xcode-select --install

[Install Brew]
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

[Install Wget]
$ brew install wget


[Permission PWOSX Folder]
$ unzip x PWOSX.zip
$ sudo chmod 777 PWOSX

[Install JDK1.8.0]
$ brew cask install java

[Then install MySQL using Homebrew]

$ brew install mysql
$ brew tap homebrew/services 
$ brew services start mysql 
$ mysqladmin -u root password 'yourpassword'

[Install GCC C++]

$ brew install boost
$ brew install gcc@7
