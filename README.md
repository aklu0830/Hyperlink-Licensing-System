# Hyperlink-Licensing-System

What is this?

The Hyperlink Licensing System allows Minecraft Plugin Devs to implement our Licensing System with Ease.


### How do I set this up?

- Please create an acocunt on https://licensesystem.hyperlink-network.com
- Create an API-Key on the dashboard. 
![API-Keys-Page](https://user-images.githubusercontent.com/71306750/138485996-469d5113-9ff5-42bb-a457-ae0f6022b177.png)
        public void onEnable() {
         APIPlugin apiPlugin = new APIPlugin();
         try {
              apiPlugin.Enable("api-908419130");
            } catch (SQLException e) {
              e.printStackTrace();
          }

    }
