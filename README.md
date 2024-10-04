 Deleting links in the current module.
     
        - What kind of links can be deleted?
          - If the object has,
             > only out-going links
             > only in-coming links 
             > both in-coming and out-going
          - If the object is parent, 
             > It first deletes the links of the children, then deletes the links of the parent.
                    - parent
                        - child
             > If the parent's child have children, it deletes the links of all children. 
                    - parent
                        - child
                            - child 
             > Level 4 has not been tested.
                    - parent
                        - child
                            - child
                                - child
 
        Instructions: 
          - When the code is executed, the interface will open.
          - In this interface, 
            * Enter the id of the object then choose the link type ("IN","OUT","IN-OUT")
            * To complete the deletion process, click the kapat/close button in the interface.
          - If the user does not have a permission to access the modules to which the links are linked,
            those links won't be deleted. These modules are displayed in the infoBox.
