# OPENi permissions library

This is an Android library project that enables OPENi native developers to visualize OPENi permissions.

## Set up

* Clone the library and reference it to an Android application project.

* Add the following line to your AndroidManifest.xml:

        <activity android:name="com.openi.permissions.PermissionsActivity" android:label="Permissions" />

* To start PermissionsActivity add the following at one of your activities:

        startActivity(new Intent(this, PermissionsActivity.class));


