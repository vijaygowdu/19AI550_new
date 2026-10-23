# Ex.No: 3  Basic movements in Unity 
### DATE: 23/10/2026                                                                            
### REGISTER NUMBER : 212223040236
### AIM: 
 To learn the basic movements translation,scaling and rotation of game objects through code.
### Procedure:
1. Setup the Scene
2. Open Unity and create a 3D Scene.
3. Add three objects:Cube → Rename to Object1 (for movement),Sphere → Rename to Object2 (for rotation).Capsule → Rename to Object3 (for scaling).
4. Add the Script,Create a C# Script → Name it TransformOperations.cs.
5. Write the code for translation,scaling and rotation,save and close the script
6. Save the script
7. Select any empty GameObject (or create one: GameObject → Create Empty).
8. Attach the TransformOperations script to it.
9. In the Inspector, assign Object1 → Drag the Cube,Object2 → Drag the Sphere.Object3 → Drag the Capsule.
10. Run the Scene Press Play ▶️ in Unity
11. Stop the program.
### Program 
```
using UnityEngine;

public class exp3 : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
public Transform o1;
public Transform o2;
public Transform o3;
void Start()
{
    

}

 // Update is called once per frame
 void Update()
{
     o1.Translate(0.2f, 0, 0);
     o2.Rotate(0.2f, 0, 0);
     o3.localScale += new Vector3(0, 0.2f, 0);
}
}

```
### Output:

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/58e18352-b4cc-4d84-a378-17b9da5d6150" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f497c40d-1376-4470-b6a3-aae8a024d499" />



### Result:
Thus the basic movement is learned through scripting


