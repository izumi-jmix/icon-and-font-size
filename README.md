## Inline-icon and theme size problem project

### Steps to reproduce:
1. Change caption position of a <form>, like:
```xml
<form id="form" dataContainer="userDc" captionPosition="TOP">
```
2. Add a <textField>, bound it to a property. Also add an icon and "inline-icon" stylename, like:
```xml
<textField id="usernameField" property="username" editable="false" 
           icon="CHECK_CIRCLE" stylename="inline-icon"/>
```
3. Change size at theme settings to "Small", or, at least "Medium".

![](./images/Theme%20settings.png)

4. Bug sample:

![](./images/Incorrect%20alignment.png)