# ARFoundationPlacementIndicator
This is a template project for Unity's <a href="https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@2.2/manual/index.html">AR Foundation</a> system. It's ready to build and includes an AR placement indicator. This is a reticle that tracks the center of your screen in the AR world. So it snaps to surfaces such as tables, the floor, walls, etc. It can be used to spawn in objects, or any other feature you wish to include in your AR app.

# What is AR Foundation?
Right now, there are two main AR SDK's. ARCore for Android and ARKit for iOS. <a href="https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@2.2/manual/index.html">AR Foundation</a> provides the developer with an API to create apps/games for both platforms seamlessly. There's no need for separate projects/SDK's - it's all built into one. This is similar in a way to Unity's integration of VR. Here's a list of features AR Foundation provides:

- World tracking: track the device's position and orientation in physical space.
- Plane detection: detect horizontal and vertical surfaces.
- Point clouds, also known as feature points.
- Reference points: an arbitrary position and orientation that the device tracks.
- Light estimation: estimates for average color temperature and brightness in physical space.
- Environment probes: a means for generating a cube map to represent a particular area of the physical environment.
- Face tracking: detect and track human faces.
- Image tracking: detect and track 2D images.
- Object tracking: detect 3D objects.
- <a href="https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@2.2/manual/index.html">Learn more here.</a>

# Demo Scene
<b>AR Session:</b> runs and manages the current AR session.

<b>AR Session Origin:</b> defines the center of the AR session. Also includes a few other components that we need: AR Raycast Manager, AR Plane Manager.

<b>AR Camera:</b> renders the device camera and AR objects.

<b>PlacementIndicator:</b> AR reticle which snaps to the tracked surfaces.
