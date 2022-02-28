# React native App permissions handler

- This repo shows the permission handler

- "checkCamera" function checks/asks the permissions for camera to use in app. If the platform is android then permissions.android is using if the platform is ios then permissions.ios is using. Platform is the part of "react-native" module and PERMISSIONS is the part of "react-native-permissions" library.

- "checkGallery" function checks/asks permissions for photo gallery to use in app. It asks permissions platform dependent.

- "checkLocation" function checks/asks permissions for Locations to use in app. It asks permissions platform dependent.

- "checkLocationEnabled" function checks and returns result if "location is already enabled" or "location is disabled" with button to go to settings to enable the location

- "showPermissionsBlocked" shows the popup to user if permission is blocked with button to go to settings to enable the location
