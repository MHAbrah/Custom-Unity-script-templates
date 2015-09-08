# CustomUnityScriptTemplates
Some more extensive script templates for C# development.

## Usage
1. Place the script templates into the script template folder:

  **PC:** "C:\Program Files\Unity\Editor\Data\Resources\ScriptTemplates" (or similar)
  
  **MAC:** /Applications/Unity/Unity.app/Contents/Resources/ScriptTemplates/ (or similar)
  
2. Restart Unity if it was open when you added the files to the script template folder.
3. Right-click in the *Project* window and choose *"Create >"*.
4. Pick a script template of your choice.
  
## Templates
### 81-MonoBehaviour-NewBehaviourScript.cs.txt
The standard MonoBehaviour subclass with a few added **magical** Unity *event functions*:
-  **Awake():** Called when #SCRIPTNAME# is loaded, even if the behaviour is disabled but not if the GameObject it is attached to is inactive.
-  **OnEnable():** Called when #SCRIPTNAME# is enabled, before *Start()*.
-  **OnDrawGizmosSelected():** Draw gizmos when GameObject that #SCRIPTNAME# is attached to is selected.
-  **OnDrawGizmos():** Draw gizmos of the GameObject that #SCRIPTNAME# is attached to.
-  **OnValidate():** Called when the script is loaded or a value is changed in the inspector (Called in the editor only).
