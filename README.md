# glchecklist
A checklist for "debugging" openGL apps

## When only a black screen is rendered 
* Does the render part call glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BUFFER_BIT) ?
* Does the render part call SwapBuffers()/glXSwapBuffers() ?
