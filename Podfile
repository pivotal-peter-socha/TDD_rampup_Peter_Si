#Podfile

# Select the appropriate platform below
# Specify the minimum supported iOS version (or later) required by Kiwi
platform :ios, '7.0'
# platform :osx

#
# Some other entries might already exist in the file
# ...
#

# Add Kiwi as an exclusive dependency for the AmazingAppTests target
target :TDD_rampupTests, :exclusive => true do
   pod 'Kiwi'
end

# If you're using Xcode 5 with a brand new project
# (XCTest based instead of OCUnit based) use this instead:
target :TDD_rampupTests, :exclusive => true do
   pod 'Kiwi/XCTest'
end
