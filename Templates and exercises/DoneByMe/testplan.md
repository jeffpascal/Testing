## My test plan for ORA.32_Display EI Table_T1.0

1. Table name: List of External Incidents. Column Names: Business Reference, Label, Gross Amount
2. Make sure "Manage your list by deleting or adding new External Incidents" is written above the table
3. Check value length (if it is too long, it should be truncated and show up in a pop-up)
4. Each line can be deleted by using the trash-bin. Check that the pop-up shows up before deleting.
5. Check that bottom of the table has the button "Add"
6. When clicking the add button, make sure the form has "Business Reference" "Label" and "Gross Amount"
7. Submit the form with empty values, and make sure a red error message is displayed right under the related field: "This field is required"
8. On Validate click, and all fields are filled, a line is added to the table and database. 
9. On "Validate and Add one" click, Popin stays opened and the fields are cleared.
10. Before creating a new EI in the database, a control is made on the EI Business Reference to avoid/prevent the user from creating duplications. If the  Business Reference of a EI is already linked to the Risk Assessment, a red error message is displayed right under the related field :
“A EI with the same Business Reference is already linked to the current assessment”
11.	RG.RAS.GUI	On “Cancel” click, the popin is closed without any modification on the EI table	
12	RG.RAS.GUI	On “Save” click, the form is saved in the database.	
13. RG.RAS.GUI	On page load, the table is filled with the previously added EI (stored in the database)	