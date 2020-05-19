# stencilShader
 Read/write stencil shaders for Unity for nice magic-window like effects.
 
 ## How to use:
 Apply the Write shader to the material of the object you would like to hide behind the window.
 Apply the Read shader to the material of the window itself.
 
 Modify both materials "Stencil Reference Value" value to the same "i.e: 1". You can use different reference values for different objects.
 
 See the result: The object behind the window will be only available to be seen when the users' camera is "looking" in the direction of  both objects. 
 This makes some cool magic or trippy effects for your Unity projects. Looks even nicer on VR projects, where users can move freely around the object.

![Result](https://github.com/jesusatgar/stencilShader/blob/master/img/result.jpg)
