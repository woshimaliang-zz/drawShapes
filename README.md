# drawShapes
1, Use ShapeView for each shape and its underlying rendering.

2, Programmatically create shape views instead of on putting uiview to storyboad.

3, each shapview has its own PanGesture for simplcity and much easier maintain effort.

4, draw shape programmatically instead of using images for better performance and flexibility, also easy to extend.

To-do:

5, I had thought about using UI Dynamics(like UIAttachmentBehavior) to implement the pan effect, which is surely doable and 
with much less code.

6, I haven't got time to implement the line connection, which should be implemented at viewController level. Draw lines across the 
shape views. ( when doing that, there should be an array varaible that holds all the shapeViews.)
