# How To Use
1. Access to page  
 https://ufonian.github.io/.physics3.json-Editor/
2. Set Target File
3. Set Import File(Optional)
4. \[Start Editing\]
  * Use \[▼ \] \[▲\] to Move-Up/.Move-Down
  * Check \[Import\] to add Setting from Import File
    * !: When Import a Setting, the same name setting in Target File will be overwritten.
5. \[Export\] to create Result File

# Functions
The following items will be automatically modified during output.
* \[Id\]s will rename as "PhysicsSetting<N>"
* `$.Meta.PhysicsSettingCount`
* `$.Meta.TotalInputCount`
* `$.Meta.TotalOutputCount`
* `$.Meta.VertexCount`

# Attention

* Before using this application, make sure to back up the Target file.
* For now, this tool requires that the imported JSON file use the same ordering for $.Meta.PhysicsDictionary and $.PhysicsSettings; the Id values must match at the same array indices.
