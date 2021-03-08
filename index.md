## Welcome to my ePortfolio!
# Shaun R Degueldre


### Self-Assessment

My knowledge of the computer science field has grown so much within the last few years. Prior to going back to school, the most I was capable of was creating a small network in home.  Not only have I learned fundamental concepts such as data structures & algorithms, software engineering and databases, but also tools used to help with development in a given project with a team of developers and testers. These tools include using bitbucket for version control and git to push/pull code on my local machine. I also have experience in utilizing agile for the Software Development Lifecycle. Since deciding to become a computer science major I have added a second concentration on to my degree in Cyber Security.  I have also studied Machine Learning, and Augmented Reality. I have multiple side projects all within the field of computer science. Some of those said projects include raspberry pi development as I have taken what I have learned to create some home devices with IoT and creating a web application. Below are files that showcase my skills within software development. I have organized them into four separate categories that highlights my skillset as a developer.

### Code Review link to video

<a href="https://https://youtu.be/laQ9A8wF2XA">Walkthrough Code Review</a>

### Software Design and Engineering


The artifact is a system where the user can share resources and information on different and various topics where other users have the ability to also add to the created system, update an artifact, and remove them from the system.  To have the ability to add, update, or delete from the system the user must register before they gain the ability to perform the given operations within the system. The reason this item was selected was based off the requirements that where due for the final project.  Not long before taking this course I had taken part in a prior course where it was required to work within databases as well as client/server development.  Having recently taken that course I wanted to take on the challenge of making an application based off what I had previously learned. It was improved by a concept to now a fully functioning system. The biggest challenge was getting started. I decided to make requirements for the application based off the flow-charts I had created. From there it was easy to see what I needed to do and what functionality needed to be included for the overall system. Below is some of the code that I used to help make the application a user friendly experience. 

```markdown
package cs499application;

import javafx.scene.Cursor;
import javafx.scene.control.Button;
import javafx.scene.control.ComboBox;
import javafx.scene.control.Label;
import javafx.scene.control.TextArea;
import javafx.scene.control.TextField;
import javafx.scene.layout.HBox;

public class AppStyles {

    private static String buttonStyles = "";
    private static String mainScreenStyles = "";
    private static String topBarStyle = "";
    private static String leftBarStyle = "";

    public static void setButtonStyles(Button btn) {

        buttonStyles = "-fx-padding: 10px;"
                + "-fx-text-fill: black;"
                + "-fx-font-size: 14px;"
                + "-fx-max-width:160px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-background-color:seagreen;"
                + "-fx-border-radius:0px";

        btn.setStyle(buttonStyles);
        btn.setCursor(Cursor.HAND);

    }


    public static void FormatSearchField(TextField txt) {

        buttonStyles = "-fx-padding: 10px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-min-width:550px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }


    public static void FormatTextField(TextField txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-min-width:150px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }

    public static void FormatTextField(Label txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 13px;"
                + "-fx-min-width:100px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }

    public static void FormatTextField_Values(Label txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: Black;"
                + "-fx-font-size: 13px;"
                + "-fx-min-width:150px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }

      public static void FormatTextField_LevelOne(TextField txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-max-width:50px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }



    public static void FormatTextField(ComboBox txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-min-width:150px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }

    public static void FormatTextField_LevelTwo(TextField txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-min-width:200px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }


     public static void FormatTextField_LevelThree(TextField txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-min-width:280px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }

    public static void FormatTextField_LevelTwo(TextArea txt) {

        buttonStyles = "-fx-padding: 5px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-min-width:250px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-border-radius:0px";

        txt.setStyle(buttonStyles);
        txt.setCursor(Cursor.TEXT);

    }

    public static void FormatSearchButton(Button btn) {

        buttonStyles = "-fx-padding: 10px;"
                + "-fx-text-fill: blue;"
                + "-fx-font-size: 15px;"
                + "-fx-max-width:150px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-background-color:gray;"
                + "-fx-border-radius:0px";

        btn.setStyle(buttonStyles);


    }

    public static String getMainScreenStyles() {
        return mainScreenStyles;
    }


      public static void FormatSearchBar(HBox btn){

         String btnStle = "-fx-padding: 5px;"
                + "-fx-text-fill: white;"
                + "-fx-font-size: 12px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-background-color:#c0c0c0;"
                + "-fx-border-radius:0px";
               btn.setStyle(btnStle);


    }

    public static void styleTopBarButtons(Button btn){

         String btnStle = "-fx-padding: 5px;"
                + "-fx-text-fill: white;"
                + "-fx-font-size: 12px;"
                + "-fx-max-width:100px;"
                + "-fx-border-insets: 1px;"
                +" -fx-background-insets: 1px;"
                + "-fx-background-color:blue;"
                + "-fx-border-radius:0px";
               btn.setStyle(btnStle);


    }




    public static String getLeftBarStyle() {

        leftBarStyle  = "-fx-padding: 15px;"
                + "-fx-font-size: 14px;"
                + "-fx-max-width:170px;"
                + "-fx-spacing:10px;"
                + "-fx-border-width: 2;"
                + "-fx-border-color: seagreen;;";

        return leftBarStyle;

    }

    public static void setLeftBarStyle(String leftBarStyle) {
        AppStyles.leftBarStyle = leftBarStyle;
    }





}
```
### Algorithms and Data Structure

