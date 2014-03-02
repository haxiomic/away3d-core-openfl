#Fork of Away3D-OpenFL to test fixes and improvements 

-----------------
##[Away3D main repository](https://github.com/away3d/away3d-core-openfl)
-----------------
####Current Changes

- repeated calls during render-time to **getUniformLocation** & **getAttribLocation** were a bottleneck so they've been replaced (in an adhoc manner for now) with caches