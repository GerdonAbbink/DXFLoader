# DXFLoader
A DXF Loader for three.js

### Usage:

    let loader = new THREE.DXFLoader();
    loader.load('URL', function(data) {
        scene.add(data);
    )};
