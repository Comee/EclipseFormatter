# Eclipse has already supported it
![align items in columns](https://github.com/Comee/EclipseFormatter/blob/master/align_items_in_columns.png)

# EclipseFormatter
Align fields, assignments and variable declarations in columns.

# How to use
## 1. Install Plugin:
### 1.1 If you install eclipse using Eclipse Installer:
Download your eclipse version related org.eclipse.jdt.core_xxx.jar file and put it in C:\Users\${currentUser}\.p2\pool\plugins

### 1.2 If you use portable version eclipse:
Download your eclipse version related org.eclipse.jdt.core_xxx.jar file and put it in ${installedDirectory}\plugins

## 2. Config
After restart, config it:
![Formatter](http://7xi5qz.com1.z0.glb.clouddn.com/github/eclipseformatter/formatter_edit.png)

## 3. Example
![Example](http://7xi5qz.com1.z0.glb.clouddn.com/github/eclipseformatter/format.gif)

# How it works
I override org.eclipse.jdt.internal.formatter.linewrap.FieldAligner and make it enable to align assignments and variable declarations in columns by equals.
