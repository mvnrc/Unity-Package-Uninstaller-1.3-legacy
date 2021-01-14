# Unity Package Uninstaller 1.3 (Free version)

<img src="https://img.shields.io/badge/v1.3-deprecated-orange" />

#### 📥  [Download .unitypackage File](https://github.com/mvnrc/Unity-Package-Uninstaller-1.3-legacy/raw/main/Package%20Uninstaller.unitypackage)

#### Note: The free version is no longer supported! To download the latest version please visit http://www.movinarc.com/unity-package-uninstaller

`Package Uninstaller` helps you remove and clean up any unwanted assets that you have downloaded from Asset Store, or anywhere else.

<img src="https://forum.unity.com/proxy.php?image=http%3A%2F%2Fi.imgur.com%2FZTKGdvj.gif&hash=975184f21954446949995f10d3eea2d9" />

#### Features:

- Package Contents Selector: choose the files you want to keep or remove.

- Search Bar: just type the name of the package you are looking for, instead of scrolling down the list.

- Detailed Info: move your mouse over the package to see more details.

- Easy to Use UI: for a better user experience.

Have you ever wanted to uninstall (unimport) a unity package from your project? Currently, you will need to delete packages’ files one by one. Also, there is the risk of removing wrong files. With Package Uninstaller, you no longer need to do this (often-) tedious task.

Package Uninstaller will remove and clean up any files related to the packages.
How? Simply select the package you have already imported and click Uninstall.

[Forum Thread](https://forum.unity.com/threads/unity-package-uninstaller.378829/)

#### Remove
To remove the **Package Uninstaller** asset itself, simply locate the `Package Uninstaller.unitypackage` file on your computer using the _Browse_ button and hit _Uninstall_.

#### Troubleshooting

- _Package Uninstaller menu does not appear:_
When you import the Package Uninstaller, make sure that the Unity Editor builds the project successfully without any errors, at least once. Otherwise, the editor won't be able to add the menu (it's an almost common case for every utility asset). Don't forget to restart the editor afterward.
If that didn't solve the issue, close the Unity editor, then go to your project folder on your PC and remove all the sub-folders inside the Movinarc folder, except the Assets folder.

- _Some of the files are not removed after uninstalling the package:_
Package Uninstaller only removes the files/folders that are included inside the original asset that you've downloaded from Asset Store, not the ones which have been created after importing the asset.

- _I can't see my asset in the list of packages:_
That could be a problem with your Unity installation or corrupted files/folders. You can check that out or also manually locate the asset (`.unitypackage` file) from your computer, using the _Browse_ button.

#### Credits:
- [SharpCompress](https://github.com/adamhathcock/sharpcompress)
- Icons made by [flaticon.com](https://flaticon.com), [freepik.com](https://freepik.com)
