a README.md that describes a small-scale project (todo list, homework tracker, personal shoe catalog)

ToDo List:

Main View
- Top Parent View
 * Title
 * Intstructions Button that opens modal
- Middle Parent view (Contains both entities)
  * Entity: ToDo List -- list to todo relationship is 1:N
    - Plus button to add todo list
    - Remove button to remove list
    - Edit button to edit list
    - Check to toggle completion
    - Child View
      * Entity: List of todos -- list to todo relationship is 1:N
        * Swipable to delete
        * Check to toggle compleition
        * Text that can be edited when clicked
        * "Group" -- could be a course, project, group i.e "email" etc
        * Priority i.e low, med., high
        * Noification checkbox
- Bottom Bar Parent view
  * Home
    - Welcome Text
    - Visual calendar with todos
  * Settings
    - Specifies when to send notifications
    - Create groups and custom priorities
      
     
    
