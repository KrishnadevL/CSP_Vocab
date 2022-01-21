{% include navigation.html %}

# Blueprints
Blueprints are a flask-specific program that let individual directories function like their own flask sites, for example giving them specific static and templates files.  The several blueprints then can be imported into the master file.  Using blueprints help organize files in large websites.

### Examples 

![image](https://user-images.githubusercontent.com/89166946/150582963-4d58a376-5b87-4793-bfdc-a879f198b0c3.png)

This is an exmaple of setting up a blueprint in a secondary python file. This setup allows for the routing of the file via blueprints from main.py

![image](https://user-images.githubusercontent.com/89166946/150583123-b4bda958-a7b7-4f0d-86da-02ebf7af4451.png)

This shows how data is being pulled from the blueprint setup in the secondary python file and how its defined within main.py
