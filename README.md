# GrootCompleteTextFeild

*Base on [AutocompleteField](https://github.com/filipstefansson/AutocompleteField)*

Auto-complete words for your UITextField

  - Auto-complete when typing in UITextField
  - Custom completion text color
  - Completion by Word or by Sentence


## Installation
### CocoaPods(updating)

```
platform :ios, '8.0'
pod "GrootCompleteTextFeild", "~> 1.0" 
```

### Manual installation
Add GrootCompleteTextFeild.swift into your project.



## Usage
**Storyboard**

Add a UITextField in your Storyboard, and then giving it the GrootCompleteTextFeild subclass.

**Code**
```
import GrootCompleteTextFeild

let textField = GrootCompleteTextFeild(frame: CGRectMake(10, 10, 200, 40), suggestions: ["Mesut Özil","Alexis Sánchez","Laurent Koscielny","Aaron Ramsey"]
view.addSubview(textField)
```
License
----

MIT
