# Hyperlink-Licensing-System

What is this?

The Hyperlink Licensing System allows Minecraft Plugin Devs to implement our Licensing System with Ease.


### How do I set this up?

- Please create an acocunt on https://licensesystem.hyperlink-network.com
- 
- Create an API-Key on the dashboard. 
![API-Keys-Page](https://user-images.githubusercontent.com/71306750/138485996-469d5113-9ff5-42bb-a457-ae0f6022b177.png)

- Now import the Java Library into your project (using Intellij for this). Go to File > Project Structure > Modules > Dependencies > Click ***+*** in the dependencies list and select Jars or directories. Select the import Java API that was provided by us

- Next Copy and Paste this code into your onEnable() method

        APIPlugin apiPlugin = new APIPlugin();
        try {
            apiPlugin.Enable("api-908419130");
        } catch (SQLException e) {
       
        e.printStackTrace();
        }
