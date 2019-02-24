# moove_rblx; ui api 
API for UI, UI instances, UI containers, UI functions, and UI events.

###### INSTANCES
All instances are created with `module:CreateObject(parameters)` while replacing "Object" with the name of the instance.

> *EXAMPLE*  
> ```
> module.CreateContainer(workspace.Part.SurfaceGui, {  
>    BackgroundColor = Color3.new(255, 255, 0),  
> })  
> ```
> Creates a UI container with a background color of yellow parented to a SurfaceGui.




###### PARAMETERS
Parameters should be provided using codes that truncate the meaning of the parameter. Names should always be followed by a "&" symbol that separates different parameters. Parameters should only be used in folder names.

|CODE|MEANING|
|-|-|
|p|Purpose|
|l|Location|
