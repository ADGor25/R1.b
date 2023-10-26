erDiagram
    User ||--|{ List : creates
    User {
        String Username
        String Password
    }
    List }|--|{ ToDo : contains
    List {
        String Name
        int ListID
        int numOfToDo
        boolean Checked
        String Group
    }
    ToDo {
        String Name
        int TaskID
        boolean Checked
        String Priority
    }