I knew that I would create an application that I could implement different kinds of searching algorithms to find specific artifacts entered in by the user to help demonstrate the useful tools learning in the computer science courses and also side projects which I have worked on while learning during my education period at SNHU. Implementing searching for finding a document, implementing searching for reading a document, and also for other CRUD operations were a bit more of a struggle and a hassle to fully implement, but after quite sometime of frustration and having to walk away and cool myself down more than I would like to admit to I was able to keep a calm mind and using the resources I had at my disposal along with google I was able to get it working as intended. I looked at many different websites implementing different logic into the application until I was able to get one to work and then build off it for other portions of the application. Below is the code used to locate and update a record in the database within the application.

```markdown
Syntax highlighted code block
package cs499application;

import javafx.collections.FXCollections;
import javafx.event.ActionEvent;
import javafx.geometry.Insets;
import javafx.geometry.Pos;
import javafx.scene.Scene;
import javafx.scene.control.Button;
import javafx.scene.control.ComboBox;
import javafx.scene.control.Label;
import javafx.scene.control.TextArea;
import javafx.scene.control.TextField;
import javafx.scene.layout.HBox;
import javafx.scene.layout.VBox;
import javafx.stage.Modality;
import javafx.stage.Stage;

public class updateResource {

    private boolean updated = false;
    public void openWindow() {
        Stage popupwindow = new Stage();

        popupwindow.initModality(Modality.APPLICATION_MODAL);
        popupwindow.setTitle("Update My Resource");
        Insets buttonPadding = new Insets(10, 10, 10, 10);

        //VBox layout for main window
        VBox mainLayout = new VBox();

        HBox boxtwo = new HBox();
        Label resource = new Label("Resource Id:");
        resource.setMinWidth(80);
        TextField txt_resource = new TextField();
        AppStyles.FormatTextField_LevelTwo(txt_resource);

        boxtwo.getChildren().addAll(resource, txt_resource);

        HBox boxthree = new HBox();
        Label resoucetype = new Label("Which Detail ?");
        AppStyles.FormatTextField(resoucetype);
        ComboBox cmb_resoucetype = new ComboBox(FXCollections.observableArrayList("Resource Name", "Source", "Description", "Price"));
        AppStyles.FormatTextField(cmb_resoucetype);
        cmb_resoucetype.setMinWidth(150);
        boxthree.getChildren().addAll(resoucetype, cmb_resoucetype);

        HBox boxtfour = new HBox();
        Label newValue = new Label("Replace With:");
        newValue.setMinWidth(80);
        TextArea txt_newValue = new TextArea();
        AppStyles.FormatTextField_LevelTwo(txt_newValue);
        boxtfour.getChildren().addAll(newValue, txt_newValue);

        HBox boxsix = new HBox();
        boxsix.setAlignment(Pos.CENTER);
        Button save = new Button("Remove");
        save.setMinWidth(130);
        save.setPadding(buttonPadding);

        boxsix.getChildren().addAll(save);

        //Creating spacing for HBoxes
        boxsix.setSpacing(5);
        boxtwo.setSpacing(5);

        mainLayout.getChildren().addAll(boxtwo, boxthree, boxtfour, boxsix);
        mainLayout.setSpacing(5);

        save.setOnAction((ActionEvent event) -> {

            String str_resourceId = txt_resource.getText();
            int column = cmb_resoucetype.getSelectionModel().getSelectedIndex();
            String str_newValue = txt_newValue.getText();
            String str_column = "";

            if (!str_resourceId.isEmpty() &&  !str_newValue.isEmpty()) {

                switch (column) {
                    case 0:
                        str_column = "resourceName";
                        break;
                    case 1:
                        str_column = "source";
                        break;
                    case 2:
                        str_column = "briefDescription";
                        break;
                    case 3:
                        str_column = "briefDescription";
                        break;
                    default:
                        break;
                }


                updated = sqlConnection.updateResource(str_column, str_resourceId, str_newValue);

                if (updated) {

                    popupwindow.close();

                } else {
                    popupwindow.setTitle("Could Not Update");
                }

            } else {

                txt_resource.requestFocus();

# Header 1
## Header 2
### Header 3
            }

- Bulleted
- List
        });

1. Numbered
2. List
        mainLayout.setPadding(new Insets(10, 10, 10, 10));
        mainLayout.setSpacing(10);

**Bold** and _Italic_ and `Code` text
        Scene scene1 = new Scene(mainLayout, 300, 250);

[Link](url) and ![Image](src)
        popupwindow.setScene(scene1);
        popupwindow.setResizable(false);
        popupwindow.showAndWait();
    }

    public boolean isUpdated() {
        return updated;
    }



}
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
### Databases

I knew that I would create an application that I could implement a database that the entire application is built around to find, update, delete, and add specific artifacts entered in by the user to help demonstrate the useful tools learned in the computer science courses and also side projects over the past couple of years. The development and creation of the database is basically the backbone to this application.  Without having the database this application would not work as needed.  Implementing searching the database for finding a document, implementing searching the database for reading a document, and allowing the user to use all the CRUD operations after registering and logging into the application. It is easy to get frustrated when trying to implement databases and all the CRUD operations.  When doing so I tend to run into a long list of bugs/issues, and this takes time to work through and get it operational.  Just like everything I have done since I started in the computer science field I have found that walking away and getting a fresh set of eyes on the problem helps to illuminate the issues which are arising and the appropriate fix for those issues and bugs.  Staying calm and continuing to work through the process is best until everything finally works as intended. Below is the file I used to implement the database within my application.

```markdown
package cs499application;

