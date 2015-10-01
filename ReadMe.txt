How to set up a development environment like the one Feike is using:

###############################################################################
######## PART 1 Cygwin/ConsoleZ/Powershell terminal with fancy colors #########
###############################################################################

#01: Download cygwin, make sure installion directory is set to: "C:\cygwin64", and select all GIT packages under 'Devel'

#02: Also set the windows path to: C:\cygwin64\bin

#03: Copy the cygwin64-profile contents to your cygwin64 folder, make sure to merge or overwrite.

#04: Set a correct root directory in the .bashsrc file (the one you just copied). Search for #Default path if you can't find it.

#05: Copy the usr folder to the cygwin64 root. Merge and replace.

#06: Copy the ConsoleZ folder into the cygwin64 root.

#07: In the powershell tab of ConsoleZ run: Set-ExecutionPolicy RemoteSigned.

#08: Copy the complete WindowsPowerShell folder into the My documents folder of windows.


###############################################################################
########################### PART 2 Terminal add-ons ###########################
###############################################################################

#09: Install GIT and add the bin folder to the windows path variable. 

#10: Install NodeJS and NPM package manager (download from here: https://nodejs.org/download/release/) This will work with cygwin because of the aliases in the .bashsrc file.


###############################################################################
############################# PART 3 Code editor ##############################
###############################################################################

#11: Install sublime text 2

#12: To change sublime text background set the theme to 'Monokai Bright' and change the background color value into #00232D in the file with location: C:\Users\Feike\AppData\Roaming\Sublime Text 2\Packages\Color Scheme - Default\Monokai Bright.tmTheme

#13: Sublime text 2 packages you can install: 'Package Control', 'All Autocomplete', 'Color Highlighter'