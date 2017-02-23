# RecursiveSceneGraph
<h4>
The program consists of a Scene class, an Object class, and a Component class. <br>
A Scene can contain multiple Objects. <br>
An Object can contain multiple Components. <br>
A Component can also contain multiple Components. <br>
When a Scene's update method is called, the scene should use recursion to update all the objects. Likewise, every Object should recursively update all of its Components. Each component should then recursively update all of its attached Components.<br><br>
Complete the updateObject method in the Scene class, the updateComponent method in the Object class, and the updateSubComponent method in the Component class without using any loops. (hint: an input value of -1 should break the recursion)
</h4>
<br><br><br><br>
<a href="https://github.com/league-level5/RecursiveSceneGraph_Solution">solution</a>
