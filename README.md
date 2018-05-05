#  README
(https://www.raywenderlich.com/180356/ios-internationalization)

## Localizable.strings :
Place and you define yours string for location programmatically. 

## Localizable.stringsdict: 
Pluralization (Roles for setting words in plural)

https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPInternational/StringsdictFileFormat/StringsdictFileFormat.html
http://www.unicode.org/cldr/charts/latest/supplemental/language_plural_rules.html

## Localizable Storyboard:
When you set your project with more than one language, automatic xcode create for us a localizable sb

## Localizing Your Icon:
You have create a InfoPlist.string and localize and setting : CFBundleDisplayName

## Internationalizing Numbers: 
using %@ in Localizable.string and NumberFormatter.localizedString(from: 1000, number: .decimal) for substitute.

## Internationalizing Images : 
The best pratices it's not internationalizate image, but if you use , you have setting in Localizable.string for sample "imageName"="LubieTo"; and change programmatically like this : 
imageView.image = UIImage(named: NSLocalizedString("imageName",
comment: "name of the image file"))