import java.sql.Connection;
import java.sql.DatabaseMetaData;
import java.sql.DriverManager;
import java.sql.ResultSet;
import java.sql.SQLException;
import java.sql.Statement;
import java.util.ArrayList;
import java.util.logging.Level;
import java.util.logging.Logger;

public class sqlConnection {

    private static Connection con;
    private static String status;
    private static users curentUser;

    public static void ConnectDB() {

        try {
            Class.forName("com.mysql.jdbc.Driver");
            //We create a connection bro providin db name, username-> root Password -> null  
            con = DriverManager.getConnection("jdbc:mysql://localhost:3306/resourcesdb", "root", "");
            status = "Connected...";
            CreateResourceTables();
            CreateUserTables();
        } catch (ClassNotFoundException | SQLException e) {
            System.out.println(e);
            status = "Not Connected";
        }

    }

    public static void CreateResourceTables() {
        String tbleOne = "resource";

        //Check if table resource exists
        if (!checkTable(tbleOne)) {

            try {
                String create = "CREATE TABLE resource ("
                        + " resourceName varchar(45) NOT NULL,"
                        + " resourceId varchar(30) NOT NULL,"
                        + " source varchar(50) NOT NULL,"
                        + " briefDescription text NOT NULL,"
                        + " providerEmail varchar(25) NOT NULL,"
                        + " price varchar(20) NOT NULL,"
                        + "resourceType varchar(30) NOT NULL,"
                        + "CreationDate timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,"
                        + " PRIMARY KEY (resourceId)"
                        + ") ";

                Statement st = con.createStatement();
                st.execute(create);

            } catch (SQLException ex) {
                Logger.getLogger(sqlConnection.class.getName()).log(Level.SEVERE, null, ex);
            }
        }
    }

