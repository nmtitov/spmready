# spmready
is a small tool to check if all your pods are ready to migrate to swift package manager

## In your Project Directory:

## Download newest script version

`curl https://raw.githubusercontent.com/StatusQuo/spmready/master/main.swift -o spmready.swift`

## Make it executable
`chmod +x spmready.swift`

## Run & Hope for the best
`./spmready.swift`


### Alternative 

`./spmready.swift {PATH_TO_PODFILE}`

# Background

This script scans all pods in your podfile and checks if the Repository (master) on github has a SwiftPackage.swift file.
This is not a guarantee that this pod works with spm on your platform/machine/etc. but it can give you a first impression, how far away you are from migrating to Swift Package Manager.

https://swift.org/package-manager/

https://cocoapods.org/
