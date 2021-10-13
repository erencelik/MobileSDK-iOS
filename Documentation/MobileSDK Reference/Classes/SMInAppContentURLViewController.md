# SMInAppContentURLViewController Class Reference

**Inherits from** <a href="../Classes/SMInAppContentViewController.md">SMInAppContentViewController</a> :   
UIViewController  
**Declared in** SMInAppContentURLViewController.h  

## Overview

A view controller for URL In App Content

## Tasks

### 

[+&nbsp;viewControllerForCategory:](#/api/name/viewControllerForCategory:)  

[+&nbsp;viewControllerForCategory:AndOptions:](#/api/name/viewControllerForCategory:AndOptions:)  

<a title="Class Methods" name="class_methods"></a>
## Class Methods

<a name="/api/name/viewControllerForCategory:" title="viewControllerForCategory:"></a>
### viewControllerForCategory:

This will provide you a custom viewcontroller with one web view loaded with the url provided by an in app content for a specific category of an URL type

<code>+ (instancetype _Nonnull)viewControllerForCategory:(NSString *_Nullable)*category*</code>

#### Parameters

*category*  
&nbsp;&nbsp;&nbsp;An NSString of the desired category of In App Content  

#### Return Value
An SMInAppContentURLViewController

#### Discussion
The viewcontroller will take all available space in screen and will contain a close button if it is presented as it is. Otherwise the app will have to provide a UIContainerView which will contain the view controller

#### Declared In
* `SMInAppContentURLViewController.h`

<a name="/api/name/viewControllerForCategory:AndOptions:" title="viewControllerForCategory:AndOptions:"></a>
### viewControllerForCategory:AndOptions:

This will provide you a custom viewcontroller with one web view loaded with the url provided by an in app content for a specific category of an URL type

<code>+ (instancetype _Nonnull)viewControllerForCategory:(NSString *_Nullable)*category* AndOptions:(SMInAppContentStyleOptions *_Nullable)*options*</code>

#### Parameters

*category*  
&nbsp;&nbsp;&nbsp;An NSString of the desired category of In App Content  

*options*  
&nbsp;&nbsp;&nbsp;An <a href="../Classes/SMInAppContentStyleOptions.md">SMInAppContentStyleOptions</a> object allowing you to customise the in app content  

#### Return Value
a SMInAppContentURLViewController

#### Discussion
The viewcontroller will take all available space in screen and will contain a close button if it is presented as it is. Otherwise the app will have to define a UIContainerView which will contain the view controller

#### See Also

* <code><a href="../Classes/SMInAppContentStyleOptions.md">SMInAppContentStyleOptions</a></code>

#### Declared In
* `SMInAppContentURLViewController.h`