    public static void CreateUserTables() {
        String tble = "users";

        //Check if table resource exists
        if (!checkTable(tble)) {

            try {
                String create = "CREATE TABLE users ("
                        + " UserName varchar(45) NOT NULL,"
                        + " password varchar(30) NOT NULL,"
                        + " UserEmail varchar(50) NOT NULL,"
                        + " CreationDate timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,"
                        + " PRIMARY KEY (UserEmail)"
                        + ") ";

                Statement st = con.createStatement();
                st.execute(create);

            } catch (SQLException ex) {

                System.out.println("" + ex);
            }
        }
    }

    public static boolean checkTable(String tableName) {

        try {
            DatabaseMetaData dbm = con.getMetaData();
            // check if table exista
            ResultSet tables = dbm.getTables(null, null, tableName, null);
            if (tables.next()) {

                System.out.println("Exists");
                return true;

            } else {

                System.out.println("Does Not Exists");
                return false;
            }
        } catch (SQLException ex) {

            System.out.println(" " + ex);
        }

        return false;
    }

    public static boolean registerClient(users user) {

        boolean result = false;
        String uname = user.getUsernme();
        String userEmail = user.getUserEmail();
        String userPass = user.getUsrepass();

        if (checkUser(userEmail)) {

            System.out.println("User Exists Bro!!");
            return false;
        }

        //Using INSERT statement to insert data into our database
        String query = "INSERT INTO users (UserName,password,userEmail) VALUES('" + uname + "','" + userPass + "','" + userEmail + "')";

        try {

            Statement st = con.createStatement();
            int value = st.executeUpdate(query);

### Jekyll Themes
            if (value == 1) {

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/korey266/korey266.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
                return true;
            }
        } catch (SQLException exc) {

### Support or Contact
            System.out.println(" " + exc);
        }

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
        return result;

    }

    /*We check if user exists first, so that we do not duplicate user details like emails*/
    public static boolean checkUser(String userEmail) {

        String query = "SELECT * FROM users WHERE userEmail = '" + userEmail + "' ";

        try {

            Statement st = con.createStatement();
            ResultSet rst = st.executeQuery(query);

            return rst.next();

        } catch (SQLException exc) {

            System.out.println(" " + exc);
        }

        return false;
    }

    public static boolean logIn(String userEmail, String pass) {

        String query = "SELECT * FROM users WHERE userEmail = '" + userEmail + "' AND password =  '" + pass + "'";

        try {

            Statement st = con.createStatement();
            ResultSet rst = st.executeQuery(query);

            curentUser = new users();
            if (rst.next()) {

                curentUser.setUserEmail(rst.getString("userEmail"));
                curentUser.setUsernme("UserName");
                curentUser.setUsrepass(rst.getString("password"));
                curentUser.setIsRegistered(true);
                return true;
            } else {

                curentUser.setIsRegistered(false);
                return false;
            }

        } catch (SQLException exc) {

            System.out.println(" " + exc);
        }

        return false;
    }

