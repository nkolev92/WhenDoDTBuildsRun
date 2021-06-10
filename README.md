# This is a sample repo to show you when DT builds run

Directory.Build.Props contains a target that runs during a dt build and posts the date as a warning. 

To illustrate how many DT builds happen when branch switching, switch from `main` to `onlyBChanges` and observe the error list. 

Note that the different from `main` to `onlyBChanges` is the PackageVersion.
