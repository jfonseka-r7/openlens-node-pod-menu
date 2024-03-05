# OpenLens Node/Pod Menu Extension

This OpenLens extension adds back the node and pod menu functionality that was removed from OpenLens itself in 6.3.0.
You may use either "l" or "v" to open the logs panel when selecting a pod.

# Installing this extension

In OpenLens, navigate to the Extensions page. In the text box, press on the folder icon and search for the tar zip file in your machine.

```
openlens-node-pod-menu-0.0.1-tgz
```

After a few moments, the plugin should appear in the list of installed extensions and be enabled. You might need to restart Lens if its not enabled by default.

# How to build this extension locally

You must use Node Version Manager (NVM) to down the supported version of Node on your machine.

Clone the repo and from the root run the following:

```sh
# Choose the same version of Node that is used in the Electron version
# that OpenLens uses. It might work with other (newer) versions of
# Node but I haven't tested it.
nvm install 16.14.2

npm run build && npm pack
```

# License

Like the OpenLens repository itself at the point from which this extension is based upon, the content of this repository is released under the MIT license. See the file `LICENSE` for details.