    public static ArrayList<resource> getResources() {

        String query = "SELECT * FROM  resource ";

        ArrayList<resource> resources = new ArrayList<>();
        try {

            Statement st = con.createStatement();
            ResultSet rst = st.executeQuery(query);

            while (rst.next()) {

                resource rsc = new resource();
                rsc.setPrice(rst.getString("price"));
                rsc.setResoucetype(rst.getString("resourceType"));
                rsc.setResourceName(rst.getString("resourceName"));
                rsc.setResource_id(rst.getString("resourceId"));
                rsc.setSource(rst.getString("source"));
                rsc.setProvider(rst.getString("providerEmail"));
                rsc.setResourceDescription(rst.getString("briefDescription"));
                rsc.setCreationDate(rst.getString("CreationDate"));

                resources.add(rsc);

            }

        } catch (SQLException exc) {

            System.out.println(" " + exc);
        }

        return resources;
    }

    public static ArrayList<resource> getResources(String hint) {

        String query = "SELECT * FROM  resource WHERE resourceName LIKE '%" + hint + "%' OR source LIKE '%" + hint + "%' OR briefDescription LIKE '%" + hint + "%' "
                + " OR providerEmail LIKE '%" + hint + "%' OR  price LIKE '%" + hint + "%'  OR resourceId LIKE '%" + hint + "%' "
                + " OR resourceType LIKE '%" + hint + "%'";

        ArrayList<resource> resources = new ArrayList<>();
        try {

            Statement st = con.createStatement();
            ResultSet rst = st.executeQuery(query);

            while (rst.next()) {

                resource rsc = new resource();

                rsc.setPrice(rst.getString("price"));
                rsc.setResoucetype(rst.getString("resourceType"));
                rsc.setResourceName(rst.getString("resourceName"));
                rsc.setResource_id(rst.getString("resourceId"));
                rsc.setSource(rst.getString("source"));
                rsc.setProvider(rst.getString("providerEmail"));
                rsc.setResourceDescription(rst.getString("briefDescription"));

                resources.add(rsc);

            }

        } catch (SQLException exc) {

            System.out.println(" " + exc);
        }

        return resources;
    }

    public static boolean addResource(resource rsc) {

        String query = "INSERT INTO resource (resourceName,resourceId,source,briefDescription,providerEmail,price,resourceType)"
                + " VALUES('" + rsc.getResourceName() + "','" + rsc.getResource_id() + "','" + rsc.getSource() + "','" + rsc.getResourceDescription() + "',"
                + "'" + rsc.getProvider() + "','" + rsc.getPrice() + "','" + rsc.getResoucetype() + "')";

        try {

            Statement st = con.createStatement();
            int value = st.executeUpdate(query);

            if (value == 1) {

                return true;
            }

        } catch (SQLException exc) {

            System.out.println(" " + exc);

        }

        return false;
    }

    /*tO REMOVE A RESOURCE, THE USER MUST BE THE ORNER OF HE RESOURCE*/
    public static boolean removeResource(String resourceId) {

        String query = "DELETE FROM resource WHERE resourceId = '" + resourceId + "' AND providerEmail = '" + curentUser.getUserEmail() + "' ";

        try {

            Statement st = con.createStatement();
            int val = st.executeUpdate(query);
            System.out.println(" Value " + val);

            if (val >= 1) {

                return true;
            }

        } catch (SQLException exc) {

            System.out.println(" " + exc);
        }

        return false;
    }

    //This function will update current users books only
    public static boolean updateResource(String Column, String resourceId, String newValue) {

        String query = "UPDATE resource SET " + Column + " = '" + newValue + "' WHERE resourceId = "
                + "'" + resourceId + "' AND providerEmail = '" + curentUser.getUserEmail() + "'";

        try {

            Statement st = con.createStatement();
            int val = st.executeUpdate(query);
            if (val >= 1) {

                return true;
            }
        } catch (SQLException exc) {
            System.out.println(" " + exc);
        }

        return false;
    }

    public static String getStatus() {
        return status;
    }

    public static users getCurentUser() {

        return curentUser;
    }

}
```
