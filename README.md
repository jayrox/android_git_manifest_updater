_Git Pre-Commit Hook_

---------

Auto-updates the following values:

AndroidManifest.xml
```
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    package="com.example.app"
    android:versionCode="#####"
    android:versionName="#.#.###" >
```

strings.xml
```
<string name="version">#.#.###</string>
```

Replacing version data in the .xml files with versions from the repo's Git tags.
