# whereIsCage

1.	Tailor est un outil pour améliorer la qualité de code. Pour l'installer :

Requires Java (JRE or JDK) Version 8 or above: Java SE Downloads

- Homebrew, Linuxbrew
brew install tailor

- Mac OS X (10.10+), Linux
curl -fsSL https://tailor.sh/install.sh | sh

- Windows (10+)
iex (new-object net.webclient).downloadstring('https://tailor.sh/install.ps1')

Installer tailor dans votre projet automatiquement :
tailor --xcode /path/to/demo.xcodeproj/
Cela devrait créer un script dans le projet Xcode.

Install homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

If getting error 
"	activesupport requires Ruby version >= 2.2.2."
then you should run the following command:
brew install ruby
