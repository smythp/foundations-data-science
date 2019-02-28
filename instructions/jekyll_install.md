Installation


# Windows

Note that Jekyll does not officially support Windows. But it still works.

Download the latest version of (RubyInstaller for Windows)[https://rubyinstaller.org/downloads/]. This should be the first item under the heading "WITH DEVKIT."

Run the executable installer. Use default options.

At installation completion, leave the box checked that allows installation to the command line.

When closing the installer, a command line should appear with a menu prompt. Type 1 and press Enter.

Once the menu appears again, press Enter to close it.

Click the Start menu or press the Windows button on your keyboard (the button near Control).

Type `cmd` and press Enter.

At the command line, type these commands:

	gem install jekyll
	gem install bundler

At this point, Jekyll should be installed and available. You can type jekyll --version to confirm that it's available to you.

# Mac OS

To install Jekyll, you'll first need Ruby. And to install Ruby, you'll first need Homebrew.

1\. Open your terminal by clicking the magnifying glass in the top right of your desktop and typing terminal in the bar that appears. Terminal should be the first application that appears. 
2\. Install xcode cli tools. (If you have xcode cli tools, you can skip this step.) Enter the following:

	xcode-select --install
	
You may need to agree to a terms and conditions window that appears. 
3\. Install Homebrew. (If you already have Homebrew, you can skip this step.) After the xcode installation completes, enter the following to install Homebrew. (Make sure you don't omit the beginning or end of this command.)

	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

4\. Install Ruby:

	brew install ruby
5\. Install Jekyll and Bundler:

	sudo gem install jekyll
	sudo gem install bundler
	
6\. Check that Jekyll is installed:

	jekyll -v
	
You should see a version number.	

