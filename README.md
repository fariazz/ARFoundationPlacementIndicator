# ARFoundationPlacementIndicator
This is a template project for Unity's AR Foundation system. It's ready to build and includes an AR placement indicator. This is a reticle that tracks the center of your screen in the AR world. So it snaps to surfaces such as tables, the floor, walls, etc. It can be used to spawn in objects, or any other feature you wish to include in your AR app.

# What is AR Foundation?
AR Foundation is a Unity package that combines the SDK's of ARCore (Android) and ARKit (iOS) into one system. It allows you as a developer, to create augmented reality apps without the worry of setting it up for a specific device. AR Foundation allows you to create one project and build to either Android or iOS. This is a similar concept to Unity's VR system, where the developer doesn't have to worry about supporting every type of device.

# Demo Scene
<b>AR Session:</b> runs and manages the current AR session.

<b>AR Session Origin:</b> defines the center of the AR session. Also includes a few other components that we need: AR Raycast Manager, AR Plane Manager.

<b>AR Camera:</b> renders the device camera and AR objects.

<b>PlacementIndicator:</b> AR reticle which snaps to the tracked surfaces.
